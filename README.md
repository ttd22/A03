# A03
Spring 2021 IS117 Assignment 3 for Section 2

**PART 1: Directions on Using Webstorm/Github/Git.**

**A - SETTING UP**
1. Install Webstorm: Download from  https://www.jetbrains.com/student/
2. Install Git as a Local Program: Download from https://git-scm.com/downloads
3. Set Up Github: Create a Github account at https://github.com/join

**B - WEBSTORM AND GITHUB GUIDE**
1. Create a Repository on Github: Click the + sign in the upper right corner. Choose “Create New repository”. The Repository is set up. Make the repository public and add the readme file. Click create.

2. Connect Github with Webstorm: In Webstorm press (Ctrl+Alt+S) for system preferences. Select Version control Git. Enter the path to the git.exe

3. Add Github Password to Webstorm: In Webstorm press (Ctrl+Alt+S) for system preferences. Select Appearance and Behavior | System Settings | Passwords

4. Create a Repository from Webstorm: Select VCS and Import into Version Control

5. Import a Repository from Github: From Main page Select Checkout from version control → Git OR From within Webstorm Select VCS → Checkout from version control → Git. Enter Github repository name. Enter local path name

6. Creating a Webstorm File: Choose File → HTML →  HTML 5 or File → Stylesheet

7. Add files to Git: The Add to Git dialog opens. Click Add. This adds to local file system

8. Commit Your Changes: Add a message in the commit message. Click commit

9. Push Change to Remote Repository: Click “Ctrl → Shift →  K” Or “VCS →  Git → Push”. File is now on Github

10. Set up Github Pages: Click Settings. Check the repository name

11. Choose GitHub Page Location: Select “Master branch”. Note the published URL

12. Check your GitHub Pages: Copy the Github.io URL into a browser. Post the URL into Moodle with your Github account URL

**C - GIT GUIDE**
1. Create a new git Repository: Create a new directory, open it and perform a [git init].

2. Checkout a repository: Create a working copy of a local repository [git clone /path/to/repository]. When using a remote server, the command is [git clone username@host:/path/to/repository]

3. Workflow: The local repository consists of three "trees" maintained by git. The first one is Working Directory which holds the actual files. The second one is the Index which acts as a staging area and finally the HEAD which points to the last commit you've made.

4. Add & commit: To propose changes, use [git add <filename>]. To actually commit these changes, use [git commit -m "Commit message"]

5. Pushing changes: To send changes to your remote repository, execute [git push origin master]. Change master to whatever branch you want to push your changes to. If you have not cloned an existing repository and want to connect your repository to a remote server, you need to add it with [git remote add origin <server>].

6. Branch: Create a new branch named "feature_x" and switch to it using [git checkout -b feature_x]. Switch back to master [git checkout master]. And delete the branch again [git branch -d feature_x]. A branch is not available to others unless you push the branch to your remote repository [git push origin <branch>]

7. Update & merge: To update your local repository to the newest commit, execute [git pull]. To merge another branch into your active branch, use [git merge <branch>]. You also need to mark them as merged with [git add <filename>]. Before merging changes, you can also preview them by using [git diff <source_branch> <target_branch>]



**PART 2: Glossary to include these terms in a bulleted list.**

**Branch** - A set of development code that does not interfere with the production system.

**Clone** - A copy of a **repository** that lives on your computer instead of on a website's server somewhere, or the act of making that copy. 

**Commit** - Snapshots of your entire **repository** at specific times.

**Fetch** - When using it, you're adding changes from the remote **repository** to your local working **branch** without **committing** them.

**GIT** - An open source program for tracking changes in text files.

**Github** - A code hosting platform for collaboration and version control.

**Merge** - **Merging** takes the changes from one **branch** (in the same **repository** or from a fork), and applies them into another. 

**Merge Conflict** - A difference that occurs between **merged branches**. 

**Push** - To push means to send your **committed** changes to a remote **repository** on **GitHub.com**.

**Pull** - Pull refers to when you are **fetching** in changes and **merging** them. 

**Remote** -  The version of a **repository** or **branch** that is hosted on a server, most likely **GitHub.com**.

**Repository** - It contains project files and stores each file's revision history, and it can have multiple collaborators and can be either public or private.



**References:**
1. Hendela, Arthur. “Introduction to Github and Webstorm” Introduction to Website Development, New Jersey Institute of Technology. Lecture. 
2. Dudler, Roger. “git - the simple guide”. https://rogerdudler.github.io/git-guide/.
3. “Github glossary”. _Github Docs_, https://docs.github.com/en/github/getting-started-with-github/github-glossary.
