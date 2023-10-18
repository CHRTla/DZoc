## Instructions on how to work with Git

# Main commands
Use the folloing commands to start your work with Git
+ Use ___git init___ to initialize the repository
+ Use ___git add___ to start tracking your file and remember the changes
+ Use ___git status___ to see the state of your current working directory
+ Use ___git commit___ to save (commit) changes to your file
+ Use ___git reset___ to undo the commit
+ Use ___git log___ to see the history of all changes done to your currnt working directory
+ Use ___git checkout [version-code]>___ to go back to the previous commit (See also "working with branches")

# Working with branches
A branch is an isolated development environment within a single repository.
- Using ___git branch___ shows you all existing branches, as well as which branch you are currently on
    - Adding a name to the command (i.e. ___git branch [name]___) creates a new branch
- Use ___git checkout [branch-name]___ to switch between branches
- Use ___git merge [branch-name]___ to merge the current branch with a different one
    - If merging branches contain conflicting information, conflicts may occur.
- Use ___git branch -m [branch-new-name]___ to rename the current branch
- Use ___git branch -d [branch-name]___ to delete a branch

# Working with repositories