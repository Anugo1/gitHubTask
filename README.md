# Task on git and version control

* Explain version control
* Explain difference between git and github
* List 3 other github alternative
* Explain the difference between git fetch and git pull
* Explain in simpler terms git rebase and the command for it 
* Explain in simpler terms git cherry-pick and the command for it 

## Version Control
Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter.

## Difference between Git and Github

| Git      |  Github    |
|:-|:-|
|Git is a software  | GitHub is hosted on the web  |
|  Git is a command-line tool   |  GitHub is a graphical user interface      |
|  Git is installed locally to the system    |  GitHub is hosted on the web       |

## 3 GitHub Alternatives
- **GitLab** **:** A web-based DevOps lifecycle tool that provides a Git repository manager with features such as issue tracking and CI/CD pipeline.
- **Bitbucket** **:**  A cloud-based version control system that offers unlimited private repositories, issue tracking, wiki, and pull requests.
- **Gitea** **:** A community-managed fork of Gogs, offering a similar set of features. It’s also lightweight and free, with an active community providing regular updates and support.

## Difference between git fetch and git pull
| git fetch | git pull |
|:-|:-|
| The Git Fetch command is used to fetch all changes from the remote repository to the local repository. It doesn’t make any changes to the current working directory. It stores all the changes in a separate branch called the remote-tracking branch. git merge or git rebase command is used to merge these changes into our current working directory.  | Git Pull command is used to fetch all changes from the remote repository to the current working directory. It automatically try to merge or rebase them into our current working directory. It is the combination of git fetch and git merge or git rebase. It can generate merge conflicts if there are conflict changes between our local and remote branches.  |
|**syntax** `git fetch [options] [<repository> [<refspec>...]] ` |**syntax** `git pull [options] [<repository> [<refspec>...]] `   |
## Git Rebase simply explained
**Git Rebase** is a way to update a branch (like a feature or bug fix) to match the latest changes from another branch (usually the main branch, called “master”). It’s like rewriting the history of your branch to make it look like it was created from a newer starting point.

### Syntax **:**`git rebase <base> [<branch>] `


## Git Cherry pick Simply Explained
**Git cherry pick** **:** git cherry-pick in git means choosing a commit from one branch and applying it to another branch. This is in contrast with other ways such as merge and rebases which normally apply many commits into another branch.

git cherry-pick is just like rebasing, an advanced concept and also a powerful command. It is mainly used if you don’t want to merge the whole branch and you want some of the commits.

### Syntax **:** ` git cherry-pick<commit-hash>`
