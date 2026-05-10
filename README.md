# 2.GITHUM_ASSIGNMENT_MUNNA
# Git Assignment 2 – Working with Changes & History

## Objective

Track code changes and manage commit history using Git commands.


# Project Path

C:\Users\Administrator\OneDrive\Desktop\GITHUBASSIGNMENT


# Step 1: Check Git Status

Command:

git status

Output:

On branch main
Changes not staged for commit:
        modified:   app.py

Untracked files:
        GITASSIG2


# Step 2: Stage All Changes

Command:

git add .


Explanation:
- Adds all modified and new files to staging area


# Step 3: First Commit

Command:

git commit -m "Hello World"


Output:

[main bbf00e5] Hello World
 2 files changed, 9 insertions(+), 1 deletion(-)
 create mode 100644 GITASSIG2


# Step 4: Make Another Change

Modified `app.py` again by adding:


print("Good Morning Everyone")


# Step 5: Stage Updated Changes

Command:

git add .



# Step 6: Second Commit

Command:

git commit -m "added Good Morning Everyone"

Output:

[main 81b7987] added Good Morning Everyone
 1 file changed, 2 insertions(+), 1 deletion(-)


# Step 7: View Full Commit History

Command:

git log


Output:

commit 81b79878b3f9e4fc63e5f95acf4a762cd793ffff
Author: munna7844sap-collab <munna7844sap@gmail.com>

    added Good Morning Everyone

commit bbf00e5f628d600b3eed9f61af91e334ce0b7cf1

    Hello World



# Step 8: View Compact One-Line History

Command:

git log --oneline


Output:

81b7987 added Good Morning Everyone
bbf00e5 Hello World
88b9d31 Initial commit: add app.py with basic Python code

Explanation:
- Displays short commit history in one line format




# Conclusion

Successfully:
- Modified project files
- Checked file changes
- Staged changes
- Created multiple commits
- Viewed detailed and compact commit history

<img width="776" height="618" alt="image" src="https://github.com/user-attachments/assets/f2d8aaa2-475b-4338-8c82-5844c1548b4c" />

<img width="569" height="102" alt="image" src="https://github.com/user-attachments/assets/e4ffe105-cf95-49f9-b12f-f3558f8662f3" />

<img width="1365" height="668" alt="image" src="https://github.com/user-attachments/assets/10e5b728-8cb5-4874-ab3a-a4501069c5df" />


