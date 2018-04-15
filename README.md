# Git-Commands

General Commands:
----------------
1. git clone repo-name // clone git repo to local system
2. git add . // add all in present directory
3. git commit -m "comment" // commit changes to git with comment
4. git push // push all changes
5. git pull // update local git from remote git

Master & Branch:
----------------
1. Create directory with name of your repo // will create directory name Healthcare-UI
2. git clone -b master <repo> master // will run this command under directory Healthcare-UI
3. git worktree add ../<branch name> directory-name // git worktree add ../dev dev (under Healthcare-UI we have master , under master we will run this command)
4. git worktree add ../<branch name> directory-name // git worktree add ../prod prod (under Healthcare-UI we have master , under master we will run this command)

Status:
-------
1. git status // You can verify which branch you are on using
2. git branch -r // If you want a list of the available branches (in the remote repo) execute
