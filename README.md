# PLPBasicGitAssignment
Basic Git And GitHub Workflow 

# PLPBasicGitAssignment steps
### Task 1: Repository Setup
1. Created a new repository on GitHub named `PLPBasicGitAssignment`.
2. Initialize it with a README file.

### Task 2: Local Setup
3. Created a local folder named `PLPBasicGitAssignment`.
4. Initialized a Git repository in the local folder.
5. Linked the local repository to the GitHub repository.

### Task 3: Making Changes
6. Created a `hello.txt` file with the message "Hello, Git!".
7. Staged and committed the changes.

### Task 4: Pushing to GitHub
8. Pushed the changes to the GitHub repository.

### Task 5: Verification
9. Verified the presence of `hello.txt` and the commit message on GitHub.

## Commands Used

```bash
# Navigate to the project directory
cd path/to/PLPBasicGitAssignment

# Initialize a new Git repository
git init

# Link to the GitHub repository
git remote add origin <repository-url>

# Add a greeting to hello.txt
echo "Hello, Git!" > hello.txt

# Stage the file
git add hello.txt

# Commit the changes
git commit -m "Add hello.txt with a greeting"

# Push to GitHub
git push -u origin main
