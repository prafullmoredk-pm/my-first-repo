Git & GitHub Mastery Summary
1. Core Concepts (The Mental Model)

Git: A local version control system (your personal "Time Machine").

GitHub: A cloud platform to host and share your Git repositories.

Commit: A permanent snapshot of your files at a specific moment.

HEAD: A pointer showing where you currently are in the project history.

Main: Your primary, official timeline (branch).

2. Essential Commands

Command	What it does
git init	Turns a folder into a Git repository.
git status	Shows what files are changed, staged, or untracked.
git add <file>	Moves changes to the "Staging Area" (the shopping cart).
git commit -m "msg"	Saves the staged changes permanently with a message.
git log --oneline	Shows a simplified history of your saves.
git branch <name>	Creates a parallel universe to test new ideas.
git checkout <name>	Swaps between your different branches.
git merge <name>	Combines work from a side branch into your current one.
3. Remote Syncing (The Cloud)

git push: Sends your local saves up to GitHub.

git pull: Grabs the latest changes from GitHub and updates your Mac.

PAT (Token): Your secret "digital key" used instead of a password to push code.

The Professional Daily Workflow
Follow this "Circle of Life" for every coding session to avoid errors:

Sync: git pull (Start by getting any changes made by others).

Branch: git checkout -b feature-name (Never work on main directly).

Code: Make your changes in your editor.

Stage: git add . (Gather all your changes).

Commit: git commit -m "Explain what you did" (Save your work).

Merge: git checkout main → git merge feature-name (Bring it home).

Push: git push (Upload everything to the cloud).