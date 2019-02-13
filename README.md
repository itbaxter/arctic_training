# Arctic Training Hands on Materials
Arctic Data Science Center Training Tutorial February 2019: Hands on materials for the Arctic training workshop.

- Data
- Lessons
- Notes

Made some changes from RStudio.
- changes show up in Staging after I hit save.
- but this doesn't save changes to the repository until I check Staged & Commit.

You can explicitly choose what goes into the commit.
- Unless it is a binary file, then it changes the whole thing.

Format of commit descriptions:
- What? (Concise)
- Why? (Descriptive)

Using the command line
- git status
- git add
- git commit

Great job!

Thanks!

Pushing at the same time.
- the second person to push will get an error message
- it will then tell you to pull first
- then it will auto-merge and commit (you'll see a branch in the git window)
- then the second person will push the most recent version
    - everyone should pull before they start to edit and not edit same place at same time
    - when a conflict arises someone (the owner?) should resolve the merge

Pull -> Edit -> Add -> Pull -> Commit -> Push

Branching
- git branch [branch_name] **to create branch
- git checkout [branch_name] **to switch
- git merge **to merge the branch

Adding fork_in_road branch for testing
- Gave a conflict to resolve
- You're merges if they are on the same place will be like the conflict w/ a collaborator
