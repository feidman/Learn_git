~ Learn git command 
# Learn Git in Short

## Get started
### Install Git

### Git initialize
  - CD to the dir you want to trace as the dir for git repo.
  - GIT INIT to initialize the dir( create ./git )

### Status and add to trace stage
  - GIT STATUS to show the status.
	There are 3 stages totally in git traced file:
	(1) modified;
	(2) staged;
	(3) commited;
  - GIT ADD files to add the files to be traced by git.
  - ignore some files by edit the .gitignore file;
  - GIT DIFF to show the difference between the traced file and the staged file which was not committed yet.
  - GIT DIFF --STAGED to show the difference between the traced file and the commited file(in repo).  

### Commit
  - GIT COMMIT to commit changes from staged area to repo(local).
  - GIT COMMIT -m "commit message";
  - GIT COMMIT -a to commit chages direct from modified work space by jump over the step of "GIT ADD";

### Remove files from git trace list
  - GIT RM will remove the file from traced lists of git and work space.(rather than delete directly from work space);
  - GIT RM --CACHEd to remove the file from staged area of git. (the file still exists in the work space);

### Rename files
  - GIT MV will rename a file tarced by git.

### Remote
  - GIT REMOTE ADD NAME [url] to add the current local repo to remote repo.
  - GIT REMOTE PUSH ORGIN MASTER to push commit to remote repo.
  - GIT CLONE [url] to clone from remote repo
  - GIT PULL to update the remote repo to local repo.


