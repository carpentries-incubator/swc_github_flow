### Instructions for contributing with git and GitHub

##### Prerequisites and other options
-   Editing requires a GitHub account. You can set one up at <https://github.com>
-   If you don’t want to use Github, you can suggest changes by emailing a lesson maintainer
-   TODO add link to contact maintainers

Note: The GitHub webpage interface works well for making relatively small edits, like adding a link, fixing typos, or adding several lines of explanation. For more larger edits, the command line interface is recommended.

##### Glossary of terms
-   TODO
-   branch, gh-pages, master, origin, upstream, fork, remote

### Working from the GitHub webpage (graphical interface)

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

    a) If you just made the fork, go on to [Making Your Edits](TODO add link).

    b) If you made the fork a while ago, make sure it is up to date with the latest changes in the Carpentry lesson repository before starting to edit.

    -   Check the status of your repository - look if there is a message underneath the navigation bar, such as `This branch is <#> commits behind ...'`:

    ![repo_status](images/repo_status.PNG)
