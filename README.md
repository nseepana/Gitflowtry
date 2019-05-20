create git repo:
$ git init

create new branch and switch to that branch
$ git checkout -b feature

list all branches
$ git branch -a
$ git branch -r

to stage modified/newly added changes
$ git add .

to commit staged changes
$ git commit -m "commit message here"


create git repository from:
https://github.com/new


push an existing repository from the command line
$ git remote add origin https://github.com/nseepana/gitflowtry.git
$ git push -u origin master

Short answer from Torek:
origin/master is "where master was over there last time I checked"
master is "where master is over here based on what I have been doing"