Hello, welcome to my first repository!

Questions and the answers:

a. What is an issue?
--------------------
A GitHub issue is a tool that helps users track tasks, improvements, bugs, and other project-related activities. It serves as a way to organize and manage project work, making it easier for team members to collaborate effectively.


b. What is a pull request?
--------------------------
A pull request (PR) in version control systems like Git lets developers propose changes to a codebase. After making changes in their branch, they can submit a PR for review, which, if approved, can be merged into the main branch.


c. Describe the steps to open a pull request?
---------------------------------------------
1- Go to the original repository on GitHub (not your forked one).
2- You should see a notification asking if you would like to compare and open a pull request from the branch you just pushed.
3- If not, navigate to the "Pull requests" tab and click on "New pull request."
4- Select your branch in the "compare" dropdown, and the base branch (main)
5- Provide a descriptive title and detailed explanation of what you have done in the pull request 
6- Submit the pull request by clicking "Create pull request." 


 d. Describe the steps to add a collaborator to a repository (share write permissions)
--------------------------------------------------------------------------------------
1. Go to the repository where you want to add a collaborator.

2. Go to the Repository Settings

3. Access the Collaborators Section: In the left-hand sidebar, click on Collaborators and Teams under the "Access" section.

4. Add a Collaborator: type the GitHub username, full name, or email address of the person you want to add.
    Select the correct user from the dropdown list that appears.

5. Send the Invitation: Click the Add <username> to the repository button to send an invitation.

6. Wait for Acceptance

7. Manage Collaborator Permissions: Allow write permission

e. What is the difference between git and GitHub?
-------------------------------------------------
Git: It is a distributed version control system used to track changes in source code during software development. It allows multiple developers to work on a project simultaneously without overwriting each other's changes. It operates locally on your computer. It manages your project's history, handles branching and merging, and allows you to revert to previous versions of your code.

GitHub: It is a Web-based Hosting Service for Git Repositories in the cloud. It provides a collaborative environment where developers can share their code, contribute to open-source projects, and collaborate on private repositories.


f. What does git diff do?
-------------------------
The `git diff` command in Git is used to display the differences between various states of your repository. It allows you to compare changes in your working directory against the last commit, or between any two commits, branches, or specific files.


 g. What is the main branch?
----------------------------
The "main branch" is the primary branch in a version control system where the stable, production-ready version of the project is maintained.


 h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
-----------------------------------------------------------------------------------------------------------------------------
Generally, it's not recommended to push changes directly to the main branch, especially in a collaborative environment. Instead, it's better to create a new branch off of the main branch to work on a new feature, bug fix, or any update. This keeps your main branch stable and allows you to work on changes without affecting others.
    