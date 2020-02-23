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

how to solve conflict
assume i am behind from developed branch and i made many of the changes in the same branch steps are as follows: 
1). it has to be commit hpw many changes in my local
    using visual studio code gitlens extension
    1). click on "+" button that means i am staging my whole files\
    2). type a message in a box and hit on tick button
    3). click on triple dots button and choose pull option that means git pull
    4). now conflicts files shown into the left pane 
        a). open the file 
        b). select the option of accept both changes 
        c). as per rhe requirement we will resolve all the changes and save the file
        d). same points for rest of other conflicted files
    5). hit on tick button 
    6). click on triple dots button and choose push option that means git push into the selected branch


`git status` Check Status of your current branch
`git branch` see the all branches


`git checkout -b Develop origin/master` How to make a new branch+swtiched into new branch
`git push origin -u BranchName` for pushing new branch
`git checkout -q Testing` how to switch on the branch
 how to rename the branch.
   `git branch -m new-name` if we are into same branch
   `git branch -m old-name new-name` if we are rename other branch name
how to delete the branch
`git branch -d Delete` from local
`git push origin --delete Delete` from remotely
`git fetch -p` for update the list which no longer exist on the remote will be deleted.

`git push origin Developing:Develop` if we changed local branch name from remote branch
For Merging
    1.) `git checkout -q localbranchname` Select that branch you need to update/merge the changes
       
    2.) `git merge UpdatedLocalBranch`