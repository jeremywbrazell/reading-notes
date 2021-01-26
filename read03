# Git Reading Notes

## Version Control

### Local Version Control (Local VCS)
Entails one database on your HD that stores changes to files

## Centralized Version Control (CVCS)
Entails a single server storing all changes and file versions, which are accessible by various clients.  This streamlines the collaboration process by eliminating the need to involve all local databases, allowing programmers to see their team member’s activities w/ certain files, and gives administrators more control over divvying up revision privileges.

### Distributed Version Control (DVCS)
Addresses the major vulnerability of the CVS: the server as a single point of failure.  If a CVS doesn’t work, collaborators can’t work w/ one another on a file or save changes and new versions.  In the event of corruption of a central database hard drive, with the absence of backups – all work will be lost, except for any portions on local machines.

To prevent this, DVCS allows clients to create mirrored repositories.  These backups can be places on the server to replace any lost information.

## States

Files in Git can reside in 3 main states: committed, modified, and staged.

### Committed
Data is stored in a local db

### Modified
File has been changed but not committed to db

### Staged
Flagged a file’s changed version to be committed in this snapshot

## Git Customizations

### Configuration of Variables
git config – allows the setting of configutation variables that control aspects of Git’s operation & look

### Default Text Editor
Without configuration of a default text editor, Git will use the system’s default editor, Vim.

### Checking Settings
To do so, use the git config - - list command

## Cloning
You can clone a copy of an existing Git repository from a particular server
$ git clone https://github.com/test

## The Life Cycle of File Status
1. After you edit a file, Git flags it as modified because of changes made after the previous commit.
1. You stage the modified file.
1. Then, you commit staged changes.

## Checking File Status
$ git status

## ACP Process (Add, Commit, Push)

### Tracking & Staging a New File  

### Single File
 git add filename

### All Files
$ git add *
After using these commands, files are tracked and staged for committing.
Then do “git status” to see if it took.


## Committing a File
$ git commit -m “made change x,y,z”
This commits changes for the file or files.  Can have one commit message for multiple files.

## Pushing Changes
$ git push origin master





