What is Git?
------------------------
&nbsp;&nbsp;&nbsp;&nbsp; ▪ Git is a version control system (VCS), which is a tool that helps developers track changes to files and coordinate work on those files across different people or machines.

&nbsp;&nbsp;&nbsp;&nbsp; ▪ In simpler terms, Git helps you keep track of the changes you make to your project, and it makes it easier to collaborate with others on the same project.

------------------------
Key Features of Git:
------------------------
&nbsp;&nbsp;&nbsp;&nbsp; ○ <strong>[Tracking Changes]</strong>: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ➡ Git allows you to track changes to files, see who made a change, and even go back to previous versions of your project.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ➡ It does this by saving a "snapshot" of the project at different points in time.

&nbsp;&nbsp;&nbsp;&nbsp; ○ <strong>[Collaboration]</strong>:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ➡ Multiple people can work on the same project without overwriting each other's work.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ➡ Git keeps track of everyone’s changes and merges them together smoothly.

&nbsp;&nbsp;&nbsp;&nbsp; ○ <strong>[Branching and Merging]</strong>:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ➡ Git allows you to create "branches" (copies of the project) where you can work on a new feature or fix a bug without affecting the main project.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ➡ Once you're done, you can merge the branch back into the main project.

&nbsp;&nbsp;&nbsp;&nbsp; ○ <strong>[Distributed]</strong>: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ➡ Git is distributed, meaning that every developer has a full copy of the project and its history on their own computer.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ➡ This makes it more robust because even if a central server goes down, each developer still has the full history of the project.

------------------------
Common Git Commands:
------------------------
&nbsp;&nbsp;&nbsp;&nbsp; ▪ <strong>git init</strong>: Initializes a new Git repository.

&nbsp;&nbsp;&nbsp;&nbsp; ▪ <strong>git clone <url></strong>: Clones a remote repository to your local machine.

&nbsp;&nbsp;&nbsp;&nbsp; ▪ <strong>git status</strong>: Shows the current status of the repository, including changes and files that are staged for commit.

&nbsp;&nbsp;&nbsp;&nbsp; ▪ <strong>git add <file></strong>: Stages a file for commit (this means you're telling Git you want to save the changes made to that file).

&nbsp;&nbsp;&nbsp;&nbsp; ▪ <strong>git commit -m "message"</strong>: Commits the staged changes with a message describing the changes.

&nbsp;&nbsp;&nbsp;&nbsp; ▪ <strong>git push</strong>: Pushes your local commits to the remote repository (e.g., GitHub).

&nbsp;&nbsp;&nbsp;&nbsp; ▪ <strong>git pull</strong>: Pulls the latest changes from the remote repository to your local machine.

------------------------------
Summary of Terminal Commands:
------------------------------
    # Navigate to your github_commands directory
    cd path/to/github_commands
    
    # Create the commands.md file
    touch commands.md / New-Item commands.md
    
    # Edit the commands.md file using nano or your preferred text editor
    nano commands.md
    
    # After editing, stage and commit the file
    git add commands.md
    git commit -m "Add commands.md with Git commands documentation"
    
    # Push the changes to GitHub
    git push origin main























