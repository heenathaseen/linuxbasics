### alias


    Aliases are very useful when it comes to fast working in Linux,used to run a long or hard remember command with a simple word. There are two types of aliases temporary and permanent.

### unalias

    The unalias command is used to remove entries from the current user's list of aliases. unalias removes aliases created during the current login session. It also suppresses permanent aliases; however, they are affected only for the current login session and are restored after the user logs in again.

### arch
    arch command is used to print the computer architecture. Arch command prints things such as “i386, i486, i586, alpha, arm, m68k, mips, sparc, x86_64, etc.

### arp

    arp command manipulates the System’s ARP cache. It also allows a complete dump of the ARP cache. ARP stands for Address Resolution Protocol. The primary function of this protocol is to resolve the IP address of a system to its mac address, and hence it works between level 2(Data link layer) and level 3(Network layer).

### at
    The at command schedules a command to be run once at a particular time that you normally have permission to run. The at command can be anything from a simple reminder message, to a complex script. You start by running the at command at the command line, passing it the scheduled time as the option. It then places you at a special prompt, where you can type in the command (or series of commands) to be run at the scheduled time. When you're done, press Control-D on a new line, and your command will be placed in the queue.

### awk
    Awk is a scripting language which is used for processing or analyzing text files. Or we can say that awk is mainly used for grouping of data based on either a column or field , or on a set of columns. Mainly it's used for reporting data in a usefull manner.

### bc

    bc command is used for command line calculator where we can do basic mathematical calculations.
### blkid
    The blkid program is the command-line interface to working with libblkid(3) library. It can determine the type of content (e.g. filesystem, swap) a block device holds, and also attributes (tokens, NAME=value pairs) from the content metadata (e.g. LABEL or UUID fields).
### cal
    cal command is a calendar command in Linux which is used to see the calendar of a specific month or a whole year.
### cd
    The cd command, also known as chdir (change directory), used to change the current working directory in operating systems 
### chage
    The chage command is restricted to the root user, except for the -l option, which may be used by an unprivileged user to determine when his/her password or account is due to expire.
### chattr
    The chattr command in Linux is a file system command which is used for changing the attributes of a file in a directory. The primary use of this command is to make several files unable to alter for users other than the superuser. 

### chgrp
    The chgrp command changes the group of each FILE to GROUP. If the --reference option is specified, chgrp changes the group of each FILE to that of RFILE.
### chmod
    A set of flags associated with each file determines who can access that file, and how they can access it. These flags are called file permissions or modes, as in "mode of access." The command name chmod stands for "change mode." It restricts the way a file can be accessed.
### chown
    chown command changes the user and/or group ownership of for given file. 
### cp
    cp stands for copy. This command is used to copy files or group of files or directory. It creates an exact image of a file on a disk with different file name. cp command require at least two filenames in its arguments.
### cpio
    cpio stands for “copy in, copy out“. It is used for processing the archive files like *.cpio or *.tar. This command can copy files to and from archives.

### crontab
    crontab command opens the cron table for editing. The cron table is the list of tasks scheduled to run at regular time intervals on the system.
### curl
    curl command in Linux with Examples. curl is a command line tool to transfer data to or from a server, using any of the supported protocols (HTTP, FTP, IMAP, POP3, SCP, SFTP, SMTP, TFTP, TELNET, LDAP or FILE). 
### cut
    The cut command is a command for cutting out the sections from each line of files and writing the result to standard output. It can be used to cut parts of a line by byte position, character and field. 
### date
    date command is used to display the system date and time. date command is also used to set date and time of the system. 
### dd
    dd is a command-line utility  whose primary purpose is to convert and copy files.
    
### df
     df command that displays the amount of disk space available on the file system containing each file name argument.
   
### diff
    diff stands for difference, is used to display the differences in the files by comparing the files line by line. 
### dig
    Dig stands for (Domain Information Groper) is a network administration command-line tool for querying Domain Name System (DNS) name servers. It is useful for verifying and troubleshooting DNS problems and also to perform DNS lookups and displays the answers that are returned from the name server that were queried.
### dnf
    DNF is a software package manager that installs, updates, and removes packages on RPM-based Linux distributions. It automatically computes dependencies and determines the actions required to install packages
### du
    du command, short for disk usage, is used to estimate file space usage and also used to track the files and directories which are consuming excessive amount of space on hard disk drive.
### expr
    The expr command evaluates a given expression and displays its corresponding output. It is used for:
    Basic operations like addition, subtraction, multiplication, division, and modulus on integers.
    Evaluating regular expressions, string operations like substring, length of strings etc.
