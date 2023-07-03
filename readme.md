# Git Basic Commands : 

### To initialize any directory as git repo : 
### ``` git init ```
### Add the items in repo for staging : 
### ``` git add || git add . ``` 
### ('.' adds all new files)
### For current status of your repo : 
### ``` git status ```
### Commiting the changes : 
### ``` git commit -m "Your Message for Commit" ```
### To add a remote to your newly created repository on github : 
### ``` git remote add ShortNameForTheRemoteLikeOrigin URLOfRepo ```
### To push to the remote repo we use : 
### ``` git push NameOfRemote(origin) TheBranchYouWantToPush(master) || git push -u origin master ``` 
### (If you want to save this setting we use "-u" so that next time we only have to use "git push" to commit to origin master)
### To pull changes from remote repo : 
### ``` git pull NameOfRemote(origin) BranchToBePulled (master || newBranch) ```
### To create new branch : 
### ``` git branch newBranchName ```
### Switiching to another branch :
###  ``` git checkout branchName ``` (Default Branch is master)
### To merge changes to branch from a different branch : 
### ``` git merge BranchNameToBeMergedWith ```
### To view all branches 
### ``` git branch -a ```
### To Delete a Git branch 
### ``` git branch --delete BranchToBeDeleted ```
### To rename the branch
### ```git branch -m new-branch-name```
### Check all the previous commits
### ```git log```
### Check a particular commit
### ```git show CommitId(2f385e9be48dab7d65e0b7d66c958e9806b66c15)```
