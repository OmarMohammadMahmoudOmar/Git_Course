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