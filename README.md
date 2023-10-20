# Ex-01-Linux-Commands


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
 ![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/454188b1-a751-47f0-bec0-0c8a3390e452)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/bee191fb-e3d5-48d3-9932-e63f310fc3c1)


### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/8e1fab7e-e43b-44ad-a781-9bfd97922f0e)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/6d568c82-6b6e-473a-9ff3-b52f87e559ae)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/15a1c5f8-484f-4d2e-87d9-5256aeaa4077)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/feee197d-e0cb-448b-90a5-4c1163ea7a2b)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/0a282905-28df-4ce2-92fa-ae79f69fe11c)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/8ab62178-7bc7-4031-b198-12e0749b457b)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/25cdce1b-b8a1-481a-8d9e-ca545b7fca8f)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/8efd4ef8-b6c8-4e1b-b0e8-56b569313538)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/b6d9695d-d5aa-44f7-8975-8b33a6d168bc)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/9e0ee477-5e94-4efb-bcd5-0e912384466d)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/ff6a3b64-270e-47d1-b915-5b7f4d00ab18)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/7692bd6b-75cf-4b97-8cf5-1c3cfc7ee1a7)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/5ce1ab4f-3d93-4784-8daa-6cbcc5726691)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/9e0ace2f-b355-40df-86b9-4a089d8f0a9c)


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
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/b926090c-91a8-4bdf-9a59-9c5c09c98302)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/5406a091-66d5-41e2-b23a-43aabac57a6b)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/5118d6ed-d4e5-40e9-8696-525d32a4fa8b)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/f772b0c1-c7bc-4211-ac9b-c1b4d66d3b95)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/7d006876-b41f-4253-9eb0-630b591d8ad4)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/45fa2622-1b96-4b49-90bd-8618caa90c9f)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/302a91ca-e55b-4332-9283-9f822e2de910)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/77fba77b-2b39-45f9-9720-7cc389d51944)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/32352c1c-8041-460a-a8d7-1ef5622dc08f)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![image](https://github.com/AjaysuryaS/Ex-01-Linux-Commands/assets/114158396/caaaa897-690b-491b-92ed-7ed5c3b1de94)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
