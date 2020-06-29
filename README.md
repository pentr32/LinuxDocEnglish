# What is Linux?

Linux means the kernel of the system where it is central to control everything on a PC. Linux is a combination of software, called GNU / Linux, which defines the operating system.

> *GNU is the free software that provides open source equivalents of many common UNIX commands.*
>
> *The Linux part of this combination is the Linux kernel, which is the core of the operating system.*

The story of Linux begins with UNIX, an operating system developed at AT&T Bell Labs in the 1970s.

> *UNIX is written in C programming language.*
>
> *Linux was written in C and Assembly language.* 

Linux started back in 1991 as a hobby project by Linus Torvalds who has studied in Helsinki, Finland at the University of Helsinki. Linux is Open-Source so that means everyone can use it, see source code and make changes.

Linus made the source programming code (the instructions a computer uses to operate) freely available, allowing others to participate and shape this new operating system.

Lots of hackers. **especially ethical hackers** use linux with python because python can import some tools that exist in the system and use them to make very advanced scripts. Python is also very easy to learn and it gives good performance.

**Free and Open Source Software (FOSS)** -  refer to a software where the copy-right has been given up, so  everyone is allowed to view source code and make changes. That's what Linus Torvalds has done with Linux even though he has created Linux he can't ban a person because Linus has given up rights with GPLv2 license.

**Free/Libre and Open Source Software (FLOSS)** - a researcher studying practices and methods used by developers in the free software community decided that these questions were independent of the developers' political views, so he used the term “FLOSS,” meaning “Free/Libre and Open Source Software,” to explicitly avoid a preference between the two political camps

<br><br>

## BSD

BSD stands for "Berkeley Software Distribution". It is the distribution name of the source code from the University of California, Berkeley which has been used as an extension to AT & T's Research UNIX operating system.

<br><br>

## Difference between Linux and BSD

Linux is a group of free open source operating systems built around Linux Kernel, which is like the UNIX operating system. It belongs to UNIX just like family operating systems. It was packaged as Linux distribution to distribute for both server and desktop purposes. BSD (Berkeley Software Distribution) is derived from the UNIX operating system, which was purely written in programming language C. It belongs to the UNIX operating system family. The core type of the BSD operating system is monolithic. The default user interface in BSD is the command line user interface.

<br><br>

|                |**Linux**                        |**BSD**                        |
|----------------|-------------------------------|-----------------------------|
|*License*|It is licensed under the General Public License (GPL).|It is licensed under the BSD License which is much less restrictive.fun?'|
|*Development*|Developed by the developer community.|Developed by the University of California, Berkeley.|
|*Control*|Mostly controlled by Linus Torvalds.|Not controlled.|
|*OS*|Concentrates mostly on kernel development.|Concentrates completely on an OS.|
|*Base system*|It is a group of many small 'sub systems'.|It has a base system that supports the entire operating system.|
|*Upgrade*|Difficult to upgrade and requires package management etc.|Easy to upgrade.|
|*Hardware support*|Supports all types of hardware for a short time.|Takes longer to support all types of hardware.|
|*Copy-left*|Have a copy-left.|No copy-left.|

<br><br>

## What is an Operating System (OS)

Software that runs on a computer device and manages the hardware and software components that make up the system. Commonly abbreviated as **OS**.

The users today will choose from among 3 major operating systems which are **Microsoft Windows**, **Apple macOS**, **Linux**. Only **Microsoft Windows** is based on proprietary code that is not **Unix** or **Linux** based.

<br><br>

## Basic linux commands.

Typical format for command is:
> *command [options] [arguments]*

<br>

**System**
|                |                        |                        |
|----------------|------------------------|------------------------|
|*uname -a*| --- |Display linux system infomartion|
|*uname -r*| --- |Display kernel release information|
|*uptime*| --- |Show how long the system has been running + load|
|*hostname*| --- |Show system host name|
|*hostname -i*| --- |Display the IP address of the host|
|*last reboot*| --- |Show system reboot  history|
|*date*| --- |Show the current date and time|
|*cal*| --- |Show the month  calendar|
|*w*| --- |Display who is online|
|*whoami*| --- |Who  you  are  logged in as|
|*finger user*| --- |Display information about user|

<br><br>

