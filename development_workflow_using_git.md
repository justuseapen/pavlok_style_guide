Development Workflow using Git for Pavlok Software Team
=======================================================

At Pavlok, we're building world-class behavior modification software at a ridiculously low cost. We must maintain a meticulously high standard of code quality if we are to outlast the competition. Technical debt, is the very real problem that you face when you push code into production without fully understanding how it works. Pavlok is a company about building good habits. Let's use good habits to build great software.

# Good habits are going to beat out experience

*It doesn't matter if you're a rockstar developer if other developers come into your code base feeling like a monkey at mensa conference.*

Git
===
*"Git is a distributed revision control and source code management (SCM) system with an emphasis on speed, data integrity, and support for distributed, non-linear workflows."*
*- Wikipedia*

## New Projects
1. You'll need to initialize a new local repository in your project's root directory using `git init`
2. Now you can begin tracking your changes!
3. *But first,* you need to create a `.gitignore` file. In a Rails app this should be available by default.
4. Your `.gitignore` file should include `.DS_Store` if you're using a mac
5. Then, move all your changes into a temporary staging area by running `git add -A`
6. You can make those changes permanent by running `git commit -m"Initial commit"`

## Sharing Code
Pavlok uses Github to host and share code. If you're dropping into one of our codebases, just run `git clone git@github.com:justuseapen/REPO_NAME.git`. That will copy the master branch of the repository into your current directory.

### Follow along with this tutorial:
1. Fork one of the Pavlok repositories to your profile.
2. Clone the repo to your machine.
3. Make the root of the project your working directory.
4. Run `git checkout -b NEW_BRANCH_NAME_HERE` to create a new branch off of master
5. Fix a bug, refactor a model, build a feature, write a test, enhance the README, it doesn't matter, just make a single, small change.
6. Save your changes.
7. Stage your changes `git add -A`
8. Commit your changes `git commit -m"COMMIT MESSAGE GOES HERE"
9. Push your branch to GitHub `git push origin BRANCH NAME`
10. Make a pull request

Congratulations! That is going to be the workflow you use on any new project you join at Pavlok! If you're currently working on a project, you can simply start that workflow at step 4. 

# Branches
The default branch in a project is known as a master branch. This is the branch that we will push to production and is therefore sacred.

## Ten commandments of the master branch
1. Thou shalt not pollute the master branch with buggy code.
2. Thou shalt refactor thy code before pushing to master.
3.

# Existing projects