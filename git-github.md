
# first-Time Git Setup

git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
----------------------------------------------------

#some additional instructions

git config --global core.editor emacs
git config --list
git config user.name
git help <verb>
man git-<verb>
git help config

----------------------------------------------------

# create a new repository on the command line

echo "# test-02" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/andrzejmp/test-02.git
git push -u origin master

# push an existing repository from the command line

git remote add origin https://github.com/andrzejmp/test-02.git
git push -u origin master

-----------------------------------------------------------------
# synchronization with the central repository's master branch using a rebase
# https://www.atlassian.com/git/tutorials/syncing/git-pull

git checkout master
git pull --rebase origin
------------------------------------------------------------------

# tutorials
# https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup
# https://git-scm.com/doc

