# Linux-command
 sudo su            root user
 tty                 terminal type
 touch file.txt        creare file
 rm file.txt           remove file
 mkdir                 create directory


 # What is an Operating System?

- An Operating System or OS is a program that provides an environment to run other applications. 
- OS interacts with hardware which means it acts as the mediator between hardware and user interface.
- It manages hardware, software, and memory resources.

# Why we require an Operating System?
- Operating system plays a crucial role in computer system, it allows you to interact with computers without knowing how to speak in computer's language.
- It acts as interpreter or translator as it translates human readable (high level) language into machine level (binary or low level in 0's or 1's format) language.

# Types of Operating System-
# 1) Desktop OS-
      Operates in Desktop Machines.
      Used for general-purpose tasks such as making presentations, gaming etc.
      Serve for a single user at a time.
      Examples- Ubuntu-desktop, Windows 10,8, kali Linux
# 2) Server OS- 
      Operates in Server Machines.
      Used for hosting purposes.
      Multiple clients can be handled at the same time.
      Server multiple user devices.
      Examples- Windows 1.3 Server, 1.9 Server, Linux, Ubuntu, centos, Fedore 

# History of Linux-

In earlier days, computers were as big as houses or parks. So, you can imagine how difficult it 
was to operate them. Moreover, every computer has a different operating system which made it 
completely worse to operate on them. Every software was designed for a specific purpose and was 
unable to operate on other computer. It were extremely costly and normal people neither can afford 
it nor can understand it.
- *1969 (UNIX)*   -    Ken Thompson and Dennis Ritchie      -    developed at AT&T Bell labs. It is not free.
- *1983 (GNU Project)*   -    Richard Stallman       -     free version of UNIX
- *1991 (LINUX)*    -      Linus Torvalds       -      make first Linux kernel which is freely available to anyone.

Linux is a kernel and not an operating system and GNU is a collection of free software, these two project collabs give us the “Linux” or “GNU/Linux” operating system

# Development of OS-

- i) Single user and single-tasking at the same time.
- ii) Single user and multiple tasking at the same time.
- iii) Multiple users and multiple tasking at the same time.

# Features of Linux -
## 1) Open Source- 
               The source code of Linux OS is openly available to anyone. 
                Anyone can open it, expand it and modify it as required.
                Simply open source means have freedom to:
                    -run program, for any purposes.
                    -study how program works and change it.
                    -distribute versions.

## 2) Free- 
         Free to use this OS for personal use, on the server, and for educational use.
         A free License and collaborative project that can be developed by the user contribution.

## 3) Security- 
            Linux is a more secure OS:
                 -Limited permissions
                 -Superuser and standard user privileges
                 -Open source- allowing anyone to inspect, modify and improve code
                               enable large communities to fix vulnerabilities
                 -A global development community looks at different ways to enhance its security, 
                  hence it is highly secured and robust so you don't need an anti-virus to scan it regularly.

## 4) Lightweight-
                Required less hardware resources.
                4-8 GB hard disk space required to install.
                it can be installed on any small hardware and it uses quite small disk space while installation.

## 5) Multiuser Capability- 
                An operating system that allows and grants permission to multiple users to access underlying hardware resources simultaneously.
                Multiple users can access the same system resources like memory, hard disk, etc. 

## 6) Multitasking-
                 It allows numerous users to work on various tasks at once.
                 There are two approaches to this:
                     -Single users doing multiple tasks.
                     -Multiple users do multiple tasks which includes editing file, and using browsing facility at the same time.

# Linux Distributions-

- Linux has a number of different versions for new users and hardcore users.
- Linux distributions are various versions of the Linux operating system that bundle the Linux kernel with other software packages, tools, and applications.
- Nearly every version of Linux is free to download.

*Popular Linux distributions include:*
- LINUX MINT
- MANJARO
- DEBIAN
- UBUNTU
- ANTERGOS
- FEDORA
- ELEMENTARY OS
- OPENSUSE

# Windows vs Unix vs Linux-


