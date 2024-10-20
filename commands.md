# Git Commands

## 1. Basic Setup
1. **Initialize a new Git repository**  
   `git init`

2. **Configure user details**  
   `git config --global user.name "Your Name"`  
   `git config --global user.email "your.email@example.com"`

## 2. Working with Files
3. **Create new files**  
   `touch filename.txt`  
   `vim filename.txt`

4. **Add files to the staging area**  
   `git add filename.txt`  
   `git add .`

5. **Check the status of your working directory and staging area**  
   `git status`

## 3. Committing Changes
6. **Commit changes to the repository**  
   `git commit -m "commit message"`

## 4. Viewing History
7. **Show commit history**  
   `git log`

8. **Show commit history in one line**  
   `git log --oneline`

## 5. Working with Branches
9. **Create a new branch**  
   `git checkout -b branch-name`

10. **Switch between branches**  
    `git checkout branch-name`  
    `git switch branch-name`

11. **List all branches**  
    `git branch`

## 6. Removing Files
12. **Remove files from the working directory**  
    `rm filename.txt`

13. **Remove files from the staging area (but keep in working directory)**  
    `git rm --cached filename.txt`

## 7. Restoring Changes
14. **Restore a file to its previous state**  
    `git restore filename.txt`

## 8. Branch Operations
15. **Merge changes from one branch to another**  
    `git merge branch-name`

16. **Delete a branch**  
    `git branch -d branch-name`

## 9. Creating a Branch from Another Branch
17. **Create a new branch based on another branch**  
    `git checkout -b new-branch existing-branch`

## 10. File Operations
18. **Edit a file using the Vim editor**  
    `vi test.txt`

19. **List files in the current directory**  
    `ls`

## 11. Staging and Committing Changes
20. **Check the status of your working directory and staging area**  
    `git status`

21. **Stage a specific file for commit**  
    `git add test.txt`

22. **Commit the staged changes with a descriptive message**  
    `git commit -m "test added in main"`

## 12. Pushing and Pulling Changes
23. **Push local changes to the remote repository**  
    `git push`

24. **Pull updates from the remote repository to your local repository**  
    `git pull`

## 13. Advanced Branch Operations
25. **Delete a branch locally**  
    `git branch -d staging`

26. **Force delete a branch locally (if it hasn't been merged)**  
    `git branch -D staging`

## 14. Merging and Rebasing
27. **Set Git to only allow fast-forward merges when pulling**  
    `git config pull.ff only`

28. **Merge branches without fast-forwarding (create a merge commit)**  
    `git merge --no-ff`

29. **Rebase your current branch onto another branch**  
    `git rebase`

