## GIT commands to synchronize changes

`git pull`:
 is a combined action that involves two operations: **git fetch** and **git merge**. When you execute **git pull**, Git fetches changes from the remote repository (using the **git fetch** command) and then automatically merges those changes with the current working branch (using the **git merge** command).

`git fetch`:
 is used to retrieve all changes from a remote repository but does not merge them with the current working branch. This means that changes are fetched into your local repository, but you can decide when and how to merge them with your current branch.

 Using **git fetch** is safer in situations where you want control over the exact moment of merging changes and want to avoid automatic merging
