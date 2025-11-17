# Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands
## NAME: YASHWINI M
## REG NUMBER: 212223230249
## Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

 ## 3.a) Installation and Configuration of Oracle VirtualBox
# Aim:
To install and configure Oracle VM VirtualBox.

# Pre-requisites:
* Machine with Internet access

* Minimum 4 GB RAM

* Sufficient storage space

# Steps:
1.Download Oracle VM VirtualBox:

* Visit Oracle VirtualBox Official Site
* Download installer for your OS (Windows/macOS/Linux).

2.Install Oracle VM VirtualBox (Example: Windows):

* Launch Installer → Allow Changes → Click Next.
* Choose Installation Options → Click Next.
* Accept Network Interface Warning → Click Yes.
* Click Install.
* Finish Installation and Launch VirtualBox.

3.Configure VirtualBox:

* Open VirtualBox.

* Click New → Name VM → Select Type (Linux/Windows) and Version.

 * Allocate:

Minimum 2 GB RAM

Create Virtual Hard Disk (20 GB recommended).

* Start Virtual Machine and provide ISO to install OS.

# Result:
Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux
# Aim:
To install and configure Kali Linux in Oracle VirtualBox.

# Pre-requisites:
* Oracle VM VirtualBox Installed

* 4 GB RAM and 20 GB Storage Minimum

* Kali Linux ISO image
# Steps:
1.Download Kali Linux ISO:

* Visit Kali Linux Official Site

* Download 64-bit ISO (Installer version).

2.Create a New Virtual Machine:

* Open VirtualBox → Click New.

* Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).

3. Allocate Memory:
* Minimum 2 GB RAM (recommended 4 GB).

4.Create Virtual Hard Disk:


* Select VDI (VirtualBox Disk Image).

* Choose Dynamically allocated.

* Set Disk size to 20 GB or more.

5.Configure ISO Image:

* Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.

6.Start Installation:

* Boot Virtual Machine → Choose Graphical Install.

* Set Language, Region, Keyboard.

* Configure Network → Set Hostname (e.g., kali).

* Set root password.

* Disk Partitioning: Use entire disk → All files in one partition.

* Install System → Install GRUB Bootloader → Finish Installation.

7.Login to Kali Linux:

* Use root credentials.

8.(Optional) Install Guest Additions:

* Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
# Snapshots:
AWS Account Creation Snapshot

## Snapshot 1: Installing Oracle VirtualBox image

<img width="1161" height="427" alt="image" src="https://github.com/user-attachments/assets/4601a0ef-d745-41f6-ad82-5f3dc39058a5" />

## Snapshot 2: Kali Running in Virtual image

<img width="787" height="483" alt="image" src="https://github.com/user-attachments/assets/1fbcef39-2761-4f43-9492-4af14ee84661" />

# Result:
Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali
# About Linux:

* Open-source operating system.

* Kernel manages communication between hardware and software.

* Commands are case-sensitive.
# Commands:
# 1) ls Command

The ls command is used to display a list of content of a directory.

Syntax: ls

<img width="783" height="57" alt="image" src="https://github.com/user-attachments/assets/f5a47861-18c6-4691-bf31-71ee845752b9" />

# 2) pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
<img width="250" height="67" alt="image" src="https://github.com/user-attachments/assets/f109b5da-c6db-483c-b169-7bfca0a073c2" />


# 3) mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir

<img width="795" height="92" alt="image" src="https://github.com/user-attachments/assets/cbc52820-d96a-42aa-a805-74967f55fb63" />

# 4) rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir

<img width="766" height="102" alt="image" src="https://github.com/user-attachments/assets/c51c75a9-fa58-4bcc-aa8c-9b5509b29c93" />

# 5) cd Command

The cd command is used to change the current directory.

Syntax: cd



# 6) cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..


<img width="362" height="212" alt="image" src="https://github.com/user-attachments/assets/09efb782-1edc-416d-aebd-fae177fc4ca6" />

# 7) cp Command

The cp command is used to copy a file or directory.

Syntax: cp


<img width="315" height="157" alt="image" src="https://github.com/user-attachments/assets/12fc3307-5834-445e-b1d0-9bbe63255651" />


# 8) gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name


<img width="415" height="37" alt="image" src="https://github.com/user-attachments/assets/3a0038a2-4240-4c8c-97b5-2eb0aca63841" />

# 9) su Command
The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su


<img width="276" height="105" alt="image" src="https://github.com/user-attachments/assets/abadda1d-b010-48f3-94b6-23557eb24ed6" />

