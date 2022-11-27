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

1.Commit
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
```markdown
git pull
```




