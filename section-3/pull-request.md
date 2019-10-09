## What is a Pull Request
Pull requests are proposed changes to a repository submitted by a user and accepted or rejected by a repository's collaborators. Like issues, pull requests each have their own discussion forum.


## Creating the pull request

1.  On GitHub, navigate to the main page of the repository.
    
2.  In the "Branch" menu, choose the branch that contains your commits.
    
    <img src="/section-3/branch-dropdown.png" width="215" height="163"/>
    
3.  To the right of the Branch menu, click  **New pull request**.
    
    ![Pull Request button](/section-3/images/new-pull-request.png)
    
4.  Use the  _base_  branch dropdown menu to select the branch you'd like to merge your changes into, then use the  _compare_  branch drop-down menu to choose the topic branch you made your changes in.
    
    ![Drop-down menus for choosing the base and compare branches](/section-3/images/compare-branch.png)
    
5.  Type a title and description for your pull request.
    
6.  To create a pull request that is ready for review, click  **Create Pull Request**. To create a draft pull request, use the drop-down and select  **Create Draft Pull Request**, then click  **Draft Pull Request**. 
    
    ![Create pull request button](/section-3/images/pull-request-send.png)

## Merging a pull request

1.  Under your repository name, click  **Pull requests**.
    
    ![Issues and pull requests tab selection](/section-3/images/pull-requests.png)
    
2.  In the "Pull Requests" list, click the pull request you'd like to merge.
    
3.  Depending on the merge options enabled for your repository, you can:
    
    -   Merge all of the commits into the base branch  by clicking  **Merge pull request**. If the  **Merge pull request**  option is not shown, then click the merge drop down menu and select  **Create a merge commit**.
        
        ![merge-pull-request-button](/section-3/images/pull-request-merge.png)
        
    -   Squash the commits into one commit by clicking the merge drop down menu, selecting  **Squash and merge**  and then clicking the  **Squash and merge**  button.
        
    -   Rebase the commits individually onto the base branch by clicking the merge drop down menu, selecting  **Rebase and merge**  and then clicking the  **Rebase and merge**  button.
    
    **Note:**  Rebase and merge will always update the committer information and create new commit SHAs.
    
4.  If prompted, type a commit message, or accept the default message.
    
5.  Below the commit message fields, click the email address drop-down menu and choose a Git author email address. Only verified email addresses appear in this drop-down menu. If you enabled email address privacy, then  `<username>@users.noreply.github.com`  is the default commit author email address.
    
6.  Click  **Confirm merge**,  **Confirm squash and merge**, or  **Confirm rebase and merge**.
    
7.  Optionally,  delete the branch. This keeps the list of branches in your repository tidy.