### fdisk
    fdisk' Command To Manage Disk Partitions In Linux. Fdisk(fixed disk or format disk) is a text-based command-line utility for viewing and managing hard disk partitions on Linux. Using fdisk you can view, create, resize, delete, change, copy and move partitions.
### file
    The file command tests each argument in an attempt to classify it. There are three sets of tests, performed in this order: filesystem tests, magic tests, and language tests. The first test that succeeds causes the file type to be printed.
### find
    Find is a command for recursively filtering objects in the file system based on a simple conditional mechanism. Use find to search for a file or directory on your file system. Using the -exec flag, files can be found and immediately processed within the same command.
### firewall-cmd
    The command-line tool firewall-cmd is part of the firewalld application, which is installed by default. It can be used to make permanent and non-permanent runtime changes.
### free
     free command which displays the total amount of free space available along with the amount of memory used and swap memory in the system, and also the buffers used by the kernel
### ftp
    The ftp command runs the classical command-line file transfer client, FTP. It's an interactive text user interface for using the ARPANET standard File Transfer Protocol. It can be used to transfer files to and from a remote network
### grep
    The grep command which stands for “global regular expression print,” processes text line by line and prints any lines which match a specified pattern. The grep command is used to search text or searches the given file for lines containing a match to the given strings or words.
### head
     The head command, as the name implies, print the top N number of data of the given input. By default, it prints the first 10 lines of the specified files. If more than one file name is provided then data from each file is preceded by its file name.

### history
    The GNU history command keeps a list of all the other commands that have been run from that terminal session, then allows you to replay or reuse those commands instead of retyping them.
### hostname
    Description. hostname is used to display the system's DNS name, and to display or set its hostname or NIS (Network Information Services) domain name. When called without any arguments, hostname displays the name of the system as returned by the gethostname function.
### id
    id command in Linux is used to find out user and group names and numeric ID’s (UID or group ID) of the current user or any other user in the server. .
### ifconfig
    Ifconfig stands for "Interface Configuration",IFCONFIG command to assign ip address and netmask to an interface or to disable or enable a given interface.
### iostat
    The iostat command is used for monitoring system input/output device loading by observing the time the devices are active in relation to their average transfer rates. The iostat command generates reports that can be used to change system configuration to better balance the input/output load between physical disks.
### ip
    The ip command is used to assign an address to a network interface and/or configure network interface parameters on Linux operating systems. This command replaces old good and now deprecated ifconfig command on modern Linux distributions.
### kill
    kill command in Linux (located in /bin/kill), is a built-in command which is used to terminate processes manually. kill command sends a signal to a process which terminates the process.
### last
    The last command in Linux is used to display the list of all the users logged in and out since the file /var/log/wtmp was created. One or more usernames can be given as an argument to display their login in (and out) time and their host-name.
### less and more
    Similar to more, less command allows you to view the contents of a file and navigate through file. The main difference between more and less is that less command is faster because it does not load the entire file at once and allows navigation though file using page up/down keys.
### ln
    The ln command is used to create links between files. Before going into the application of the ln command in detail, please refer the below link for a clear understanding of the hard link and soft link in Linux
### locate
    locate command is used to find the files by name. 
### lpstatandlpadmin
    lpstat displays status information about the current classes, jobs, and printers. When run with no arguments,lpstat will list jobs queued by the current user.
    lpstat is now part of the CUPS (Common Unix Printing System). You may need to install CUPS before using lpstat, and related tools such as lpr.
    lpadmin configures printer and class queues provided by the common printing system CUPS. It can also be used to set the server default printer or class.

### ls
    The ls command isused to list information about files and directories within the file system. 
### lsof
    lsof meaning 'LiSt Open Files' is used to find out which files are open by which process.
### lspci
    lspci is a command that prints detailed information about all PCI buses and devices in the system. It is based on a common portable library libpci which offers access to the PCI configuration space on a variety of operating systems.
### mail
    Whenever a mail is sent, initially the mail command calls the standard send mail binary which is located in /usr/sbin/sendmail. This call will connect the local Mail Transfer Agent (MTA) into sending the email to the destination. The Simple Mail Transfer Protocol (SMPT) server on port 25 which is locally running Mail Transfer Agent (MTA) will receive the emails.
### man
    The man command is used to format and display the man pages. The man pages are a user manual that is by default built into most Linux distributions (i.e., versions) and most other Unix-like operating systems during installation.
### mdadm
    To create a RAID 5 array with these components, pass them in to the mdadm --create command. You will have to specify the device name you wish to create ( /dev/md0 in our case), the RAID level, and the number of devices: sudo mdadm --create --verbose /dev/md0 --level=5 --raid-devices=3 /dev/sda /dev/sdb /dev/sdc.
