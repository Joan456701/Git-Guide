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
