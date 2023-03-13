## [0x01. Shell, permissions](https://github.com/YasminKinawi/alx-system_engineering-devops/tree/master/0x01-shell_permissions)
### Learning Objectives
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

#### 0. My name is Betty
[Create a script that switches the current user to the user betty.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/0-iam_betty)

#### 1. Who am I
[Write a script that prints the effective username of the current user.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/1-who_am_i)

#### 2. Groups
[Write a script that prints all the groups the current user is part of.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/2-groups)

#### 3. New owner
[Write a script that changes the owner of the file hello to the user betty.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/3-new_owner)

#### 4. Empty!
[Write a script that creates an empty file called hello.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/4-empty)

#### 5. Execute
[Write a script that adds execute permission to the owner of the file hello.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/5-execute)

#### 6. Multiple permissions
[Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/6-multiple_permissions)

#### 7. Everybody!
[Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/7-everybody)

#### 8. James Bond
[Write a script that sets the permission to the file hello as follows:](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/8-James_Bond)

* Owner: no permission at all
* Group: no permission at all
* Other users: all the permissions

#### 9. John Doe
[Write a script that sets the mode of the file hello to this:](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/9-John_Doe)

#### 10. Look in the mirror
[Write a script that sets the mode of the file hello the same as olleh’s mode.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/10-mirror_permissions)

#### 11. Directories
[Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/11-directories_permissions)

#### 12. More directories
[Create a script that creates a directory called my_dir with permissions 751 in the working directory.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/12-directory_permissions)

#### 13. Change group
[Write a script that changes the group owner to school for the file hello](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/13-change_group)

#### 14. Owner and group
[Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/100-change_owner_and_group)

#### 15. Symbolic links
[Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/101-symbolic_link_permissions)

#### 16. If only
[Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/102-if_only)

#### 17. Star Wars
[Write a script that will play the StarWars IV episode in the terminal.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x01-shell_permissions/103-Star_Wars)
