# git_command_list

## Info & Nav

`git log` View the history of current branch.

`git show <COMMIT>` View the changes of one commit.

`git diff` View the diff of the unstaged code.

`git diff --cache` View the diff of the staged code.

`git status` View the current git status.

`git remote -v` View all the remotes.

`git branch -v` View all the branches.

---

`git fetch <REMOTE>` Update all the branches of a remote.

`git fetch <REMOTE> <BRANCH>` Update the a branch of a remote.

`git checkout <BRANCE>` Change the current branch to another branch.

`git checkout <COMMIT>` Change the current branch to an anonymous branch in which the commit is the last commit.

## Modify Remotes

`git remote add <REMOTE_NAME> <REMOTE_GIT_LINK>` Add a new remote.

`git remote remove <REMOTE_NAME>` Remove a remote.

`git remote rename <REMOTE_NAME> <REMOTE_NEW_NAME>` Rename a remote.

`git remote set-url <REMOTE_NAME> <REMOTE_GIT_LINK>` Change a git link of a remote.

`git push <REMOTE> <LOCAL_BRANCH>:<REMOTE_BRANCH>` Push the local branch to the specific branch of the remote.

`git push <REMOTE> :<REMOTE_BRANCH>` Delete the remote branch. 😈😈😈😈😈😈😈😈

`git push -f <REMOTE> <LOCAL_BRANCH>:<REMOTE_BRANCH>` Forcely push the local branch to the specific branch of the remote.😈😈😈

## Modify Branches

`git branch <BRANCH_NAME>` Create a branch using current status.

`git branch -D <BRANCH_NAME>` Delete a branch.

`git checkout -b <BRANCH_NAME>` Create a branch using current status and checkout to the new branch.

## Modify in Branch

`git add --all` Stage all the local changes.

`git commit -m <COMMIT_STR>` Commit current staged code using the commit message.

`git commit -am <COMMIT_STR>` Commit current staged and unstaged code using the commit message.

`git commit --amend` Merge the staged code to last commit. ♥️♥️♥️♥️♥️♥️

`git reset HEAD~<n>` Reset the branch head to the **n**th most recent commit.

`git reset --hard HEAD` Remove the staged and unstaged changes.

`git pull <REMOTE> <BRANCH>` Fetch the branch of the remote and merge it to current branch.

`git pull --rebase <REMOTE> <BRANCH>` Fetch the branch of the remote and rebase to current branch.

`git rebase <BRANCH>` PLS google it, I don't know how to illustrate it in one line. :P

`git merge <BRANCH>` Create a new commit to make the different code of two branches together.

`git revert <COMMIT>` Create a new commit to change the code to the status of the commit.

`git cherry-pick <COMMIT>` Create a new commit to copy the changes of the specific commit.

`git rebase -i` PLS google it, I don't know how to illustrate it in one line. :P
