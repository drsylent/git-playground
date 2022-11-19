# git-playground
Here is a tutorial for using git and GitHub, using GitHub Desktop!

# Normal usage

## Fork this repository

On GitHub (in a browser), while you are in this repository, on the top right corner there is a button, called fork.

## Clone your repository for local work

Open GitHub Desktop and clone the forked repository! Check whether you are currently in the default (main) branch.

## Checkout another branch

Checkout another branch, called "other": in GitHub Desktop, on the top the second button shows you your current branch. If you push this, you can switch to a desired branch.

## Modify a file and push your changes

Modify hello.txt. Create a commit in GitHub Desktop (bottom left corner) with a corresponding message (for example: Modified hello.txt in other branch). Push your changes: on the top the third button is used for synchronising with the remote repository. If you push it, it will push your new commit.

## Check for changes and modify this file again in your browser

In your browser change your branch to "other". You should see, that hello.txt has your recently commited change. Click on the button with a pencil icon, and change this file again. On the bottom, create a corresponding message and commit.

## Pull the changes locally

In GitHub Desktop, synchronise your local branch to the remote branch. You should see the changes made in your browser now also on your local machine.

## Create a new file locally and commit - but don't push

Create a new file in your local environment, and create a new commit in GitHub Desktop for adding this file with a corresponding message (for example: Added new file from local machine).

## Create a new file in the browser and commit

Create another file (with a different name) in your browser and commit it with a corresponding message (for example: Added new file from browser).

## Try to push your changes from the local machine

Return to your local environment, and try to push (synchronise) now! It will fail first - however if you continue on, it will pull your remote changes! Check the history now (top left corner, instead of Changes tab, choose History tab): how many commits will you push now? Push these changes.

## Create a pull request and check the options

Create a pull request from the other branch to the main branch (you can do this either in your browser or in GitHub Desktop). When you create it, check out all the options available before creation and after creation as well.

## Accept the pull request and delete the brach

Accept the pull request in your browser. It will offer you to delete the source (other) branch - do it.

## Create a new local branch, modify a file and push your changes

In GitHub Desktop change your branch to main and fetch/pull. Now create a new branch (branch button, New branch button) with name "conflict". Modify hello.txt, commit (example message: Modification from conflict branch) and push. Check in your browser whether this branch can be seen.

## Modify the same file in the same place in the main branch

In GitHub Desktop checkout the main branch. Modify hello.txt in the same location. Commit (example message: Modification from main branch) and push.

## Create a pull request and resolve the conflict

In your browser create a pull request from the conflict branch to the main branch. It will show you, that there is a conflict. Resolve this conflict in your browser and accept the pull request.
