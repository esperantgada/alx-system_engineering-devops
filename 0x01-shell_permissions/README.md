**0x01. Shell, permission**

 **su betty**  Changes your user  to betty.

 **whoami** Displays the effective user ID of current user. Other alternative **id -un**

 **groups** Prints all the groups the current user is part of.

 **chown betty hello** Changes the owner of the file hello to the user betty

 **touch hello** Creates an empty file called hello 
 
 **chmod u+x hello** Adds execute permission to the owner of the file hello

 **chmod ug+x,o+r hello** Adds execute permission to user and group owner, and read permission to others for file hello

 **chmod ugo+x hello** Add execution permission to everyone for file hello.

**chmod 007 hello** Adds permissions for the file hello, owner and group don't have any permissions and other users have all permissions.

 **chmod 753 hello** Adds permissions, so owner has all permissions, group has read and execute permissions and others have write and execute permissions.

**chmod --reference=olleh hello** Copies the mode of file olleh to file hello.

**chmod -R +X .** Adds execute permission to all subdirectories of the current directory for the everyone. Regular files should not be changed.

**mkdir -m 751 my_dir** Creates a directory called my_dir with permissions 751 in the working directory. User has all read, write, and execute permissions. Group has read and execute permissions. Others have just execute permission.

**chgrp school hello**s Change the group owner to school for the file hello

chown vincent:staff *  **Changes owner to betty and the group owner to holberton for all files and directories in current directory.**

**chown -h vincent:staff _hello** Changes the owner and group owner of file _hello to betty and holberton respectively.

**chown --from=guillaume betty hello** Changes the owner of the file hello to betty only if it is currently owned by guillaume

**telnet towel.blinkenlights.nl** Plays the Star Wars IV episode in the terminal. This is a premade script provided online.**
