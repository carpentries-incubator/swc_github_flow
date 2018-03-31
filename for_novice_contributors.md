## Instructions for contributing with git and GitHub

##### Prerequisites and other options
-   Editing requires a GitHub account. You can set one up at <https://github.com>
-   If you don’t want to use Github, you can suggest changes by emailing a lesson maintainer
-   TODO add link to contact maintainers

Note: The GitHub webpage interface works well for making relatively small edits, like adding a link, fixing typos, or adding several lines of explanation. For more larger edits, the command line interface is recommended.

##### Contents
  -    Working from the GitHub webpage (graphical interface)
  -    Working from the

##### Glossary of terms
-   TODO
-   branch, gh-pages, master, origin, upstream, fork, remote

## Option 1 - Working from the GitHub webpage (graphical interface)

##### Getting Ready:

1.  Identify the url and repository name for the lesson you want to make changes for, eg <https://github.com/swcarpentry/git-novice>. The base branch in all the Carpentry lessons is called `gh-pages`.

2.  It’s not possible to for you to directly edit the version of the lesson in the Carpentry repository, so the overall idea of “GitHub Flow” is that you can submit edits by: 1) making your own copy of the lesson repository, 2) making a branch in your own copy, 3) making the changes on that dedicated branch, and then 4) sending your proposed changes back to the Carpentry version of the repository by creating a pull request.

3.  Have you already forked the repository for this lesson?

    If **NO**:

    a) Fork a copy of the base repository's  ```gh-pages``` branch into your account. Do this by selecting ```gh-pages``` on the dropdown option of branches on the left hand side of the repository's page, then clicking the 'Fork' button in the upper right:

    ![1_gh_pages_button](images/1_gh_pages_button.PNG)

      b) When the *“Where should we fork this repository?”* screen appears, click on your Git username (or other organizational account, if you are a member of any other organizations on GitHub).

      c) The lesson will then be forked into your repository.

    If **YES**:

    TODO: clean up indenting/numbering for this section

    a) If you just made the fork, go on to [Making Your Edits](TODO add link).

    b) If you made the fork a while ago, make sure it is up to date with the latest changes in the Carpentry lesson repository before starting to edit.

    -   Check the status of your repository - look if there is a message underneath the navigation bar, such as *"This branch is <#> commits behind ...*"

    ![repo_status](images/repo_status.PNG)

      -   If the message says that your branch is even, proceed to the [Making Your Edits](TODO add link) section.

      -   If it says that your branch is behind, proceed to the next step.

    -   Click *"Compare"* (below the green *"Clone or download"* button  on the right (shown above).

        -   If you see a message saying there isn’t anything to compare, such as -

     ![nothing_to_compare](images/nothing_to_compare.PNG)

          That means that GitHub is comparing your changes with the master repository. In other words, everything that you have, the master has also. In order to make the opposite comparison - to see what the master has that you do not - click on the *“switching the base”* link.

          You should now see something similar to:

         ![comparing_changes](images/comparing_changes.PNG)

         The base and head forks have now been switched, so the comparison is now between the changes in the master repository and yours.

         -   Click *“Create pull request”* - this is creating a pull request to you (for your repository) asking to pull changes from the master repository into your repository. Enter a title for the request and then click the green *"Create pull request"* button.

      ![open_a_pull_request](images\open_a_pull_request.PNG)

      -   On the next screen click *“View pull request”* to view the pull request you just created for your repository. Towards the bottom of the screen, look for this message:

      ![merge_pull_request](images\merge_pull_request.PNG)

      -   Click on *“Merge pull request”*, add any notes you want, then click *“Confirm merge”*.
      -   The status should now be *“Merged”*, and your repository will be up to date with all the changes from the remote repository! Congrats, you are ready to start making your edits!

##### Making your edits
1.Create a new branch in your fork of the master repository for each significant change you wish to make. Do this by clicking on the *'Branch'* dropdown, and entering a new branch name in the *“Find or create a branch…”* dialog

![create_branch](images\create_branch.PNG)

  Click the blue “create branch” button and this will create a copy of whatever branch you have selected in the drop-down (in this case, `gh-pages`) into a new branch named whatever you enter for the name.

2.Make any changes to any files in the branch you just created. Since you are making changes in a branch you just created, select *“Commit directly”* and then click *“Commit changes”*:

  ![commit_changes](images\commit_changes.PNG)

3.You’ll now see that the branch will be a commit ahead of the master - click on “Pull request” to open the Pull Request submission screen to submit those changes to the master repository for consideration:

![pull_request_button](images\pull_request_button.PNG)

4.Add a short explanation of your suggested changes, then press *“Submit Pull Request”* at the bottom of the page. It will be helpful if your description is more detailed than the commit message (eg you can explain why you changed something). People will be able to see the code you changed though, so you don’t have to repeat every single thing you changed.

Note that any additional changes you make on this branch later will also be added to this pull request.

5.Wait for feedback from the community on your Pull Request!

6.If you receive feedback, make the changes on GitHub and the pull request will update automatically.
