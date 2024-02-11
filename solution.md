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

![fileB dummycontent](images/dummyfileB.png)

5. Copying fileA contents to fileC contents with ```cp /home/altschool/misc/fileA /home/altschool/misc/filec```

![copying files with cp](images/cpFileC.png)

6. Moving fileB content with ```mv /home/altschool/misc/fileB /home/altschool/misc/fileD```

![moving contents with mv](images/mvfileD.png)

7. Creating misc.tar archive with ```tar -cvf misc.tar misc```

![misc.tar archive](images/tararchive.png)

8. Compressing misc.tar archive created with ```gzip misc.tar```

![Compressing tar archive](gziptar.png)

