# Practice in the Terminal

## The Command Line

- A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text. The command line typically presents you with a prompt. As you type, it will be displayed after the prompt. Most of the time you will be issuing commands

## Basic Navigation

- Whenever we refer to either a file or directory on the command line, we are in fact referring to a path. ie. A path is a means to get to a particular file or directory on the system.
- There are 2 types of paths we can use, absolute and relative. Whenever we refer to a file or directory we are using one of these paths. Whenever we refer to a file or directory, we can, in fact, use either type of path.

## More About Files

- Linux under the hood, everything is actually a file. A text file is a file, a directory is a file, your keyboard is a file (one that the system reads from only), your monitor is a file (one that the system writes to only) etc.
-  A file extension is normally a set of 2 - 4 characters after a full stop at the end of a file, which denotes what type of file it is. 
-  Linux is case sensitive.
-  A space on the command line is how we seperate items. They are how we know what is the program name and can identify each command line argument.
-  Anything inside quotes is considered a single item.
-  To make a file or directory hidden all you need to do is create the file or directory with it's name beginning with a . or rename it to be as such. Likewise you may rename a hidden file to remove the . and it will become unhidden. The command ls which we have seen in the previous section will not list hidden files and directories by default. We may modify it by including the command line option -a so that it does show hidden files and directories.

## Manual Pages

-The manual pages are a set of pages that explain every command available on your system including what they do, the specifics of how you run them and what command line arguments they accept. Some of them are a little hard to get your head around but they are fairly consistent in their structure so once you get the hang of it it's not too bad.

## File Manipulation

- Creating a directory:  The command we are after is mkdir which is short for Make Directory.
- The command to remove a directory is rmdir, short for remove directory.  There is no undo when it comes to the command line on Linux.
- To create blank files, use the command touch.
- The command we use to copy file is cp which stands for copy.
- To move a file we use the command mv which is short for move. It operates in a similar way to cp. One slight advantage is that we can move directories without having to provide the -r option.
- The command to remove or delete a file is rm which stands for remove. When rm is run with the -r option it allows us to remove directories and all files and directories contained within.

## Cheat Sheet

- [Source](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)
