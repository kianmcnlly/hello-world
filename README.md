# learning about git

Most coders tend to keep all their projects inside a directory called either code or workspace.
mkdir code - make direct code
cd code change directory
if you run git status, you should see that git is aware of a new file in the directory, but that it is still untracked. Git has given us a hint as to how we can start tracking files: use "git add" to track.

So lets add our README: git add README.md

Now when we run git status again, we can see that (this time in green), git knows that we want it to track a new file.
