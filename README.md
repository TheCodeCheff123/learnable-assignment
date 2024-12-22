# learnable-assignment

What is Version Control?

Version control is a system that helps track changes to files over time. It allows multiple people to work on the same project, keeps a history of changes, and makes it easy to revert to earlier versions if needed. It's widely used in software development to manage source code.

Difference Between Git and GitHub <br>
Git: A distributed version control system. It's a tool used locally to track changes in your code and collaborate with others.
GitHub: A web-based platform that hosts Git repositories. It provides collaboration features like issue tracking, pull requests, and web interfaces for managing code.

3 Alternatives to GitHub <br>
GitLab: Offers similar features as GitHub but includes built-in CI/CD tools. <br>
Bitbucket: Popular for teams using Atlassian tools like Jira. <br>
SourceForge: A platform for hosting and managing software projects, especially open-source ones.

Difference Between git fetch and git pull <br>
git fetch: Downloads changes from the remote repository but doesn't merge them into your local branch. It's like checking for updates. <br>
git pull: Combines git fetch and git merge, downloading the changes and immediately merging them into your local branch.

Git Rebase (Simple Terms) <br>
Rebase is like "replaying" your changes on top of another branch. It helps keep the commit history linear and clean by avoiding unnecessary merge commits. <br>
example <br>
    git rebase <branch-name>

Git Cherry-Pick (Simple Terms) <br>
Cherry-pick allows you to take a specific commit from one branch and apply it to another branch. It's useful when you need to include a specific change without merging the entire branch.
example <br>
    git cherry-pick <commit-hash>



