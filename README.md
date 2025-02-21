# A02
# WebStorm Tutorial

1. Downloaded and Install WebStorm from https://www.jetbrains.com/community/education/#students/ or https://www.jetbrains.com/webstorm/ (Choosing necessary OS as needed)
2. Download and Install Git from https://git-scm.com/downloads (Choosing necessary OS as needed)
3. Create a github account at https://github.com/join if you don't already have one
4. Opening WebStorm press (Ctrl+Alt+S) to open System Preferences
5. Select Version control Git. Enter the path to the git.exe (if its not already there)
6. Under System Preferences again, Select Appearance and Behavior -> System Settings -> Passwords. Add a location for the password folder and then click okay.
7. On Github.com, Click the + sign in the upper right corner and choose “Create New repository”
8. Make sure the repository is set to public and to generate a readme file.
9. You can also create a new repository in WebStorm. Click New Project -> Check Create Git Repository -> Create
10. To clone a repository, click the clone repository button on the main page. Insert the URL to the repository and click clone
11. After cloning a repository or making a new one, go to File -> New -> HTML File. (WebStorm may prompt you to add it to Git. You can do it this way or a manual way later on.)
12. To add manually, right click anywhere in the HTML file and go to Git -> Add.
13. To commit your changes, right click, go to Git -> Commit
14. To push, go to Git -> Push
15. Now that the file is on Github, go to the repository you're working in and click settings. Check the repository name
16. Now select master branch and take note of URL given.
17. Copy the url into your browser and see your site.


# Definitions

Branch - A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes.

Clone - A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.

Commit - A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.

Fetch - When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them. Unlike git pull, fetching allows you to review changes before committing them to your local branch.

GIT - GIT is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.

Github - GitHub Apps provide a service to an entire organization and use their own identity when performing their function. They can be installed directly on organizations and user accounts and granted access to specific repositories. They come with granular permissions and built-in webhooks.

Merge - Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.

Merge Conflict - A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.

Push - To push means to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.

Pull - Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. See also fetch.

Remote - This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.

Repository - A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.

# Sources
Arthur H. Hendela. "Introduction to Github and Webstorm." (Powerpoint Shared in Canvas)

“GitHub Glossary - GitHub Docs.” GitHub Docs, docs.github.com/en/get-started/learning-about-github/github-glossary.
