# Collaborating on GitHub with RStudio

This guide will help you get set up with our shared GitHub repository using RStudio.

## Step 1: Install Git

First, verify if Git is installed on your computer. Open your terminal and type `git --version`. If Git isn't installed, you can download and install it from the [Git website](https://git-scm.com/downloads).

## Step 2: Set Up Git in RStudio

Once Git is installed:

1. Open RStudio
2. Navigate to `Tools -> Global Options -> Git/SVN`.
3. Make sure the path to your Git executable is correct. If not, navigate to where you installed Git and select the Git executable.

## Step 3: Clone the GitHub Repository to RStudio

1. In RStudio, go to `File -> New Project -> Version Control -> Git`.
2. Paste the URL of our GitHub repository in the "Repository URL" field.
3. Choose the directory where you want to create the project and give it a name.

After this, RStudio will create a new project that links to our GitHub repository.

## Step 4: Working with the Repository

You should now see a new project in RStudio that represents our GitHub repository. You can add scripts, markdown files, data files, etc. to the project. Remember to save your changes in RStudio.

## Step 5: Commit Changes

When you add or modify files, these changes can be "committed" to save a version of your project:

1. Go to the Git pane (usually in the upper-right corner).
2. Check the boxes next to the files you want to commit.
3. Write a commit message describing your changes.
4. Click 'Commit'.

## Step 6: Push Changes to GitHub

After committing changes, you can "push" these changes to the GitHub server. Click the 'Push' button in the Git pane.

## Step 7: Pull Changes from GitHub

If your teammates have made changes on GitHub, you can "pull" these changes to your local copy of the project. Click the 'Pull' button in the Git pane.

## Important Tips

- Always "pull" from the repository to keep your local copy up to date before you start working on your part of the project, to avoid merge conflicts later on.
- "Commit" and "push" your changes often. Frequent commits with clear messages will make it easier to track the progression of the project and allow you to revert changes if something goes wrong.
- Coordinate with your teammates on who is working on what to avoid editing the same files at the same time, which can lead to merge conflicts.