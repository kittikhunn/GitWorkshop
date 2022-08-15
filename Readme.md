# Git Config
## Configuration Level

## Local
```
git config --local user.name="kittikhunn"
git config --local user.email="kittikhun.scy@gmail.com"
```

## Global
```
git config --global core.editor "code --new-window--wait"
```

### System
```
git config --system -e
```

## Git Log
### Filter
```
git log --since=2022-08-14
git log --since="1 days ago"
git log --since=1.days
git log --until=1.days
git log --since=2.weeks --until=1.days
git log --after=2.weeks --before=1.days
git log --grep="readme" Search files that contain "readme"
git log --author="kittikhunn"
git log 34b3..HEAD
git log Readme.md
```

### Format
```
git log -p
git log --stat
git log --format=oneline
git log --oneline
git log --oneline --graph --decorate3db7

## Git Show
```
git show 4dde
git show HEAD
git show HEAD^
git show HEAD^^
git show HEAD^^^
git show HEAD~5
```

## Git Blame
```
git blame Readme.md
```

## Git ls-tree
```
git ls-tree HEAD
git ls-tree main
git ls-tree db53 #use git log id
```

## Git add and commit
```
git add .
git add Readme.md
git commit -m "messgae"
git commit -am "add and commit
git commit --amend
git commit -m "commit and add new message"
git remote add origin <URL of remote repository>
git remote -v
```

## Git Remove (git rm)
```
git rm <filename> #ลบบน working space
git rm --cached <filename> #ลบบนตัวกลางกับ repo
```

## Git diff
```
git diff
git diff --cached
git diff
git diff 9f53..4dde
git diff HEAD..HEAD~2 จากตัวใหม่ล่าสุดไปตัวก่อนหน้า (move back)
git diff HEAD~2..HEAD จากตัวก่อนหน้ามาตัวล่าสุด (move forward)