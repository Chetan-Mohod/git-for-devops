Here's a `commands.md` file structured with topics and their related commands based on your input:

```markdown
# Git Commands for DevOps

## Directory Management
- `mkdir git-for-devops`  - Create a new directory named `git-for-devops`
- `cd git-for-devops`     - Change into the `git-for-devops` directory
- `ls -lrt`               - List directory contents in long format, sorted by time
- `clear`                 - Clear the terminal screen
- `pwd`                   - Print the current working directory

## File Management
- `vim hello-dosto.txt`   - Open (or create) `hello-dosto.txt` with Vim
- `rm hello-dosto.txt`    - Remove the file `hello-dosto.txt`
- `touch nibba.txt nibbi.txt` - Create `nibba.txt` and `nibbi.txt`
- `rm hello.txt`          - Remove the file `hello.txt`
- `vi hello.txt`          - Open (or create) `hello.txt` with Vim
- `ls -la`                - List all files, including hidden ones

## Git Initialization
- `git init`              - Initialize a new Git repository
- `git status`            - Check the status of the repository

## Staging and Committing Files
- `git add nibbi.txt`     - Stage `nibbi.txt` for commit
- `git add nibba.txt`     - Stage `nibba.txt` for commit
- `git rm --cached nibba.txt` - Unstage `nibba.txt`
- `git commit -m "adding 2 files"` - Commit staged changes with a message
- `git rm nibbi.txt`      - Remove `nibbi.txt` from the repository
- `git restore nibbi.txt` - Restore `nibbi.txt` to the working directory
- `git restore --staged nibbi.txt` - Unstage `nibbi.txt`

## User Configuration
- `git config --global user.name "Chetan-Mohod"` - Set global username
- `git config --global user.email "chetanmohod1998@gmail.com"` - Set global email

## Branching
- `git branch`            - List all branches
- `git checkout -b dev`   - Create and switch to a new branch `dev`
- `git checkout master`    - Switch back to the `master` branch

## Managing Branches and Files
- `touch nibbu.txt`       - Create `nibbu.txt`
- `git rm nibbu.txt`      - Remove `nibbu.txt` from the repository
- `git checkout dev`      - Switch to the `dev` branch
- `git checkout master`    - Switch back to the `master` branch
- `rm nibbu.txt`          - Remove `nibbu.txt` from the filesystem

## Logging and Status Checks
- `git log`               - Show the commit history
- `git log --oneline`     - Show the commit history in a condensed format
- `git status`            - Check the current status of the repository

## Cleanup
- `clear`                 - Clear the terminal screen

## Additional Commands
- `git commit`            - Commit changes (prompt for message)
- `git checkout`          - Switch to the last checked-out branch
```
