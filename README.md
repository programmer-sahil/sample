# Git Repository Initialization and Basic Workflow

# 1. Initialize a Git Repository
# To start using Git, initialize a repository with the following command:
git init  # Initializes a new Git repository in the current directory
# This will set up a new Git repository in the current directory.

# 2. Add Files to Staging Area
# After initializing the repository, add files to the staging area to start tracking changes.
# To add all files in the directory, use:
git add .  # Adds all files in the directory to the staging area
# This stages all the files, preparing them for the next commit.

# 3. Commit Changes
# Once files are staged, commit the changes to your local repository with a descriptive message.
git commit -m "Initial commit"  # Commits the staged changes with a message
# This command stores the changes in the repository, creating a snapshot of the current project state.

# 4. Add More Changes
# You can continue making changes to files, adding them to the staging area, and committing them as needed.

# 5. Link to a Remote Repository (Optional)
# If working with a remote repository (e.g., on GitHub, GitLab), link your local repository to the remote one.
git remote add origin <repository_url>  # Links the local repository to a remote one
# Replace <repository_url> with the actual URL of your remote repository.

# 6. Push Changes to Remote Repository
# Push your committed changes to the remote repository (e.g., GitHub, GitLab).
git push origin master  # Pushes the changes to the master branch on the remote repository
# This uploads your local changes to the remote repository, making them accessible to others.
