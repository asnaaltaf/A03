# A03
## Directions on Using Webstorm 
Step 1 - Install [Webstorm] (https://www.jetbrains.com/community/education/)

Step 2 - Select "Apply Now" to fill out a form in order to access JetBrain tools

Step 3 - Install [**Git**] as a local program (https://git-scm.com/downloads). 
         Select the Download option that is compatible with your device. 
         
Step 4 - Create a [**Github**] account (https://github.com/join). 
         Enter your username, email address, and password. 
         
Step 5 - Connect Github with Webstorm
         In Webstorm press (Ctrl+Alt+S) for system preferences. 
         Select Version control Git. Enter the path to the git.exe
         
Step 6 - Add Github Password to Webstorm 
         In Webstorm press (Ctrl+Alt+S) for system preferences
         Select Appearance and Behavior | System Settings | Passwords
         
Step 7 - Create a **Repository**
         Click the + sign in the upper right corner 
         Choose “Create New repository”
         
Step 8 - Make the Repository pubic and add the readme file.
         Click Create.
         The Repository is now set-up.
         
Step 9 - WebStorm integrates with many popular version control systems, like Git (or GitHub)
         You have the ability to view changes you or others make and **commit** and **push** your changes if needed.
         
Step 10 - If you want to check out a project from a version control system, see Check out a project (**clone**) for details.

Step 11 - In the case that you need to resolve a merge conflict on Github
          (a) Under your repository name, pull requests
          (b) In the "Pull Requests" list, click the **pull** request with a **merge conflict** that you'd like to resolve.
          (c) Near the bottom of your pull request, click Resolve conflicts
          (d) If you would like to add a **merge** que, in the "Pull Requests" list, click the pull request you would like to add to a merge queue to
          
Step 12 - If you would like to add a new **remote**, use the git remote to add a command on the terminal

Additional Info 
- The git **fetch** command downloads commits, files, and refs from a remote repository into a local repo.
- In the case that you need to fix bugs, **branches** allow you to develop features to do so.
  Additionally, you can safely experiment with new ideas in a contained area of your repository
 
-------------

Definitions: 

Branch - Branches allow you to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository

Clone - You can clone a repository from GitHub.com to your local computer to make it easier to fix merge conflicts, add or remove files, and push larger commits.

Commit - A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when.

Fetch - In review, git fetch is a primary command used to download contents from a remote repository

GIT - Git is a distributed version control system that tracks changes in any set of computer files

Github - GitHub is a distributed version-control platform where users can collaborate on or adopt open source code projects, fork code, share ideas and more.

Merge - Merging is Git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch.

Merge Conflict - Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge

Push - The git push command is used to upload local repository content to a remote repository.

Pull - Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub.

Remote - A remote URL is Git's fancy way of saying "the place where your code is stored."

Repository - A repository contains all of your project's files and each file's revision history.




Sources: 

[1] IntroToGitHub-20190318.pptx

[2] https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html#ws_getting_started_open_project

[3] https://www.atlassian.com/git/tutorials/syncing/git-fetch
