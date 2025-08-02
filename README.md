# Git Tips


----
**EXIT VIM**
esc + :q!
---

- ~ home dir

- ../ parent

- TAB - lookup

- pwd - current dir

- ls - files in dir

- cd - go to

- touch - create file

- mkdir - create dir

- git clone - clone rep

- git init - init git rep

- git remote add origin ssh

- git status - info

- git remote add origin url - connect to rep

- git add file or --all - add files to be commited

- git commit - commit file

- git push - push to rep git push -u main first time

- git log   (add "--oneline" if short)

- git commit --amend --no-edit - changing prev commit and creating new commit with new changes + prev changes --no-edit means that message should not be changed

- git restore --staged <file> - rolling back with "-add" (if not commited) (use "." if want to roll back all files)

- git reset --hard <commit hash> - will delete all commits before this one

- git restore <file> - changing file to prev state if modifed

- git diff - lookup for changes in last commit (add --staged if staged)

- echo <text> - log to console (add > OR >> <file> to add to file (> delets file`s content >> - just adds) 
