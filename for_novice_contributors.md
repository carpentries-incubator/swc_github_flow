### Instructions for contributing with git and GitHub

##### Prerequisites and other options
- Editing requires a Github account. You can set one up at [https://github.com](https://github.com).
- If you don’t want to use Github, you can suggest changes by emailing a lesson maintainer

### Working from the GitHub webpage (graphical interface) 

##### Getting Ready:

1. Identify the url and repository name for the lesson you want to make changes for, eg [https://github.com/swcarpentry/git-novice](https://github.com/swcarpentry/git-novice). The main branch in all the Carpentry lessons is called gh-pages. 
2. It’s not possible to for you to directly edit the version of the lesson in the Carpentry repository, so the overall idea of “Github Flow” is that you can edit by making your own copy of the lesson repository, making a branch in your own copy, making the changes on that dedicated branch, and then sending your proposed changes back to the Carpentry version of the repository.

###### Have you already forked the repository for this lesson?

- If NO:
1. Fork a copy of the master repository (i.e. ```swcarpentry/<lesson-name>```) ```gh-pages``` branch into your account. Select the ```gh-pages``` branch, then use the Fork button:

![GitHubFlowForNewbies-1.jpg - location of fork button](https://github.com/dtwrub/swc_github_flow/tree/patch-1/images/GitHubFlowForNewbies-1.jpg)
    
2. When the “Where should we fork this repository?” screen appears, click on your Git username (or other organizational account, if you are a member of any other organizations on GitHub).

3. The lesson will then be forked into your repository.

- If YES: 
1. If you just made the fork, go on to Making Your Edits (ADD LINK).
2. If you made the fork a while ago, make sure it is up to date with the latest changes in the swcarpentry lesson repository before starting to edit:

    1. Check the status of your repository - look if there is a message underneath the navigation bar, such as:

![GitHubFlowForNewbies-2.jpg - # commits behind](https://github.com/dtwrub/swc_github_flow/tree/patch-1/images/GitHubFlowForNewbies-2.jpg)

    If the message says that your branch is behind in commits, proceed to the next step. If it says that your branch is even, proceed to the Making Your Edits section.

    2. Click “Compare” (below the green “Clone or download” button in the graphic above.
    
    3. If you see a message saying there isn’t anything to compare, as:
    
    ADD IMAGE 3 - base switch
    
    That means that GitHub is comparing your changes with the master repository. In other words, everything that you have, the master has also. In order to make the opposite comparison - see what the master has that you do not - click on the “switching the base” link.
    
    4. You should now see something similar to:
    
    ADD IMAGE 4 - comparing changes, able to merge
    
    The base and head forks have now been switched, so the comparison is now between the changes in the master repository and yours.

    5. Click “Create pull request” - this is creating a pull request to you (for your repository) asking to pull changes from the master repository into your repository. Enter a title for the request and then click “Create pull request”:
    
    ADD MAGE 5 - open a pull request
    
    6. On the next screen click “View pull request” to view the pull request you just created for your repository.
    
    7. Towards the bottom of the screen, look for this message:
    
    ADD IMAGE 6 - merge pull request
    
    Click on “Merge pull request”, add any notes you want, then click “Confirm merge”.

    8. The status should now be “Merged”, and your repository will be up to date with all the changes from the remote repository.
    
##### Making Your Edits:

    
    