|              Windows                |                Unix             |               Linux          |
|-------------------------------------|---------------------------------|------------------------------|
|        Proprietary Based            |        Proprietary Based        |   Community Based            |
|            Purchase                 |             Purchase            |   Free                       |
| Less Secure                         |   More Secure                   |  More Secure                 |
| Closed Source                       |     Closed Source               |Open Sourece                  |
| Heavy                               | Lightweight                     | Lightweight                  |
| Non-portable                        | Portable                        | Portable                     |
|   Easy to use (gui)                 | Hard to use(cli)                | Hard to use(cli)             |
| 80% Desktop                         |  90% Server                     | 90% Server                   |
| Microlithic Kernel                  | Monolithic Kernel               | Monolithic Kernel            |

# Architecture Of Linux OS-
Linux architecture consists of innermost Hardware layers, kernel, shell, and 
outer application layer




## 1) Application Layer:
- Users interact with the system through varies applications such as office, games, etc.
- These applications run in the outer layer of the architecture.

## 2) Shell:
- Shell provides an environment to run any application.
- It provides an interface to the user to interact with hardware.
- Shell acts as a command interpreter.
- It converts high-level language into computer-level language.
* Shell can be of:
  i) Graphical Shell
  ii) Command line Shell
- Examples: k shell, bash shell, sh shell, etc.

## 3) Kernel:
- Kernel is a core component of Linux architecture.
- Manages hardware (CPU, Memory, and devices).
- It controls process management, memory management, and device management.
- It tracks all active processes running on systems.
- In Linux, we use a Monolithic kernel.
- 

## 4) Hardware: 
All the hardware components such as motherboard, CPU, hard disk, etc. are comes under 
this layer. 


# Monolithic kernel vs microlithic kernel-

## Monolithic Kernel-
- It manages the system's resources between system applications and system hardware.
- which are required for system applications that are already installed.
- Large in size and provides high execution speed.
- All prerequisites are already installed and required to install new packages.
- It offers memory management, file management, and process scheduling.

## Microservices-
- In the microlithic kernel, only required dependencies are pre-installed.
- lightweight in size
- Application software running on microlithic architecture have ability to install its
own dependencies by itself.
- It is slow in execution 

[12:10 PM, 11/25/2024] Vicky❤️: # Linux Prompt-
- The Linux command line is a text interface to your computer. Often referred to as the shell, terminal, console, or prompt.
- The command prompt is an executable CLI program, cmd.exe
- The default prompt for many Linux distributions is often a string ending with the dollar sign ('$') for regular users and a hash ('#') for the root or superuser.
- The prompt typically includes information about the current user, hostname, and the current working directory.

*[user@hostname current_directory]$*

* user: The current username.
* hostname: The name of the computer or server.
* current_directory: The path to the current working directory.
* $ or #: The prompt character, which is usually a dollar sign ('$') for regular users and a hash ('#') for the root user.

## Example- john@mylinuxmachine:~$
This prompt indicates that the current user is "john," the hostname is "mylinuxmachine," and the current working directory is the user's home directory (~).

# Commands-
- Commands are nothing but executable programs that perform specific tasks written in it.
- These executable programs can be called using their name as per the provided syntax.
- Commands are nothing but executable programs that perform specific tasks written in it.
- These executable programs can be called using their name as per the provided syntax.
  General Syntax:

## [commands] -[options] -[argument] [multiple arguments]
- Commands- To run the command.
- Options - To adjust the behavior of the commands.
- Arguments - The behavior, file folder name.

# sudo (Super User DO)-
 
- Generally used as a prefix for some commands that only superusers are allowed to run.

- If you prefix any command with “sudo”, it will run that command with elevated privileges or in other words allow a user with proper permissions to execute a command as another user, such as the superuser. -
- This is the equivalent of the “run as administrator” option in Windows. The option of sudo lets us have multiple administrators.
# su (short for substitute or switch user) 
- allows you to run commands with another user’s privileges.
- using su is the simplest way to switch to the administrative account in the current login session. 
# Basic Commands in Linux-
## pwd- Print Working Directory.                                                                                                                                     
- Displays the current working directory, shwoing the full path to your current  location in the file system.
  
## tty-          .. This command displays the current user terminal number. 	
 ## Who am i-    .. Display current user details.
## whoami-       ..It simply prints the username of the currently logged-in user.
## w-            .. Display all current user details with their time schedule.
- Provides a summary of information about currently logged-in users, including details like usernames, terminal, remote host (if applicable), login time, idle time, JCPU (total time used by all processes attached to the terminal), PCPU (total time used by the current process), and more.

