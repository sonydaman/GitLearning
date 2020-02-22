how to start a project in github
1.) ctrl+` #this will open the shell

2.) `git init`  # this will initlize intialize the repo into a specific folder
3.) `git add README.md` #for add specific file into a staging  
        if we want to add all files `git add *`
4.) `git commit -m "first commit"` for commit into our local branch
5.) `git remote add origin https://github.com/sonydaman/GitLearning.git`
    this is only for first time while we need to add our remotely repo link
6.) `git push -u origin master` push the local changes into the remote branch