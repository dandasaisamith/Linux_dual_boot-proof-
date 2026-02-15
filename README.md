# Linux Dual Boot & Basic Commands – Proof Repository

>> Student Information
Name: Danda Sai Samith
Course: CYBER SECURITY
Date: 15/02/2026  


# 1️ Proof of Linux Dual Boot

##  System Information (Linux)
Output of `lsb_release -a`:

Distributor ID: Ubuntu  
Description:    Ubuntu 22.04.3 LTS  
Release:        22.04  
Codename:       jammy  

Output of `uname -r`:

6.5.0-18-generic  

Output of `whoami`:

sai
>> 2 Basic Linux Commands Usage

Below are commands I personally executed and tested:


## 1. pwd
Shows current working directory.

Example:
$ pwd


##  2. ls
Lists files and folders in a directory.

Example:
$ ls


##  3. cd
Changes directory.

Example:
$ cd Documents
$ pwd



##  4. mkdir
Creates a new folder.

Example:
mkdir linux_practice
 ls
linux_practice


##  5. touch
Creates a new file.

Example:
 touch test.txt
 ls
test.txt



##  6. cat
Displays file content.

Example:
$ cat test.txt



##  7. rm
Removes a file.

Example:
$ rm test.txt



##  8. man
Displays manual/help page.

Example:
$ man ls

 ## 9.UPGRADE   
to update the os 

sudo apt upgrade

 ## 10.UPDATE    
to update the version
sudo apt update
 

 ## 11.VS CODE  
 topen the vs code(custom)
code

 ## 12.TILIX    
 for multitasking of terminals
sudo apt install tilix -y
   tilix
    
 ## 13.sudo apt install konsole 
 to run the console 
 konsole



# 3️ My Personal Learning Notes 

>>  What I Learned About Dual Boot
Dual boot allows two operating systems to be installed on one computer. When the system starts, the GRUB bootloader lets the user choose which OS to load. I installed Ubuntu alongside Windows by shrinking the Windows partition and allocating space for Linux.

Key observations:
- Partition management is important.
- Backup is necessary before installing.
- GRUB is automatically configured during installation.


>> What I Learned About Linux Commands

Linux is command-line oriented and very powerful. Commands are case-sensitive. I learned that:

- `pwd` shows current directory path.
- `ls -l` shows detailed file permissions.
- `sudo` allows administrative access.
- File permissions use read (r), write (w), execute (x).

Example:
$ ls -l

-rw-r--r-- 1 user user 0 Feb 14 10:30 file.txt

This means:
Owner can read/write.
Group can read.
Others can read.


##  Challenges Faced
- Initially confused about partitions.
- Had to disable Secure Boot.
- Needed internet to update packages.


##  Conclusion
This exercise helped me understand:
- Linux installation process
- Terminal navigation
- File and directory management
- Basic system commands

I now feel comfortable using basic Linux commands in the terminal.