##  wh tab tab-   .. To see similar commands or autocomplete cmd. using the <tab> key for command autocompletion is a feature of many Linux shells, such as Bash.
-  When you type a partial command and press the <tab> key twice, the shell attempts to autocomplete or show a list of possible commands or files that match the entered characters.
## Clear or ctrl+l - 
- It clears screen but not background data.
- Remember that using Clear does not erase the command history or any background data; it just provides a visually clean terminal window.
- If you scroll up, you'll still see previous commands and their output.
## cal  -
- It displays current month of calendar. This command is used to display a calendar in the terminal. By default, it shows the calendar for the current month.
## cal year - 
- It displays specified year calendar. 	
## cal month year - 
- It displays specific months calendar in particular year 
## cal -3- 
- It displays the previous, current, and next month's calendar of the current year. 
## date-
- It shows the current date and time.
- This output includes the day of the week, the month, the day of the month, the time, and the Coordinated Universal Time (UTC) offset.
- The exact output may vary depending on your system's configuration.
 ## date -s “YYYY/MM/DD HH:MM:SS “-
- It sets a date and time. The date -s option is used to set the date and time.
## reboot OR init 6 -
To restart the system
[12:10 PM, 11/25/2024] Vicky❤️: # Basic Commands in Linux-
## power off OR init 0-
- To power off the system 
## logout OR exit OR ctrl + d -
- Log out from the currently logged-in user.

# Commands To View System Information-                                                                                                                           
## hostnamectl
Show detailed information about the system
## u name
- It displays the Operating System name.
## u name -r
It displays kernel release information.
## u name -a
#### It displays:
- Kernel Version: This includes information about the kernel version running on the system.
- Hostname: This displays the name of the system on the network (fully qualified).
- Kernel Release: This provides the release number of the kernel.
- Kernel Architecture: This indicates the system's architecture, such as x86_64 for 64-bit systems or i686 for 32-bit systems.
- Operating System: This specifies the name of the operating system.
# Listing-
## ls(List)-
* It is used to list files and directories in a directory. It is used to list files and directories in a directory.
- l: Long format. Displays detailed information about files, including permissions, owner, group, size, and modification time.
- a: All entries. Shows hidden files (those starting with a dot .).
- r: Recursive. It is used to display files and directories in reverse order. It reverses the order of the sorting, showing the files or directories in descending order based on their names.
- t: Sort by modification time, newest first.
- S: Shows fi# Directory-

## mkdir(make directory)- 
- Used to create directories (folders).
- It allows users to create one or more directories with specified names. mkdir is a fundamental utility for managing the directory structure in a Linux file system.
  
### Creating a Single Directory:
- mkdir my_directory

### Creating Multiple Directories:
- mkdir dir1 dir2 dir3
- mkdir dir{1..10}

### Creating Nested Directories: 
- mkdir -p /path/to/directory

  
## rmdir (Remove Directory)- 
- Command is used to remove empty directories in Linux.
- rmdir directory_name

# Moving and Copying-
## mv (Move)-
- Command in Linux is used to move or rename files and directories 
- mv file_name /destination
- mv old-dir/filename new_name
## cp (Copy)- 
- Command in Linux is used to copy files and directories from one location to another.
- It can be used to duplicate files and create backups.
- cp file_name /destination
- cp -r dir_name /destination 
# echo- 
- for printing messages or information to the console

# File-
## touch-
- Used to create empty files and update the access and modification timestamps of existing files.
- touch new_file.txt
- touch file1.txt file2.txt file3.txt
- touch existing_file.txt
- This command updates the access and modification timestamps of the existing file without modifying its content.
## cat- 
- display the content of files and concatenate file.
- displaying the content of files and concatenating files, but you can use it in combination with input redirection to create a file with data
- cat filename.txt- Display content
- cat file1.txt file2.txt- Concatenate
- cat file1.txt > newfile- copy one file into another
## rm-
- used to remove files.
- rm [option] filename
- -f : forcefully
- -v : verbosely
- -r : recursively.les or directories with its size

[12:10 PM, 11/25/2024] Vicky❤️: ## more –
- more command provides line by line navigation and page by page navigation in downward direction but, upward scrolling not possible.
- more file_name.txt
## less – 
- less command allow navigation keys for scrolling up and down. 
- less file_name.txt
## head – 
- head command show few lines from top of the file. 
- if head command is used without any option, it will show top ten lines by default. –n is used to give count of lines to be shown.
- head [options] [file]
- head file.txt
- head -n 5 file.txt
  
