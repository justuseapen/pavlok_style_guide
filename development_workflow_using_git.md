Development Workflow using Git for Pavlok Software Team
=======================================================
At Pavlok, we're building world-class behavior modification software at a ridiculously low cost. We must maintain a meticulously high standard of code quality if we are to outlast the competition. Technical debt, is the very real problem that you face when you push code into production without fully understanding how it works. Pavlok is a company about building good habits. Let's use good habits to build great software.

# Good habits are going to beat out experience

*It doesn't matter if you're a rockstar developer if other developers come into your code base feeling like a monkey at mensa conference.*

Git
===
*"Git is a distributed revision control and source code management (SCM) system with an emphasis on speed, data integrity, and support for distributed, non-linear workflows."*
*- Wikipedia*

# New Projects
1. You'll need to initialize a new local repository in your project's root directory using `git init`
2. Now you can begin tracking your changes!
3. *But first,* you need to create a `.gitignore` file. In a Rails app this should be available by default.
4. Your `.gitignore` file should include `.DS_Store` if you're using a mac
5. Then, move all your changes into a temporary staging area by running `git add -A`
6. Finally, you can make those changes permanent by running `git commit -m"Initial commit"`