# Shell, Permissions
* `0-iam_betty`: Changes the current user to betty.
* `1-who_am_i`: Prints the effective username of the current user.
* `2-groups`: Prints all groups the current user is part of.
* `3-new_owner`: Changes the owner of the file hello to the user betty.
* `4-empty`: Creates an empty file named hello.
* `5-execute`: Adds execute permission to the owner of the file hello.
* `6-multiple_permissions`: Adds execute permission to owner and group, and read permission to others, for the file hello.
* `7-everybody`: Adds execute permission to the owner, group owner, and other users for the file hello without using commas.
* `8-James_Bond`: Sets permissions of hello to no permissions for owner and group, and full permissions for others.
* `9-John_Doe`: Sets the mode of the file hello to -rwxr-x-wx.
* `10-mirror_permissions`: Sets the permissions of hello to match the permissions of olleh.
* `11-directories_permissions`: Adds execute permission to all subdirectories of the current directory for owner, group, and others without modifying regular files.
* `12-directory_permissions`: Creates a directory named my_dir with permissions 751.
* `13-change_group`: Changes the group owner of the file hello to school.
* `14-change_owner_and_group`: Changes the owner to vincent and the group owner to staff for all files and directories in the current working directory.
* `15-symbolic_link_permissions`: Changes owner and group owner of the symbolic link _hello to vincent and staff.
