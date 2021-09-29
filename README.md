# git_demo

Related to this slideshow:
https://docs.google.com/presentation/d/1ndSqG7PhwBwRgj71c9uWaXztQPgjgVSef9lm5cPlQ8s/edit?usp=sharing

Steps:
1. Open VScode and go to Terminal > New Terminal
2. Navigate to your desktop inside the new terminal, and make a directory for this demo, `mkdir [NAME THIS DIRECTORY]`
3. Navigate so you are inside your directory, `cd [THING YOU NAMED YOUR DIRECTORY]`
4. Clone this directory by going to the green Code button at the top of the page, copying the link under HTTPS, and running `git clone "[THAT URL]"` in your terminal
	Make sure that you are in the right place on your computer. Feel free to run `pwd` (`cd` for Windows) at any time.
5. Try going into this directory and list the contents `ls` (or `dir` for Windows). There should be things in there, such as this README.md
6. Now open this folder from the file system in VScode. File > Open... and find either the original directory you made on your desktop or the github directory (either will be fine)
7. Find the folder labeled "dir" with your assigned number at the end. Use the right click function to rename that directory your first name.
8. Open the file inside your directory, and use the text editor to add a new sentence to the bottom of the file.
9. Safe this file with command s for mac or control s for windows and linux. Or go to File > Save
10. Return to the terminal.
11. Add the new file: `git add .`
12. Lockin your submissions: `git commit -m "useful message"`
13. Send your answers to github: `git push`
14. Go check on github to see your changes update.
