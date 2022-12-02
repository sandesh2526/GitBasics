# Git Basic Commands : 

### To initialize any git repo : ``` git init ```
### Add the items in repo for staging : ``` git add || git add . ``` 
### (adds all new files)
### For current status of your repo, us : ``` git status ```
### Commiting the changes : ``` git commit -m "Your Message for Commit" ```
### To create new branch : ``` git branch newBranchName ```
### Switiching to another branch : ``` git checkout branchName ``` (Default Branch is master)
### To merge changes to branch from a different branch : ``` git merge BranchNameToBeMergedWith ```
### To add a remote to your newly created repository on github : ``` git remote add ShortNameForTheRemoteLikeOrigin URLOfRepo ```
### To push to the remote repo we use : ``` git push NameOfRemote(origin) TheBranchYouWantToPush(master) || git push -u origin master ``` 
### (If you want to save this setting we use "-u" so that next time we only have to use "git push" to commit to origin master)
### To pull changes from remote repo : ``` git pull remoteName(origin) BranchToBePulled(master || newBranch) ```