# Git & GitHub – Interview Questions **WITH ANSWERS** (DevOps Focus)

---

## 📌 PART 1: Git Interview Questions (With Answers)

### Basics

1. **What is Git?**
   Git is a distributed version control system used to track changes in source code and collaborate efficiently.

2. **Why is Git called a distributed VCS?**
   Because every developer has a full copy of the repository, including complete history.

3. **Difference between Git and GitHub?**
   Git is a version control tool; GitHub is a platform that hosts Git repositories and provides collaboration features.

4. **What problem does Git solve?**
   It prevents code conflicts, tracks history, enables collaboration, and allows rollback.

5. **What is a repository?**
   A repository is a storage location for project files and their version history.

---

### Git Architecture

6. **Explain Git architecture.**
   Git has three areas: Working Directory, Staging Area, and Local Repository.

7. **What is the staging area?**
   It is an intermediate area where changes are prepared before committing.

8. **What is a commit?**
   A commit is a snapshot of changes saved in the repository with a unique hash.

9. **What is HEAD?**
   HEAD points to the current branch and latest commit.

10. **What is SHA in Git?**
    SHA is a unique hash used to identify commits securely.

---

### Core Commands

11. **Difference between `git clone` and `git fork`?**
    Clone copies a repo locally; fork creates a copy in your GitHub account.

12. **What does `git status` do?**
    Shows the current state of the working directory and staging area.

13. **What is `git add`?**
    Adds changes to the staging area.

14. **Difference between `git commit` and `git push`?**
    Commit saves changes locally; push sends them to the remote repository.

15. **What is `git pull`?**
    Fetches and merges changes from remote to local.

16. **Difference between `git pull` and `git fetch`?**
    Fetch downloads changes only; pull fetches and merges.

17. **What does `git log` show?**
    Displays commit history.

18. **What is `git diff`?**
    Shows differences between files, commits, or stages.

---

### Branching & Merging

19. **What is a branch?**
    A branch is an independent line of development.

20. **Why use branches?**
    To isolate features, bug fixes, and experiments.

21. **What is merging?**
    Combining changes from one branch into another.

22. **Merge vs Rebase?**
    Merge preserves history; rebase rewrites history for cleaner logs.

23. **What is a fast-forward merge?**
    When the branch pointer moves forward without creating a merge commit.

24. **What is a merge conflict?**
    Occurs when Git cannot automatically merge changes.

25. **How do you resolve merge conflicts?**
    Manually edit files, remove conflict markers, and commit.

---

### Undo & Recovery

26. **Difference between `git reset` and `git revert`?**
    Reset rewrites history; revert creates a new commit.

27. **Types of `git reset`?**
    Soft, Mixed, Hard.

28. **Which is used in production and why?**
    `git revert` because it is safe and auditable.

29. **What is `git checkout`?**
    Used to switch branches or restore files.

30. **What is `git reflog`?**
    Tracks all changes to HEAD for recovery.

---

### Advanced Git

31. **What is `.gitignore`?**
    Specifies files Git should not track.

32. **What are tags?**
    Used to mark specific points like releases.

33. **Lightweight vs annotated tags?**
    Annotated tags store metadata; lightweight do not.

34. **What is `git stash`?**
    Temporarily saves uncommitted changes.

35. **What is cherry-pick?**
    Applies a specific commit from another branch.

36. **How do you recover a deleted commit?**
    Using `git reflog`.

---

### Git in DevOps

37. **How is Git used in CI/CD?**
    Commits trigger pipelines automatically.

38. **What is GitOps?**
    A practice where Git is the source of truth for deployments.

39. **Why is Git critical in DevOps?**
    Automation, traceability, rollback, and collaboration depend on Git.

---

## 📌 PART 2: GitHub Interview Questions (With Answers)

40. **What is GitHub?**
    A Git repository hosting and collaboration platform.

41. **What is a pull request?**
    A request to merge code changes after review.

42. **Why are PRs important?**
    They enforce review, quality, and security.

43. **What is a protected branch?**
    A branch with restricted direct pushes.

44. **What are GitHub Issues?**
    Used for tracking bugs, tasks, and features.

45. **What are GitHub Actions?**
    CI/CD workflows triggered by GitHub events.

46. **What are GitHub Secrets?**
    Secure storage for sensitive values.

47. **What is a GitHub webhook?**
    Sends events to external systems.

48. **What are runners?**
    Machines that execute GitHub Actions jobs.

49. **GitHub-hosted vs self-hosted runners?**
    GitHub-hosted are managed; self-hosted offer more control.

50. **How do you secure GitHub repositories?**
    Branch protection, reviews, secrets, and access control.

---

## 📌 PART 3: Real Interviewer–Style Mock Interview (Q&A)

**Q: Why do we use Git in DevOps?**
A: Git enables automation, versioning of infra, CI/CD triggers, and safe rollbacks.

**Q: How do you undo a bad production deployment?**
A: By reverting the commit and redeploying via pipeline.

**Q: How does Git integrate with CI/CD?**
A: Commits trigger pipelines automatically using webhooks.

**Q: What branching strategy do you follow?**
A: Feature branches with protected main branch and PR reviews.

**Q: Why is GitOps better than manual deployment?**
A: It ensures consistency, auditability, and automated recovery.

---


✅ This file is **interview-ready**. Use it for **revision + mock interview practice**..
