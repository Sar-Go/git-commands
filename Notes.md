* git push -f
-f is short for force

* the 3 trees of git ?
Commit History (head); The staging index, Working directory

* git reset?
undo local changes to the state of a git repo

* git soft reset?
moves the HEAD back tot he specified commit, undoes all the changes made between where head was pointing nad the specified commit, and saves all the changes in the index.

* git reset hard ?
undoes the changes and removes the associated files from the working directory, staging area, commit history

* How to reset my branch to the latest dev branch?
git merge -no-commit dev
This will merge, commit, and override the added changes

git reset --hard dev
