# Important git commands

### Beginner level commands

- `git init` -> it initialize a new repo.. repository is a folder managed by git where we can track all the changes in that folder.


- `mkdir` -> create a new folder or (directory its not a repo it just a normal folder but u can make it repo using init command)

-  `touch fileName` -> using this command u can create a new file inside a git repo just write touch and filename with its domain name example --> touch index.js

- `vim filename` -> it will open that file inside the your terminal or git bash for start writing just press Esc+i it will enter in writing mode for exit just press Esc then wite :wq and enter 

- `git add <filename>` --> it will add all the untracked file into tracked mode means after this git start tracking all the changes etc thing in that file.


- `git add .` it will add all the untracked file in single command.


- `git commit -m "commit message"` to save your changes and create a new version of code. -m for a message about something you add (new feature) in this version of code(software)

- `cat <filename>` --> it will show the contant of given file.

- `git remote add origin <ssh link of your repo from github>`  --> connect your local repo to github repo

- `git push origin <branch name>`  -> push your branch code on github connected repo

- `git cat-file <flag> <hash>` -> use when you want to know about a particular hash. flag can be -t or -p  , t for datatype , p for print the content that hash contains.

- `git commit --amend <message>` -> it helps you to change some data of last commit without creating a new commit.Exampe you have done a commit and u forgot some code to  write thn just put your code into file and run this command it will update the data without create a new commit.

- `git rm --cached <filename>` --> it will remove the given file from trackable files and put into untracked file
- `git restore --staged  <filename>` --> it will undo the recent changes in the code and put into last add code situation


## Git Branching

- `git branch` --> print the all existing branches

- `git checkout -b <new branch name>` --> create a new branch

- `git checkout <branch name>` --> move current branch to target branch

- `git merge <name of that branch which you want to merge to current branch> -m <message for merging>` -> it will merge a target branch to current branch always move to that branch first in which you want to merge . example you want to merge a feature branch into master branch then first move to master branch using git checkout master cmd and after that execute this command git merge feature1 -m "mereging feature into master"


- `git clone <repo ssh link>` --> clone the repo from github to local machine




## Github 

- `fork` -> always do fork when you r not a part of that project in which you want to contribute 

- `pull request` --> dont push your code in someone master branch directly always push a another branch and create a pull request to merge your code . he will review your code and if he ffels its good then he will accept your pull request.

- `git pull origin master` --> whenever you push your code before the push use this command it will help you to up to date with repo commits and you will not face any error.