### mkdir and rmdir

    Directories are created with the mkdir function and deleted with the rmdir function. This function creates a new, empty directory. The entries for dot and dot-dot are automatically created. The specified file access permissions, mode, are modified by the file mode creation mask of the process.
### mkisofs
    Mkisofs command is used to create filesystems for writing on CD-ROM devices. The mkisofs command prepares the files to be burnt on the medium. mkisofs creates an iso file, which is the image file (archive) of the optical disk.
### mount
     The mount command mounts a storage device or filesystem, making it accessible and attaching it to an existing directory structure.
### mutt
    Mutt is a command line based Email client. It's a very useful and powerful tool to send and read mails from command line. Mutt also supports POP and IMAP protocols for receiving mails. It opens with a coloured interface to send Email which makes it user friendly to send emails from command line.
### mv
    mv stands for move. mv is used to move one or more files or directories from one place to another in file system 
### nano
    GNU nano is a popular command line text editor t

### netstat
    Netstat command displays various network related information such as network connections, routing tables,interface statistics, masquerade connections, multicast memberships etc.,
### nice
     nice runs command COMMAND with an adjusted "niceness", which affects process scheduling. A process with a lower niceness value is given higher priority and more CPU time. A process with a higher niceness value (a "nicer" process) is given a lower priority and less CPU time, freeing up resources for processes that are more demanding.Niceness values range from -20 (most favorable to the process) to 19 (least favorable to the process).With no COMMAND, nice prints the current niceness level.
### renice
     the renice command modifies the priority of running processes. It is similar to the nice command, but is used for processes that are already running.
### nslook
     nslookup command. nslookup (name server lookup) is a tool used to perform DNS lookups in Linux. It is used to display DNS details, such as the IP address of a particular computer, the MX records for a domain or the NS servers of a domain. nslookup can operate in two modes: interactive and non-interactive.
### passwd
     The passwd command is used to change the password of a user account. A normal user can run passwd to change their own password, and a system administrator (the superuser) can use passwd to change another user's password, or define how that account's password can be used or changed.
### pam_tally2
     pam_tally2 comes in two parts: pam_tally2.so and pam_tally2. The former is the PAM module and the latter, a stand-alone program. pam_tally2 is an (optional) application which can be used to interrogate and manipulate the counter file. It can display users' counts, set individual counts, or clear all counts.
### paste
     It is used to join files horizontally (parallel merging) by outputting lines consisting of lines from each file specified, separated by tab as delimiter, to the standard output.
### ping
     PING (Packet INternet Groper) command is the best way to test connectivity between two nodes. Whether it is Local Area Network (LAN) or Wide Area Network (WAN). Ping use ICMP (Internet Control Message Protocol) to communicate to other devices.
### perloneliner
     Perl one-liners are small and awesome Perl programs that fit in a single line of code and they do one thing really well.
### pkill
     The pkill command sends a signal to one or more processes, using the same flexible selection methods as pgrep.
### ps
     he ps (i.e., process status) command is used to provide information about the currently running processes, including their process identification numbers (PIDs). A process, also referred to as a task, is an executing (i.e., running) instance of a program.
### pwd
     The pwd command is a command line utility for printing the current working directory. It will print the full system path of the current working directory to standard output. 
### reboot
     To reboot the system
### poweroff
     To poweroff or shut down the system
### remove
     rm stands for remove here. rm command is used to remove objects such as files, directories, symbolic links and so on from the file system .
### rpm
     RPM command is used for installing, uninstalling, upgrading, querying, listing, and checking RPM packages on your Linux system. RPM stands for Red Hat Package Manager. With root privilege, you can use the rpm command with appropriate options to manage the RPM software packages.
### rsync
     Rsync ( Remote Sync) is an open source command utility that provides fast incremental file transfer from one host to another
### scp
     SCP (secure copy) is a command line utility that allows you to securely copy files and directories between two locations. 
### screen
     Screen or GNU Screen is a terminal multiplexer,it means that you can start a screen session and then open any number of windows (virtual terminals) inside that session. Processes running in Screen will continue to run when their window is not visible even if you get disconnected.

### sed
     SED command in UNIX is stands for stream editor and it can perform lot’s of function on file like, searching, find and replace, insertion or deletion
### sort
     SORT command is used to sort a file, arranging the records in a particular order. By default, the sort command sorts file assuming the contents are ASCII
### ss
     The ss command is a tool used to dump socket statistics and displays information in similar fashion (although simpler and faster) to netstat. The ss command can also display even more TCP and state information than most other tools.
