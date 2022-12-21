# 0x01. Shell, permissions

## Learning Objectives:bulb:

* What do the commands chmod, sudo, su, chown, chgrp do
* Linux file permissions
* How to represent each of the three sets of permissions (owner, group, and other) as a single digit
* How to change permissions, owner and group of a file
* Why can’t a normal user chown a file
* How to run a command with root privileges
* How to change user ID or become superuser
* How to create a user
* How to create a group
* How to print real and effective user and group IDs
* How to print the groups a user is in
* How to print the effective userid
---

### [0. My name is Betty](./0-iam_betty)
* Create a script that switches the current user to the user betty.

### [1. Who am I](./1-who_am_i)
* Write a script that prints the effective username of the current user.


### [2. Groups](./2-groups)
* Write a script that prints all the groups the current user is part of.


### [3. New owner](./3-new_owner)
* Write a script that changes the owner of the file hello to the user betty.

### [4. Empty!](./4-empty)
* Write a script that creates an empty file called hello.


### [5. Execute](./5-execute)
* Write a script that adds execute permission to the owner of the file hello.


### [6. Multiple permissions](./6-multiple_permissions)
* Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

### [7. Everybody!](./7-everybody)
* Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello

### [8. James Bond](./8-James_Bond)
* Write a script that sets the permission to the file hello as follows:
  * Owner: no permission at all
  * Group: no permission at all
  * Other users: all the permissions

### [9. John Doe](./9-John_Doe)
* Write a script that sets the mode of the file hello to this:
  * -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

### [10. Look in the mirror](./10-mirror_permissions)
* Write a script that sets the mode of the file hello the same as olleh’s mode.

### [11. Directories](./11-directories_permissions)
* Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

### [12. More directories](./12-directory_permissions)
* Create a script that creates a directory called my_dir with permissions 751 in the working directory.

### [13. Change group](./13-change_group)
* Write a script that changes the group owner to school for the file hello

### [14. Owner and group](./100-change_owner_and_group)
* Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.


### [15. Symbolic links](./101-symbolic_link_permissions)
* Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.


### [16. If only](./102-if_only)
* Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.

### [17. Star Wars](./103-Star_Wars)
* Write a script that will play the StarWars IV episode in the terminal.
