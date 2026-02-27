# My Git Lab: The Daily Grind 👍

I built a small coffee shop website to understand how Git works while actually coding. Instead of only reading about it, I followed these steps to practice tracking my work.

# Step 1: Getting Started
What I did:
I created a new folder for my project and ran git init to tell Git to start tracking it. Then I configured my name and email so Git could record who made the changes. I created my first file, index.html, and saved it using git add and git commit.
What I learned:
Git follows a simple process: make a change, stage it, and commit it.

# Step 2: Checking My Work
What I did:
I created two more files: menu.txt and styles.css. I staged them, but then edited the CSS file again before committing. I used git diff to see my unstaged changes and git diff --staged to review what was already prepared for commit.
What I learned:
I can stage a file and continue editing it. Git keeps track of both the staged and unstaged versions.

# Step 3: Fixing Mistakes
What I did:
I accidentally staged a file containing private keys. I used git restore --staged to unstage it. Then I created a .gitignore file so Git would ignore that file entirely. Later, I accidentally deleted my menu text, but I used git restore to recover it.
What I learned:
Mistakes are not permanent. Git allows me to undo changes and recover lost work.

# Step 4: Trying New Ideas (Branching)
What I did:
I wanted to add a rewards page without affecting the main site. I created a branch called feat-loyalty and worked there. When I switched back to the main branch, the rewards file was not present because it only existed on the feature branch.
What I learned:
Branches act like separate timelines. I can develop features independently without impacting the main project.

# Step 5: Putting It All Together
What I did:
I merged the rewards feature into the main branch. Then I intentionally edited the same line of code differently in two places to observe the outcome. Git reported a merge conflict. I manually resolved it by choosing the correct version and committing the fix.
What I learned:
Git handles most merges automatically, but when the same line is changed in different ways, I must decide which version to keep.

# Step 6: Handling Emergencies
What I did:
While working on unfinished CSS changes, I needed to fix a bug quickly. I used git stash to temporarily store my incomplete work and return the project to a clean state. I also used git worktree to create a second working copy of the repository in another folder, allowing me to work on two tasks simultaneously. After finishing, I restored my stashed changes.
What I learned:
Git allows me to switch tasks efficiently without committing unfinished work.

# Step 7: Traveling Back in Time
What I did:
I reviewed my commit history and located the ID of my first commit. I used git checkout to return to that point in history. The project reverted to its original state. When finished reviewing, I switched back to the latest version.
What I learned:
Git maintains a complete history of the project. I can revisit any previous state to review or recover work.