**Hardware**
|                |                        |                        |
|----------------|------------------------|------------------------|
|*dmesg*| --- |Detected hardware and boot messages|
|*cat /proc/cpuinfo*| --- |CPU model|
|*cat /proc/meminfo*| --- |Hardware memory|
|*cat /proc/interrupts*| --- |Lists the number of interrupts per CPU per I/O device|
|*lshw*| --- |Displays information on hardware configuration of the system|
|*lsblk*| --- |Displays block  device  related information in Linux|
|*free -m*| --- |Used and free  memory (-m for MB)|
|*lspci -tv*| --- |Show PCI devices|
|*lsusb -tv*| --- |Show USB devices|
|*dmidecode*| --- |Show hardware info from the BIOS|
|*hdparm -i/dev/sda*| --- |Show info about disk sda|
|*hdparm -tT /dev/sda*| --- |Do a read speed test on disk sda|
|*badblocks -s /dev/sda*| --- |Test for unreadable  blocks on disk sda|

<br><br>

**Users**
|                |                        |                        |
|----------------|------------------------|------------------------|
|*id*| --- |Show the active user id with login and group|
|*last*| --- |Show last logins on the system|
|*who*| --- |Show who is logged on the system|
|*groupadd  admin*| --- |Add  group "admin"|
|*useradd –c "Robert"*| --- |g admin –m sam #Create user "rob"|
|*userdel rob*| --- |Delete user rob|
|*adduser rob*| --- |Add user "rob"|
|*usermod*| --- |Modify user information|

<br><br>

**File commands**
|                |                        |                        |
|----------------|------------------------|------------------------|
|*ls -al*| --- |Display all information about files/ directories|
|*pwd*| --- |Show the path of current  directory|
|*mkdir  directory-name*| --- |Create a directory|
|*rm file-name*| --- |Delete file|
|*rm -r directory-name*| --- |Delete directory recursively|
|*rm -r file-name*| --- |Forcefully  remove file|
|*rm -rf directory-name*| --- |Forcefully  remove  directory recursively|
|*cp file1 file2*| --- |Copy file1 to file2|
|*cp -r dir1 dir2*| --- |Copy dir1 to dir2, create dir2 if it doesn't exist|
|*mv file1 file2*| --- |Rename source to dest / move source to directory|
|*ln -s /path/to/file-name link-name*| --- |Create symbolic link to file-name|
|*touch file*| --- |Create or update file|
|*cat > file*| --- |Place standart input into file|
|*more file*| --- |Output contents of file|
|*head file*| --- |Output contents of file|
|*tail file*| --- |Output last 10 lines of file|
|*tail -f file*| --- |Output contents of file as it grows  starting with the last 10 lines|
|*gpg -c file*| --- |Encrypt file|
|*gpg file.gpg*| --- |Decrypt file|
|*wc*| --- |Print the number of bytes, words, and lines in files|
|*xargs*| --- |Execute  command lines from standart input|

<br><br>

**Process  related**
|                |                        |                        |
|----------------|------------------------|------------------------|
|*ps*| --- |Display your  currently  active  processes|
|*ps aux / grep 'telnet'*| --- |Find all process id related to telnet process|
|*pmap*| --- |Memory map of process|
|*top*| --- |Display all running processes|
|*kill  pid*| --- |Kill  process with mentioned  pid id|
|*killall  proc*| --- |Kill all processes  named  proc|
|*pkill  process-name*| --- |Send signal to a process with its  name|
|*bg*| --- |Resumes suspended jobs without  bringing  them to foreground|
|*fg*| --- |Brings the most recent job to foreground|
|*fg n*| --- |Brings job n to the foreground|

<br><br>

**File permission related**
|                |                        |                        |
|----------------|------------------------|------------------------|
|*chmod  octal file-name*| --- |Change the permissions of file to octal|
|*chmod 777 /data/test.c*| --- |Set rwx permission for owner, group, world|
|*chmod 755 /data/test.c*| --- |Set rwx permission for owner, rx for group and world|
|*chown owner-user file*| --- |Change owner of the file|
|*chown  owner-user:owner-group file-name*| --- |Change owner of the file|
|*chown  owner-user:owner-group file-name*| --- |chown  owner-user:owner-group  directory|

<br><br>

