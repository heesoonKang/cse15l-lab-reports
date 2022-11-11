## **Week 7 Lab Report** ##

##** Part 1 Sequence of keys to change "10" to "1391" in TestDocSearch.java **## 

1. First, log into your ssh account.
2. Next, git clone week-6-skill-demo1 from github. 
<pre><code>  git clone https://github.com/ucsd-cse15l-f22/skill-demo1 week6-skill-demo1
</code></pre> 
3. `cd` week6-skill-demo to change directory to demo files.
4. `Vim` TestDocSearch.java to edit java file.
**Key Sequence**
* Use `J` and `L` move cursor commands to get to "10" in Line 14.
* Use `D` and `E` commands to delete "10".
* Press `I` to enter the insert mode .
* Type in "1391".
* Press `ESC` to go to Normal Mode.
* `Shift + ;wq` to save and exit.

**Output**
Now, the "10" in TestDocSearch.java is replaced with 1391 and will fixed the error on the Junit test.


## **Part 2 Questions** ##

**Q1) Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why?**

If I had to work on a program that i was running remotely, it would be based on type and amount of files that I need to copy over to the remote server. For example, if it was files with size and memeory not as big for me to edit it on the IDE like VS code, then I would edit it on IDE since that is more familiar and easier for me. However, if the size of the files so big that either takes forever to copy over or i would not have enough memory to take in all files, then I would use vim to edit the remote server.

**Q2) What about the project or task might factor into your decision one way or another? (If nothing would affect your decision, say so and why!)**

Usually, if I am dealing with projects then most likely the files will be big and in that case, using VIM will more faster and convenient to edit files.
