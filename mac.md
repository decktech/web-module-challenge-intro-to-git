## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? verison control software.
2. What is the difference between Git and GitHub? git is the software that sends information to github where it can be stored and shared as 'open source code.'
3. Why do we create a branch? so we can make changes to code without changing the source code.
4. What is the purpose of a Pull Request? to suggest changes to code.
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main. git checkout <branch name>
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do? `git fetch` downloads all changes from a remote repository without integrating into the head (current branch). `git merge` takes the contents of a source branch and integrates it with a target branch. `git pull` is used to fetch and download content from a remote repository and immediately update the local repository to match that content. So git fetch is used add changes made to code by other developers into your own local repository, without intgrating in your current branch. git merge allows you to integrate the branches. git pull does both fetch and merge for a target branch.
7. What is a merge conflict? an event that takes place when Git is unable to automatically resolve differences in code between two commits. Git can merge the changes automatically only if the commits are on different lines or branches.
8. How do you resolve a merge conflict? to solve this, make the neccessary changes, use git add ., then git commit