## tail –
- tail command show few lines from bottom of file.
- tail [options] [file]
- tail file.txt
- tail -n 5 file.txt


# Helping Commands-
## man- 
### Mannual page- 
- It is form of documentation in Unix-like operating systems that provides detailed information about a specific command, utility, or function.
-  These mannual pages serve as a reference guide, offering users comprehensive information on how to use a particular command or program.
- Access man page by using man command 
## info- 
same as manual page
  
# Redirectors-
- Redirectors are used to write terminal output into file.
- Output, generated from any command, on terminal can be transferred into existing file.
- If file does not exist, automatically new file will be created.
## Single Redirector (>):
- Redirect the output of a command to a file, overwriting the file if it exists.
- command > filename.txt

## Double Redirector (>>):
- Append the output of a command to a file, without overwriting existing content
- command >> filename.txt

## Piping (|):
- redirect the output of one command as input to another command.
- command1 | command2
e.g.- history | head -5
[12:10 PM, 11/25/2024] Vicky❤️: # File editor in linux-
- Editors are used to create new files, and edit or modify the content inside it.
- Simply editors are used to read and write data in existing or newly created file.
- Editors can be classified on the basis of interfaces that they use, i.e. Graphical Editors and Command Line Editors. 
## Graphical editor: 
- Graphical editor uses graphical user interface.
- It is easy to use but consumes more memory than command line editors.
- In Linux, following are some well-known graphical editors, 
### 1. gedit: -
- It is same as that of notepad in windows.
- You can open gedit graphically in application menu and also using command as $gedit. 

### 2. kedit: -
- It is similar to gedit but contain some advance features.
-  Generally, we have to install ked…
[12:11 PM, 11/25/2024] Vicky❤️: # Hierarchy of Linux File Management System-
In Linux, files are well managed using file management system. Linux File Management System manage files in hierarchical structure where, “/” (slash) is main directory or root directory (root node in hierarchy). All other directories comes beneath “/” directory. 

