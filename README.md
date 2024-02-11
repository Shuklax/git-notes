sing hiphen( - ) in fron of abbreviated flags and (--) in front of full forms of flags

Check for git version
`git --version`

How to initalise a git repo, how to enable git
`git init`

How to make a new branch
`git branch <branch-name>`

How to view the branches
`git branch`

To send the untrack files to the staging area 
`git add .`

How to switch to different branch
`git switch <branch-name>`

How to create a new branch and switch at the same time
`git checkout -b <branch-name>`

Tracking/knowing which files to put
`git add <file-1> <file-2> <file-3>`
for tracking everything
`git add .`

Putting commit/finalising version of code
`git commit -m <commit-message>`

Pushing code to github
`git push`

upstream mean from local to remote and vice versa

To display the commit history of a Git repository. It provides a chronological list of commits, showing details about each change made to the project's files over time.
`git log` and to see the content/files of each commit use `git log --stat` or `git log --numstat`

If I wanna get the `git log` commit hashes in the short form then use `git log --oneline`

To see specific commit(s) info, use `git show`

To see your changes in the working directory and all the other stuff `git status`

To merge my local branch onto the remote xyz branch `git rebase origin/xyz` but for this you have to be on the intended local branch on top of which you have to merge xyz

To create a branch on my origin main branch from my local machine, the new branch name as fuu --> `git push origin main:fuu`; To delete it `git push -d origin fuu`

Only in push we write the origin and branch name seperately otherwise it is always written as origin/xyz where xyz is the branch name.
So, if I wanna push my main/head branch from local to main/xyz branch in remote then I write `git push origin main:main` or `git push origin main:head` or `git push origin xyz:main`

