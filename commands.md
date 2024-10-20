
# Git Commands

## 1. Basic Setup
- **Initialize a new Git repository**
  ```bash
  git init
  ```
- **Configure user details**
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"
  ```

## 2. Working with Files
- **Create new files**
  ```bash
  touch filename.txt
  vim filename.txt
  ```
- **Add files to the staging area**
  ```bash
  git add filename.txt
  git add .
  ```
- **Check the status of your working directory and staging area**
  ```bash
  git status
  ```

## 3. Committing Changes
- **Commit changes to the repository**
  ```bash
  git commit -m "commit message"
  ```

## 4. Viewing History
- **Show commit history**
  ```bash
  git log
  ```
- **Show commit history in one line**
  ```bash
  git log --oneline
  ```

## 5. Working with Branches
- **Create a new branch**
  ```bash
  git checkout -b branch-name
  ```
- **Switch between branches**
  ```bash
  git checkout branch-name
  git switch branch-name
  ```
- **List all branches**
  ```bash
  git branch
  ```

## 6. Removing Files
- **Remove files from the working directory**
  ```bash
  rm filename.txt
  ```
- **Remove files from the staging area (but keep in working directory)**
  ```bash
  git rm --cached filename.txt
  ```

## 7. Restoring Changes
- **Restore a file to its previous state**
  ```bash
  git restore filename.txt
  ```

## 8. Branch Operations
- **Merge changes from one branch to another**
  ```bash
  git merge branch-name
  ```
- **Delete a branch**
  ```bash
  git branch -d branch-name
  ```

## 9. Creating a Branch from Another Branch
- **Create a new branch based on another branch**
  ```bash
  git checkout -b new-branch existing-branch
  ```
## 1. File Operations
- **Edit a file using the Vim editor:**  
  `vi test.txt`
- **List files in the current directory:**  
  `ls`

## 2. Staging and Committing Changes
- **Check the status of your working directory and staging area:**  
  `git status`
- **Stage a specific file for commit:**  
  `git add test.txt`
- **Commit the staged changes with a descriptive message:**  
  `git commit -m "test added in main"`

## 3. Pushing and Pulling Changes
- **Push local changes to the remote repository:**  
  `git push`
- **Pull updates from the remote repository to your local repository:**  
  `git pull`

## 4. Branch Operations
- **Delete a branch locally:**  
  `git branch -d staging`
- **Force delete a branch locally (if it hasn't been merged):**  
  `git branch -D staging`

## 5. Merging and Rebasing
- **Set Git to only allow fast-forward merges when pulling:**  
  `git config pull.ff only`
- **Merge branches without fast-forwarding (create a merge commit):**  
  `git merge --no-ff`
- **Rebase your current branch onto another branch:**  
  `git rebase`
