## Git Command Reference

### Quick Commands
* **git add Example.md**: Moves a specific file to the staging area.
* **git add .**: Adds all modified and new files in the current directory to staging.
* **git status**: Displays which files are staged, unstaged, or untracked.
* **git commit -m "message"**: Records the staged snapshot to the permanent version history.
* **git push**: Sends local branch commits to the remote repository.
* **git remote add origin "url"**: Connects your local repo to a specific remote server.
* **git pull**: Fetches changes from the remote and merges them into your current branch.

### Restore and Diff Commands
* **git diff**: Shows changes in the working directory that are not yet staged.
* **git diff --cached**: Shows changes that are staged and ready for commit.
* **git restore --staged .**: Unstages files but keeps the actual code changes in your directory.
* **git restore .**: Discards all local changes and resets files to the last commit.

### Log and History Commands
* **git show**: Displays the content changes and metadata of the most recent commit.
* **git log -p**: Shows the commit history along with the specific code diffs for each.
* **git log --oneline**: Summarizes the commit history into a compact, one-line format.
* **git log --grep='Example'**: Filters the commit log for messages containing "Example".
* **git checkout 9804adb**: Moves the HEAD to a specific commit (Enter "Detached HEAD" state).
* **git checkout main**: Switches the working environment back to the main branch.
* **git revert 9804adb**: Inverts the changes of a specific commit by creating a new "inverse" commit.

### Branch Commands
* **git branch logfolder**: Creates a new branch called "logfolder".
* **git checkout logfolder**: Switches your working directory to the "logfolder" branch.