how to start a project in github
1.) ctrl+` #this will open the shell

2.) `git init`  # this will initlize intialize the repo into a specific folder
3.) `git add README.md` #for add specific file into a staging  
        if we want to add all files `git add *`
4.) `git commit -m "first commit"` for commit into our local branch
5.) `git remote add origin https://github.com/sonydaman/GitLearning.git`
    this is only for first time while we need to add our remotely repo link
6.) `git push -u origin master` push the local changes into the remote branch

how to clone the project in github "
1). `git clone https://github.com/sonydaman/GitLearning.git`  #this will give the whole project into your local and by default branch will be master.

how to push the changes into the remote branch
1). `git add README.md` #for add specific file into a staging 
2). `git commit -m "Your message"` for commit into our local branch, -m stands for message which message u want to add put in the quotes
3). `git push -u origin master` push the local changes into the remote branch

how to pull the changes into the local branch
1.) `git pull`