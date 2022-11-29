# git-tutorial
This tutorial goals is learning expert level Git &amp; GitHub

Git Configuration
-------
 1. Create Name, email, color scheme
  
``` markdown
git config --global user.name "USERNAME"
git config --global user.email "USER EMAIL"
git config --global color.ui auto
```

Git Staging Area
-------
  1. Git initialize
  
``` markdown  
git init
```
  
  2. Git add to staging area
 
 ``` markdown  
git add FILES NAME
git add . (Add all file)
git add -A (Add every single file)
git rm --cached FILE NAME (Remove the file which you want remove)
```

  3. Check status
``` markdown  
git status
```


Git Commit
-------

1. Commit
``` markdown  
git commit -m "message"

```
2. Change message from previous commit
``` markdown  
git commit --amend -m "new message" 
```
3. Commit Details
```markdown
git log (Shows details about commits)
git show HASH CODE (Shows detail about commit)
git diff (Shows all difference about commits)
```

Git Push An Existing Repository from the Command Line
-------

1. Create SSH on GitHub
2. Create provate token on GitHub
3. Create repository from GitHub
```markdown
git remote add origin htttps github username
git bracnh -M main
git push -u origin main
```
Note: After creating token is going to be your password!

Git Pull
-------
1. Fetch the specified remote’s copy of the current branch and immediately merge it into the local copy. This is the same as
2. Similar to the default invocation, fetches the remote content but does not create a new merge commit.
```markdown
1. git pull
2. git pull --no-commit
```

Git Branch
-------
1. Delete branch
2. Copy branch
3. Show which branch you are in
4. Check all branches
5. Switch between branches
6. Create branch

```markdown
1. git branch -d + (BRANCH NAME FOR DELETE)
2. git branch -c
3. git branch
4. git branch -a
5. git branch checkout + (BRANCH NAME FOR SWITCH)
6. git branch -b + (BRANCH NAME YOU WANT TO CREATE)
```

Git Merge
-------
```markdown
git merge + (BRANCH NAME YOU WANT TO MERGE)
```

Git Rebase
-------
Rebasing is the process of moving or combining a sequence of commits to a new base commit.

```markdown
1. git pull -r origin (BRANCH NAME)
```
Manuel fix the conflicts

```markdown 
2. git add .
3. git rebase --continue
4. git push -f (Force push)
```




