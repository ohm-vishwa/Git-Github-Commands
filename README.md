# Git & Github Commands
Quick Refrence of git &amp; github commands

> ## see configuration
```bash
git config --list
```

> ## set user name
```bash
git config --global user.name "ohm_vishwa"
```

> ## set email
```bash
git config --global user.email "example@email.com"
```

## Basic Commands

> ## initialize git
```bash
git init
```

> ## clone github repo
```bash
git clone <url>
```

> ## view files
```bash
ls
```

> ## view hidden files
```bash
ls -la
```

> ## check status
```bash
git status
```

> ## staging single file
```bash
git add <file name>
```

> ## staging all files
```bash
git add .
```

> ## commit on git
```bash
git commit -m "message"
```

> ## add & commit togther 
```bash
git commit -am "message"
```

> ## push code on github repo (Once)
```bash
git push -u origin main
```

> ## after `-u origin main` 
```bash
git push
```

> ## verify remote
```bash
git remote -v
```

> ## add remote repo 
```bash
git remote add origin <url>
```

> ## set new url
```bash
git remote set-url origin <url> 
```

> ## check branch
```bash
git branch
```

> ## rename branch
```bash
git branch -M main
```

> ## navigate
```bash
git checkout <branch_name>
```

> ## create new branch
```bash
git checkout -b <new_branch_name> 
```

> ## delete branch
```bash
git branch -d <branch_name>
```

> ## push other branch
```bash
git push --set-upstream origin <branch_name>
```

> ## compare commits, branches, files & more
```bash
git diff <branch_name>
```

> ## merge 2 branches or create pull request
```bash
git merge <branch_name>
```

> ## feth & dawnload content from a remote repo local repo
```bash
git pull origin main
```

> ## view all commit 
```bash
git log
```

> ## remove staged changes
```bash
git reset <file_name>
```

or,
```bash
git reset
```

> ## restore commited changes (for one commit)
```bash
git reset HEAD~1
```

> ## restore commited changes (for many commits) using `git log`
```bash
git reset <commit_hash>
```

or,
```bash
git commit --hard <commit_hash> 
```
> ## Token Authorization
```bash
git remote set-url origin https://<token>@github.com/<user_name>/<repo_name>
```
