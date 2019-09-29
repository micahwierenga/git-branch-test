# Git Branch Test

## git add .
Translation: "I want to put all my changes in the staging area so they can then be committed to my local repository. If I've created a new file (or files), I want it to now be tracked by Git."

## git commit -m "Message"
Translation: "I want to put all the changes that are in my staging area into my local repository so they can then be pushed to my remote repository."

## git push origin master
Translation: "I want to push the changes from my master branch to my remote repository (called `origin`)."

## git branch branchName
Translation: "I want to create a new branch called `branchName` so that I can create new code without messing up my local master branch."

## git checkout branchName
Translation: "I want to switch to my branch called `branchName`."

## git push origin branchName
Translation: "I want to push the changes from my branchName branch to my remote repository (called `origin`). If this is the first time I have pushed this branch to my remote repository, then this will create a new remote branch, which will also be called `branchName` on my remote repository. From here, I can go to my remote repository, switch to the branch called `branchName` and create a new pull request in order to get the changes on the branchName branch into the master branch."

## git pull origin master
Translation: "I want to pull all of the changes from the master branch of my remote repository (called `origin`) into the master branch of my local repository. This way, my local master branch is completely up-to-date with my remote master branch."

## git branch -d branchName
Translation: "I want to delete the branchName branch from my local repository."

## git branch
Translation: "I want to see the full list of branches on my local respository, as well as see on which branch I'm currently located."

## git checkout fileName.js
Translation: "I would like to get rid of all uncommitted changes from the file called `fileName.js`."