# TASK 3.1 - Explore your operating system

# Operating system details
- Command: sw_vers
- What it does: Displays the macOS product name, version and build version
- What I observed: The operating system is macOS, version 27.2, with build version 26B123

# Current account identity
- Command: whoami
- What it does: Displays the username of the currently active computer account
- What I observed: The command displayed my account username

# Available and used storage
- Command: df -h
- What it does: Displays the total, used and available storage space of mounted filesystems in human-readable units.
- What I observed: My main data volume has 129 GiB(1 GiB is 1024MB) used and 305 GiB available, with approximately 30% capacity used

# System activity snapshot
- Command: top
- What it does: Displays a live overview of running processes, CPU usage, memory usage, and system activity.
- What I observed: My Mac had 546 processes, including 2 running and 544 sleeping. CPU usage was approximately 90.92% idle, and memory usage was 15 GB.
- My understanding: The command helps monitor system performance and identify which processes are consuming system resources.


# TASK 3.2 - Understand Processes


- Command: ps aux
- What it does: Displays a snapshot of running processes with details such as user, PID, CPU usage, memory usage and command
- What I observed: The output displayed processes each with a unique PID
- My understanding: A process is a program currently being executed. A PID (Process ID) is a unique numerical identifier assigned to each process, which helps the operating system manage and monitor it
Two examples of processes-
Google Chrome: An application process that runs when browsing the internet
Terminal: An application process that runs commands entered by the user


# TASK 3.3 - Understand paths and permissions

# File permissions

- Command: "ls -l mission-02-terminal/terminal-practice/notes.txt"
- What it does: Displays detailed file information, including its permissions
- What I observed: The permission string was " -rw-r--r-- "
- My understanding: The owner has read and write permissions but does not have execute permission. Group members and others have read-only access


# TASK 3.4 - Explain operating-system responsibilities
Operating system manages the computer's hardware and software resources

Process management-
The OS manages running programs. It starts, schedules and stops processes and shares CPU time between them which is called timeslicing
Example: When Google Chrome and Terminal are open together, the OS manages both running applications

Memory management-
OS manages the computer's RAM. It allocates memory to running programs and frees it when programs no longer need it
Example: When you open Google Chrome, the OS allocates RAM so Chrome can run. When you close it, that memory can be reused

Device management-
OS manages hardware devices and helps applications communicate with them using device drivers
Example: When you type on your keyboard, the OS receives the input and makes it available to the application you're using

File management-
OS manages how files and folders are created,stored,organised, accessed,renamed and deleted
Example: When you create notes.txt, save it in a folder, or rename it, the OS manages those file operations

User interface/shell-
OS provides ways for users to interact with the computer. This can be through a Graphical User Interface (GUI) or a Command-Line Interface (CLI)
Example:
- GUI: Using Finder on your Mac to open folders and files.
- CLI: Using Terminal commands such as pwd and ls to navigate and view files

Security and permissions-
OS protects files and computer resources by controlling who can access, read, modify or execute them.
Example: 
Your notes.txt file has permissions -rw-r--r-- . This means its owner can read and edit it, while other users have read-only access




