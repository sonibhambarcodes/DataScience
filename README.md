This project gives an overview of Big Data
git add filename --> add file to the staging area for commit
git commit -m 'message' --> staging area files are commited on the local repo
git push   --> pushing files on global repo
git log --> creates log of the changes done in the repo
git status --> gives the status of the modified files, committed or not
git checkout -- filename --> undo changes of uncommitted files
git revert commit_id --> undo changes for the particular commit wrt commit_id and commits the undone
git revert -n commit_id --> explicit commit is needed to perform after undoing of the commits
git branch --> gives you the list of branches
git branch branch_name --> creates the new branch with branch_name
git checkout branch_name --> makes the branch_name active
git merge branch_name--> merges the branch_name into active branch
git push --set-upstream origin branch_name -->   pushes the branch_name remotely
git checkout -b branch_name --> creates the branch_name and make it active as well
git branch -d branch_name --> deletes (-d) the given branch_name

