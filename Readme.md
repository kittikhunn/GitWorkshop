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
git log --grep="readme" #Search files that contain "readme"
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