**Network**
|                |                        |                        |
|----------------|------------------------|------------------------|
|*ip addr show*| --- |Display all network interfaces and ip address|
|*ip address add 192.168.0.1 dev eth0*| --- |Set ip address|
|*ethtool eth0*| --- |Linux tool to show ethernet status|
|*mii-tool eth0*| --- |Linux tool to show ethernet status|
|*ping host*| --- |Send echo  request to test connection|
|*whois domain*| --- |Get  who is information for domain|
|*dig domain*| --- |Get DNS information for domain|
|*dig -x host*| --- |Reverse  lookup host|
|*host google.com*| --- |Lookup DNS ip address for the name|
|*hostname -i*| --- |Lookup  local ip address|
|*wget file*| --- |Download file|
|*netstat -tupl*| --- |Listing all active  listening ports|

<br><br>

**Compression / archives**
|                |                        |                        |
|----------------|------------------------|------------------------|
|*tar cf home.tar home*| --- |Create  tar  named home.tar containing home/|
|*tar xf file.tar*| --- |Extract the files from file.tar|
|*tar czf file.tar.gz files*| --- |Create a tar with gzip  compression|
|*gzip file*| --- |Compress file and renames it to file.gz|

<br><br>

**Install  package**
|                |                        |                        |
|----------------|------------------------|------------------------|
|*rpm -i pkgname.rpm*| --- |Install  rpm  based  package|
|*rpm -e pkgname*| --- |Remove  package|

<br><br>

**Install from source**
|                |                        |                        |
|----------------|------------------------|------------------------|
|*./configure*| --- ||
|*make*| --- ||
|*make  install*| --- ||

<br><br>

**Search**
|                |                        |                        |
|----------------|------------------------|------------------------|
|*grep pattern files*| --- |Search for pattern in files|
|*grep -r pattern dir*| --- |Search recursively for pattern in dir|
|*locate file*| --- |Find all instaces of file|
|*find /home/rob -name 'index*'*| --- |Find files names  that start with "index"|
|*find /home -size +10000k*| --- |Find files larger  than 10000k in /home|

<br><br>

**Login (SSH and TELNET)**
|                |                        |                        |
|----------------|------------------------|------------------------|
|*ssh  user@host*| --- |Connect to host as user|
|*ssh -p port user@host*| --- |Connect to host using  specific port|
|*telnet host*| --- |Connect to the system using telnet port|

<br><br>

**File transfer**
|                |                        |                        |
|----------------|------------------------|------------------------|
|*scp*| --- ||
|*scp file.txt server2:/tmp*| --- |Secure copy file.txt to remote host /tmp folder rsync|
|*rsync -a /home/apps /backup/*| --- |Synchronize source to destination|

<br><br>

**Disk usage**
|                |                        |                        |
|----------------|------------------------|------------------------|
|*df -h*| --- |Show free  space on mounted filesystems|
|*df -i*| --- |Show free  inodes on mounted filesystems|
|*fdisk -l*| --- |Show disks partitions sizes and types|
|*du -ah*| --- |Display disk usage in human readable form|
|*du -sh*| --- |Display total disk usage on the current  directory|
|*findmnt*| --- |Displays target  mount point for all filesystem|
|*mount  device-path  mount-point*| --- |Mount device|

<br><br>

**Directory traverse**
|                |                        |                        |
|----------------|------------------------|------------------------|
|*cd ..*| --- |To go up one  level of the directory  tree|
|*cd*| --- |Go to $HOME directory|
|*cd /test*| --- |Change to /test directory|

<br><br>

# REMEMBER

> A pair of single quotes ( ' ) will  prevent the shell from interpreting  any  metacharacter.
> 
> The semicolon (;) can  be  used to separate multiple commands to be  executed in order.
> 
> To execute the same command as previously  executed  five  commands  ago, you  would type: !-5
> 
> HOME is an example of an environment variable.
>
> The command  that  can  report the location of a command: which
>
> The history  command  will print a list of the commands  that  you've  previously  executed.
>
> The environment variable that contains a list of directories that is searched for commands to execute is 'PATH'
>
> To search the man page sections for the keyword  example, which of the following  you can execute  'man –k example' and 'apropos example'
>
> The following  sections  commonly  appear on a man page: DESCRIPTION, NAME, SYNOPSIS
>
> To start searching a man page, the first  key you press is: /
>
> To exit the info page, press: Q
>
> Commands typically  executed by a user are covered in section 1 of the manual.
>
> If you  are  reading the synopsis of a command from a man page, then items in square  brackets  are: Optional
>
> The info page is like a guide; a man page is a more concise reference.
>
> Section 9 of man pages relates to **Kernel  routines**
