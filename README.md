# GitHub Tutorial

_by simeon karakatsiotis_

---
## Git vs. GitHub
Git and Github go hand in hand when coding. git does **NOT** require Github in order to work, git is a "_photographer_" of your code and takes "_snapshots_" of your `code` that has been put to the staging area when you `add` and `commit`.

Github is more of an extension of git. Github is a cloud platform that creates a remote repository and saves your commits in the cloud for future use. 


---
## Initial Setup
 To make a github account go to <URL> https://github.com/ and press sign up to github at the top right of the webpage. then put in your email and password to start your `coding` expirences in github. **BUT DO NOT FORGET** to verify your github by checking your email and clicking the link to verify that you are a human and not a robot. if you dont do this no one will be able to see your repositorys on github.


---
## Repository Setup
 in order to make a git repository you first need to initialize  git in a folder along your cloud nine workspace. Once you do that, you must go to <URL> https://github.com/ and go to the top right to make a new repository by clicking the plus button  next to your profile icon and then clicking new repository button. Then name the repository the same as your master git folder to create a ready connection. hen there is a command that should be copy and pasted into your command line on cloud nine to then finish the connection between your remote and local repositories.


---
## Workflow & Commands

* `Git init`:initialize git to a repo
* `Git add`: adds to the _"staging area"_
* `Git commit`:creates the _"snapshot"_ of your code
* `Git status`:checks what you have done in your repo
* `Git push`: pushes to your cloud
* `Git clone`: clones repo to your c9
* `Forking`:clones remote repo to push changes to
* `Git pull`: ask for pull requests to pull down any changes from the cloud

---
## Collaboration 
    
 once you make the connection between your (`local`) repository and your (`remote`) repository you can then `git add`, `git commit` and then `git push` to your remote repository which saves your changes and you can access your file wherever you wish. 

you can also use github to `clone` or `fork` someone elses work. To clone someone elses work  all you simpily have to do is press the clone/download button on your remote repository or someone elses (github page) and then in your `local workspace` use the `git clone` command along with the `<URL>` provided from the github page (remote repository) then submit it into the command line and therfore successfuly cloning that persons work. However there is a drawback to this, is the fact that you cannot push back to that persons repository unless they list you as a contributor. If you want to push changes to the repository then this is where `forking` comes into play. `Forking` someones repository gives you a copy of that persons remote repository to which you can change and push changes too. This does not push changes to the persons original repository, it specifically pushes to your remote repository that you forked from them. To fork a repository simpily press the button on the top right of the persons repository you want to fork that says fork, and then git clone it into your `local` repository. then you can change and push all you like.