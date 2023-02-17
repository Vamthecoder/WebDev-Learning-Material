# Git Commands 

1. Git Clone Command
2. Git Commit Command 
3. Git Add .  


# Git Special Commands 

*   git config --global user.email "you@example.com"
  git config --global user.name "Your Name"


### Git Commit 
* It is a lightweight snapshot which copy paste your project to repo. 
you can create multiple commit. and every previous commit is a ancestor to next child. Ex. C0 is grandpa and C1 is papa and C2 is child. you can access any commit whenever you want. 

### Git Branches 
* branch early, and branch often

### git commit branches and merge branches to main

adding more changes. to merge the file and make conflicts


# DAY2

## "Git add [file name]" - to stage a new file or track any file to git repo before commit.

## "Git status" - to know what commits have been done in past.

## "Git commit" - to commit something on the repo.

## "Git commit -m ["a meaningful message"]" - to commit the staged file to repo with the proper message.

## "Git log" - to check how many commits have been done in the past on the repo. 

## "Git Checkout" - to switch on to another branch. Ex. Main -to- Dev -to- Feature -to- File

## "Git checkout [commit hash code/ branch name]" - to switch to any commit have done in the past. Ex. Git checkout C0

## "Git branch" - to create a new branch. 

## "Git checkout -b [branch name]" - to checkout and create a new branch at the same time. 

## "touch .gitignore" - to create a new file to keep your texts hidden from main git cloud/ repo. you can put any file name to hide it from git to be uploaded on repo. 

## "Git push" - to publish your commit to repos

# DAY3

## *One Way to work in team in Github* You can invite collaborator to work on the same repo to work on same project without forking and pull requests.

## *Second way to work in team in Github* You can fork any work area to work on the same project without making branch and will make no changes in another persons repo.  

## "Git init" - Initialized empty Git repo. To make a new directory of git in local. 

## "Git add --a" - To stage the current folder or file. 

## "Git commit -a -m ["A meaningful message"]" - To stage and commit a file at the same time.

## "Git Clone [URL of Clone from git ]" - To clone a project from anyone's online repo on your local repo. copy git project clone and paste to git bash.

## "git config --list" - to show what are the configuration of git or whomever are trying to commit.

## "*.log" - mention in ".gitignore" file to ignore all the log or error file from git to commit. it would not track any error.log files in directory.

## "[folder name]/" -  To ignore the whole folder from git by mentioning foldername/ in .gitignore .

# DAY4

## "git diff" - To check whomever working project made changes in the prject or repo. it compares with staged data and modified (working).

## "git restore --staged [filename]" - To unstage the staged file.

## "git restore [filename]" - To restore the modified file. It restore the deleted data from local file source code.

## "git rm [filename]" - To remove file from local storage.

## "git rm --cached [filename]" - To remove file cache if it has been in commit after putting any file in ignore or after deleting the file cache remains.

## "git remote add origin [link]" - To add repo from remote or github with the help of link.

## "git pull" - To pull the new data or updated data from branches to master.

## "git config --global alias.[word] [attribute/command]" - To make a short name of your commands or attributes. you can create by using this alias. Ex: S for status - git config --global  alias.s status or git config --global alias.c checkout / git config --global alias.sc 'commit -a -m' .

## "git rebase" - To push your branch in to main without keeping a different branch like it always a part of the main. and rebase will always work while being in branches. Ex: 'Git rebase main' while being in the Branch*

## "git checkout [commitID]" - To checkout to commit and see Head. Head is the last commit has made in the repo. 

## Note: Hash is commit's ID. which is unique and used to see which commit was made by user and when in git log

## git checkout [branchname^] - To checkout to previous commit from last commit with the help of caret (^). without using commit hash. 

## "git branch -f main HEAD~[number]" - To force move a branch to any commit over head. Ex: if you use 'HEAD~5' it will push main branch 5 commits above the HEAD. 

## "git branch -f main [commithash]" - To move any branch to any specific commit by using commit hash/unique ID. 

## "git reset HEAD~1" - It will move a branch backwards as if the commit had never been made in the first place. Tts method of "rewriting history" doesn't work for remote branches that others are using.

## "git revert" - In order to reverse changes and share those reversed changes with others.

