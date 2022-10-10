### Command line Terminology

pwd = print working directory; tels you what your current working directory is 
ls = list contents of directory
file (input file name without parentheses) = obtain information about what type of file a file or directory is
cd = change directory
        - if you ***cd*** without any arguments, you will return back to your home directory 
        - usually, cd is ran with a single command line argument which is the location we would like to change into
Tab Completion = auto complete an action
ls -a = lists the contents of a directory, including hidden files 
.(file name) = hides file 

~ (tilde) = shortcut for home directory; if home directory is /home/ryan, you could refer to the directory Documents with the path ***/home/ryan/Documents or ~/Documents
. = reference to your current directory 
.. = parent directory; you can use this severeal times in a path to keep going up a hierarchy 

echo = command which is used to ***display messages***


prompt - command - command line arguments
user@bash: - ls - -l /home/ryan
All separated by spaces
must be a space b/w the ***command*** and the ***first command line argument*** also 

After line 1 (above) plays out, then you get outputs *(multiple lines on terminal)* from running the command

After command has ran and completed, the prompt will appear again ready for you to enter another command

#### What is a shell?
- part of the OS that defines ***how the terminal will behave and looks after running (or executing) commands for you.*** 
- most common shell available: ***bash***

echo = command which is used to ***display messages***


[<===BACK](README.md)



#### Absolute vs Relative Paths

***Absolute path***
- a file or directory location *in relation to the root of the file system*
- specifies location (file or directory) in relation to the ***root directory*** 
- you can identify them easily as they always begin with a forward slash (/)

Example of absolute path:

user@bash: ls /home/ryan/Documents
file1.text file2.txt file3.txt...

- will provide the same output regardless of our current location when we run it



***Relative path***
- a file or directory location *relative to wheer we currently are in the file system*
- specifies location (file or directory) in relation to where we currently are in the system. ***They will *not* begin with a slash.*** 

Example of relative path:

user@bash: ls Documents
file1.text file2.txt file3.txt...

- documents is a directory in our current location


***root directory*** 
- top of the hierarchical structure 
- denoted by a single slash (/) 
    - has subdirectories and so on; files may reside in any of these directories 
