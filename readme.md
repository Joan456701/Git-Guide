### 1. Config user
``` 
git config --global user.name "Your Full Name"
git config --global user.email "your-email-address"
git config --list
```

### 2. Init git
```
mkdir "Repository Name"
cd ".\Repository Name"
git init
dir -hidden
```

### 3. First Commit  
```
git status
git add .\file.ext
git status
git commit -m "Initial commit"
git status
git log
```

### 4.Create branch dir/branch-name
```
git branch dir/branch-name
git branch
```

### 5.Checkout branch
```
git checkout dir/branch-name
git status
```

### 6.Merge to master
```
git checkout master
git status
git merge dir/branch-name
git status
git log
```

### 7.Create Stash
```
git status
git stash
git status
```

### 8.Apply Stash
```
git stash list
git stash apply 
git status
```

### 9.Drop Stash
```
git stash list
git stash drop 1
git stash list
```

### 10.Pop Stash
```
git stash list
git stash pop
git stash list
```
### 11.Revert Commit
 ```
 git log --online
 git revert [COMIT_ID]
 ```

### 12.Cherry Pick
```
git log --online
git cherry-pick [COMIT_ID]
```

### 13.Reset
```
git log --online
git reset --soft HEAD~1
```

### 14.Create Patch
```
git diff HEAD > <file>
```

### 15.Apply Patch
```
git apply <file>
```

### 16.Init GitHub
```
git remote add origin [REMOTE-URL]
git push -u origin master
git push origin --all
```
