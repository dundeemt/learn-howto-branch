learn-howto-branch
==================

practice branching and merginggit branch  - lists branch, current active branch marked with asterisk (*)

git branch branch-name - to create a branch named, branch-name, at the current point from the current branch
git checkout branch-name - Switch to the new branch

git push origin branch-name - push your branch to the server for others to see, fork

git merge branch-name - 1st, switch to the merge target, in this case 'master', then issue the merge command and branch name to merge, this will commit the merge if it is clean.  If not, the dirty files will be marked up, then edit them as needed.  When done fixing, 'git add' tham to re-stage and mark as resolved, then 'git commit'

