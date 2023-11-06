![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/0579aa0f-e55a-45d3-991d-ee5d931a08d0)# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/2e25d1f8-ae87-48e6-b54f-343696b36169)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/31e62ce1-5261-43a2-a8c5-96d3200f6588)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/c3ec4d9f-3f88-473b-a731-4fb78150b1da)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/d31f18fa-373d-4822-8e67-4d8d8ff751a9)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/94eee196-7fcf-4405-b004-fcd99cd219e2)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/d9a8c40d-01ec-434d-a5f1-0961897fa36b)


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/22400268-dafd-4d89-b9a9-d0712185d83c)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/41f55dbb-0edc-4628-804c-0fab51abdbba)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/1fcb6c88-f6f0-4e7c-9e3a-565b9404ea37)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/db7426c2-0b41-49c4-b420-b459ab7b43d0)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/8ac12aa7-5a4f-4537-b4c6-66db5fa7eeb1)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/8a0384f6-d0c1-4d95-96d2-77be9bb83d7f)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/7de37e85-8bb6-4e46-b6e1-251ab8114da4)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/07e9ef8f-61fb-45f9-98ed-db9565d2cf24)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/7a3cdb05-5992-422d-97d4-ab5b31183811)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/94111500-d7f4-4d98-9f03-f52b3876efd5)

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/a38dccb4-47ac-4766-8f4a-3d6692f56ce5)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/52ef1566-e4ca-4e9c-9d3e-96b2a9e70004)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/d752c2f5-ec9f-41ae-b630-70ca0f5a14ca)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/057e6ea9-48cf-43ed-8916-0d8d5813f231)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/b59bb849-47c8-4c32-9432-38135553846b)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/067b49a2-4715-4f1e-a152-3b1884ce710e)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/b6329a4b-b327-4003-be5c-c6dde99093cd)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/b848aee1-1051-42f1-a145-c27b2bb2d964)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/45af348f-e969-4f70-a9a7-f019ff09236d)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/114158396/f712e9ab-5491-4ec8-9d47-d238ec7dc607)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
