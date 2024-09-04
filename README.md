# git-advanced

# Assignment: Git Branching and Merging

## Objective
Demonstrate proficiency in Git branching, merging, and conflict resolution.

## Task Steps

1. **Create Repository**
   - Create a new repository on GitHub called `git-advanced`.
   - Clone the repository to your local machine.

2. **Branch Creation and Initial Commit**
   - Create a new branch called `feature-1` and switch to it.
   - Create a new file named `shared.txt` with the following content:

     ```
     This is a shared file.
     Line 1: Original text.
     Line 2: Original text.
     ```

   - Stage and commit the file with a meaningful message.
   - Push the `feature-1` branch to GitHub.

3. **Second Branch Creation and Modification**
   - Create another branch called `feature-2` and switch to it.
   - Checkout the `shared.txt` file from the main branch to ensure consistency.
   - Modify the `shared.txt` file by changing the second line to:

     ```
     Line 2: Modified text in feature-2.
     ```

   - Stage and commit the changes with a meaningful message.
   - Push the `feature-2` branch to GitHub.

4. **Modifying `feature-1` Branch**
   - Switch back to the `feature-1` branch.
   - Modify the `shared.txt` file by changing the second line to:

     ```
     Line 2: Modified text in feature-1.
     ```

   - Stage and commit the changes with a meaningful message.
   - Push the `feature-1` branch to GitHub.

5. **Merging and Conflict Resolution**
   - Merge the `feature-1` branch into the main branch.
   - Merge the `feature-2` branch into the main branch, which should introduce a conflict.
   - Resolve the conflict by editing the file and committing the resolution.
   - Push the updated main branch to GitHub.

6. **Cleanup**
   - Delete the `feature-1` and `feature-2` branches.

