Update, testing new intermediate Git commands. Such as git init, git diff, git diff --staged
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
