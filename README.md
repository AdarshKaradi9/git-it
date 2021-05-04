# Git Practice

I am just practicing some git's command in it.

## Why ?

Everything is being practiced for manual doing!

## Commands Practiced
* `git config –global user.name "[name]`
    > This command is used to set the author name and email address respectively to be used with your commits.

* `git init`
    > It will initialize git in the working folder.

* `git add .`
    > This will stage all the files in which the changes are made or new file added.

* `git add <FILENAME>`
    > This will stage only that file which you will name it.
    > You can name multiple files also.
    > eg: git add index.html index.js

* `git status`
    > This will show you the status of the current branch, basically your changes.
    > Will be good to run after every `git add`.

* `git commit -m <MESSAGE>`
    > Giving the message to your change that you and other dev's can understand.

* `git commit -m <MESSAGE> -m <DESCRIPTION>`
    > You can add some description to the commit message, describing your own commit. 
    > In case of husky error use -n short for --no-verify.

* `git commit -am <MESSAGE>`
    > This command can directly add and commit simultaneouly.
    > But you can't use this when you have created a new file, you can only use this on modified files.

* `git push -u origin <BRANCH NAME>`
    > This will set the upstream that is basically means that when ever you use `git push` it will push that branch without asking you.

* `git push`
    > This will push your code to github repo.
    > All the changes will be pushed to github repo.

* `git pull`
    > This will fetch all the changes from Github repo.
* `git checkout -b <NEW BRANCH NAME>` 
    > You can make a duplicate branch of your current branch using this command.
    > eg: CURRENT-BRANCH: main 
    >     git checkout -b new-branch
    > CURRENT-BRANCH: new-branch (duplicate of main branch)
* `git branch`
    > You can make multiple branches and to know in which branch are you in.
    > This will tell the current branch as well as branches which are in local-machine.
* `git branch -all`
    > This will let you know all the branches in local as well as in origin.
* `git branch -d <BRANCH NAME>`
    > If you want to delete any branch from your repo.
* `git remote add origin <LINK OF REPO>`
    > Once you have created a new folder and initialized git in it.
    > You have to make new repo in github and set the connection between your local repo with origin
* `git remote -v`
    > After adding this will let you know the remotes of current repo.
* `git reset <FILENAME>`
    > If you want to unstage the current add then just run this.
* `git diff`
    > This will show the difference between from current branch and main.
* `git log`
    > This will show all the commits that has been made yet.
* `git reset --hard origin main`
    > It will reset all the changes that has been made yet from origin.

## Start developing in new branch
1. `git checkout master`
2. `git checkout -b <NEW BRANCH NAME>`
3. This will switch to new branch then develop the new feature in this branch
4. `git add .`
5. `git commit -m <MESSAGE> -m <DESCRIPTION>`
6. `git push -u origin <NEW BRANCH NAME>`

## Stashing
1. `git stash`
2. This command temporarily shelves (or stashes) changes made to in working copy so that we can work on something else such as changing branch, and then come back on the branch and re-apply them later on. Used when we are mid-way through a code change and aren't quite ready to commit.
3. `git stash apply`
4. This will re-apply the stashed changes

## Merging a branch to master
1. `git checkout master`
2. `git
    
