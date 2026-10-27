# Git and GitHub – Simple Notes

### 1. Git

* Git is a version control system.
* It tracks changes made to files.
* It helps us manage project history.

### 2. GitHub

* GitHub is an online platform for storing Git repositories.
* It allows us to upload and share our code.

### 3. Git Init (`git init`)

* Creates a new Git repository in the current directory.
* Used when starting a new project.
* Creates a hidden `.git` directory to store Git information.

### 4. Git Clone (`git clone`)

* Downloads an existing repository from GitHub to our local machine.
* Copies the project files and Git history.
* Automatically configures the remote repository.

### 5. Git Status (`git status`)

* Shows the current state of files.
* Identifies new, modified, deleted, and staged files.

### 6. Git Add (`git add`)

* Stages changes for the next commit.
* Example: `git add test.txt`
* To stage all changes: `git add -A`

### 7. Git Commit (`git commit`)

* Saves staged changes in the local repository.
* Every commit has a message describing the changes.
* Example: `git commit -m "Add a new file"`

### 8. Git Push (`git push`)

* Uploads committed changes from the local repository to GitHub.
* Example: `git push origin main`

### 9. Git Pull (`git pull`)

* Downloads and integrates changes from GitHub into the current branch.
* Example: `git pull origin main`

### 10. Git Remote (`git remote -v`)

* Shows the remote repositories connected to the local repository.
* `origin` is the default remote name commonly used for a cloned repository.

### 11. Git Log (`git log`)

* Shows the commit history.
* Example: `git log --oneline`

### 12. Git Workflow

When creating a new file and uploading it to GitHub:

1. Create a file.
2. Check changes using `git status`.
3. Stage changes using `git add`.
4. Save changes using `git commit`.
5. Upload changes using `git push`.

### 13. Git Init vs Git Clone

* `git init`: Creates a new local Git repository.
* `git clone`: Copies an existing repository from a remote location.
* A cloned repository already contains the `.git` directory.

### 14. GitHub Authentication

* GitHub does not accept normal account passwords for Git operations over HTTPS.
* A Personal Access Token (PAT) can be used instead.
* Never share your token with anyone.

### Important Point

* `git add` → Stages changes.
* `git commit` → Saves changes locally.
* `git push` → Uploads committed changes to GitHub.
* Git does not automatically upload local changes to GitHub.

