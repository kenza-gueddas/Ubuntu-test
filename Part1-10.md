# Git exo — my answers

## Part 1: Setup & config

- Git version: `2.52.0`

- Config commands used:

  - `git config --global user.name "Kenza Gueddas"`
  - `git config --global user.email "kenzagueddas2006@gmail.com"`

---

## Part 2: Create Your First Repository

Commands used:

- `mkdir ubuntu-test`
- `cd ubuntu-test`
- `git clone https://github.com/kenza-gueddas/Ubuntu-test.git`

---

## Part 3: First Commit

Command used to check the state of the repository:

- `git status`

Command used to stage the README file:

- `git add README.md`

Command used to commit the change:

- `git commit -m "Added first line in README"`

Command used to see the commit history:

- `git log`

---

## Part 4: Make Changes

After editing the file `README.md`, running `git status` showed that the file was modified but not yet staged.

This means Git detected the change, but the modification will only be included in a commit once the file is added to the staging area.

---

## Part 5: Exploration

- `git diff`  
Shows the differences between the working directory and the last commit.

- `git log --oneline`  
Displays a simplified version of the commit history with one commit per line.

---

## Part 6: Working with Branches

Command to list all branches:

- `git branch`

Command to create a new branch:

- `git branch feature-script`

Command to switch branch:

- `git switch feature-script`

Command to create and switch branch at the same time:

- `git switch -c dev`

Command to verify the current branch:

- `git status`
- `git branch`

---

## Part 7: Working with a Script

The repository contains a bash script called `test.sh`.

Scripts can be tracked by Git like any other file.  
If modifications are made to the script, they can be staged and committed.

---

## Part 8: Merge Branches

Before merging, changes made in a branch are not visible in the `main` branch.

After merging the branch into `main`, the files and commits from that branch become part of the main project history.

---

## Part 9: Push to GitHub

Command used to push commits to GitHub:

- `git push`

After pushing, the commits appear on the repository page:

https://github.com/kenza-gueddas/Ubuntu-test

---

## Part 10: Clone a Repository

Command used to clone a repository:

- `git clone https://github.com/kenza-gueddas/Ubuntu-test.git`

After cloning, the repository can be accessed locally and the files can be checked using:

- `ls`
