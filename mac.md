## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is an open source distributed version control system.
2. What is the difference between Git and GitHub?
Git is an open source distributed version control system (enables you to 
freely manage and log  your code) , while GitHub is a cloud-based server 
that stores Git repos.
3. Why do we create a branch?
Personal branches allow me edit code without altering the main branch. 
I am able to merge my branch with main once my code is complete. This 
allows many programmers to write code without intefering with each other.
4. What is the purpose of a Pull Request?
Pull requests compares my branch with the branch I am seeking to 
contribute code to. If the code is acceptable, my branch will be merged to 
the other branch.
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
git checkout "desired_branch"
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
Git fetch: fetches or grabs the updates in the remote main so that you can see the changes. 
Git merge: If the updates in the remote branch are desirable, then they  will be merged to your local branch.
Git pull: Combines git fetch and git merge into one step.
7. What is a merge conflict?
The situation when two or more commits (between multiple developers' code) conflict with one another on the same line of code.
8. How do you resolve a merge conflict?
After determining which code change you want to merge, you will then create a new commit to push up that code change.
