su betty - switches the current user to the user
id -un - prints the effective username of the current user
id - prints all the groups the current user is part of
sudo chown betty hello - changes the owner of the file hello to the user betty
touch hello - creates an empty file called hello
chmod 700 hello - adds execute permission to the owner of the file hello
chmod 114 hello - adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
chmod 111 hello - adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 007 hello - sets the permission to the file hello as follows
chmod 753 hello - sets the mode of the file hello
sudo chmod --reference=olleh hello - sets the mode of the file hello the same as olleh’s mode
chmod a+X * - adds execute permission to all subdirectories of the current directory
mkdir -m 751 my_dir - creates a directory called my_dir with permissions 751
chgrp school hello - changes the group owner to school for the file hello
