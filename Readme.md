CSCI 5828 - Spring 2018
Homework 2
Brandon Boylan-Peck
02/19/2018

0:
git init
copy NUL Readme.md
EDIT Readme.md
git status
git add Readme.md
git status
git commit -m "commit 0"

1:
EDIT Readme.md
git add .
git commit -m "commit 1"

2:
git log --graph
EDIT Readme.md
git add .
git commit -m "commit 2"

3:
git log
git checkout b542a
git checkout -b bug-fix
git log
EDIT Readme.md
git add .
git commit -m "commit 3"

4:
EDIT Readme.md
git add .
git commit -m "commit 4"

5:
git merge master
EDIT Readme.md (fixed merge conflict)
git add .
git commit -m "commit 5, Merge conflict"

6:
git log --graph
EDIT Readme.md
git add .
git commit -m "commit 6"