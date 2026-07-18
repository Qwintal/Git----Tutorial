# Git -- Tutorial
Learn basic Git commands.


``` git init ``` --> Gits starts tracking that folder, making it a repository.

``` git status ``` --> check which files are being tracked.

``` git add ``` --> pushes files into staging area.

``` git commit -m "hi" ``` --> This commits the file that are in the staging area. 

``` git log ``` --> To check all check points, commit history. 

``` git long --oneline ``` --> See all commits in concise form.

``` git add . ``` --> Push all files into stagin area.

``` git restore --staged . ``` --> Remove back from staging area. 

``` .gitignore ``` --> Tells git to ignore this file in the repo, do not track changes inside file. 

``` .gitkeep ``` --> Tells git to track this folder ( Helps to track empty folder, which git ignores ).

### What is branching??
#### --> Without effecting the main code, you can make changes and later you can either discard or add in main code. 

``` git branch name ``` --> New branch 

``` git branch ``` --> See all branches 

``` git switch branch_name ``` --> To switch to different branches.  

``` git merge branch_name ``` --> Merges the branch_name to main branch.  ( Esc :wq )

``` git branch -d branch_name ``` --> Delete specific branch.

``` git swtich -c branch_name  ``` --> Shortcut to create and new branch and switch to it. 

#### Merge conficts happens when same file has been changed in different branches and push to main, then auto merge fails. \n Manual intervention is required to do file commit.

