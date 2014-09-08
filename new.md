## This is a new markdow document

Purpose to

* test writing markdown
* test creating new doc

you can include URLs like this 

[BBC](http://bbc.co.uk)

### Update Process

I created the repository using the git clone url command
Useful to copy and in windows use insert button to paste URL

Commands for creating and synching files:

* I created this file using ¦touch (file name)¦ command. 
* You can see the Status of the GIT repository using ¦GIT Status¦ command
* To add the files to the files GIT tracks use ¦GIT add (file name)¦ command  (adding to index).  You can use ¦git add . ¦ to add all the files in the directory  
* Changes commited to local repository using ¦git commit - m "Commit Message" ¦ command
* Run ¦git status¦ to make sure nothing else to commit
* Check the log using   ¦git log¦ command to see that commit is there
* use ¦git push origin master¦ command to push the master branch to the origin (set up when we cloned).  Will ask you for your password

### Synching Fork Process

You always have to synch from the original repo (that you forked from) to the local git on the computer and then push back to the Github forked copy.

* use the ¦git remote -v¦ command to see remote urls associated with local repository
* To add the reference to the original repo use the ¦git remote add upstream (URL)¦ commmand
* use ¦git remote -v¦ command to check status
* now you can synch changes using ¦git fetch upstream¦ command  This brings the new updates into a new branch called upstream/master
* To merge the upstream/master in to master branch use ¦git merge upstream/master¦ command.  This merges changes into master branch
* You can now push the changes to your GitHub forked copy using ¦git push origin master¦ as above