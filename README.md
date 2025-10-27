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
 
<img width="1302" height="103" alt="image" src="https://github.com/user-attachments/assets/8da17cb7-a180-4460-8fdf-5ae44ca328fa" />


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="380" height="99" alt="image" src="https://github.com/user-attachments/assets/06834922-f739-4ce1-8cf3-5f4b48e0864c" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="1044" height="127" alt="image" src="https://github.com/user-attachments/assets/22bb5aa3-b070-4737-adab-968aef382f6d" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="997" height="139" alt="image" src="https://github.com/user-attachments/assets/d93f18bf-d4ba-42fb-8655-7f3313b24b0d" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="403" height="174" alt="image" src="https://github.com/user-attachments/assets/adf50c8d-0c7b-4f7b-9367-154c220a67e2" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="377" height="196" alt="image" src="https://github.com/user-attachments/assets/991d79e7-29f2-4c5c-aa2e-cb48c0334880" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="378" height="151" alt="image" src="https://github.com/user-attachments/assets/db8f7b82-b52e-4166-b015-e2f96d8c00cd" />



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="561" height="43" alt="image" src="https://github.com/user-attachments/assets/3839d18c-2020-4c9b-a4ac-d5e21d26d56c" />


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="329" height="100" alt="image" src="https://github.com/user-attachments/assets/db79cfa7-7617-4218-b207-2a6eb2299b2b" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

 <img width="275" height="209" alt="image" src="https://github.com/user-attachments/assets/bdfccdc3-536e-4b9f-9ad2-09b416fabb1d" />

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="393" height="297" alt="image" src="https://github.com/user-attachments/assets/7523c006-ed00-40e7-beff-f572507a5a0a" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="439" height="586" alt="image" src="https://github.com/user-attachments/assets/4bebda5a-8aa6-4bce-b167-bef10f6ca2db" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="318" height="254" alt="image" src="https://github.com/user-attachments/assets/b528310a-a6fb-413f-86ae-66bca6ccaf7a" />

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="1730" height="76" alt="image" src="https://github.com/user-attachments/assets/b94f78a5-5975-42b6-9d6a-38902ddc7dbb" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="584" height="115" alt="image" src="https://github.com/user-attachments/assets/2d2046b0-5dcb-4a7b-ad82-bdba1435d591" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="724" height="510" alt="image" src="https://github.com/user-attachments/assets/9b37c772-ca2b-489d-9033-c1f2dd7cae1e" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

<img width="764" height="198" alt="image" src="https://github.com/user-attachments/assets/c45bdf63-4d53-4118-a4d7-1679b188d484" />

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

 <img width="616" height="265" alt="image" src="https://github.com/user-attachments/assets/d2748aa0-da76-4d81-a878-88c6c8076262" />

### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="392" height="112" alt="image" src="https://github.com/user-attachments/assets/b3550f3e-ab9a-4463-9155-b9c2a6819e11" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="812" height="226" alt="image" src="https://github.com/user-attachments/assets/df8cd85f-973b-4ef3-aebd-864765be5d13" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="1063" height="127" alt="image" src="https://github.com/user-attachments/assets/3f26fe32-1ea6-4329-9699-cc526ab7a2ae" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

 <img width="610" height="145" alt="image" src="https://github.com/user-attachments/assets/de689df7-8baa-4358-9ef7-d34746c06988" />

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="716" height="125" alt="image" src="https://github.com/user-attachments/assets/02eb049a-907d-4b48-920f-33f9eaa17498" />

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="1171" height="177" alt="image" src="https://github.com/user-attachments/assets/ea36ea94-0679-4980-a7fe-8d189e9b8eec" />


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

 <img width="288" height="379" alt="image" src="https://github.com/user-attachments/assets/86753b47-58ea-455b-a598-ac4317d03331" />

### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
<img width="361" height="247" alt="image" src="https://github.com/user-attachments/assets/d5a6ff1b-ed2e-4ac1-81db-5ea80483d653" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
<img width="737" height="706" alt="image" src="https://github.com/user-attachments/assets/49f55872-7d44-4f84-be2b-ca9ec53f50eb" />

<img width="391" height="150" alt="image" src="https://github.com/user-attachments/assets/e80a5eee-90a3-4cce-81c9-cc70a23e758a" />

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
<img width="595" height="54" alt="image" src="https://github.com/user-attachments/assets/e6fcb5b1-f602-427c-ba72-832d6bde2591" />

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
<img width="741" height="230" alt="image" src="https://github.com/user-attachments/assets/421463ab-0efb-4e7c-b31f-857ebcdd1740" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="220" height="59" alt="image" src="https://github.com/user-attachments/assets/b10327ab-8e03-46b4-8da8-21337c20b491" />

<img width="267" height="56" alt="image" src="https://github.com/user-attachments/assets/7e7cdee7-fa3c-4845-b650-cbc60cddcc5b" />

## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
