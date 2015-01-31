# git-commands
simple git commands


# How to start working with git

## git basics:


* Create a account on github 
* now create a repository of your project
* add the gitignore file from [gitignore](http://www.gitignore.io/) or while you can add it when you create repo
* Give permissions to those who are colloborators .
    
    
    
* you can either create a repo from the terminal(if you have one )
    
    
* Installation : on linux (debian system )

        >> sudo apt-get install git   
        
* Installation : on windows based 
    
    * Download git bash from the [MSYSgit](https://code.google.com/p/msysgit/downloads/list?q=label:Featured)
    * install by clicking on exe .
    
* basic commands to setup your username and email 
    * `git config --global user.name  MY_USERNAME`
    * `git config --global user.email MY_EMAIL`
    
* basic commands :
    * `git --help` 
    * `git clone https:github.com/AnyRepository`  (to copy any repo in your system )
    * `git status` ( to know the status of repo)
    * `git add filename1, filename2`....       ( to add the untracked files )
    * `git add -A`        (adds all the untracked files )
    * `git commit -m "message of each commit " filename`
    * `git commit -a `    ( to commit all the changed files )
    * `git pull ` ( to fetch the changes )
    * `git push ` ( to push the changes on central server ) 
    
    * `git diff` filename to know the changes between 2 commits 
    
    * `git stash`  ( to undo the changes )
    * `git rm filename` (untracking file . diff from rm in linux )
    * `git mv originalFilename newFilename ` ( renaming file )
    
    
##### source - [Refer github documentation ](http://git-scm.com/doc) 


#### some common errors: 
* fast-forward : It comes when you try to push changes on the server but server is ahead a few commits .To
    solve this just commit your changes first and pull the changes from server. 
         

**Note** : Do not edit the .git directory files ever
    
    
only the text changed is sent not the whole file. 
Every commit is a new vesrion you can say
A life cyle - Add, commit push pull

    

    

 
