This project gives an overview of Big Data
git add filename --> add file to the staging area for commit
git commit -m 'message' --> staging area files are commited on the local repo
git push   --> pushing files on global repo
git log --> creates log of the changes done in the repo
git status --> gives the status of the modified files, committed or not
git checkout -- filename --> undo changes of uncommitted files
git revert commit_id --> undo changes for the particular commit wrt commit_id and commits the undone
git revert -n commit_id --> explicit commit is needed to perform after undoing of the commits
