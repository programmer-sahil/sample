# Git Repository Initialization and Basic Workflow

## 1. Initialize a Git Repository
# To start using Git, initialize a repository in the current directory:
```bash
git init  # Initializes a new Git repository
```

# This command creates a new Git repository in the current directory.

## 2. Add Files to Staging Area
# After initializing the repository, add files to the staging area to track changes.
# To add all files in the directory, use:
```bash
git add .  # Stages all files in the directory for the next commit
```

# This command prepares all files for committing.

## 3. Commit Changes
# Once files are staged, commit the changes with a descriptive message:
```bash
git commit -m "Initial commit"  # Commits the staged changes with a message
```

# This stores the changes in the repository, creating a snapshot of your project’s current state.

## 4. Add More Changes (Optional)
# Continue making changes to your files. Once modified, add them to the staging area and commit as necessary.

## 5. Link to a Remote Repository (Optional)
# If you're working with a remote repository (e.g., GitHub, GitLab), link your local repository to the remote:
```bash
git remote add origin <repository_url>  # Links the local repository to a remote one
```

# Replace <repository_url> with the actual URL of your remote repository.

## 6. Push Changes to Remote Repository
# Push your committed changes to the remote repository to share them with others:
```bash
git push origin master  # Pushes changes to the master branch on the remote repository
```

# This command uploads your local commits to the remote repository, making them accessible to collaborators.
