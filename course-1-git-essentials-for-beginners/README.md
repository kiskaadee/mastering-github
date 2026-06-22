# Git & Version Control: Introduction and Roadmap

## 1. Course Information
* **Course:** Git Essentials for Beginners
* **Module:** 01 - Introduction and Roadmap
* **Status:** 🟩 Completed
* **Date Studied:** 2026-06-22
* **Estimated Time:** 15 minutes

---

## Learning Objectives

1. Master the basic Git commands for committing, branching, and managing repositories.

0. Gain hands-on experience in Git installation on different operating systems (Ubuntu, Mac, Windows).

0. Learn how to work with remote repositories and clone them for collaboration.

0. Understand Git architecture and workflows, enabling effective team collaboration.

## Overview

This introductory lecture of the "Git Essentials for Beginners" course provides an overview of Git, its environment, and the course structure to build a solid foundation for learning Git.

Course Introduction and Git Basics
- Explains the concept of Version Control Systems and the history and purpose of Git.

- Introduces the Git environment, including local Git, Git command line, and remote Git servers like GitHub and BitBucket.

Installation and Configuration
- Guides through installing Git on Windows, Linux, and Mac operating systems.

- Covers Git configuration, initialization of repositories, making commits, and viewing logs.

Core Git Concepts and Operations
- Emphasizes understanding Git architecture and workflow as essential for mastering Git.
- Discusses key operations such as adding, editing, removing files, reverting changes, working with branches and tags, and using aliases to improve efficiency.
- Introduces working with remote repositories and filtering commit logs.

This overview sets the stage for deeper exploration of Git's features and practical usage throughout the course.


## Module Outline

01 - [Course 1: Git Essentials](README.md): In this module, we will introduce the foundational concepts of Git and its importance in version control. You'll get a clear roadmap of the topics covered in the course, ensuring you understand the tools and skills that will be developed throughout.

02 - [Getting Started](02-basics-of-version-control-systems.md): In this module, we will delve into the basics of version control systems, exploring what they are and why they are essential for modern software development. You'll learn about different types of VCS, the origins of Git, and why it stands out as the go-to solution for version control in the tech landscape.

03 - [Git Installation and Basic Concepts](03-installing-and-configuring-git.md): In this module, we will guide you through the process of installing Git across different platforms and configuring it for your development environment. You'll explore core Git concepts such as initializing repositories, making your first commit, and cloning repositories, laying a strong foundation for practical version control.

04 - [Git Architecture and Basic Operations](04-gits-architecture-and-three-stages.md): In this module, we will dive deep into Git's architecture, covering its three essential stages—working directory, staging area, and repository. You'll learn about crucial concepts like the HEAD pointer, hash values, and how to manage files within Git. Additionally, we'll explore key commands such as Git diff and efficient ways to add and commit changes.

05 - [Revert the Changes](05-handling-changes-and-rollback.md): In this module, we will focus on handling changes in Git, covering how to undo file modifications, amend commits, and roll back commits if needed. You'll also learn to clean up your working directory by removing untracked files, ensuring a clean and organized project history.

06 - [Ignore Files](06-controlling-tracked-files-gitignore.md): In this module, we will explore how to control which files Git tracks by using the .gitignore file. You'll learn to prevent unnecessary files from cluttering your repository, how to handle empty directories, and the nuances of ignoring files that are already tracked in Git.

07 - [Git Branches](07-git-branches-and-parallel-development.md): In this module, we will explore the power of Git branches, which allow for parallel development and feature isolation. You'll learn how to create and manage branches, switch between them, and merge changes back into the main codebase. Additionally, we will introduce a Git prompt script to streamline branch-related operations.

08 - [Tags](08-tagging-and-detached-head.md): In this module, we will focus on the concept of tagging in Git, a useful feature for marking important points in your project history. You'll learn how to create and manage tags, explore the structure of the tags folder in .git, and understand how to re-tag or replace old tags. We'll also cover how to checkout tags and navigate the detached HEAD state.

