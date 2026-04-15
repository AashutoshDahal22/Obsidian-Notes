#work #project

`git add .` = *adds all the changed files into the commit*
`git commit -m ""` = *adds commits to the changed to be pushed*
`git show --name-only` =*shows the fiels that has been changed in the latest push*
`git show` = *shows the files that has been changed in the latest push along with the changes made in the code*
`git switch branchName` = *to quickly switch between branches when there is no changes in one particular branch*
`git cherry-pick commit hash`= *to pick commit from one branch and add it into another*
`git log --oneline` = *to display all the commit hashes in the particular branch*
`git checkout -b branchName` = *to create a new branch in particular to the current branch as a base*
`git branch -d branchName` = *to delete the particular branch*
`git branch -m newBranchName` = *to rename a branch* (this has a variation in which we can name another branch without checking it out)
`git rebase branchName` = *to merge the histories of the branches into a singular and managed commit history*
`git reset --soft HEAD~1` = *to undo the changes made in the last commit*
`git stash` = *to temporarily save the current code without commiting it into the remote branch*
`git stash pop` = *to take the temporary changes and apply into the current working dir*
`git stash list` = *to list the available stashesh*
`git stash push -m "message"` = *to name the stash for proper recognition and useage*
`git stash clear` = *clears all stash from the list*
`git stash drop stash@{0}` = *to delete the specific stash*

