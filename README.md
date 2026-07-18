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

#### Merge conficts happens when same file has been changed in different branches and push to main, then auto merge fails. Manual intervention is required to do final commit.

#### Stashing --> To temporary store changes without pushing into main branch.

``` git stash ``` --> Save changes in stash.

``` git stash list ``` --> List of saves in stash.

```  git stash pop ``` --> Retreive all chagnes from stash to working tree, stash will be empty ( if new terminal opens press q to return back )

``` git stash apply ``` --> Push all changes in stash to main branch but also keep them in stash. 

``` git tag -a first -m 'first" ``` --> Annotated tag ( has more details about commit ).

``` git tag second ``` --> Light weight tag.

``` git tag ``` --> See all tags.

``` git log --oneline -4 ``` --> Latest 4 commits

#### Rebase
git rebase is a command used to integrate changes from one branch into another by moving or "replaying" your sequence of commits on top of a new base commit. Unlike git merge which combines branches by creating a new, separate "merge commit," rebasing completely rewrites your branch's commit history to make it perfectly linear.

``` git rebase main ``` --> Rebase feature branch into main.

``` git clone ... ``` --> Copy repo.

``` git push ``` --> Push into github. 

``` git pull ``` --> Pulls all changes in.

#### A fork means taking a copy of existing repository to develop it independently.

