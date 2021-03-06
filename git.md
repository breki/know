## Common commands

- `git add <file>`: add the file changes to the commit queue
- `git add --all`: adds all the changed files (removed, too) to the commit queue
- `git branch`: displays a list of checked out branches and which is the active branch
- `git branch -d <branch>`: deletes a local branch
- `git checkout -b <branch>`: creates a new branch and switches to it
- `git checkout <branch>`: switches to a different branch
- `git checkout <file name>`: reverts the file to HEAD, overwriting your change
- `git checkout -- *`: discard all changes in the working directory
- `git commit -m "<message>"`: commits the changes, using the specified commit message
- `git config --list --show-origin`: list all Git configuration settings and to which configuration they belong (global, system, local, worktree)
- `git diff >a.patch`: saves the current changes to a patch file called `a.patch`
- `git merge <branch>`: merges changes from a different branch
- `git pull "origin" <branch>`: pulls the changes to the branch from the remote repo
- `git push "origin" <branch>`: pushes the branch changes to the remote repo
- `git reset --hard origin/<branch_name>`: resets the branch, undoing all local changes. The `--hard` option changes all the files in your working tree to match the files in `origin/branch`
- `git rm <file name>`: removes the file
- `git status`: displays the working tree status

## Configuring git

### Associating Notepad++ with Git
```
git config --global core.editor "'C:/Program Files/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"
```
