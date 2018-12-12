# Hello This is my first GitHub and Git practice part1
----
## Basic Git Command line

1. git clone [URL of repository]
2. git remote -v
3. git remote add origin [URL of repository]
4. git status
5. git add [filename] or git add . (add all file)
6. git commit -m "some commit message"
7. git log
8. git push origin master
9. git config --global user.email "your email"
10. git config --global user.name "your name"
11. git config --local -l
----
## Fetch And Merge Repo
(Need create a new repo on GitHub first)
1. git remote add upstream [URL of repository]
2. git fetch upstream
3. git merge upstream/master (--allow-unrelated-histories)
4. git push origin master
5. git remote rm upstream
----
## Create And Connect New Repo (Local)
(Need create a new repo on GitHub first)
1. mkdir [folder name]
2. cd [.../.../folder name]
3. touch README.md
4. git init (it means .git control the situation in this folder)
5. git add README.md
6. git commit -m "some texts"
7. git remote add origin [URL of the new repo you create]
8. git push -u origin master
----
## Create The Branch And Merge Process
1. git checkout -b [brach name] 
    ( == git branch [branch name] and git checkout [branch name])
2. git branch (show the current branch you stay)
3. git push origin [branch name]
4. git clone [URL of repository] -b [branch name]
5. git status
6. git add [filename] (git add .)
7. git commit -m "commit message"
8. git push origin [branch name]
9. git checkout master
10. git merge [beanch name]
11. git status (need back to local master )
12. git add .
13. git commit -m "commit message"
14. git push origin master
----
## Markdown Practice

*hello*

**hello**

*hello

>hello
    hello world

[links](http://www.google.com)
----

## BRANCH TEST