### ssh
     The ssh command provides a secure encrypted connection between two hosts over an insecure network. This connection can also be used for terminal access, file transfers, and for tunneling other applications. Graphical X11 applications can also be run securely over SSH from a remote location
### sysctl
     using the sysctl Command. The /sbin/sysctl command is used to view, set, and automate kernel settings in the /proc/sys/ directory. This is the same information seen if each of the files were viewed individually. The only difference is the file location.
### tail
     The tail command, as the name implies, print the last N number of data of the given input. By default it prints the last 10 lines of the specified files. If more than one file name is provided then data from each file is precedes by its file name.
### tar
     The tar command stands for tape achieve, which is the most commonly used tape drive backup command used by the Linux/Unix system
### tcpdump
     tcpdump is a most powerful and widely used command-line packets sniffer or package analyzer tool which is used to capture or filter TCP/IP packets that received or transferred over a network on a specific interface. tcpdump also gives us a option to save captured packets in a file for future analysis. It saves the file in a pcap format, that can be viewed by tcpdump command or a open source GUI based tool called Wireshark (Network Protocol Analyzier) that reads tcpdump pcap format files
### top
     Top command displays processor activity of your Linux box and also displays tasks managed by kernel in real-time. It'll show processor and memory are being used and other information like running processes. This may help you to take correct action.
### touch
     The touch command is the easiest way to create new, empty files. It is also used to change the timestamps (i.e., dates and times of the most recent access and modification) on existing files and directories
### tr
     The tr command  is a command line utility for translating or deleting characters. It supports a range of transformations including uppercase to lowercase, squeezing repeating characters, deleting specific characters and basic find and replace. It can be used with UNIX pipes to support more complex translation. tr stands for translate.
### traceroute
     The traceroute command is used in Linux to map the journey that a packet of information undertakes from its source to its destination. One use for traceroute is to locate when data loss occurs throughout a network, which could signify a node that's down.
### umask
     new files are created with a default set of permissions. Specifically, a new file's permissions may be restricted in a specific way by applying a permissions "mask" called the umask. The umask command is used to set this mask, or to show you its current value.
### uname
     The uname command reports basic information about a computer's software and hardware. When used without any options, uname reports the name, but not the version number, of the kernel (i.e., the core of the operating system).
### uniq
     uniq is the tool that helps to detect the adjacent duplicate lines and also deletes the duplicate lines. uniq filters out the adjacent matching lines from the input file(that is required as an argument) and writes the filtered data to the output file .
### uptime
     It is used to find out how long the system is active (running). This command returns set of values that involve, the current time, and the amount of time system is in running state, number of users currently logged into, and the load time for the past 1, 5 and 15 minutes respectively.
### useradd
     useradd command is used to create new accounts in Linux
### vi
     The vi editor is the most popular and commonly used Linux text editor. It is usually available in all Linux Distributions. It works in two modes, Command and Insert. Command mode takes the user commands, and the Insert mode is for editing text.
### vmstat
     vmstat reports information about processes, memory, paging, block IO, traps, disks and cpu activity. The first report produced gives averages since the last reboot. Additional reports give information on a sampling period of length delay.
###w
     The command w on many Unix-like operating systems provides a quick summary of every user logged into a computer, what each user is currently doing, and what load all the activity is imposing on the computer itself.
### who
     who command with no command-line arguments shows the names of users that are currently logged in, and depending on which Unix/Linux system you are using, may also show the terminal they're logged in on, and the time they logged in.
### watch
     watch is used to run any designated command at regular intervals. It displays its output on a console (i.e., all-text mode display) or terminal window (i.e., a window in a GUI that emulates a console) that is temporarily cleared of all other content (i.e., prompts, commands and results of commands)
### wc
     The wc command is a command line utility for printing newline, word and byte counts for files. It can return the number of lines in a file, the number of characters in a file and the number of words in a file. It can also be combine with pipes for general counting operations.
### wget
     Wget is the non-interactive network downloader which is used to download files from the server even when the user has not logged on to the system and it can work in the background without hindering the current process.
### ypcat
     ypcat prints the values of all keys from the NIS database specified by mapname, which may be a map name or a map nickname.
### yppasswd
     the yppasswd command changes a network password in the NIS database
### yum
     YUM (Yellowdog Updater Modified) is an open source command-line as well as graphical based package management tool for RPM (RedHat Package Manager) based Linux systems. It allows users and system administrator to easily install, update, remove or search software packages on a systems.
### zip
     ZIP is a compression and file packaging utility for Unix. Each file is stored in single .zip {.zip-filename} file with the extension .zip.
### sar
     Using sar, you can also collect all performance data on an on-going basis, store them, and do historical analysis to identify bottlenecks.Sar is part of the sysstat package.
