# Commands and Screenshots for Assignment

##### Created the altschool user with ```sudo adduser -m altschool```
   
![useradd screenshot](images/1.altschooluser.png)

#### After switching to the altschool, created the sub directories with ```mkdir code tests personal misc```

![subdirectories screenshot](images/1b.subdirectories.png)

1. Changing directory to the tests using absolute pathname with ```cd /home/altschool/tests```

![absolutepath screenshot](images/2a.abslutetests.png)

2. Changing directory to the tests using relative pathname with ``` cd ./tests```

![relativepath screenshot](images/2b.relativetests.png)

3. Using echo command to creae a fileA with ```echo 'Hello A' > /home/altschool/misc/fileA```

![echo Hello A](images/3.echoHelloA.png)

4. Creating empty fileB with ```touch /home/altschool/misc/fileB``` and using `echo` for dummy content

![fileB dummycontent](images/4.dummyfileB.png)

5. Copying fileA contents to fileC contents with ```cp /home/altschool/misc/fileA /home/altschool/misc/filec```

![copying files with cp](images/5.cpFileC.png)

6. Moving fileB content with ```mv /home/altschool/misc/fileB /home/altschool/misc/fileD```

![moving contents with mv](images/6.mvfileD.png)

7. Creating misc.tar archive with ```tar -cvf misc.tar misc```

![misc.tar archive](images/7.tararchive.png)

8. Compressing misc.tar archive created with ```gzip misc.tar```

![Compressing tar archive](images/8.gziptar.png)

9. Creating a user and forcing the user to change his password upon login
> We first have to make our altschool user a sudoer then proceed to create the user and the password expiry command.

![making altschool a sudoer](images/9a.sudooaltschool.png)

> Adding the user val using the `adduser`

![Creating val user](images/9b.userval.png)

> Passwd expiry upon login command for val user with ```sudo passwd --expire val```

![Password expiry](images/9c.valpasswd.png)

10. To lock a user password with ```sudo passwd -l val```

![User lock](images/10.userlock.png)

11. Creating a valerie user with no login shell with command ```sudo useradd -s /sbin/nologin valerie```

![no login shell user(images/nologinshell.png)]

12. Disabling password based authentication for ssh with ```sudo vi /etc/ssh/shd_config```
> It's already disabled in the config file

![vi ssh config file](images/12.passwdauth.png)

13. Disabling root login for ssh using the same command by editing the ssh config file with ```sudo vi /etc/ssh/sshd_config```

![root ssh config](images/13.root.png)
