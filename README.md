# Project: Cryptocurrency Seniment Analysis

## Project Description
This project involved the analysis of data related to cryptocurrencies sourced from a Telegram channel. Our main goal was to gain a better understanding of various aspects of cryptocurrencies. We utilized Git as a version control tool throughout the project's development. In this project, we made an effort to implement all the commands and instructional steps provided in the training to enhance our skills.

## Version Control with Git
We employed Git as a version control tool for managing the project's source code. Git allowed us to easily track changes in the project and leverage the benefits of version control.

## Commits
During the course of the project, we made more than 20 meaningful commits. Each commit represented a specific event in the project's development, such as the implementation of new features or bug fixes.

## Branches
We utilized three meaningful branches to organize development tasks. The main branch (main) served as the primary development branch, while two other branches named new-feature and other-coins were created for specific purposes.

## Resolving Conflicts
We encountered two conflicts (conflicts) during the project. One occurred when merging changes into the main branch, and the other happened when merging changes from the new-feature branch into the main branch. Resolving these conflicts was most successful when using Git tools and code editors. Below, you can see two different approaches to resolving conflicts:

![Conflict Resolution 1](https://github.com/ArashST79/sentiment-analysis/blob/main/Screenshot%20(667).png
)
![Conflict Resolution 2](https://github.com/ArashST79/sentiment-analysis/blob/main/Screenshot%20(672).png
)

## Branch Protection
To enhance code quality and streamline development, we protected the main branch (main) on the GitHub repository. This means that merging another branch into the main branch requires the submission of a pull request. This step ensures that changes are thoroughly reviewed and agreed upon before merging branches. It can be seen from this photo that you are blokced to merge the changes, unless everyone admit it.

![pull request](https://github.com/ArashST79/sentiment-analysis/blob/main/Screenshot%20(671).png
)

## Gitignore
We have included a Gitignore file as requested. This file prevents unnecessary files from being committed to Git. For instance, outputs like images or files that have no need to be shared in Git, are excluded. Additionally, for our project, .ipynb_checkpoints are not uploaded to GitHub, as shown below:

![Gitignore Example](https://github.com/ArashST79/sentiment-analysis/blob/main/.gitignore)

## FAQ
Certainly, here are brief answers to your six questions:

1. **What is the .git directory? What information is stored in it? How is it created?**
   - The `.git` directory is the heart of a Git repository, containing metadata and object databases.
   - It stores information like commit history, branch references, configuration, and more.
   - It's created when you initialize a Git repository using `git init`.

2. **What does "atomic" mean in atomic commit and atomic pull-request?**
   - "Atomic" in Git refers to making a single, self-contained change that doesn't break the repository.
   - In an atomic commit, you make a single logical change in a single commit.
   - In an atomic pull-request, the changes are self-contained, testable, and don't depend on each other.

3. **Explain the differences between fetch, pull, merge, rebase, and cherry-pick.**
   - `fetch`: Retrieves changes from a remote repository without merging.
   - `pull`: Combines a `fetch` and a `merge` in one step to update your branch.
   - `merge`: Integrates changes from another branch into your current branch.
   - `rebase`: Moves or combines a sequence of commits to a new base commit.
   - `cherry-pick`: Selects and applies specific commits from one branch to another.

4. **Explain the differences between reset, revert, and restore.**
   - `reset`: Moves the current branch to a different commit, discarding commits.
   - `revert`: Creates new commits to undo specific changes made in the commit history.
   - `restore`: Restores a file in your working directory to a specific commit state.

5. **What is the meaning of "stage"? What does the `stash` command do?**
   - "Stage" refers to preparing changes for the next commit. You use `git add` to stage changes.
   - The `stash` command temporarily saves uncommitted changes to allow you to switch branches or perform other actions without losing work in progress.

6. **What is the concept of a "snapshot," and how does it relate to a commit?**
   - A "snapshot" in Git refers to a snapshot of your entire project's state at a specific point in time.
   - Commits in Git are snapshots of your project, capturing the state of all files and directories at the time of the commit.

You can include these question answers in your README in a section explaining Git concepts or as a separate FAQ section.

