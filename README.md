Update, testing new intermediate Git commands. 

Such as git init, git diff, git diff --staged
git log -p (log the patches)
git log -p -2(log only 2 most recent commits)
git log --pretty=format:"%h - %an (logs out the authorname)

git commit --amend (undo your commit if you forgot something in the stage area)
git reset
git --checkout (go back to the previous version of the pull)
git restore --staged
git remote -v (to check remote origins)
git remote add name <url>(to add new remote)
git remote rename name new_name
git remote remove name

git tag (adds temporary tag)
git tag -a name (adds annotated tag, need GPL licence)
git tag -l (lists tags)
git tag -a v1.2 9fceb02 (tags the 1.2 version later, first 8 numbers of your commit)
git tag -d version (deltes the tag with that version)

git config -- global alias.test commit (adds shortcut when using commit, typing  git test will trigger git commit).

git checkout -b branchName (create new branch and checkout to it)
git switch -c branchName (same^)
git merge
git mergetool

git branch -v (to see last commit by each branch)
git branch --merged --no-merged (to see which branch've/haven't been merged before)
git branch move newbranch testing-branch (changes the name of the local branch)
git push --set-upstream to push it remotely (the newbranch name)
git push origin --delete branch-name (to delete branch remotely)

branch workflow
introducing 'Long-running branches' and 'Topic branches'
Example: main (only stable branch)
, develop (branch that merges many topics but is quite unstable for merging to main)
, topic (short-lived branch with only one purpose)

git branch --all (to see all branches)
git fetch origin (to pull all data from the origin point date)
git pull origin (git fetch + git merge)
git checkout -b localorigin origin/testbranch merge (makes local tracking branch of the remote origin to have the actual branch that you can work with)
git checkout testbranch (shortcut form the above upstream branch^)
git branch -vv (shows which local branch tracks which remote)
