0- The script 0-iam_betty in the file switches the current user to the user betty.

1- The script 1-who_am_i in the file prints the effective username of the current user.

2- The script 2-groups in the file prints all the groups the current user is part of.

3- THe script 3-new_owner in the file changes the owner of the file hello to the user betty.

4- The script 4-empty in the file creates an empty file called hello.

5- The script 5-execute in the file adds execute permission to the owner of the file hello.

6- The script 6-multiple_permissions in the file adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

7- The script 7-everybody in the file adds execution permission to the owner, the group owner and the other users, to the filehello.

8- The script 8-James_Bond in the file sets the permission to the file hello as follows:

	Owner: no permission at all
	Group: no permission at all
	Other users: all the permissions

9- The script 9-John_Doe sets the mode of the file hello to this:
	-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

10- The script 10-mirror_permissions in the file sets the mode of the file hello the same as olleh's mode.

11- The script 11-directories_permissions in the file adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

12- The script 12-directory_permissions in the file creates a directory called my_dir with permissions 751 in the working directory.
