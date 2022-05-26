0-current_working_directory; prints the absolute path name of the current working directory
1-listit; display the contents list of the current directory
2-bring_me_home; changes the working directory to the users home directory
3-listfiles; displays current directory in long format
4-listmorefiles; displays current direcory contents, including hidden files starting with .
5-listfilesdigitonly; displays current directory contents
6-firstdirectory; creates a directory named my_first_directory in the /tmp/ directory
7-movethatfile; move the file betty from /tmp/ to /tmp/my_first_directory
8-firstdelete; deletes the file betty
9-firstdirdeletion; deletes the directory my_first_directory that is in the /tmp directory
10-back; changes the working directory to the previous one
11-lists; lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory
12-file_type; prints the type of the file named iamafile
13-symbolic_link; a symbolic link /bin/ls in the current working directory
14-copy_html; copies all the HTML files from the current working directory to the parent of the working directory
100-lets_move; moves all files beginning with an uppercase letter to the directory /tmp/u
101-clean_emacs; deletes all files in the current working directory that end with the character ~
102-tree; creates the directories welcome, to, school in the current directory
103-commas; lists all the files and directories of the current directory, separated by commas (,).

Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
The listing should end with a new line

school.mgc; magic file that can be used with the command file to detect School data files
