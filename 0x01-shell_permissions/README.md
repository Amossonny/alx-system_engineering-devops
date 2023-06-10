* su betty is a script that switches the current user to the user betty
* whoami is a script that prints the effective username of the current user
* groups is a script that prints all the groups the current user is part of
* chown betty hello is a script that changes the owner of the file hello to the user betty
* touch hello is a script that creates an empty file called hello
* chmod u+x hello is a script that adds execute permission to the owner of the file hello
* chmod ug+x,o+r hello is a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
* chmod a+x hello is a script that adds execution permission to the owner, the group owner and the other users, to the file hello
* chmod 007 hello is a script that sets the permission to the file hello as follows: ------rwx
* chmod 753 hello is a script that sets the mode of the file hello to this: -rwxr-x-wx
* chmod --reference=olleh hello is a script that sets the mode of the file hello the same as olleh’s mode
* chmod -R a+X is a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
* mkdir -m 751 my_dir is a script that creates a directory called my_dir with permissions 751 in the working directory
* chgrp school hello is a script that changes the group owner to school for the file hello
* chown -R vincent:staff . is a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory* chown -h vincent:staff _hello is a script that changes the owner and the group owner of a symbolic link _hello in the working directory to vincent and staff respectively
