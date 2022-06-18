`git init`: initialize current folder as a git repository
`git clone <URL>`: brings the git repo from <URL> to current folder
`git status`: tells us what we need to know about our repository
`git add <FILE>`: adds <FILE> to the staging area
`git commit`: opens a text editor to write a commit message
    `git commit -m "MESSAGE"`: writes MESSAGE as a commit without a text editor
`git log`: shows the log (history) of our commits
    `git log --oneline`: shows the shorter oneline commit
`git diff`: compare current uncommited state with last know git state
    `git diff --staged`: runs git diff between the staging area and last known state
`git diff HEAD~<NUMBER>`: compares HEAD with commit <NUMBER> ago (relative)
`git diff <HASH>`: compares HEAD with the commit in <HASH>