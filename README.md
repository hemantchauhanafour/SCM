# SCM (Source Code Management)
## Difference between Git Pull and Git Fetch

| Git Fetch | Git Pull |
| --- | --- |
| Gives the information of a new change from a remote repository without merging into the current branch | Brings the copy of all the changes from a remote repository and merges them into the current branch |
| Repository data is updated in the .git directory | The local repository is updated directly |
| Review of commits and changes can be done | Updates the changes to the local repository immediately. |
| No possibility of merge conflicts. | Merge conflicts are possible if the remote and the local repositories have done changes at the same place. |
| Command for Git fetch is git fetch \<remote> | Command for Git Pull is git pull \<remote> \<branch> |
| Git fetch basically imports the commits to local branches so as to keep up-to-date that what everybody is working on. | Git Pull basically brings the local branch up-to-date with the remote copy that will also updates the other remote tracking branches. |
| | |


added blank lines