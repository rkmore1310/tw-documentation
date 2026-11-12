# Git – Distributed Version Control System

## What is Git?
Git is a distributed version control system that runs locally on your computer to track changes in project files over time[cite: 8, 9]. It records project snapshots as a sequence of commits so you can inspect history, recover earlier versions, and work safely on new features[cite: 3, 11, 49].

## Key Concepts Learned in Class
- **Three Main Areas:**
  1. **Working Directory:** Where you create and edit files[cite: 18].
  2. **Staging Area:** Where you select changes for the next snapshot using `git add`[cite: 18].
  3. **Local Repository:** Where committed history is permanently stored using `git commit`[cite: 18].
- **Core Commands:**
  - `git init` – Initializes a new local Git repository[cite: 17].
  - `git status` – Shows untracked, modified, and staged files[cite: 21].
  - `git add <file>` / `git add .` – Adds changes to the staging area[cite: 22, 23].
  - `git commit -m "message"` – Saves staged changes with a clear message[cite: 24].
  - `git log --oneline` – Displays a compact list of past commits[cite: 26].
  - `git diff` – Compares changes between file versions[cite: 27].
- **Branching & Merging:** Using `git switch -c <branch>` to isolate new work and `git merge` to combine changes back into `main`[cite: 52, 53].
- **Undoing Changes:** Using `git restore` to discard unstaged edits and `git revert` to safely undo a commit without erasing history[cite: 32, 33].

## Why It Is Useful
It prevents accidental file loss, replaces messy filenames like `project_final_latest.py`, and works offline on your local machine[cite: 4, 5, 9].