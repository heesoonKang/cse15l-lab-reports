## **Week 7 Lab Report** ##

##** Part 1 Sequence of keys to change start to base in DocSearchServer.java

1. First, open the terminal and type vim DocSearchServer.java
2. The above command will allow us to edit the DocSearchServer.java file.
3. Next, git clone week-6-skill-demo1 from github.   


`/start<Enter>cebase<Esc>ncebase<Esc>ncebase<Esc>:wq`
- '/start<Enter>' This part of key sequence will search for the first instance of file and get on the code.
- 'ce' The code ce will delete the word start and edit insert mode.
- 'base' The code base needs to be typed since we are already in the insert mode.
- 'Esc' The code will exit from the insert mode
- 'n' This code will jump to the next instance of start.
- 'cebase<Esc>' This part of code will replace start with word base. Repeat this process until all start lines are change
  to the base.


**Output**
After this sequences of keys, we will have all of start changed to the base.


## **Part 2 Questions** ##

**Q1) Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why?**

If I had to work on a program that i was running remotely, it would be based on type and amount of files that I need to copy over to the remote server. For example, if it was files with size and memeory not as big for me to edit it on the IDE like VS code, then I would edit it on IDE since that is more familiar and easier for me. However, if the size of the files so big that either takes forever to copy over or i would not have enough memory to take in all files, then I would use vim to edit the remote server.

**Q2) What about the project or task might factor into your decision one way or another? (If nothing would affect your decision, say so and why!)**

Usually, if I am dealing with projects then most likely the files will be big and in that case, using VIM will more faster and convenient to edit files.
