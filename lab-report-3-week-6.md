# Week 6 Lab Report

### Streamlining ssh Configuration
---

[link to index](https://dan248lee.github.io/cs15l-lab-reports/index)

![image](sshfolder.jpg)
>Access the .ssh folder inside your pc
>
>Then open the folder through vs code

---

![image](configfile.jpg)
>Create a new file called config inside the ssh folder


---
![image](configwithssh.jpg)
>Open the config file using ~./.ssh/config

---
![image](addlines.jpg)
>Then add the lines of code given:
>>Host ieng6
    HostName ieng6.ucsd.edu
    User cs15lwi22zzz (use your username)

---
![image](sshieng6.jpg)
>Then access your ssh with the code ssh ieng6
>Congratulations!!!
---

>Now using the shorter method of calling a remote engine, lets copy a file using scp

![image](newFile.jpg)

>Created a new file called newFile.java
---

![image](CopiedFile.jpg)
>After copied the new file with the scp command, replacing the long username login with just ieng6