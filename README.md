# Git Assignment - <davidvaz77>

================================

a. What is an issue?
Issues are used to track todos, bugs, feature requests, and more. - a project management tool 

b. What is a pull request?

A pull request is a feature commonly used in collaborative software development environments. It allows developers to notify others about changes they’ve made to a project and propose that these changes be merged into a target branch of a repository (usually the main branch).

c. Describe the steps to open a pull request?

Go to your repository on GitHub and navigate to the "Pull Requests" tab.
Click "New Pull Request."
Select the base branch (e.g., main) and your compare branch.
Add a title and description for your pull request.
Review the changes in the "Files changed" tab.
Request reviewers (optional).
Click "Create Pull Request."
Address any feedback and push additional commits if needed.
Merge the pull request once approved and (optionally) delete the branch.

d. Describe the steps to add a collaborator to a repository (share write permissions)

Navigate to the repository > Settings > Collaborators.
Click "Add collaborator" and enter the username/email.
Select the user and click "Add collaborator".
The collaborator accepts the invitation to gain access.


e. What is the difference between git and GitHub?

Git is a tool for version control, allowing you to manage and track changes in your codebase locally or across distributed teams.
GitHub is a platform that hosts Git repositories and provides collaboration tools like pull requests, code reviews, and issue tracking, enhancing the capabilities of Git with social and collaborative features.
Git is the underlying technology for version control, while GitHub is a service built on top of Git, providing a space for collaboration, sharing, and managing projects


f. What does git diff do?

git diff is essential for reviewing changes, understanding what has been modified, and preparing commits. It's a vital tool

g. What is the main branch?

The main branch is the primary branch in a Git repository where stable, production-ready code is maintained.
It serves as the central point for integrating changes from other branches.
Keeping the main branch in a stable and deployable state is a common best practice in software development.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

Avoid pushing directly to the main branch after the initial commit to ensure code stability, enable code review, and maintain a clean version history.
Use branches and then merge after reviewing and testing