## Welcome to ObiWanCloud Project:

## download VS Code, Git, Git Bash :
1. Download and isntall GIT first https://git-scm.com/
2. once GIT is install, reload the Visual Studio to recongnied the new Git install
3. install the Git Bash plugin
4. now initialized the source control to Git(login and grant access to your local VS code)


## Git Configuration

For Git to accepts the commit and status, etc. commands from Bash shell, you have to set your identity, otherwise, you will get error messages:

# Step 1:
 
you must first set these 2 global variables:
- git config --global user.email "email@example.com"
- git config --global user.name  "Username"

## GIT INIT: Git initialization
git init

# Step 2(This is to force you to use terminal commands instead of using GUI to create files and folder):
1. using the Linux command TOUCH "file name with extension" to create a new file
2. use VIM or NANO editor to edit the file, or just used the VS code editor
3. to view the content of the file, use the CAT command: CAT 'Filename'


## working with GIT BASH:
 
# 1. Creating a folder using MKDIR command:
-mkdir obiwancloud (Mkdir 'Folder name')
![alt text](create_folder.png)
- A. rename the folder if you make a mistake
mv obiwancloud ObiWanCloud (mv 'old_folder' 'New_folder')
![alt text](folder_rename.png)

# 2. create a file using the TOUCH Command:
TOUCH LICENSE (TOUCH 'File name[.]extension of the file')
![alt text](create_license.png)

# 3. GIT ADD: Now allow GIT to track the file by using the GIT ADD 'File name" command to track individual file to track or 'GIT ADD .' to track everything in the directory
![alt text](track_folder.png)


## GIT STATUS: checking which files or folder has been tracked.
git status
![alt text](track_folder.png)

## GIT COMMIT