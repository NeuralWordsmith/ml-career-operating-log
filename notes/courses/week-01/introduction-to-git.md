---
tags:
  - course
  - datacamp
  - git
  - version_control
status: Completed
start_date: 2026-07-04
end_date: 2026-07-05
---

# Course: Introduction to Git

# 1. Summary & Goals

## Course Summary

This course introduces Git as a version-control system for software and data projects. It begins with the practical reason version control exists, then builds toward the core Git workflow: creating repositories, tracking files, staging changes, committing project states, inspecting history, comparing versions, and safely undoing changes.

The course should establish Git as a system for preserving meaningful project states, not merely as a list of terminal commands.

## Learning Goals

By the end of this course, I should be able to:

- Explain why version control is useful for software and data projects.
- Distinguish a project folder from a Git repository.
- Initialize a repository from an existing or new project.
- Explain the role of tracked files, the staging area, and commits.
- Stage file changes and save them as commits.
- Inspect repository history using logs.
- Compare project states across commits and staged changes.
- Restore, unstage, revert, or otherwise undo changes using the appropriate Git operation.
- Treat Git history as a structured record of project states rather than as a vague backup system.

## Course Promise

Use Git to put a project under version control, preserve meaningful snapshots of work, inspect how a project changed over time, and undo changes without losing the conceptual difference between the working directory, staging area, commits, and repository history.

---

# 2. Core Concepts & Notes

## Chapter 1: Introduction to Git

Learn the benefits and fundamentals of Git for version control in software and data projects. This chapter introduces the shell context, repository creation, staging, committing, and the first version-control workflow.

### Official activity sequence

- Introduction to version control
- Navigating the shell
- Checking the version of Git
- Creating repos
- Converting an existing project
- Creating a new repo
- Staging and committing files
- Adding a file to the staging area
- Saving files

[[Version Control - Project History Beyond Manual Saving]]  
[[Git - Repository as Project Files Plus Git History Storage]]  
[[Git - Staging Changes Before Committing]]  

## Chapter 2: Version history

Learn how to compare files at different points in time and restore files to previous states. This chapter turns commits into usable history: logs, filtering, file history, diffs, staged comparisons, restoring, unstaging, and reverting.

### Official activity sequence

- Viewing the version history
- Viewing a repository's history
- Finding the log message
- Version history tips and tricks
- Limiting the view of a repo's history
- Viewing a file's history
- Filtering commits by date
- Comparing versions
- Comparing staged files
- Comparing to the second most recent commit
- Restoring and reverting files
- Unstaging a file
- Reverting a commit
- Congratulations

[[Git - Commit Tree and Blob Object Structure]]  
[[Git - Filtering and Inspecting Commit History]]  
[[Git - Comparing Repository States with Diff]]  
[[Git - Choosing Revert Checkout or Restore for Undo]]

---

# 3. Key Takeaways & Reflections

- **Everything covered in this course:** [[Introduction to Git - Major Takeaways]]
- **Cheat Sheet:** [[Introduction to Git - Cheat Sheet]]

## Reflection Prompts

- Where did Git behave like a state-tracking system rather than a simple file-saving tool?
- Which Git commands were easy to type but required a clearer mental model?
- Which boundary became most important: working directory vs staging area, staging area vs commit, or commit history vs current file state?

---

# 4. Related Projects & Applications

- **Exercises:** [[Introduction to Git - Exercise Plan]]

## Application Targets

- Put a small local project under Git version control.
- Make several commits with meaningful messages.
- Inspect the history and compare earlier project states.
- Practice undoing changes with the correct command for the situation.
