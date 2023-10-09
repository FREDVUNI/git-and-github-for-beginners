# Git, GitHub, and GitHub Pages for Beginners

Welcome to the world of version control, collaboration with Git and GitHub, and deploying your projects with GitHub Pages! This guide will walk you through the basics, from creating repositories to managing branches, and finally, publishing your projects using GitHub Pages. 🚀

## Table of Contents
1. [**What is Git?**](#what-is-git)
2. [**What is GitHub?**](#what-is-github)
3. [**Local Repository**](#local-repository)
4. [**Remote Repository**](#remote-repository)
5. [**Understanding 'origin'**](#understanding-origin)
6. [**Uploading Code Using Drag and Drop**](#uploading-code-using-drag-and-drop)
7. [**Clone the Repository**](#clone-the-repository)
8. [**Making Changes and Pushing**](#making-changes-and-pushing)
9. [**Creating a Local Project**](#creating-a-local-project)
10. [**Branching**](#branching)
11. [**Creating a Branch**](#creating-a-branch)
12. [**Changing the Default Branch to 'main'**](#changing-the-default-branch-to-main)
13. [**Working with Branches**](#working-with-branches)
14. [**Merging Changes**](#merging-changes)
15. [**Pull Requests**](#pull-requests)
16. [**Deleting Branches**](#deleting-branches)
17. [**Git Commits**](#git-commits)
18. [**Resetting Commits**](#resetting-commits)
19. [**Forking**](#forking)
20. [**GitHub Pages**](#github-pages)

---

## What is Git? 📚
Git is a distributed version control system that allows you to track changes in your code over time. It helps you collaborate with others and maintain a history of your project.

## What is GitHub? 🌐
GitHub is a web-based platform that provides hosting for Git repositories. It makes collaboration easier by offering features like issue tracking, pull requests, and more.

## Local Repository 💻
A local repository is a copy of your project on your computer, where you can work and make changes without affecting the main project.

## Remote Repository 🚪
A remote repository is a version of your project hosted on a platform like GitHub. It serves as a central location where you can collaborate with others.

## Understanding 'origin' 🌍
'Origin' is a default name for the remote repository on GitHub. It's where your local changes are pushed to or pulled from.

## Uploading Code Using Drag and Drop 🖱️
1. Create a new repository on GitHub.
2. Drag and drop your project files into the repository on the GitHub website.
3. Commit changes by adding a commit message.
4. Click 'Commit Changes.'

![image](https://github.com/FREDVUNI/git-and-github-for-beginners/assets/41730664/15d8b561-023b-4f7b-8d05-1647d74a00ee)

## Clone the Repository 📥
To work on your project locally:
1. Copy the repository URL from GitHub.
2. Open your terminal.
3. Use `git clone <repository_url>` to clone the repository to your local machine.

## Making Changes and Pushing 🚢
1. Make changes to your files.
2. Use `git add .` to stage changes.
3. Commit changes with `git commit -m "Your commit message."`
4. Push changes to GitHub using `git push origin main`.

## Creating a Local Project 🏗️
1. Create a project directory.
2. Initialize Git with `git init`.
3. Add files with `git add .`.
4. Commit changes with `git commit -m "Initial commit."`
5. Create a repository on GitHub.
6. Set the remote with `git remote add origin <repository_url>`.
7. Rename the default branch to 'main' with `git branch -M main`.
8. Push changes with `git push -u origin main`.

## Branching 🌿
A branch is a separate line of development in Git. It allows you to work on features or fixes independently.

## Creating a Branch 🎉
1. Use `git branch <branch_name>` to create a new branch.
2. Switch to the new branch with `git checkout <branch_name>` or `git switch <branch_name>`.

## Changing the Default Branch to 'main' 🔄
The 'main' branch has replaced 'master' as the default in Git to promote inclusivity and avoid historical connotations.

To rename your default branch to 'main':
1. Use `git branch -M main`.

## Working with Branches 💪
1. Create and switch to a new branch.
2. Make changes, commit them, and push to your remote repository.
3. Merge changes back to 'main' using `git merge <branch_name>`.

## Merging Changes 🤝
1. Ensure you are on the 'main' branch.
2. Use `git merge <branch_name>` to integrate changes from another branch.
3. Resolve conflicts if necessary.

## Pull Requests 🚀
1. Create a Pull Request (PR) on GitHub to propose changes from your branch.
2. Review and discuss the changes with collaborators.
3. Merge the PR once approved.

## Deleting Branches 🗑️
To delete a branch:
1. Use `git branch -d <branch_name>` locally.
2. On GitHub, delete the branch via the web interface.

## Git Commits 📝
- `git log`: View commit history.
- `git reset <commit>`: Reset to a specific commit.
- `git reset --hard HEAD^`: Reset to the last commit.
- `git commit --amend`: Edit the last commit message.

## Forking 🍴
Forking creates a copy of someone else's repository under your GitHub account. It's useful for contributing to open-source projects.

1. Fork a repository on GitHub.
2. Clone your fork to your local machine.
3. Make changes, commit, and push to your fork.
4. Create a Pull Request to contribute changes to the original repository.

## GitHub Pages 🌐
GitHub Pages allows you to host your website directly from your GitHub repository. To publish a site using GitHub Pages:
1. Create an 'index.html' file in your repository.
2. Go to your repository's 'Settings' tab on GitHub.
3. Scroll down to the 'GitHub Pages' section.
4. Under 'Source,' select 'main branch' or another branch containing your website.
5. Click 'Save' to publish your site at `https://username.github.io/repository-name`.

That's it! You're now equipped with the basics of Git, GitHub, and how to publish your projects using GitHub Pages. Happy coding and sharing your work with the world! 😊
