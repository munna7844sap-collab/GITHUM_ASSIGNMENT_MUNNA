# 3.GITHUM_ASSIGNMENT_MUNNA
# Git Branching & Feature Development

## Objective
Work with Git branches and manage feature development separately from the main branch.


# Project Details

Project Name: GITHUBASSIGNMENT

Main File: `app.py`


# Tasks Performed

## 1. Checked Existing Branch

git branch

Output:

* main


## 2. Created a New Branch


git branch feature-update


## 3. Switched to Feature Branch

git checkout feature-update


Output:

Switched to branch 'feature-update'


## 4. Verified Current Branch

git branch

Output:

* feature-update
  main

## 5. Modified `app.py`

Added new feature logic inside the application.

Example:

print("Welcome to GitHub Assignment")

def new_feature():
    print("New Feature Added Successfully")

new_feature()

<img width="837" height="260" alt="image" src="https://github.com/user-attachments/assets/b4b28032-85eb-4276-893a-70edc26a9f5b" />


## 6. Checked Git Status


git status

Output showed modified file:

modified: app.py



## 7. Staged Changes

git add .



## 8. Committed Changes

git commit -m "Added new feature logic"


Output:

[feature-update 9d96677] Added new feature logic


## 9. Switched Back to Main Branch


git checkout main


## 10. Merged Feature Branch into Main

git merge feature-update

Output:

Updating 81b7987..9d96677
Fast-forward


## 11. Verified Commit History


git log --oneline


Output:

9d96677 Added new feature logic
81b7987 added Good Morning Everyone
bbf00e5 Hello World
88b9d31 Initial commit



## 12. Deleted Feature Branch Safely

git branch -d feature-update

Output:


Deleted branch feature-update


# Dummy Branch Practice

## 13. Created Dummy Branch


git branch dummy-branch


## 14. Added Dummy Commit

git add .
git commit -m "Dummy branch commit"



## 15. Deleted Dummy Branch

git branch -d dummy-branch

Output:

Deleted branch dummy-branch

<img width="730" height="623" alt="image" src="https://github.com/user-attachments/assets/e84a24b3-8b48-45c0-a92d-3bf41c620100" />

<img width="992" height="496" alt="image" src="https://github.com/user-attachments/assets/939dea46-bfe8-4010-ae57-899be1a99a24" />



# Conclusion

Successfully completed Git branching and feature development workflow using:

- Branch creation
- Branch switching
- Feature development
- Commit management
- Branch merging
- Branch deletion
- Git history verification

<img width="1331" height="671" alt="image" src="https://github.com/user-attachments/assets/bfe33318-bfa0-4476-9f38-239e3e40bc9e" />

