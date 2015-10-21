# GitHub Tutorial

## _By Jonathon Valerio_

---
## Git vs. GitHub
### Git:
* Git allows you to do very small projects to even bigger projects on your local computer with effeciency and speed. Allowing you to easely get done any type of project and use its database programming.
* Git is LOCAL, which means this can be used locally without the use of Github, Git can be used on its own platform.

### Github:
* Github allows you to take these changes that you have made and place them all over the web so people can see and work on your projects. This allows you to easely collaborate with your friends and share eachothers work in order to get progress done.
* Github would be considered web based and allowing sharing using the forking repositories and cloning, as well as git commit and many others you could do with git hub (The Remote)

_Basically, Git is the local PC database and Github would be the web based database where you would be able to share your work with others_


---
## Initial Setup

### Github Account:
* Your github account is there for you to refer to in times of need in sharing your projects and those you had git with you. Your github account is the number one source for you to check if you have everything you need and to make sure that the repository and everything was transferred from the git, as well as forking and cloning and other projects. Sign up for a [GitHub](http://www.github.com) account TODAY!

### SSH Key:
* SSH keys are a overall security code to your repositiories and to make sure there is no breeching involved in these projects. The key is the overall only way to get acces within other repositiories as well as yours in case you need it after you have commited.

### Git Configs:
1. user.name
  * This basically ensures that your name is attached to your repositiories and everythiong else. It's good to print your name in and everything else. 
  
    `You can achieve this by planting in git config user.name "John Doe" or your name in the quotes, after this it should be able to work.`

2. user.email
 * This basically ensures as well with your name that your email is linked up with your repositories as well, This associates commits with your account and makes sure this is your email. If a clone was to be made hthey can see the email and such as well with the email. 

    `You can be able to do this with planting git config user.email and your email after that, for example; johndoe556@gmail.com`


---
## Repository Setup

### Git Init:
 * This git Init is an on switch for those that wanna associate a certain repository with git, by just simply planting git init within the command line and the git will be initialized to that type of repository, be careful, once you add a git to a folder or a workspace, it can be very _very_ hard to undo this action. Here, this will allow you to use the git actions and such.

### Your First 'Add' and 'Commit':
 * The following directions will be used in the workspace, this add and commit allows you to view your git from the remote github and allows others to view this as well:
 
  1. First, you may have to check your work to make sure that everything is saved with the sutosave option, everything will be seen in this commit and seen on Github.
  2. Now, you will have to put git add "file name", this allows it to be pushed to this account and be noticed with the site in general
  3. After, you would need to now commmit, commiting is the use of making sure that you are ready to push this file to Github and everything is okay and gets approved. This commit and add is basically the two steps needed to add this and be seen with the:
  4. You may now place git push in your command line because of the fact that this will be pushed to the account and verything else. These steps are to verify it is within the remote
  5. Check [Git](Github.com) to see if these changes have been saved under repositories. 

### Making A Repo:
  * Making a Repo means sharing your project to the remote known as Github, you may need some steps to get this done!
  
   1. In the upper right hand corner of the page of your github, click +, and you will be rerwarded with a couple of options, you will click new repository.
   2. Create a name for this, something you are able to remember, if you want, add a description!
   3. Pick between a public or private repositories.
   4. Initialize this with one of your readme.md's!
   5. You are all done! Click Create Repo.

### Remote:

 * By adding git remote add in the command line, this will proceed to make a remote to something or add a remote to something that is out of your local workspaces. Remote names are also called origin. These remotes allow you access through the git.


---
## Workflow & Commands
### Vocabulary:
1. Status - Status to check the stability of your git or something is wrong (git status)
2. Add - To add your repo to another remote or github (git add)
3. Commit - To make the final steps to adding to a remote, you commit, which is mostly a verification on if you want to continue to add, otherwise known as saving your changes done to the folder. (git commit -m "enter message")
4. Push - Pushes this to the remote. (final step; git push)
