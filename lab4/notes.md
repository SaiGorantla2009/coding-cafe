The --global flag configures Git to use your username and email across your entire computer. Omitting it means you would need to manually set your credentials for every new repository you create.

Running standard ls hides the .git directory because files starting with a dot are hidden by default. Using ls -a reveals all files, including hidden ones like .git.

Git lists three folders available for tracking, and everything in the list corresponds to files you personally created.

Nothing disappeared because the .venv/ directory wasn't being tracked or displayed initially. The only new addition is the .gitignore file created in Section 3.

The .gitignore file should be committed because it defines the rules for which files Git should ignore. Committing it ensures that temporary or junk files aren't accidentally shared with collaborators.

The file transitioned from "untracked files" to "changes to be committed," moving from your working directory into the Staging Area.

It recorded the changes to the main timeline with the commit message "lab work so far," reporting that 5 files were modified.

This is known as a short commit hash—a unique identifier assigned to a commit for easy reference and tracking in the future.

The standard Git workflow loop consists of four steps: editing files, checking the status (git status), adding files to the staging area (git add), and committing the changes (git commit).

GitHub automatically renders a README.md file located in the root directory as the primary landing page for the project.

It securely caches a local authentication token, eliminating the need to enter your password repeatedly.

GitHub displayed README.md, lab4, week02, and .gitignore as the repository's main file structure view.

Pushing does not alter your local history; it simply uploads a copy of your existing local commits to a remote server on GitHub.

A private repository on GitHub is visible only to you and your designated collaborators, whereas a repository that hasn't been pushed or uploaded to GitHub at all exists solely on your local machine and isn't stored in the cloud.