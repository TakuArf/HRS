hi  
this is a commit and push test.  
and koichiro's note (feel free to edit this file ^^)  
it may include some false infomation, be careful

### setup
```
git clone https://github.com/TakuArf/HRS.git
git branch
git switch 実装
git branch
```

### commit (record) changes in local side
- i have to search about push more to avoid a disaster
```
git config user.name  (check local username is the same as github one)
git config user.email
git config --list     (check a current git setting)

git branch            (check a current branch)

(update files, COMMIT FOR EACH FILE)

git status
git add .             (u can specify what to stage)
git status
git commit -m "[comment]"
```

### communicate b/w local and remote
```
(from remote to local)
git fetch
git pull origin 実装
(it may cause conflicts, if so, u must resolve it)


(from local to remote)
git push origin 実装
```

### other commands
```
ls -Force         (show hidden files in powershell, u can see .git folder)
```

### grocery 
these concepts except (fetch, pull, push) are all for both local and remote  
u should interpret for branches in git

- development branch
  - add:    make it ready for commit
  - commit: reflect changes to the current branch (in local side)
  - push:   reflect the commit to the remote branch
- main (or remote) branch 
  - pull:   propose the commit to main or other branch / get updated info from another branch
  - merge:  accept the pull request
