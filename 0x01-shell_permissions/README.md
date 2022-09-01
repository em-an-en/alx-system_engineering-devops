0-iam_betty switches the current user to the user betty
1-who_am_i prints the effective username of the current user
2-groups prints all the groups the current user is part of
3-new_owner changes the owner of a file hello to the user betty
4-empty creates an empty file called hello
5-execute adds execute permission to the owner of the file hello
6-multiple_permissions adds execute permission to the owner and the group owner & read permission to the other users to the file hello
7-everybody adds execute permission to the owner, the group owner and the other users, to the file hello
8-James_Bond sets no permission to the owner and group owner & all permissions for other users to the file hello
9-John_Doe sets the mode of the file hello to all permissions for the owner, read & execute permissions for the group owner and write & execute permissions for other users
10-mirror_permissions sets the mode of the file hello the same as olleh's mode, both files are in the working directory
11-directories_permissions adds execute permissions to all subdirectories of the current directory for the owner, the group owner and all other users but the regular files should remain unchanged
12-directory_permissions creates a directory called my_dir with permissions 751 in the working directory
13-change_group changes group owner to school for the file hello
100-change_owner_and_group changes the owner to vincent and the group owner to staff for all the files and directories in the wd
101-symbolic_link_permissions changes the owner and the group owner of _hello to vincent and staff respectively, the file _hello is a symbolic link and is in the wd
102-if_only changes owner of the file hello to betty only if it is owned by guillaume, the file is in the wd
103-Star_Wars will play the Star Wars IV episode in the terminal
