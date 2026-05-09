1 _ Create a folder called learn_git.
--->![alt text](image.png)
2 _ Cd (change directory) into the learn_git folder.
--->![alt text](image-1.png)
3 _ Create a file called third.txt.
// touch third.txt
--->![alt text](image-2.png)
4 _ Initialize an empty git repository.
// git init
---git ->![alt text](image-3.png)
5 _ Add third.txt to the staging area.
// git add third.txt
---git ->![alt text](image-4.png)
6 _ Commit with the message "adding third.txt".
// git commit -m "adding third.txt"
---git ->![alt text](image-5.png)
7 _ Check out your commit with git log.
// git log
---git ->![alt text](image-6.png)
8 _ Create another file called fourth.txt.
// touch fourth.txt
---git->![alt text](image-7.png)
9 _ Add fourth.txt to the staging area.
// git add fourth.txt
---git ->![alt text](image-8.png)
10 _ Commit with the message "adding fourth.txt"
// git commit -m "adding fourth.txt"
---git ->![alt text](image-9.png)
11 _ Remove the third.txt file.
// git rm third.txt
--git->![alt text](image-10.png)
12 _ Add this change to the staging area. (Using the command "git add . "
// git add .
--git->![alt text](image-11.png)
13 _ Commit with the message "removing third.txt".
// git commit -m "removing third.txt"
--git->![alt text](image-12.png)
14 _ Check out your commits using git log.
// git log
--git->![alt text](image-13.png)
15 _ Change your global settings to core.pager=cat - you can read more about that here.
// git config --global core.pager cat
--git-> ![alt text](image-14.png)
16 _ Write the appropriate command to list all the global configurations for git on your machine.You can type git config --global to find out how to do this.
// git config --global --list
--git->![alt text](image-15.png)


