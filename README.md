Setting Up a GitHub Repository: 
Task 1: Repository Creation
Log in to GitHub:
If you haven’t already, log in to your GitHub account.
Create a New Repository:
Click on the “+” icon in the top right corner and select “New repository.”
Type a short, memorable name for your repository (e.g., “PLPBasicGitAssignment”).
Optionally, add a description (e.g., “My first repository on GitHub”).
Choose a repository visibility (public, private, or internal).
Check the option to initialize the repository with a README file.
Click “Create repository.”
Task 2: Local Setup
Local Folder Setup:
Create a new folder on your local machine (e.g., “PLPBasicGitAssignment”).
Open a terminal or command prompt and navigate to the created folder.
Git Initialization:
Initialize a new Git repository in your local folder using the command:
git init

Connecting to GitHub:
Link your local repository to the GitHub repository you created in Task 1:
git remote add origin <repository-url>

Task 3: Making Changes
Create a File:
Inside your local folder, create a new text file (e.g., hello.txt).
Add a simple text message (e.g., “Hello, Git!”).
Committing Changes:
Stage the changes:
git add hello.txt

Commit the changes with a meaningful message:
git commit -m "Add hello.txt with a greeting"

Task 4: Pushing to GitHub
Pushing to GitHub:
Push the committed changes to your GitHub repository:
git push -u origin main

Task 5: Verification
Verify on GitHub:
Visit your GitHub repository in a web browser.
Confirm that the hello.txt file and commit message are visible.
Submission:
Ensure all changes are pushed to your GitHub repository.
