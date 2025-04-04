# Git Workflow Instructions

This document provides step-by-step instructions for creating a branch using your name and pushing code to the repository.

## Prerequisites

- Ensure you have Git installed on your machine.

- Clone the repository to your local machine if you haven't already:

  ```

  git clone [git-url](https://github.com/dinhtanloc/IQC_2025.git)

-   Navigate to the repository folder:

    cd IQC_2025

    ```
Step 1: Create a New Branch
---------------------------

1.  Use the following command to create a new branch with your name:

    git checkout -b <your-name>

    Replace `<your-name>` with your actual name (e.g., `locdinh`).

2.  Verify that you are on the new branch:

    git branch

    The branch with an asterisk (*) next to it is your current branch.

* * * * *

Step 2: Make Changes
--------------------

1.  Make the necessary changes to the codebase.
2.  Stage the changes:

    git add .

3.  Commit the changes with a meaningful message:

    git commit -m "Your commit message"

* * * * *

Step 3: Push the Branch to the Remote Repository
------------------------------------------------

1.  Push your branch to the remote repository:

    git push origin <your-name>

    Replace `<your-name>` with the name of your branch.

2.  If this is your first time pushing the branch, Git may prompt you to set the upstream branch. Use the following command:

    git push --set-upstream origin <your-name>

* * * * *

Step 4: Create a Pull Request
-----------------------------

1.  Go to the repository on GitHub (or your Git hosting platform).
2.  Navigate to the **Pull Requests** tab.
3.  Click **New Pull Request**.
4.  Select your branch and compare it with the `main` branch (or the target branch).
5.  Add a title and description for your pull request.
6.  Submit the pull request for review.

* * * * *

Notes
-----

-   Always pull the latest changes from the `main` branch before starting new work:

    git checkout main

    git pull origin main

-   Avoid committing directly to the `main` branch.
-   Use meaningful commit messages to describe your changes.

