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

- git branch - show all local (-a to show remote too)

- git branch name - making new branch

- git checkout -b name - make a branch and go to it

- git diff main HEAD - diff between main and HEAD pointer

- git diff HEAD~2 HEAD - diff between commit that was 2 steps behind and this one

- git branch -d name - delete branch only if it is part of main (-D if not)

- git merge main - merger curr with main

-  git push -u origin my-branch - sending to github and connecting it with local branch

-  git pull - get changes from github from curr branch

- git checkout name - got to branch
