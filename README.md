# Git Course
This is Git Course
 
 ## Notes Of the course
# Lesson 3
```sh
git status # Know what is going on
git add * [or] 'somefile name' # Add to the stage
git reset * [or] 'somefile name'  # return from the stage unlike git add
git commit -m 'some message' # send to Local Repo
```
# Lesson 4
```sh
git branch # know all the branches here
git remote # know the remotes
git push 'RemoteName' 'BranchName' # send to github
```
# Lesson 5
## To participate someone in a project by inviting him
1. go to [github.com/'Your github name'/'your github project'/settings/access](https://github.com/OmarMohammadMahmoudOmar/Git_Course/settings/access)
2. search that someone name
3. add it clicking on 
```sh
git pull 'RemoteName' 'BranchName' # get the files that your collaborators made to that repo
```
# Lesson 7
```sh
git config -l # show a spice of the configurations you can edit
git help config # get all of them
git config -l n--show-origin # get the places where he brings the configurations
git config --global 'Key' "Value" # Edit something
git config --global --unset "Key" # remove the value of some command
git config --global --edit # edit the configurations in their file instead of your terminal
```

# LESSON 8
```sh
ssh -T git@github.com # Enter your passowrd to get into your account
```

# lesson 9 -> Create repositiry from existing project
```sh
git init # to create .git folder
git add readme.rm
git commit -m "First commit"
git remote add origin git@github.com:username/projectName.git # Enter you Public Key Password
git push -u origin master
```

# Lesson 10 -> Create pull request, asking from the admins reviewing this code
All in video
# Lesson 11 -> Create an alias
```sh
git config global alias.yourAlias theCommandYouRepace
```

# Lesson 12 -> Branching
```sh
git branch newBranchName # to create a new branch
git branch -d branchName #see if that branched had been merged or not, if not deletes it
git checkout branchName # switch to a branch
git checkout -b newBranchName # create a branch and goes to it
git branch -m branchNewName # Rename a branch
git merge branchName # merga a specific branch
```

### To fuse your branch and Master Branch
```sh
git checkout master # go to master branch
git merge branchName
git branch -d branchName # Delete it if you are done
git push origin master # upload the updates you made
```

# Lesson 13 -> Stash
```sh
git stash # Put the added files to a box that won't be uploaded
git stash list # see the stashed files buy Id
git stash pop # return the stashed list back, then delete the stash
git stash save "Message" # Put a message along with stashed filed
git stash apply # pop but with no deleting
git stash pop stash@{id} # rerurn a specific one, not the last, then delete
git drop stash@{id}  # remove it
git stash show # show all the files hidden
git stash show stash@{id} # show all the files hidden within
git stash cleart # remove all stashes
```