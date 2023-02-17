## Some basic Git commands that are used in Practicals

### 1. Init 
  The git init command creates a new Git repository on your local machine. 
```
git init
```
### 2. Add
Git add command add the untrackable or changed file into staging area.

```
# for all file
git add .

# specific file
git add {file name}
```
### 3. Commit

To record the changes in git, commit command is used.

<img src="./images/commit.png">

### Link the remote repository & Push
   
```
git remote add origin <link>
git push origin master
```

<img src="./images/Link remote and push.png">

# Practical 1 : Pull & Merge difference
Git pull command is fetch the history from remote branch and merge it into current branch. 
    
```
git pull origin master
```

<img src="./images/p1/1.png">


Pull request is used to request the user to pull the code from our repository or branch.
The owner can review changes, approve them and merge the changes.

<img src="./images/p1/2.png">

Git merge command merge current branch with target branch.

    
```
git merge master
```

<img src="./images/p1/3.png">

