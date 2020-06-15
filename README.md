# BASH-Tutorials
Commmonly used commands for working in the command line environment

**This site will be continuously updated throughout the week.**


### Secure Shell (SSH)
SSH is a method of securely communicating with another computer.

![alt text](https://www.hostinger.com/tutorials/wp-content/uploads/sites/2/2017/07/symmetric-encryption-ssh-tutorial.jpg)

### The Servers at UNH

![alt text](https://github.com/Joseph7e/HCGS-BASH-tutorial/blob/master/UNH_servers2.png?raw=true)

### Connecting to the server

[Download putty](https://www.putty.org/)

![alt text](https://github.com/Joseph7e/HCGS-BASH-tutorial/blob/master/Putty.PNG?raw=true)

### Transferring files

[Download CyberDuck](https://cyberduck.io/download/)

Alternative Tools:

  * Filezilla - https://filezilla-project.org/

  * WinSCP - https://winscp.net/eng/index.php

  * scp - for non-windows users. https://linuxize.com/post/how-to-use-scp-command-to-securely-transfer-files/

# Common bash commands

[NH INBRE Bioinformatics tutorials](http://nhinbre.org/bioinformatics-modules/)

### Anatomy of a Command

![alt text](https://github.com/Joseph7e/HCGS-BASH-tutorial/blob/master/anatomy.png?raw=true)

### Finding Help

```bash
# use the help option
command -help

# check the commands manual
man command

# get a short description
whatis command

```
Also, google and us!

### Paths and Directories

absolute paths always start at the **root** directory of the server - '/'
  + ex.) /home/genome/joseph7e

relative paths are **relative** to where you are currently located.
  + ex.) ../genome/devin/


**special characters**

  + ../ means up one level

  + ./ means your current directory

  + ~/ means your home directory


The **list dircetory** command - ls

```bash
# list the contents of your home directory, from anywhere
ls ~/

# list the content of the directory up one level
ls ../

# list the contents of a directory two levels up
ls ../../

```

### Moving About

The **change directory** command - cd

```
# change directory 
cd /home/genome/joseph7e

cd ../../

```

Don't forget to autocomplete with the *tab* key. This will make you more efficient and less prone to mistakes.


### Move, Copy and Delete

### Opening and editing files

### grep


