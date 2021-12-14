Task 5.1.1
$ su command to login as root, su –c [command] to execute just one command as root
$ sudo command to let current user execute commands as root for limited time, but user should be in sudoers list.
$ passwd command for managing user passwords and their roles. It’s in file /etc/passwd
$ last command shows ones logged in users. lastd – unsuccessful ties to login.
$ chfn [user] command let you start changing users personal info dialog
$ help is a built-in command in the bash shell. [command] –h / --help | less | grep [arg]
The man command shows detailed manuals for each command. 
$ man [arg] 
inside man page /[arg] to search for some argument
$ info - Some programs don’t have man pages — or have very incomplete man pages — and store their documentation as info documents.
$ apropos [arg] it’s another kind of help system that allows to find proper command for an action
$ whatis [command] The whatis command shows a one-line summary of a command, taken from its man page. It’s a quick way of seeing what a command actually does.
$ cd or cd ~ allows to get to the home dir. 
$ ls –a list all files in current directory
Task 5.1.2
$ tree command list contents of directories in a tree-like format
$ ls –la shows files and directories rights
. and .. allows to go up and down relative to current directory
$ ln and ln –s A hard link isn't a pointer to a file, it's a directory entry pointing to the same inode. Even if we rename or delete file, a hard link still works.
$ find [options] [path] [expression] example: find . –name “*host*”
$ locate [option] [pattern] for example $ locate .bash_history 

