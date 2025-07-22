# git-cheat-sheet

A cheat sheet for git

Branch Commands
• git branch
List all the branches in a repository.
• git branch <branch name>
Create a new branch with the specified name.
• git checkout <branch name>
Switch to a different branch.
• git merge <branch name>
Merge the current branch with the specified branch.
• git branch -d <branch name>
Delete the specified branch.
• git push origin --delete <branch name>
Delete a remote branch.
• git checkout -b <branch name> origin/<branch name>
Clone a remote branch and switch to it.
• git merge <source branch> <target branch>
Merge the two given branches.
• git branch -m <old name> <new name>
Rename a branch.
• git rebase <branch name>
Apply all the commits of the current branch ahead of the specified branch.

Basic Commands
• git clone <URL>
Copy a remote repository to your local directory.
• git init
Initializes a GIT repository on your local system, in the current working directory.
• git status
Shows the state of the current working directory.
• git add <file>
Add the specified file from the local directory to the GIT staging area.
• git commit
Convert the staged changes to a snapshot, and save it in the local directory.
• git push
Send the commits to the remote repository.
• git diff
Show the differences between the working directory and the staging area.
• git stash
• git stash pop
Move the changes from the stash back to the working directory.
• git remote
View all remote repositories.
• git remote add origin <URL>
To add a new host to your working directory.
• git pull
Pull all the changes from the remote directory.
• git config --global user.email myemail@domain.com
Set an email which will be associated with the commits made to the repository.
• git config --global user.name "user name"
Set a user name which will be associated with the commits made to the repository.

History Commands
    • git revert <commit hash>
Undo a commit using its hash.
    • git reset <file>
Remove a file from the staging area, without modifying anything in the local directory.
    • git reset --hard <commit hash>
Permanently revert back to a previous commit.
    • git checkout <commit hash>
Temporarily transform your working directory into the state it was in at the time of the specified commit.
    • git reset --hard HEAD~2
Permanently revert the last two commits.
    • git clean -n
Perform a “dry run” of the clean command to see which files will be removed.
    • git clean -f
Remove untracked files from the working directory.
    • git rm -r <file or directory name>
Remove/untrack a file or directory from GIT.
