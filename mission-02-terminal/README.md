# Task 2.1 - Explore basic Terminal Operations

- # Operation: Current-directory display
- Command: pwd
- What it does: Displays the full path of the current working directory
- What I observed: Terminal displayed: 
/Users/revabharol/Desktop/digital-detective-8549


# Operation: Directory listing
-Command: ls
-What it does: Displays the names of files and folders in the current directory
-What I observed: It displayed all the mission folders,the evidence folder and the main README file

# Operation: Detailed listing
-Command: ls -l
-What it does: Displays files and folders with additional information such as permissions,owner,group,size and modification date
-What I observed: Directories started with d, while README.md started with -

# Operation: Change directory
-Command: cd ..
-What it does: Moves from the current directory to its parent directory.
-What I observed: My location changed from the assignment repository to Desktop

# Create directory
- Command: mkdir terminal-practice
- What it does: Creates a new directory named terminal-practice inside the current directory.
- What I observed: The command produced no output. I verified that the folder was created successfully using ls

# Create empty file
- Command: touch notes.txt
- What it does: Creates an empty text file named notes.txt inside the current directory
- What I observed: The command produced no output, but the file was created successfully

# Copy file
- Command: cp notes.txt notes-copy.txt
- What it does: Creates a copy of notes.txt with a different name, notes-copy.txt, in the same directory
- What I observed: A duplicate file named notes-copy.txt was created while the original notes.txt remained unchanged

# Move/rename file
- Command: mv notes-copy.txt backup.txt
- What it does: Renames the copied file from notes-copy.txt to backup.txt in the same directory
- What I observed: The file name changed to backup.txt, while the original notes.txt remained unchanged

# Command: cat notes.txt
-What it does: Displays the contents of a text file in the Terminal.
-What I observed:It was initially empty, add the text with echo and "This is my first line" was displayed successfully in the Terminal

# Task 2.2 — Written understanding

1. Difference between replacing and appending file contents:
Replacing file contents using > overwrites the existing content, whereas appending using >> adds new text at the end without removing the previous content

2. Difference between copying and moving a file: 
Copying creates a duplicate of a file while keeping the original in its location. Moving transfers a file to another location or changes its name.

3. Information provided by current-directory display: 
The pwd command displays the full path of the directory in which I am currently working

4. Usefulness of directory listing: 
The ls command displays the files and folders in the current directory. It helps me check available files and verify whether new files or folders have been created.


# Task 2.3 - Understand flags and pipes

Using a pipe to display the first few lines
- Command: ls -l | head
- What it does: ls -l produces a detailed directory listing. The pipe (|) passes that output to head, which displays only the first few lines
- What I observed: The output displayed total 24 and details for backup.txt, notes.txt, and README.md


# Task 2.4 - Understand package managers

-Command: brew --version
-What it does: Checks whether Homebrew is installed and displays its installed version
-What I observed: Homebrew version 7.0.13 is installed

Package managers are useful because they make software installation and management easier. They allow users to
install, update, remove software and manage dependencies and also save time(manually downloading is time consuming)

List installed Homebrew packages
- Command: brew list
- What it does: Displays software packages installed through Homebrew, separated into formulae and casks.
- What I observed: Homebrew displayed a list of installed formulae, including Git, Node.js, Python, and FFmpeg, and one cask, copilot-cli


