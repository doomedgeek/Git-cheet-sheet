Git Cheat Sheet
Initializing a Repository
git init - Initialize a new Git repository
Cloning a Repository
git clone [url] - Clone a Git repository from a remote server
Staging Changes
git add [file] - Add a file to the staging area
Committing Changes
git commit -m "commit message" - Commit changes to the local repository
Checking Repository Status
git status - Show the status of the working directory and staging area
Comparing Changes
git diff - Show the differences between the working directory and the staging area
git diff [commit1] [commit2] - Show the differences between two commits
Viewing Repository History
git log - Show the commit history
git log --oneline - Show the commit history in a condensed format
git show [commit] - Show information about a specific commit
git blame [file] - Show who made changes to a specific file
git blame -L [start],[end] [file] - Show who made changes to a specific range of lines
Branching and Merging
git branch - List all branches in the repository
git checkout [branch] - Switch to a different branch
git checkout -b [branch] - Create a new branch and switch to it
git merge [branch] - Merge changes from a different branch
git merge --abort - Abort a merge in progress
git branch -d [branch] - Delete a branch
git rebase [branch] - Rebase the current branch onto a different branch
Remote Repositories
git remote - List all remote repositories
git remote add [name] [url] - Add a new remote repository
git remote remove [name] - Remove a remote repository
git fetch [remote] - Fetch changes from a remote repository
git fetch --all - Fetch all changes from all remote repositories
git push - Push changes to a remote repository
git push [remote] [branch] - Push changes to a specific branch on a remote repository
git pull - Pull changes from a remote repository
git pull --rebase - Pull changes and rebase them onto the current branch
Miscellaneous
git stash - Stash changes to be applied later
git stash apply - Apply changes from the most recent stash
git stash list - List all stashes in the repository
git tag - List all tags in the repository
git tag -a [tagname] -m "tag message" - Create an annotated tag
git tag -d [tagname] - Delete a tag
git reset [commit] - Reset the repository to a specific commit
git reset --hard [commit] - Reset the repository to a specific commit and discard all changes
git revert [commit] - Revert changes made in a specific commit
git cherry-pick [commit] - Apply changes from a specific commit to the current branch
git submodule - Manage submodules within the repository
git config - Configure Git settings
git help - Show help for a specific Git command
git commit --amend - Modify the most recent commit