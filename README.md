## Git Branching

Git cheatsheet and branching example

### Basic Commands

* 'git init' -initialize local git repo
* 'git add filename' - stage filenam for commit
* 'git commit -m 'msg'' = commit to local repo with message msg.

### Information Commands
* 'git staus' - show whether file is staged for commit
*'git log' - show commit log
* 'git log --oneline' - show commit log (compact format)
*'git config -l' -list repo configuration



### Branching Commands
*'git branch' -list local branches
*'git branch branchName' - create new branch
*'git checkout branchName' - swithc to branch branchName

### Remote Commands
*'git remote add origin repUrl' - create alias 'origin'
* 'git push origin branchName' - push to remote branch
* 'git push -u origin branchName' - push to remote branch branchName, making it the default remote

