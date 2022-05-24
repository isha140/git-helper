## On time setup

### create a config
this config is required to identify the user who committed the commits
```
git config user.name dhruvi
git config user.email dhruviemail@email.com
```

---

### in order to create a new git repository
```
git init
```
This will create a new `.git` folder

---

## Useful commads

### in order to check the current status of repository
```
git status
```
---

### to move from working directory to staging directory
```
git add .
```
or
```
git add <file_name>
```
---

### to add a new commit
```
git commit -m "The message for the commit"
```
---

### to check previous commits
```
git log
```

---

### to go back to previous commit or a new branch
```
git checkout <branch_name/commit_id>
```

---

### to add a new remote
```
git remote add origin git@github.com:dhruvikapadia28/git-helper.git
```
---

### to push to a remote
```
git push -u origin master
```