# to add a file to your FORKED repo

1. open terminal & `cd` to the folder where your notebook is
2. type `git status` this will list all the files that git is tracking for you and their status
3. type `git add filename.ipynb` (replace filename with the name of your notebook)
4. type `git status` now you should see the file you added in green, it is now staged to commit
5. type `git commit -m 'make a comment here in quotes describing file version/changes you made'` 
6. type `git status` look for the comment that says your branch is ahead of the origin/master, this confirms the file was committed
7. type `git push` this pushes the file commit to the git hub website VERY IMPORTANT!


# to download files that have changed in our STELLAR_interns repo

1. open terminal & `cd` into the folder STELLAR_interns 
2. if you are not up to date type `git pull upsteam master`

