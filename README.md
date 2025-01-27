Git Version Control Workflow
Overview
Learn the basics of Git and GitHub by initializing a repo, staging/committing changes, working with branches, and pushing to GitHub.

Steps
Initialize Repository:
git init

Stage & Commit:
git add .
git commit -m "Initial commit"

Push to GitHub:
git remote add origin <repo-url>
git push -u origin main

Create & Push Branch:
git checkout -b develop
git push -u origin develop

Merge Branches:
git checkout main
git merge develop
git push origin main

GitHub Repo:
https://github.com/your-username/your-repo
