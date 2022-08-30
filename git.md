`git clone url` \
`git add .` \
`git commit -m “”` \
`git push`

Set user_name and email \
`git config --global user.name "FIRST_NAME LAST_NAME"` \
`git config --global user.email "MY_NAME@example.com"`

List of all remotes \
`git remote`

Change remote url \
`git remote set-url origin NewURLHere`

reset changes to last commit on remote (HEAD) \
`git fetch --all` \
`git reset --hard origin/<branch_name>` \
`git merge origin/main` - merge main commits to current branch
