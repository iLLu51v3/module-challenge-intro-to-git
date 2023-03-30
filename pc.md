## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
- A tool managing source code history and revisions.

2. What is the difference between Git and GitHub?
- Server or hub for git repositories.

3. Why do we create a branch?
- To create, change, and/or  make revisions to a project without affecting the 'main' file or pulled project.

4. What is the purpose of a Pull Request?
- To allow review of changes and differences made between braches that were pushed by you or another individual for approval.

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
- "git checkout <branch-name>" if there is another branch to move to.

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
- 'git fetch' referes to downloading changes from a repository without merging the changes. Presents the commits made to the repository.
- 'git merge' referes to merging the changes made in one branch to another. The target branch that will take one the merge change is the current branch viewed, or the 'HEAD' branch
- 'git pull' plays both roles of 'git fetch' and 'git merge' in one request.

7. What is a merge conflict?
- When separate changes (competing commits) are made to the same line at the same time. The conflict needs to be resolved before merging the branches. Done in the command line

8. How do you resolve a merge conflict?
- Navigate to the local git repository where the conflict is originating.'cd <repository name>'
- Generate a list of affected files. 'git status'
- Use a text editor
search file for conflict marker 
<<<<<<<
issue
=======
conflicting issue
>>>>>> branch-a 
- decide on which issue to keep and then delete the conflict markers.
- 'git add.'
- 'git commit -m "message"'
- Push changes to remote repository or merge the branches in the command line 

This was for competing line changes. There are other merge conflicts, though, that require varied but similar approaches.