![image](https://github.com/vishakhadhonde9/Linux-/assets/97825776/682ca238-07e1-4e22-a25f-e88de3410a67)

## /- 
- root of file system
- Every single file and directory start from the root directory.
- The only root user has the right to write under this directory.
  
## /root- 
- Home directory of root user. In this directory, root user can store its personal files.
- Every single file and directory start from root dir.
- Only root user has right to write und…
[12:11 PM, 11/25/2024] Vicky❤️: # User Management in Linux-
- A user is a person who utilizes a computer or network service.
- Linux is said to be secure because one user cannot access files of other user without its permission.
- Each user is assigned an ID that is unique for each user in the operating system.
## There are three types of user:
### 1. System user: 
- System accounts are used by the services in Linux system.
- These accounts or users generally created when services are installed in system.

[12:11 PM, 11/25/2024] Vicky❤️: ### 2. Super user: 
- Super users are those users who has all privileges of Linux system.
- On all Linux systems, by default there is the user root, also known as the super user.
- This account is used for managing Linux. Root, for instance, can create other user accounts on the system.
- For some tasks, root privileges are required. Some examples are installing software, managing users, and creating partitions on disk devices. 
### 3. Standard user: 
- local user accounts or standard user accounts are for the people who need to work on a system and who need limited access to the resources on that system.
- These user accounts typically have a password that is used for authenticating the user to the system.
# Adding New User-
- Adding new local user means creating user account.                                                                                                   
- User can be added by root user or using root user’s privileges.
- Whenever new user has been added, some files get affected. These files holds user accounts related information.
- Also whenever new user is created, by default, its home directory has been generated.
  
* useradd [username]- Create user account.

### Files affected by newly added user:
- /etc/passwd: It store user profile related information, 
- /etc/shadow: It stores user password policies
- /etc/group: It store group information.
- /etc/gshadow: Stores group password and member’s list.

# To modify user-
* usermod [username]- modify or changes exiting user acc.
* usermod option parameters username 
#### Options, 
- -u :- user id -> Set the user ID for the specified user.
  - usermod -u 1001 username
- -g :- primary group -> Set the primary group for the user.
  - usermod -g groupname username
- -c :- Comment -> Add or change the comment field for the user.
  - usermod -c "Description" username
- -s :- shell type -> Add or change the comment field for the user.
  - usermod -s /bin/bash username  
- -G :- secondary group -> Set supplementary groups for the user
  - usermod -G group1,group2 username
- -l :- login name -> Change the login name of the user.
  - usermod -l newuser olduser
- -L :- lock user password
  - usermod -L username
- -U :- unlock user password
  - usermod -U username


# To Remove user-
- delete exiting user acc
* userdel [username]
- To remove a user and their home directory
* sudo userdel -r username  

# Password Management-
## passwd: 
- Password is the secret phrase that can be used to login to the system.
- ‘passwd’ command will be used to assign or change password of any user by root user.
- whenever, password assigned to the user, it will stored in /etc/shadow file in encrypted format.
- Only root user can change password of any user, but local users can change their own password.
- Password should follow some rules such as:
* Password must be 8 character long
* It should not contain user name
* It cannot accept old password
* Any dictionary name is not allowed
* Password should not be too simplistic 
- passwd - change current user’s password 
- passwd [user_name] - assign or change other user’s password by root user.
# View and change password policy-
- chage – ‘chage’ (change age) command use to view or modify password policy of user.
* chage <option> <parameter> <username>
- Last password change -> the date when the password was changed most recently.
- Password expires -> the dat…
[12:11 PM, 11/25/2024] Vicky❤️: # Permissions in Linux-
- Linux File System Security restricts user to access the files and directories.
- User require permissions to access files or directories.
- “ls -l” or “ll” command can be used to check security of any file or directory.
- Above command will display contents from directory along with its security 
details.
### drwxr-xr-x 3 root root     4096 May  9 18:41 Linux
### -rw-rw-r-- 1 root root 60582753 May 10 12:02 file1.txt
* The first character = ‘-‘, which means it’s a file ‘d’, which means it’s a directory.
* The next nine characters = (rw-r–r–) show the security
* The next column shows the owner of the file. (Here it is root)
* The next column shows the group owner of the file. (Here it is root which has special access to these files)
* The nex…
[12:11 PM, 11/25/2024] Vicky❤️: * The chown and chgrp commands used to change the ownership and group ownership of files and directories, respectively.

## chown (Change Ownership):
- The chown command changes the ownership of a file or directory.
- You can specify both the user (owner) and the group to which the file or directory will belong.

#### Syntax:
chown user :group file/dir
- chown newowner file.txt
- chown newowner :newgroup directory/filename

## chgrp (Change Group):
- The chgrp command changes the group ownership of a file or directory.
- You can specify only the group to which the file or directory will belong.

#### Syntax:
chgrp group file/dir
- chgrp newgroup file.txt



# How to Change Permissions in Linux-
- The command you use to change the security permissions on files is called “chmod“, which stands for “change mode".
### Syntax-
* chmod <u,g,o,a><+,-,=><r,w,x> <file_name>
# Octal Notation Method-
### Syntax- 
* chmod <permission_in_numbers> <file_name>

| Octal | Binary | Permission                |
|-------|--------|---------------------------|
| 0     | 000    | No permission (---)      |
| 1     | 001    | Execute (--x)             |
| 2     | 010    | Write (-w-)               |
| 3     | 011    | Write and execute (-wx)   |
| 4     | 100    | Read (r--)                |
| 5     | 101    | Read and execute (r-x)    |
| 6     | 110    | Read and write (rw-)      |
| 7     | 111    | Read, write, and execute (rwx) |


* chmod <permission_in_numbers> <file_name>
- chmod 644 example.txt

  
# Default Permissions (umask)-
- The umask command is used to set the default permissions mask for new files and directories. 
- It determines which permissions are removed or masked when a new file or directory is created.
* Default Permission for root and standard user:
  
| User           | Directory Permissions | File Permissions |
|----------------|-----------------------|------------------|
| Root           | 755                   | 644              |
| Standard User  | 775                   | 664              |

- Calculating Permission with Umask:

| User           | Calculation          | Umask | Umask Permission |
|----------------|----------------------|-------|------------------|
| Root Dir       | 777 - 022 = 755     | 022   | 755              |
| File           | 666 - 022 = 644     | 022   | 644              |
| Standard Dir   | 777 - 002 = 775     | 002   | 775              |
| File           | 666 - 002 = 664     | 002   | 664              |


# Process Management in Linux-
# What is Process?
- Process is any program in its excecution.
- It generally takes an input, processes it and gives us the appropriate output.
- An active program which running now on the Operating System is known as the process.
# Why Process Management is required-
##### 1)Resource Allocation-
##### 2)Concurrency-
##### 3)Isolation-
##### 4)Process Prioritization-
##### 5)Process Lifecycle-

# Types of Processes:

## Foreground Processes: 
- they run on the screen and need input from the user.
- also referred to as interactive processes

## Background Processes: 
- they run in the background and usually do not need user input.
- referred to as non-interactive or automatic processes
- for example: Antivirus.
## Commands-
#### &-
- Starts the command immediately in the background.
#### Ctrl+Z-
- Stops the job temporarily so that it can be managed.
#### Ctrl+C- 
- Can be used to cancel the current interactive job
#### bg- 
- Continues the job that has just been frozen using Ctrl+Z in the background.
#### fg-
- Brings the last job that was moved to background execution back to the foreground.
#### jobs-
- Shows which jobs are currently running from current shell. 
- Displays job numbers that can be used as an argument to the command bg and fg.
## Daemon Process-
- is a type of background process that runs continuously, typically providing system services or performing tasks without direct user interaction even if terminating terminal.
- example- init, crond
# Parent Process and Child Process-
- The parent process is the process that creates another process.
- A child process is a process that is created by another process, known as its parent process.
### PID-
- Every process in the system is assigned a unique numeric identifier called a Process ID (PID).
- PIDs are used by the operating system to manage and identify processes.
- echo $$
- pidof [process name]
### PPID-
- The Parent Process ID (PPID) indicates the PID of the parent process that created the current process.
- echo $PPID
  

# Process Management Lifecycle-
#### Following are the States of Process Management Lifecycle-

### New/Create:
- The process has been created but has not yet been scheduled for execution.
- During creation, the operating system allocates resources to the process, such as memory space, CPU time, and other necessary resources.
- The operating system assigns a unique identifier to the process known as the Process ID (PID), which is used to manage and identify the process.
### Ready:
- The process is ready to be executed.
- In this state, the process is ready to execute but is waiting for the CPU to be allocated to it.
- The process may also be waiting for other events, such as I/O operations to complete or signals from other processes.
### Running: 
- The process is currently being executed.
- In the running state, the process's instructions are executed by the CPU, and it performs its intended tasks.
### Waiting:
- The process is waiting for an event to occur, such as the completion of an I/O operation.
### Terminated: 
- Eventually, the process completes its execution or is terminated.
- When a process terminates, it releases the resources it was using, including memory, files, and other system resources.
- The operating system removes the process from its process table and deallocates its resources, marking the end of its lifecycle.

  
 ![image](https://github.com/vishakhadhonde9/Linux-Second-half-/assets/97825776/1dd38ebe-44e8-43f6-af9d-cb0d962e9d39)

## Zombie Process-
- Process that has finished its task, but its parent process hasn't yet collected its exit status from the operating system.



# Commands used in Process Management-
## ps(process  status)-
 - used to list currently running processes.
 - provides information about these processes, such as their process ID (PID), terminal associated with the process, CPU and memory usage, and more.
 - provides a snapshot of the current processes on your system.
#### ps [options]
* e: This option displays information about every process on the system.
* f: This option generates a full listing, providing more details about the processes and their relationships.
* u: This option displays the owner of each process and additional information like CPU and memory usage.
* x: This option lists all processes regardless of whether they are associated with a terminal.
* aux: This option shows a detailed list of all processes running on the system, including those owned by other users.

## top-
- top command is used to show the Linux processes.
- it provides dynamic real-time view of running system.
- usually, this command shows the summary information of the system and the list of processes or threads which are currently managed by the Linux Kernel.
# Adjust Process Priority-
- When Linux processes are started, they are started with a specific priority.
- By default, all regular processes are equal and are started with the same priority, which is the priority number 0.
- In some cases, it is useful to change the default priority that was assigned to the process when it was started.
- You can do that using the nice and renice commands.
- - the niceness value ranges from -20(highest prioprity) to 19(lowewst priority).
## nice command-
- used to launch a new process with a specified niceness value.
- the niceness value ranges from -20(highest prioprity) to 19(lowewst priority).
#### Syntax:
* nice [options] [command]
* nice -n 10 command
* To check nice value:
  ##### ps -l PID

## renice command-
-  used to change the niceness value of an existing process.
-  to alter priority of running process, we use renice command.
#### Syntax:
* renice value PID

## kill command-
- used to terminate process manually.
- kill command sends a signal to a process that terminates the process.
#### Syntax-
 kill -[signal number] PID
- Three of these signals work for all processes :
- The signal SIGTERM (15) is used to ask a process to stop.
- The signal SIGKILL (9) is used to force a process to stop.
- The SIGHUP (1) signal is used to hang up a process.



# Package Management-
- Package Management is the method of installing and maintaining the package/software.
- Package management in Linux refers to the process of installing, updating, configuring, and removing software packages
- In Linux, software is available in the form of packages (packages are the collection of programs).
- And installing the packages means simply extracting the files from the archive and put it on the system.

# Repositories-
- Centralized location where software packages are stored and maintain that are made available for installation

# Dependencies-
- Some package requires shared library, or another package, called dependency.
- Dependency refers to a software component or library that another piece of software relies on in order to function correctly.

## Low-level Utilities-
- Low-level tool manages package files installation, update and uninstallation of package without their dependencies.
## High-level Utilities-
- high-level tool can install the package with their dependencies. 

| Linux Family | Low-level Tool | High-level Tool |
|--------------|----------------|-----------------|
| Red Hat      | rpm            | yum             |
| Debian       | dpkg           | apt-get         |

* Red Hat Based OS- Fedora, Linux, Amazon linux CentOS, Rhel, etc
* Debian Based OS- kali linux, Ubantu, etc
# rpm- 
- RPM packages are typically files with a .rpm extension.
- They are archives that contain the files to be installed, along with metadata such as package name, version, dependencies, and installation scripts.
#### rpm option package-name
- -i install package file
- -v verbose
- -h show hash bar
- -U Upgrade package
- -q query package
- -e erase package
# yum-
### To use YUM, you typically use commands like:
* Install a Package:
  - yum install package_name
* Update a Package:
  - yum update package_name
* Remove a Package:
  - yum remove package_name
* List Installed Packages:
  - yum list installed




[12:13 PM, 11/25/2024] Vicky❤️: # Job Scheduling in Linux-
- Job scheduling is a feature that allows a user to submit a command or program for execution at a specified time in the future.
-  On a Linux server, it is important that certain tasks run at certain times the execution of the command or program could be one time or periodically based on a pre-determined time.

# 'at' command-
- The at command in Linux is used for scheduling one-time tasks to be executed at a specified time.
- Users can submit commands or scripts, and the atd daemon manages the execution of these scheduled jobs.
- The scheduled jobs are managed by the atd (at daemon) service, which runs in the background and executes the queued tasks at the specified times.
#### Syntax-
-  at “time date”
- atq- Lists jobs
- atrm- Remove jobs

# 'cron' command-
- Cron command is used to schedule repetative task.
- Crontab job scheduling technique is very useful for creating backup, scanning system, performing jobs with daily, weekly, monthly basis, etc.
-  A daemon called crond runs in the background and check its configuration every minute to examine configuration files in order to execute commands or shell scripts specified in the crontab if the
  time matches with specified time.
- Crontab can executes job repeatedly in specified time interval.

  ![image](https://github.com/vishakhadhonde9/Linux-Second-half-/assets/97825776/3df2b18c-f69d-4227-9b32-b24ac444b5bb)

#### Syntax-
- crontab <option>
##### Options-
- -e Edit/Create cron table
- -l List cron table
- -r Remove crontable
[12:13 PM, 11/25/2024] Vicky❤️: ## Archiving and Compression-
- Archiving is the process of Bundling and Compression.
- Bundling is the process of combining multiple files and directories (same or different sizes) into one file/place.
- On the other hand, compression is the process of reducing the size of a file or directory.

# tar command-
 - tar is commonly used to bundle files and directories together into a single archive file, which can then be compressed if desired.
### tar <-options> <compress_fileName>.tar <files_to_be_compressed>
#### options-
- -c -> create an archive.
- -f -> file name. (Compulsory option)
- -v -> verbose or view.
- -t -> list the content from archive.
- -x -> execute the content from archive.
- -C -> copy content from an archive to another directory.

# Compression-
- Compression is a reduction in the number of bits needed to represent data.
- Compressing data can save storage capacity, speed up file transfer, and decrease costs for storage hardware and network bandwidth.

## GZIP: 
- GZIP is good option for compressing a lot of data as it is quick.
- Its memory usage is also low.
- GZIP compression can be used by using “-z” option in tar command or by using gzipcommand.
- GZIP compressed file can be extracted using gunzip.
## BZIP2:
- BZIP2 provide better compression ratio compared to GZIP but require more "CPU time" to accomplish it.
- “-j” option in tar or bzip2 command can be used for bzip2 compression.
- Bunzip2 is command to extract bzip2 compressed file.
## XZ:
- XZ provide impressive compression ration but in cost of very high CPU and Memory usage.
- Decompression speed is better but it also consumes a lot of memory.
- XZ compression can be done by “-J” option in tar or xz command.

| No. | Name   | Option | Extension      | Unzip Command |
|-----|--------|--------|----------------|---------------|
| 1   | gzip   | -z     | .tar.gz        | gunzip        |
| 2   | bzip2  | -j     | .tar.bz2       | bunzip2       |
| 3   | xz     | -J     | .tar.xz        | unxz          |




# Search and Filter utility in Linux-
Search utilities are used to search files from the system where as filter utilities filters the 
output. Following are some filter tools that can we use:

## sort –
- Sorts the lines alphabetically by default but there are many options available to modify the sorting mechanism.
- sort filename
#### options-
- -r: Reverse the sort order
- -n: Sort numerically
- -o: Output the result to a file


## sed – 
- sed stands for stream editor.
- It allows us to apply search and replace operation on our data effectively.
#### options:
* s: substitute occurrence of a pattern with a replacement
- sed 's/old/new/' filename
* p: Print the lines that match a pattern.
- sed -n '/pattern/p' filename
* -i: Edit the file in place (i.e., modify the original file)
- sed -i 's/old/new/' filename
* d: Delete lines that match a pattern
  -sed '/pattern/d' filename.
## wc –
- wc command gives the number of lines, words and characters in the data.
#### Options:
- -l Show Line Count
- -w Display word count
- -m Show character count
## grep – 
- grep is used to search a particular information from a text file.
- grep 'pattern' filename

#### Options:
- -v Invert match.
- -c Output count of matching lines only.
## find –
- Find command is used to search and locate the list of files and directories based on conditions you specify for files that match the arguments.
- Find can be used in a variety of conditions like you can find files by permissions, users, groups, file type, date, size, and other possible criteria.
- Syntax:
#### find <search_path> <options> <required-parameters>
##### Options,
- -name <file_name>
- Search for a file with the specified name
- -perm <mode>- File's permission bits are exactly mode (octal or symbolic)
- -user <name>- File is owned by user specified
- -group <grp_name> - File is owned by group specified.
- -empty- The file is empty
- -executable - The file is executable
- -readable- Find files which are readable
- -writable- Search for files that can be written to
- -type <type>- Search for a particular type (f,d,l,c,b,s,p)




# Namespaces -
- Linux namespaces are a way to create isolated environments within a single Linux system.
- These isolated environments allow processes to think they are running on their own independent machine, even though they are sharing the same physical system.
- Namespaces are a feature of the Linux kernel that partition kernel resources such that one set of processes sees one set of resources, while another set of processes sees a different set of resources.

 # Types of Namespaces -
 ### 1] PID namespace: 
 - Isolates process IDs.
 - Each set of processes in a PID namespace has its own numbering for processes, so a process in one namespace can have a PID of 1, while another process in another namespace might also have PID 1.

### 2] Network namespace: 
- Isolates network resources like IP addresses, network interfaces, routing tables, etc.
- Processes in different network namespaces don't see each other's network settings, which is useful for containers that need separate network configurations.

### 3] Mount namespace: 
- Isolates file system mounts.
- Processes in different mount namespaces can have different views of the filesystem.
- For example, one namespace might have /home mounted on one location, while another namespace might have it mounted somewhere else.












