# Exercise 3: Using Pull Requests for Code Review

## Objective:
To practice using pull requests for code review and collaboration on GitHub.

## Description:
In this exercise, you will simulate contributing to a GitHub repository by creating a new branch, making changes, committing them, and creating a pull request for code review and collaboration.

### Clone the Repository:
1. First, clone the repository to your local machine using Git. Open your terminal or Git Bash and run the following command:
    ```bash
    git clone https://github.com/sepehrkrz/CIROH-DevCon-GitHub.git
    ```

2. Navigate to the Cloned Repository:
    ```bash
    cd CIROH-DevCon-GitHub
    ```

### Create a New Branch:
1. Create a new branch for your changes. Replace `<your-branch-name>` with a descriptive name for your branch (e.g., `feature-add-text-file`).
    ```bash
    git checkout -b <your-branch-name>
    ```

### Create and Edit a .txt File:
1. Create a new `.txt` file and open it in a text editor to write a sample sentence.
    ```bash
    touch sample.txt
    nano sample.txt
    ```

2. Write a sample sentence in the file (e.g., "This is a sample sentence."), save, and exit the text editor.

### Commit Changes:
1. Add the newly created `.txt` file to the staging area and commit it with a descriptive message.
    ```bash
    git add sample.txt
    git commit -m "Add sample.txt with a sample sentence"
    ```

### Push the Branch to GitHub:
1. Push your local branch to the GitHub repository.
    ```bash
    git push origin <your-branch-name>
    ```

### Create a Pull Request on GitHub:
1. Go to the GitHub repository page (https://github.com/sepehrkrz/CIROH-DevCon-GitHub).
2. GitHub should detect your newly pushed branch and prompt you to create a pull request. If not, you can manually create a pull request by clicking on the "Pull requests" tab and then the "New pull request" button.
3. Choose the base branch (e.g., `main`, `master`) as the target for the pull request.
4. Choose your newly created branch (`<your-branch-name>`) as the compare branch.
5. Review the changes in the pull request and add a title and description.
6. Click on "Create pull request" to submit the pull request.

### Review and Merge:
1. Once the pull request is created, reviewers can review the changes and discuss them using GitHub's comment system. The repository owner can then merge the pull request after the review process is complete.

## Verification:

### Check GitHub Repository:
- Verify that the pull request is merged into the main branch.
- Check the commit history to see the merged changes and the merge commit message.
- Optionally, delete the merged branch on GitHub to clean up branches.

### Verify Code Changes Locally (Optional):
- If you have a local copy of the repository, pull the latest changes from the main branch and verify that the merged changes are included.
    ```bash
    git checkout main
    git pull origin main
    ```
