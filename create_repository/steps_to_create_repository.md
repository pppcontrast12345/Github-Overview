Step-by-Step Example to Create and Manage a Git Repository

-------------------------------------------------------------
Step 1: Create a directory for your project
-------------------------------------------------------------
&nbsp;&nbsp;&nbsp;&nbsp; • mkdir 'project'

&nbsp;&nbsp;&nbsp;&nbsp; • cd my-project

Step 2: Create a README file/other file
--------------------------------------------------------------
&nbsp;&nbsp;&nbsp;&nbsp; • echo 'Step by step tp create a repository' README.md 


Step 3: Add some content to the README file (you can use nano or any editor)
-------------------------------------------------------------------------------
1.0 Open the file using nano or your editor

&nbsp;&nbsp;&nbsp;&nbsp; • nano README.md/notepad README.md

2.0 Add some content in the README file like:

&nbsp;&nbsp;&nbsp;&nbsp; • "This is my Git project repository."

&nbsp;&nbsp;&nbsp;&nbsp; • After editing, save and close the file (in nano: press Ctrl+X, then Y, and Enter)

---------------------------------------------------------------------------------
Step 4: Initialize a Git repository in the project directory
---------------------------------------------------------------------------------
git init  

&nbsp;&nbsp;&nbsp;&nbsp; • Initializes a Git repository in the current directory

-----------------------------------------------------------------------------------
Step 5: Check the status of your repository to see changes (like README file added)
----------------------------------------------------------------------------------

git status

-----------------------------------------------------------------------------------
Step 6: Add the README file to Git's staging area (ready to be committed)
-----------------------------------------------------------------------------------
git add README.md

-----------------------------------------------------------------------------------
Step 7: Commit the changes to the repository with a commit message
-----------------------------------------------------------------------------------

git commit -m "Add README file with project description"

------------------------------------------------------------------------------------
Step 8: Create a remote repository on GitHub (manually, on GitHub.com)
------------------------------------------------------------------------------------

&nbsp;&nbsp;&nbsp;&nbsp; • Go to https://github.com, click "New" to create a new repository.

&nbsp;&nbsp;&nbsp;&nbsp; • Name the repository (e.g., 'my-project') and initialize it with a README (optional).

-------------------------------------------------------------------------------------
Step 9: Add the remote repository (link to your GitHub repository)
-------------------------------------------------------------------------------------

&nbsp;&nbsp;&nbsp;&nbsp; • git remote add origin https://github.com/username/my-project.git

&nbsp;&nbsp;&nbsp;&nbsp; • Replace with your GitHub URL

------------------------------------------------------------------------------------------------
Step 10: Push the changes to the remote repository (GitHub)
------------------------------------------------------------------------------------------------

&nbsp;&nbsp;&nbsp;&nbsp; • git push -u origin main

&nbsp;&nbsp;&nbsp;&nbsp; • Pushes the changes to GitHub, sets the remote 'origin' and the branch 'master'

-------------------------------------------------------------------------------------------------
Step 11: Pull the latest changes from the remote repository (to stay in sync)
-------------------------------------------------------------------------------------------------
&nbsp;&nbsp;&nbsp;&nbsp; • git pull origin main

&nbsp;&nbsp;&nbsp;&nbsp; - Pulls the latest changes from the remote repository to your local machine

&nbsp;&nbsp;&nbsp;&nbsp; • origin - It is the default name for the remote repository where your code is hosted (e.g., on GitHub).

&nbsp;&nbsp;&nbsp;&nbsp; - Alias or shortcut to the URL of the remote repository.

&nbsp;&nbsp;&nbsp;&nbsp; • branch - Is a separate line of development in Git. 

&nbsp;&nbsp;&nbsp;&nbsp; - It allows you to work on different features, fixes, or experiments without affecting the main codebase.

&nbsp;&nbsp;&nbsp;&nbsp; - You can create branches to isolate changes and later merge them.

&nbsp;&nbsp;&nbsp;&nbsp; • main - Is the default primary branch in a Git repository.

&nbsp;&nbsp;&nbsp;&nbsp; - It typically holds the stable, production-ready version of your code.
