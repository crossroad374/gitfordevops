# 📘 Git and Bash Commands with Use Cases

A comprehensive guide to some of the essential Git and bash commands used in DevOps. Each command is followed by a brief explanation of its use case, helping you understand its purpose.

---

## 🔹 `git`
- **Use case**: Initializes Git or interacts with a Git repository. Used for version control, managing repositories, commits, branches, etc.

## 🔹 `clear`
- **Use case**: Clears the terminal screen to remove clutter from previous commands.

## 🔹 `pwd`
- **Use case**: Displays the current working directory's path. Helps confirm your location in the file system.

## 🔹 `mkdir gitfordevops`
- **Use case**: Creates a directory named `gitfordevops` to organize project files.

## 🔹 `cd gitfordevops/`
- **Use case**: Navigates into the `gitfordevops/` directory.

## 🔹 `git init`
- **Use case**: Initializes a new, empty Git repository in the current directory for version control.

## 🔹 `vim hello.txt`
- **Use case**: Opens or creates the `hello.txt` file in the Vim editor for editing.

## 🔹 `ls -la`
- **Use case**: Lists all files and directories (including hidden ones) in long format, showing details like permissions, ownership, and size.

## 🔹 `git status`
- **Use case**: Shows the current status of the working directory and staging area, highlighting any changes made.

## 🔹 `rm hello.txt`
- **Use case**: Deletes the `hello.txt` file from the current directory.

## 🔹 `touch nibba.txt nibbi.txt`
- **Use case**: Creates two empty files, `nibba.txt` and `nibbi.txt`.

## 🔹 `git add *`
- **Use case**: Stages all changes (new, modified, and deleted files) for the next commit.

## 🔹 `git rm --cached nibba.txt`
- **Use case**: Unstages `nibba.txt` from the staging area without deleting it.

## 🔹 `git add nibba.txt`
- **Use case**: Stages the `nibba.txt` file for the next commit.

## 🔹 `git commit -m "adding nibba and nibbi"`
- **Use case**: Commits the staged changes with the message "adding nibba and nibbi."

## 🔹 `rm nibbi.txt`
- **Use case**: Deletes the `nibbi.txt` file from the directory.

## 🔹 `git restore nibbi.txt`
- **Use case**: Restores `nibbi.txt` to its last committed state.

## 🔹 `git config --global user.name "crossroad374"`
- **Use case**: Sets the global Git username to "crossroad374."

## 🔹 `git config --global user.email "crossroad374@gmail.com"`
- **Use case**: Sets the global Git email to "crossroad374@gmail.com."

## 🔹 `git commit -m "modified nibbi.txt"`
- **Use case**: Commits changes to the `nibbi.txt` file with the message "modified nibbi.txt."

## 🔹 `git log`
- **Use case**: Displays the commit history of the current repository.

## 🔹 `git checkout -b dev`
- **Use case**: Creates a new branch called `dev` and switches to it.

## 🔹 `ls -lrth`
- **Use case**: Lists files sorted by modification time (most recent first) with human-readable sizes.

## 🔹 `touch nibbu.txt`
- **Use case**: Creates an empty file named `nibbu.txt`.

## 🔹 `git commit -m "added nibbu in dev"`
- **Use case**: Commits the `nibbu.txt` file in the `dev` branch with the message "added nibbu in dev."

## 🔹 `git checkout master`
- **Use case**: Switches back to the `master` branch.

## 🔹 `git log --oneline`
- **Use case**: Displays the commit history in a compact, one-line-per-commit format.


---

This document serves as a quick reference for frequently used Git and Bash commands. It helps new users and developers understand the purpose and functionality of each command.
