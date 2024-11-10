# I am trying to learn git
I just started using git in my life :).

## The commands that should know to use git
- `git init` (initial git repository in .git).
- `git add` (take snapshot).
- `git commit` (to store content permanetly in your repository).
- `git status` (summary of the situation).
- `git log` (history of changes).
- `git branch` (show the branches and can put).
- `git merge` (to merge branches togheder).
- `git fetch` (what is the changes of repository that you are working with another before you pull it and merge it).
- `git pull` (to get a repository to your local things) `git pull = git fetch + git merge`.
- `git show` (show details about of commit).
- `git tag` (put tag in your commit).
- `git reset` (reset your current branch and working directory to some a HEAD before).
- `git revert` (to undo changes that you have pushed).
- `git grep` (to search string in any version of the project. if leave version in commit, it will search for all the files).
- `git cat-file commit hash` (see commit details with hash. also you can search specificly for tree of that with ```git ls-tree``` and see the contens of file data with `git cat-file blob`).
- `git diff` (compare index file with HEAD).
- `git rebase` (to apply changes from one branch to another branch, or you can use `git rebase -i ` to apply some last commits).
- `git submodules add (repo's address)` (to use a repository for a part of your repository).
- `git commit --amend` (to chandge the last commit ).
- `git cherry-pick` (to apply specific commit from one branch onto another branch).
- `git stash` (to temporary save changes that you don't want to commit. for apply that use `git stash apply`).
- `git clean` (to remove untracked files and directories).

### Upgrade
If there is a mistake or you can add more items, do me a favor and
upgrade the list.
thank you.
