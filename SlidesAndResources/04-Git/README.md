# GIT 

[Git Cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)

[Common Git Commands Walkthrough](./common_git_commands.md)

## Helpful Git terminal commands 
### Branches
* ```git checkout -b new_branch```
    - creates a new branch called new_branch
* ```git branch -D new_branch```
    - deletes a branch that has a name of new_branch
* ```git checkout branch_name```
    - checks out a branch called branch_name where all local changes will apply to this branch
* ```git push origin new_branch```
    - adds a new branch called new_branch to the remote origin 
    - aka will now have the new_branch in Github as well as locally

### Remotes
* ```git remote add origin https://some/origin/url```
    - adds a new remote origin url
    - any changes pushed up will go to this url
* ```git remote rm destination``
    - removes references to the remote called destination
* ```git remote -v```
    - prints out the url that the remote is tied to
