# Git GitHub

**Presentation:**
https://drive.google.com/file/d/1MTObsdv6AF4H033OSn1_UAgK_uYXijz_/view?usp=sharing

**Development and Release Flow for Trunk-Based Development:**
https://youtu.be/t_4lLR6F_yk?t=324

## Practice Git Clone

1. Clone the project https://github.com/mrtsfn601/gitproject using HTTPS, SSH, and GitHub CLI (optional).

## Practice Git Workflow

**Part 1**
1. Create in GitHUb a new repo https://github.com/new.
1. Create in IntelliJ a new maven project from `maven-archetype-quickstart` archetype.
2. Initialize an empty git local repo `git init`.
3. Create and switch to a new branch `git checkout -b us1`.
4. Make any changes to your maven project.
5. Add and commit changes to the local repo `git add -A` `git commit -m "Initial commit"`.
6. Push your code to the remote main branch (checkin) `git remote add origin git@github.com:your-github-username/project-name.git` `git branch -M main` `git push -u origin main` (please replace `your-github-username/project-name` with respective information).

**Part 2**
1. Pull the recent code from remote main to your local main branch `git pull origin main`.
2. Create and switch to a new branch `git checkout -b us2`.
3. Make any changes to your maven project.
4. Add and commit changes to the local repo `git add -A` `git commit -m "your-message"` (messages should be meaningful).
5. Push your code to the remote us2 branch (checkin) `git push origin us2`.
6. Create a pull request (PR), post a comment (PR review, feedback).
7. Merge your us2 branch to the main branch.
8. Delete your local branches `git branch -d us1` `git branch -d us2`.
9. Delete your remote branches.

**Part 3**
* Create your own scenarios.
* Upload your local projects to your remote repository (private repo mode is preferred).
* Work on your Java-Selenium project, commit and push your changes often, create new branches, etc.