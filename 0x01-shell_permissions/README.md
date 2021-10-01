Exercise 0: su betty Script that changes your user ID to betty.

Exercise 1: id -un Print the effective user ID of current user. Other alternative is whoami

Exercise 2: id -Gn Prints all the groups the current user is part of.

Exercise 3: chown betty hello Changes the owner of the file hello to the user betty

Exercise 4: touch hello Create an empty file called hello

Exercise 5: chmod u+x hello Add execute permission to the owner of the file hello

Exercise 6: chmod ug+x,o+r hello Add execute permission to user and group owner, and read permission to others for file hello

Exercise 7: chmod ugo+x hello Add execution permission to all for file hello.

Exercise 8: chmod 007 hello Set permissions for file hello so owner and group don't have any permissions and other users have all permissions.

Exercise 9: chmod 753 hello Set permissions so owner has all permissions, group has read and execute permissions and others have write and execute permissions.

Exercise 10: chmod --reference=olleh hello Copies the mode of file olleh to file hello.

Exercise 11: chmod -R +X . Add execute permission to all subdirectories of the current directory for the everyone. Regular files should not be changed.

Exercise 12: mkdir -m 751 dir_holberton Create a directory called dir_holberton with permissions 751 in the working directory. User has all read, write, and execute permissions. Group has read and execute permissions. Others have just execute permission.

Exercise 13: chgrp holberton hello Change gorup owner to holberton for the file hello
# holberton-system_engineering-devops
