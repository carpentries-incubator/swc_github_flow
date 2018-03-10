## Instructions for contributing with Git and GitHub

#### Prerequisites and other options
- Editing requires a GitHub account. You can set one up at [https://github.com](https://github.com).
- If you don’t want to use GitHub, you can suggest changes by emailing a lesson maintainer

## Working from the GitHub webpage (graphical interface) 

#### Getting Ready:

1. Identify the url and repository name for the lesson you want to make changes for, eg [https://github.com/swcarpentry/git-novice](https://github.com/swcarpentry/git-novice). The main branch in all the Carpentry lessons is called gh-pages. 

2. It’s not possible to for you to directly edit the version of the lesson in the Carpentry repository, so the overall idea of “Github Flow” is that you can edit by making your own copy of the lesson repository, making a branch in your own copy, making the changes on that dedicated branch, and then sending your proposed changes back to the Carpentry version of the repository.

##### Have you already forked the repository for this lesson?

- If NO:
  1. Fork a copy of the master repository (i.e. ```swcarpentry/<lesson-name>```) ```gh-pages``` branch into your account. Select the ```gh-pages``` branch, then use the Fork button:

  ![alt text](swc_github_flow/images/GitHubFlowForNewbies-1.jpg "GitHubFlowForNewbies-1.jpg - location of fork button")
    
  2. When the “Where should we fork this repository?” screen appears, click on your Git username (or other organizational account, if you are a member of any other organizations on GitHub).

  3. The lesson will then be forked into your repository.

- If YES: 
  - If you just made the fork, go on to Making Your Edits (ADD LINK).
  - If you made the fork a while ago, make sure it is up to date with the latest changes in the swcarpentry lesson repository before starting to edit:

    1. Check the status of your repository - look if there is a message underneath the navigation bar, such as:

    ![alt text](swc_github_flow/images/GitHubFlowForNewbies-2.jpg "GitHubFlowForNewbies-2.jpg - # commits behind")

    If the message says that your branch is behind in commits, proceed to the next step. If it says that your branch is even, proceed to the Making Your Edits section.

    2. Click “Compare” (below the green “Clone or download” button in the graphic above.
    
    3. If you see a message saying there isn’t anything to compare, as:
    
    ![alt text](swc_github_flow/images/GitHubFlowForNewbies-3.jpg "GitHubFlowForNewbies-3.jpg - base switch")
    
    That means that GitHub is comparing your changes with the master repository. In other words, everything that you have, the master has also. In order to make the opposite comparison - see what the master has that you do not - click on the “switching the base” link.
    
    4. You should now see something similar to:
    ![alt text](swc_github_flow/images/GitHubFlowForNewbies-4.jpg "GitHubFlowForNewbies-4.jpg - compare changes")
    The base and head forks have now been switched, so the comparison is now between the changes in the master repository and yours.

    5. Click “Create pull request” - this is creating a pull request to you (for your repository) asking to pull changes from the master repository into your repository. Enter a title for the request and then click “Create pull request”:
    ![alt text](swc_github_flow/images/GitHubFlowForNewbies-5.jpg "GitHubFlowForNewbies-5.jpg - open a pull request")
    
    6. On the next screen click “View pull request” to view the pull request you just created for your repository.
    
    7. Towards the bottom of the screen, look for this message:
    ![alt text](swc_github_flow/images/GitHubFlowForNewbies-6.jpg "GitHubFlowForNewbies-6.jpg - merge pull request")
    Click on “Merge pull request”, add any notes you want, then click “Confirm merge”.

    8. The status should now be “Merged”, and your repository will be up to date with all the changes from the remote repository.
    
#### Making Your Edits:

1. Create a new branch in your fork of the master repository for each significant change you wish to make. Do this by clicking on the Branch **dropdown**, and entering a new branch name in the “Find or create a branch…” dialog:

![alt text](swc_github_flow/images/GitHubFlowForNewbies-7.jpg "GitHubFlowForNewbies-7.jpg - create branch")

Click the blue “create branch” button and this will create a copy of whatever branch you have selected in the drop-down (in this case, “gh-pages”) into a new branch named whatever you enter for the name.

2. Make any changes to any files in the branch you just created. Since you are making changes in a branch you just created, select “Commit directly” and then click “Commit changes”:

![alt text](swc_github_flow/images/GitHubFlowForNewbies-8.jpg "GitHubFlowForNewbies-8.jpg - commit changes")

3. You’ll now see that the branch will be a commit ahead of the master - click on “Pull request” to open the Pull Request submission screen to submit those changes to the master repository for consideration:

![alt text](swc_github_flow/images/GitHubFlowForNewbies-9.jpg "GitHubFlowForNewbies-9.jpg - pull request to update your repository")

4. Add a short explanation of your suggested changes, then press “Submit Pull Request” at the bottom of the page. It will be helpful if your description is more detailed than the commit message (eg you can explain why you changed something). People will be able to see the code you changed though, so you don’t have to repeat every single thing you changed.

* If you make more changes to the branch after making the pull request, those changes will automatically get merged into the existing pull request, as long as the pull request hasn't been closed.

5. Wait for feedback from the community on your Pull Request!

6. If you receive feedback, make the changes on GitHub and the pull request will update automatically.

## Working from the terminal (command line interface)

#### Getting Ready:

1. Identify the url and repository name for the lesson you want to make changes for, eg [https://github.com/swcarpentry/git-novice](https://github.com/swcarpentry/git-novice). The main branch in all the Carpentry lessons is called gh-pages. 

2. It’s not possible to for you to directly edit the version of the lesson in the Carpentry repository, so the overall idea of “Github Flow” is that you can edit by making your own copy of the lesson repository, making a branch in your own copy, making the changes on that dedicated branch, and then sending your proposed changes back to the Carpentry version of the repository.

##### Have you already forked the repository for this lesson?

- If NO:
  1. Fork a copy of the master repository (i.e. ```swcarpentry/<lesson-name>```) ```gh-pages``` branch into your account. Select the ```gh-pages``` branch, then use the Fork button:
  ![alt text](swc_github_flow/images/GitHubFlowForNewbies-1.jpg "GitHubFlowForNewbies-1.jpg - location of fork button")

  2. When the “Where should we fork this repository?” screen appears, click on your Git username (or other organizational account, if you are a member of any other organizations on GitHub).

  3. Once the lesson has been forked to your repository, click the green “Clone or download” button on the right side of the screen, and copy the url shown:
