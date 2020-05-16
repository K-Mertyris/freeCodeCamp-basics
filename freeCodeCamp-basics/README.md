# freeCodeCamp-basics

I'll be storing the more commonly used Git commands here as a quick reference guide. Commands and the order I typically use them will be at the top, with more detailed explanations of what they're used for at the bottom.

I know, I know, this information is out there everywhere, I'm just using my Readme spot to store my shortcuts and reminders.

Common git commands:
- git clone https://github.....
- git remote -v
- git pull origin master
- git status
- git checkout -b [branch name]
- git add . OR git add [filename]
- git commit -m "[message for the commit]"
- git push origin [name of branch]
- git branch -d [local branch name]
- git fetch --prune
- git branch
- git branch -r

General steps: 
- clone remote repo from base directory on local drive
- list remotes (to make sure that the right one was pulled)
- refresh trunk (typically done after a successful pull request, but also to refresh the code if any changes happened while away)
- check the status of current branch (local branch up to date)
- check out a new branch and if it doesn't exist, create it
- stage changed files for commit to branch
- commit changes to local branch, comment on changes
- push local branch changes to remote branch
- delete local branch (if done and pull request is approved or rejected, all work on branch is complete, & remote branch is deleted)
- prune outdated branches so they don't show up when git branch -r -a is called
- check local and remote branches for cleanliness