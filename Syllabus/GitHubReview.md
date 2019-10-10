# to add a file to the repo

1. open terminal & 'cd' to the folder where your notebook is
2. type 'git status' this will list all the files that git is tracking for you and their status
3. type 'git add filename.ipynb' 
4. type 'git status' now you should see the file you added in green, it is now staged to commit
5. type ' git commit -m "make a comment describing version of file" ' 
6. type 'git status' look for the comment that says your branch is ahead of the origin/master, this confirms the file was committed
7. type 'git push' this pushes the file commit to the git hub website VERY IMPORTANT!


# to download files that have changed in the master repo

1. open terminal & 'cd' to the folder where your notebook is
2. type 'git status' this will tell you if your branch is up to date with origin/master or behind by a number of commits
3. if you are not up to date type 'git pull'
4. type 'git status' and it should now say your branch is up to date with origin/master

