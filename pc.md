## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? At a high level, GitHub is a website and cloud-based service that helps developers store and manage their code, as well as track and control changes to their code.
2. What is the difference between Git and GitHub? Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories.
3. Why do we create a branch? Git branches are effectively a pointer to a snapshot of your changes. When you want to add a new feature or fix a bug—no matter how big or how small—you spawn a new branch to encapsulate your changes.
4. What is the purpose of a Pull Request? Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main. The easiest way to switch branch on Git is to use the “git checkout” command and specify the name of the branch you want to switch to.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do? git fetch just "downloads" the changes from the remote to your local repository. git pull downloads the changes and merges them into your current branch.
7. What is a merge conflict? Merge conflicts occur when competing changes are made to the same line of a file, or when one person edits a file and another person deletes the same file.
8. How do you resolve a merge conflict? The easiest way to resolve a conflicted file is to open it and make any necessary changes
After editing the file, we can use the git add a command to stage the new merged content
The final step is to create a new commit with the help of the git commit command
Git will create a new merge commit to finalize the merge
