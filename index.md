# Lab Report 1 - Remote Access and Filesystem
Welcome to my blog! In this section, we will discuss how filesystem commands work.

**cd Command**
The cd command is used to change the directory of the terminal.

![Image](revisedCD.png)  

As shown in the image, using the cd command without arguments will change the current directory to the home directory. When in the home directory and cd is called with no arguments it doesn't do anything because the current directory is the home directory. When in the lecture1 or messages directory and cd is called without commands, it will change back to the home directory. Starting from the home directory, when the cd command is called on a directory such as lecture1, the current directory is changed to the called directory (lecture1). An error occurs when cd is called on a file as it will not do anything because cd only works moving between directories.

**ls Command**
The ls command is used to list files and subdirectories in the current directory.

![Image](ls.png) 

As shown in the image (in lecture1 directory) when the ls command is used without arguments, it lists all the files and subdirectories in the current directory. When ls is called on a directory such as messages, it lists all the files and subdirectories of that called directory. When ls is called on a file in its relative path, it will just show the file name.



In this scenario, we are in the directory of lecture1. When ls is called without arguments, it lists all the files in the lecture1 directory. When ls is called on a directory, in this case, messages, it lists all the files that are in the messages directory. When called on a file, it lists the file name.

**cat Command**
The cat command is used to view files and give the content of the file.

![Image](revisedCAT.png)

In this scenario, we are in the lecture1 directory and when the cat command is called with no arguments it is infinitely waiting for a file name so it does not do anything with no arguments. An error occurs when cat is called on a directory, the output will show that we are in a directory and are still waiting for a file to be called because cat only works with files. When cat is called on a file README, it will show the output of the content within the README file.




