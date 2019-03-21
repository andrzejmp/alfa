# Git Setup

git config --global user.name "adamabacki"

git config --global user.email adamabacki@whatisit.com

----------------------------------------------------
## Additional Instructions

git config --global core.editor emacs

git config --list

git config user.name

git help 

git help config

----------------------------------------------------
## Creating a new repository on the command line

echo new_repo >> README.md

git init

git add README.md

git commit -m "A new repo"

git remote add origin https://github.com/andrzejmp/new_repo.git

git push -u origin master

----------------------------------------------------
## Push an existing repository from the command line

git remote add origin https://github.com/andrzejmp/new_repo.git

git push -u origin master

-----------------------------------------------------------------
## Synchronization with the central repository's master branch using a rebase

git checkout master

git pull --rebase origin

------------------------------------------------------------------
## Tutorials
   
https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup
   
https://git-scm.com/doc
   
https://www.atlassian.com/git/tutorials/syncing/git-pull

