# Git and Github labs

10.1
Lab 1: Make Your Own Repo
• Create a folder, run git init.
• Make readme.md, write “Hello, world!”, stage (git add readme.md), commit (git commit
-m "First file").
• Change it, commit again, check history (git log). Output: See your two snapshots.
10.2
Lab 2: Time Travel with History
• Edit readme.md, save a few times.
• Look at changes (git diff) before staging.
• Undo with git restore readme.md. Output: File goes back to last save.
10.3
Lab 3: Try New Ideas with Branches
• Make a branch (git checkout -b fun-feature).
• Add “I’m awesome!” to readme.md, commit.
• Switch to main, add “I’m cool!” instead, commit.
• Mix them (git merge fun-feature), ﬁx any clashes. Output: Both messages in readme.md.

10.4
Lab 4: Share with GitHub
• Make a new GitHub repo (no ﬁles).
• Link it (git remote add origin <url>), send (git push -u origin main).
• Edit readme.md on GitHub, get it locally (git pull). Output: Your computer has the
online changes.
10.5
Lab 5: Team Up with Friends
• Fork a repo, copy it (git clone <your-fork-url>).
• Make a branch (git checkout -b fix-spelling), edit, send (git push origin fix-spelling).
• Ask for a Pull Request on GitHub. Output: Friends see your changes.
10.6
Lab 6: Fix a Fight (Conflicts)
• In two branches, change the same line in readme.md.
• Try to merge, ﬁx the clash by editing, save. Output: File has both changes.