# 10) mv Command
The mv command is used to move a file or a directory form one location to another location.

Syntax: mv


<img width="391" height="317" alt="image" src="https://github.com/user-attachments/assets/28af63c8-37d8-495f-a18f-e8151d93fdf9" />

# 11) rename Command
The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files


<img width="472" height="203" alt="image" src="https://github.com/user-attachments/assets/2e33b4fa-254e-4af5-a08b-b846553a70b2" />

# 12) head Command
The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head


<img width="423" height="647" alt="image" src="https://github.com/user-attachments/assets/360a7499-4039-47e6-980b-e390309b5616" />

# 13) tail Command
The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail


<img width="305" height="275" alt="image" src="https://github.com/user-attachments/assets/84bf474c-e3b8-4ffb-b955-0ab9e4a5977f" />

# 14) id Command
The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="807" height="31" alt="image" src="https://github.com/user-attachments/assets/4f52e986-6d38-43a7-ae0d-1f173730831c" />


# 15) grep Command
The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep


<img width="368" height="77" alt="image" src="https://github.com/user-attachments/assets/ee9fda3b-8878-46b3-a3b2-7a2ad3ef217e" />

# 16) tr Command
The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>


<img width="422" height="363" alt="image" src="https://github.com/user-attachments/assets/108cd05c-3a5b-4e41-b5d0-6e14e50a7d27" />

# 17) chmod Command
The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<file_name>



<img width="522" height="138" alt="image" src="https://github.com/user-attachments/assets/2e015f71-baa0-40d5-8002-42937e42cc3a" />

# 18) tar Command
The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved] $ tar xvzf file.tar *.c


<img width="405" height="185" alt="image" src="https://github.com/user-attachments/assets/73654aa4-e11d-4901-9334-820aefde655a" />

# 19) chown Command
The chown command is used to change ownership.

Syntax: chown owner_name file_name


<img width="532" height="155" alt="image" src="https://github.com/user-attachments/assets/b8a2b8fa-b095-45f8-974c-a379a99a7bde" />

# 20) make Command
The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="253" height="72" alt="image" src="https://github.com/user-attachments/assets/b319bc46-9b86-43af-8f1b-ac218c49d9d9" />

# 21) ifconfig Command
The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]


<img width="747" height="87" alt="image" src="https://github.com/user-attachments/assets/5bebe4e9-28fc-40b8-bf5d-2618c5e4697f" />

# 22) chmod 777 Command
The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name $chmod -R 777 /path/to/file/or/folder


<img width="542" height="137" alt="image" src="https://github.com/user-attachments/assets/509b3a93-ae93-47c1-852b-e9d37513cf37" />

# 23) host Command
The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host or


<img width="608" height="120" alt="image" src="https://github.com/user-attachments/assets/4cb52485-72e9-4b68-9967-dbbfb70a7fdc" />

# 24) gzip Command
The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip ..



# 25) sort Command
The sort command is used to sort files in alphabetical order.

Syntax:sort


<img width="265" height="363" alt="image" src="https://github.com/user-attachments/assets/2e8d9d29-4e4b-47f7-9fe8-52636da381a6" />

# 26) cal Command
The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal


<img width="318" height="233" alt="image" src="https://github.com/user-attachments/assets/8a213217-ee35-47dc-a4c1-543588cb31b7" />

# 27) clear Command
Linux clear command is used to clear the terminal screen.

Syntax: clear


<img width="683" height="772" alt="image" src="https://github.com/user-attachments/assets/48ac904b-7486-4035-8a97-d0e0117f2831" />

<img width="547" height="286" alt="image" src="https://github.com/user-attachments/assets/0a377cda-a9d4-40fd-9f60-1c7a4d256be7" />


# 28) mail Command
The mail command is used to send emails from the command line.

Syntax: mail -s "Subject"


<img width="771" height="65" alt="image" src="https://github.com/user-attachments/assets/5291a3d5-ef0d-4ba9-954d-d08e274526cc" />

# 29) df Command
The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df


<img width="761" height="248" alt="image" src="https://github.com/user-attachments/assets/ddd09234-3826-4d7e-9a51-84441104c848" />

# 30) find Command
The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”


<img width="342" height="96" alt="image" src="https://github.com/user-attachments/assets/a855266b-9b2b-4bcc-8edb-6c76819bc11c" />


<img width="381" height="85" alt="image" src="https://github.com/user-attachments/assets/cbd77c63-1a73-4b71-8bfb-10e0b9bfd642" />


# Result:
Thus, the execution of various Linux commands is executed successfully using Kali Linux.