09 - [Aliases](09-git-aliases-for-efficiency.md): In this module, we will explore how to create and use Git aliases, a powerful feature that allows you to shorten long or repetitive commands. You'll learn how to configure aliases for common operations and review a sample list to optimize your Git workflow. This will help you work faster and more efficiently with Git commands.

10 - [Remote Repository and Commit Log Filtering](10-remote-repositories-and-log-filtering.md): In this module, we will cover the process of working with remote repositories, including cloning them and reviewing the cloned content. Additionally, you'll dive into commit log filtering, learning how to efficiently search and filter through the log history in order to track changes, authors, or specific commits in your projects.

11 - [Course 1: Conclusion](11-part-one-review-and-essentials.md): In this final module, we will review the essential concepts and skills covered in the course, from Git basics to advanced features like branching, tagging, and remote repository management. You'll also receive recommendations on what to explore next to continue your Git journey and deepen your version control expertise.

12 - [Course 2: Merging Types, Branching Types, Stash, and Rebase](12-advanced-git-operations-overview.md): In this module, we will provide an overview of advanced Git operations, focusing on merging, branching strategies, stashing changes, and the rebase command. These techniques will help you manage complex workflows, maintain cleaner commit histories, and improve collaboration in version-controlled projects.

13 - [Merging and Conflicts](13-merge-types-and-conflict-resolution.md): In this module, we will explore the various types of merges in Git, including fast-forward and 3-way merges and provide demos to help visualize the processes. You'll learn how to handle merge conflicts when they arise, using both simple scenarios and real-world demos to ensure you can resolve conflicts confidently and efficiently in your projects.

14 - [Branching Conflicts](14-branching-conflicts-and-strategies.md): In this module, we will focus on the challenges that arise when working with multiple branches, particularly branching conflicts. You'll learn about proven branching strategies that help avoid conflicts and maintain a smooth development workflow, ensuring seamless collaboration within teams.

15 - [Stashing](15-stashing-changes-and-techniques.md): In this module, we will explore the concept of stashing, which allows you to temporarily save uncommitted changes without losing your current work context. Through detailed demos, you'll learn different stashing techniques and how to apply them in real-world development scenarios. Additionally, we'll cover how to create a branch directly from a stash to preserve work while shifting focus.

16 - [Rebasing](16-rebasing-vs-merging.md): In this module, we will dive into the concept of rebasing, a powerful Git feature used to streamline commit history and maintain a clean project timeline. You'll learn when and why to use rebasing, and how it differs from merging, and follow along with a demo to practice performing a rebase in real-world scenarios.

17 - [Course 3: Searching, Rewriting History and Reset](17-advanced-searching-rewriting-resetting.md): In this module, we will introduce advanced Git features such as searching through commit history, rewriting past commits, and using the reset command. These skills will empower you to maintain an organized and efficient project history while managing changes and correcting errors with confidence.

18 - [Searching](18-searching-with-git-grep.md): In this module, we will focus on Git's powerful searching capabilities, particularly using the git grep command. You'll learn how to search for specific content within your project and apply advanced filtering to streamline your search process, making it easier to navigate large or complex code repositories.

19 - [Rewriting History](19-rewriting-git-history.md): In this module, we will explore how to rewrite Git history to improve the clarity and organization of your project. You'll learn how to update the last commit and use the rebase command to squash multiple commits, drop unnecessary ones, and reorder commits to create a cleaner project history. These skills are essential for maintaining a professional and coherent commit timeline.

20 - [Git Reset](20-git-reset-soft-mixed-hard.md): In this module, we will break down the Git reset command, focusing on its three types: soft, mixed, and hard. You'll learn when and how to use each type of reset to manage changes in your repository, allowing you to adjust your work while maintaining control over your project history and files.

21 - [Course 3: Conclusion](21-advanced-techniques-summary.md): In this final module, we will summarize the key lessons from this course, including advanced techniques like search, history rewriting, and resetting. You'll receive guidance on how to continue developing your Git expertise, preparing you to handle complex version control challenges with confidence.
