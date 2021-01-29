#Demo 2

creating folder is VS code and push to git
First create a folder in VScode and save it
Create a empty repo in git
Then run git remote add origin with ssh of the repo
then run git push origin master

## sub heading

To update any changes to any file back to git
First check git status -- displays what all changed
second run git add .
third git commit -m "any message to display in descritpion"
fourth git push origin master
fourth git push origin master

## Trying branching

#create branch using git checkout -b name for the branch
#run git branch command to know which branch we are working on
#open files and make any changes we want and save the file
#run git add . to add the changes
#run git status to see if the cnahges were added
#run git commit -m " descritiption as to what was changed "
run git branch master and switch to master
run git diff to see what is the difference between branch and master
run git branch "branch name "
run git puch -u "anme of the branch" -- this will push all the cnages in the branch to git
then go back to git hub and compare and create a pull request to main branch

##Updating changes in master to branches

First update master, if you add a new file then you need to run git add
If you jus tmodified existing file then directly run git commit -am message of what was updated.
The -a in the above command is the git add
Then switch to branch and run git merge origin/master to see all the changes in the master to reflect in the branch
