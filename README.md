# Ex-01-Linux-Commands

## NAME : KARTHIKEYAN M
## REG.NO : 212223110020

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
 
<img width="619" height="60" alt="Screenshot 2025-08-29 085556" src="https://github.com/user-attachments/assets/b72e46ed-eed0-4d5c-9b66-67047c6c4b8a" />


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="472" height="64" alt="Screenshot 2025-08-29 090602" src="https://github.com/user-attachments/assets/8d7f6d3c-ffa6-4084-9fd7-3a551e47e9b2" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="261" height="44" alt="Screenshot 2025-08-29 090611" src="https://github.com/user-attachments/assets/5dc1929f-cee6-4b50-b6f0-57e1921c87c0" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="302" height="51" alt="Screenshot 2025-08-29 090621" src="https://github.com/user-attachments/assets/10dda474-ac5b-4deb-874b-8e126c66cf00" />

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="242" height="48" alt="Screenshot 2025-08-29 090627" src="https://github.com/user-attachments/assets/6dd245be-56cc-4b21-bcc9-3a12058b56e6" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="380" height="63" alt="Screenshot 2025-08-29 090636" src="https://github.com/user-attachments/assets/d7d2885c-f4a2-4916-9f2d-985ccd7f8e89" />

### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="319" height="45" alt="Screenshot 2025-08-29 090642" src="https://github.com/user-attachments/assets/77971fd8-54e8-4ff2-8fc3-08aa0f46d0e2" />



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name


<img width="617" height="155" alt="image" src="https://github.com/user-attachments/assets/856c940b-c0fb-418d-a241-c98706b6ffe7" />


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>


<img width="271" height="88" alt="image" src="https://github.com/user-attachments/assets/d49b8295-2f60-4626-93b9-4845e80cd2ea" />

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="369" height="50" alt="Screenshot 2025-08-29 091002" src="https://github.com/user-attachments/assets/caf880a1-7096-4f17-9335-a95eb1808a3c" />

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="435" height="202" alt="Screenshot 2025-08-29 092337" src="https://github.com/user-attachments/assets/65407614-12a9-419b-a28d-0d5229031709" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>


 <img width="501" height="211" alt="Screenshot 2025-08-29 092448" src="https://github.com/user-attachments/assets/0b77091e-c459-4ef9-917d-d23d7a61d368" />

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id


<img width="1055" height="80" alt="Screenshot 2025-08-29 092904" src="https://github.com/user-attachments/assets/c26621df-7d06-490f-b588-d2eb0b436353" />

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="304" height="55" alt="Screenshot 2025-08-29 093705" src="https://github.com/user-attachments/assets/05f4a15e-ed4b-40be-bdd2-65845f327760" />

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>


<img width="387" height="65" alt="image" src="https://github.com/user-attachments/assets/4cff11a8-c2e1-43fe-a0e8-c8f49db4df06" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>


<img width="467" height="106" alt="image" src="https://github.com/user-attachments/assets/0dadf537-b615-4a59-af9c-4eea2c8f92d0" />


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c


### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]


<img width="630" height="147" alt="image" src="https://github.com/user-attachments/assets/a4f27d3f-9315-4bd4-a114-643272dce938" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

<img width="467" height="106" alt="image" src="https://github.com/user-attachments/assets/592c4e90-cf09-4d77-8c6f-c1b274ecb68d" />

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

 <img width="253" height="75" alt="image" src="https://github.com/user-attachments/assets/8c490f9b-bf2c-479e-ad78-1c2fc1b915da" />

### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal


<img width="733" height="354" alt="image" src="https://github.com/user-attachments/assets/543d7834-2a7e-4c4b-90ea-4f3193471abb" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


<img width="725" height="200" alt="image" src="https://github.com/user-attachments/assets/f8a35cb2-8e80-44eb-a4b7-95579c90bad2" />

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df


<img width="622" height="232" alt="image" src="https://github.com/user-attachments/assets/a3b8dd1b-9c00-45fe-a99b-2836dbb964ba" />


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
