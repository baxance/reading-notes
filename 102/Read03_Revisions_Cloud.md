## Git Tutorial


### Revisions and the Cloud


##### Version Control System
A System that allows the user to revisit previous versions of the same file as it goes through various changes, and revert to previous versions if necessary.
This can be done locally from the users own machine (Local Version Control System), or the VCS can be stored on a separate server (Centralized VCS), allowing multiple users to make changes and to the same file without overwriting each other's work. There's also a *Distributed* VCS that adds another layer of security onto a Centralized VCS, creating mirrors that can be backed up in case of a server failure that could potentially wipe out all the code stored there. Git is one of these Distributed Version Control Systems.

#### Git
- As a DVCS Git stores your data every time a saved change, or a *Commit* is made.
- Most project history is stored on the user's local disk, meaning work can be done off-line or doesn't depend on the availability of a server
- All changes to project are tracked by Git, and it will automatically detect potential losses of data
- Git Files have three main stages...
  - *Committed* files are secured in your local database
  - *Modified* files are those that have been edited but have not yet been saved or *committed* yet
  - *Staged* files are those scheduled to be *committed* on the next snapshot
  
#### Set up a Git Repository

Command Line | Action
-------|-------
cd "location" | change directory to location you want repository
git init | .git subdirectory created
git add "file" | Adds names file to repository
git add "license" | Adds an open source license to your file
git commit -m "message/notes" | Note attached to commited change, used for internal tracking of project
git clone "git web address" | Copies **ALL** all versions of all files of specified project to an automatically created directory "test"
git clone "git web address" "directory name" | Does the above but into a directory of your naming


#### Workflow

Three components of the local Git repository
- Working Directory where files live
- Index transition point
- Head Most recent commit

##### Tracking Files
- Tracked files can be modified or staged
- Untracked filed were not in the previous snapshot and are not staged  

Command Line | Action
-------|-------
git status | Check file's status
git add filename | Track a single file
git add "name" | Track all files in a repository
git status | Shows changes to be committed and confirms file is staged
git commit -m “notes” | Commits changes with reference note
git commit -a | Commits all modifications of tracked files in working directory
git push origin main | Pushes the changes to remote repository (from local disc to online)
git stash | Temporarily removes changes
git stash apply | Reveals hidden changes



[<== Back to Readme](README.md)
