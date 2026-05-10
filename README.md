# 4.GITHUM_ASSIGNMENT_MUNNA
# Git Error Handling Operations

## Objective
Learn how to manage unfinished work and mistakes using Git stash, reset, and revert commands.


# Scenario
During development, temporary changes were made to `app.py`.  
The task demonstrates how to:

- Stash unfinished work
- Restore stashed changes
- Undo commits using reset
- Reverse commits using revert
- Verify commit history


# Step 1: Check Git Status

git status

Output:

On branch main
Changes not staged for commit:
        modified: app.py


# Step 2: Stash Changes Including Untracked Files

git stash -u

Output:

Saved working directory and index state WIP on main


# Step 3: Verify Working Tree

git status


Output:

nothing to commit, working tree clean


# Step 4: Check Stash List

git stash list


Output:

stash@{0}: WIP on main

# Step 5: Apply Stashed Changes

git stash apply

Output:
modified: app.py
```

---

# Step 6: Commit Restored Changes

git add .
git commit -m "Added new feature changes"

Commit ID:

b1cde09 Added new feature changes


# Step 7: Create Incorrect Commit

git add .
git commit -m "Added incorrect code"

Commit ID:

e39f619 Added incorrect code


# Step 8: Undo Last Commit Using Reset

git reset --soft HEAD~1

Explanation:

* Removes the latest commit
* Keeps changes staged

Verify:

git log --oneline

# Step 9: Create Corrected Commit

git add .
git commit -m "Fixed incorrect code"

Commit ID:

9b4baaf Fixed incorrect code

# Step 10: Undo Commit Using Revert

git revert HEAD

Output:

Revert "Fixed incorrect code"

Commit ID:

49c6fad Revert "Fixed incorrect code"


# Step 11: Verify Commit History

git log --oneline

Output:

49c6fad Revert "Fixed incorrect code"
9b4baaf Fixed incorrect code
b1cde09 Added new feature changes
e17abaf Dummy branch commit
9d96677 Added new feature logic
81b7987 added Good Morning Everyone
bbf00e5 Hello World
88b9d31 Initial commit: add app.py with basic Python code

<img width="748" height="624" alt="image" src="https://github.com/user-attachments/assets/ba37a05c-c419-40e3-8773-5be2e8f6e607" />
<img width="771" height="579" alt="image" src="https://github.com/user-attachments/assets/7f15d8f6-5c5e-4e66-a6c2-36e5c1c6bc80" />


# Conclusion

This activity demonstrated:

* Temporarily saving work using Git stash
* Restoring stashed work
* Undoing commits safely using reset
* Reversing commits using revert
* Tracking project history using git log

<img width="1361" height="714" alt="image" src="https://github.com/user-attachments/assets/f080a776-1437-457a-a974-d81ed3ceaf2a" />




