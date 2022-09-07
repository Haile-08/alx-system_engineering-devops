# 0x00. Shell, basics

In this project, i learnd about basics of shell scripting.I learned how to navigate directories using cd, pwd, ls, how to look around using ls, less, and file, and how to manipulate files with cp, mv, rm, and mkdir. Further, I practiced working with the type, which, help, and man commands, implementing wildcards, reading man pages, creating links, and using keyboard shortcuts in Bash

# commands

## man or help:

- cd
- ls
- pwd
- less
- file
- ln
- cp
- mv
- rm
- mkdir
- type
- which
- help
- man

# Learning Objectives

## General
- What does RTFM mean?
- What is a Shebang

## What is the Shell
- What is the shell
- What is the difference between a terminal and a shell
- What is the shell prompt
- How to use the history (the basics)

## Navigation
- What do the commands or built-ins cd, pwd, ls do 
- How to navigate the filesystem
- What are the . and .. directories
- What is the working directory, how to print it and how to change it
- What is the root directory
- What is the home directory, and how to go there
- What is the difference between the root directory and the home directory of the user root
- What are the characteristics of hidden files and how to list them
- What does the command cd - do

## Looking Around
- What do the commands ls, less, file do
- How do you use options and arguments with commands
- Understand the ls long format and how to display it
- What does the ln command do
- What do you find in the most common/important directories
- What is a symbolic link
- What is a hard link
- What is the difference between a hard link and a symbolic link

## Manipulating Files
- What do the commands cp, mv, rm, mkdir do
- What are wildcards and how do they work
- How to use wildcards

## Working with Commands
- What do type, which, help, man commands do
- What are the different kinds of commands
- What is an alias
- When do you use the command help instead of man

## Reading Man Pages
- How to read a man page
- What are man page sections
- What are the section numbers for User commands, System calls and Library functions

## Keyboard Shortcuts for Bash
- Common shortcuts for Bash

## LTS
- What does LTS mean? 

# Requirements

## General

- Allowed editors: vi, vim, emacs
- All your scripts will be tested on Ubuntu 20.04 LTS
- All your scripts should be exactly two lines long ($ wc -l file should print 2)
- The first line of all your files should be exactly #!/bin/bash
- A README.md file at the root of the repo, containing a description of the repository
- A README.md file, at the root of the folder of this project, describing what each script is doing
- You are not allowed to use backticks, &&, || or ;
- All your scripts must be executable. To make your file executable, use the chmod command: chmod u+x file. Later, we’ll learn more about how to utilize this command.


## Tasks

0. [Where am I?](./0-current_working_directory) : A script that prints the absolute path of the current working directory.
1. [What's in there?](./1-listit) : A script that displays the contents of your current directory.
2. [There is no place like home](./2-bring_me_home) : A script that changes the working directory to the user's home directory.
3. [The long format](./3-listfiles) : A script that displays the current directory contents in a long format.
4. [Hidden files](./4-listmorefiles) : A script that displays the current directory contents including hidden files.
5. [I loce numbers](./5-listfilesdigitonly) : A script that displays the current directory contents, using long format, while displaying group IDs in numeral and show hidden files.
6. [Welcome holberton](./6-firstdirectory) : A script that will create a directory named `holberton` in the `/tmp/` directory.
7. [Betty in Holberton](./7-movethatfile) : A scipt that will move a file called `betty` from home to the new directory created above.
8. [Bye bye Betty](./8-firstdelete) : A script that will delete file `betty` from the new location.
9. [Bye bye Holberton](./9-firstdirdeletion) : A script that will delete the directory `holberton` that is in the `/tmp/` directory path.
10. [Back to the future](./10-back) Change working directory to the previous one.
11. [Lists](./11-lists) List all files (*even ones with names beginning with a period character, which are normally hidden*) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12. [File type](./12-file_type) A script that prints the type of the named file `iamafile`. The `iamafile` will be in the `/tmp/` directory when we will run your script.
13. [We are symbols, and inhabit symbols](./13-symbolic_link) Create a symbolic link to `/bin/ls`, named `__ls__`. The symbolic link should be created in the current working directory.
14. [Copy HTML files](./14-copy_html) Create a script that copies all `html` files from the current working directory to the parent working directory while only copying files that did not exist.
15. [Let's move](./100-lets_move) A script that moves all files beginning with an uppercase letter to the directory `/tmp/u`.
16. [Clean Emacs](./101-clean_emacs) A script that deletes all files in the current directory that end with the character `~`.
17. [Tree](./102-tree) A script that creates the directory `welcome/`, `welcome/to/` and `welcome/to/holberton`.
18. [Life is a series of commas, not periods](./103-commas) A script that lists all the files and directories of the current directory separated by commas `,`.
19. [File type: Holberton](./holberton.mgc) Create a magic file `holberton.mgc` that can be used with the command `file` to detect `Holberton` data files always contain the string `HOLBERTON` at offset 0.
