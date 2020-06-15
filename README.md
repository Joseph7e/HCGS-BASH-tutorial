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

Absolute paths always start at the **root** directory of the server - '/'
  + ex.) /home/genome/joseph7e

Relative paths are **relative** to where you are currently located.
  + ex.) ../genome/devin/


**special characters**

  + ../ means up one level

  + ./ means your current directory

  + ~/ means your home directory


The **print working directory** command tells you the abolsute path to where yoy currently are.

```bash
pwd
```

The **list directory** command - ls

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


### Make Directories, Move, Copy and Remove

The **make directory** command - mkdir

  + mkdir <directory_name>

The **move** command - mv

  + mv <file> <destination>

The **copy** command - cp

  + cp <file> <destination>

The **remove** command - rm

  + rm <file>

```bash
# make a new directory
mkdir my_directory/

# move a file up one directory
mv my_file.txt ../

# move and rename a file
mv my_file.txt ../my_renamed_file.txt

# copy a file and rename
cp my_file.txt my_renamed_file.txt

# remove a file
rm my_renamed_file.txt

# remove a directory with the -r option, recursive
rm -r my_directory/

```


### Opening and editing files

There are a lot of commands to open files. The one you choose depends on what you want to do.

The **more** command allows you to view small pieces of a file at a time.

The **less** is similiar to more but has *more* options and is faster.

The **head** command shows you the top ten lines of a file.

The **tail** command shows you the bottom ten lines of a file.

The **cat** command prints the entire file to screen and also allows you to combine files together.


There are also a lot of commands to edit files. The easiest to use is **nano**.

https://wiki.gentoo.org/wiki/Nano/Basics_Guide


```bash

nano file.txt

```
### Searching through a file

**grep** is a tool that allows you to search through a file for a specified string. For example if you wanted to find your name in a roster.

```bash

grep "my search string" file.txt

```




