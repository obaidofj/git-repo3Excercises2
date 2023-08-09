# Git Kata: Fast-forward Merge

## Setup

1. Run `source setup.sh` (or `.\setup.ps1` in PowerShell)

## The task

You again live in your own branch, this time we will be doing a bit of juggling with branches, to show how lightweight branches are in git.

1. Create a (feature)branch called `feature/uppercase` (yes, `feature/uppercase` is a perfectly legal branch name, and a common convention).
   > **Done**
   ---

2. Switch to this branch
   > **Done**
   ---

3. What is the output of `git status`?
    > **On branch feature/uppercase** \
      **nothing to commit, working tree clean**

4. Edit the greeting.txt to contain an uppercase greeting
   > **Done**
   ---

5. Add `greeting.txt` files to staging area and commit
   > **Done**
   ---

6. What is the output of `git branch`?
   >  **\* feature/uppercase**
      **master**
   ---

7. What is the output of `git log --oneline --graph --all`
   >  **\* 4b9f908 (HEAD -> feature/uppercase) initaial commit** \
      **\* 670a192 (master) Add content to greeting.txt** \
      **\* b72f776 Add file greeting.txt**
   ---

   *Remember: You want to update the master branch so it also has all the changes currently on the feature branch. The command 'git merge [branch name]' takes one branch as argument from which it takes changes. The branch pointed to by HEAD (currently checked out branch) is then updated to also include these changes.*

8. Switch to the `master` branch
   > **Done**
   ---

9. Use `cat` to see the contents of the greetings
   > **Done**
   ---

10. Diff the branches
      > **Done**
   ---

11. Merge the branches
      > **Done**
   ---

12. Use `cat` to see the contents of the greetings
      > **Done**
   ---

13. Delete the uppercase branch
      > **Done**
   ---


## Useful commands

- `git branch`
- `git branch <branch-name>`
- `git branch -d <branch-name>`
- `git switch`
- `git branch -v`
- `git add`
- `git commit`
- `git commit -m`
- `git merge <branch>`
- `git diff <branchA> <branchB>`
- `git log --oneline --graph --all`
