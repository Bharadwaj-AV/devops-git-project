# DevOps Git Project

## 📌 Objective
This project is built to demonstrate Git version control best practices in a DevOps context. It uses Git and GitHub for project tracking, collaboration, and release management.

## 🛠️ Tools Used
- Git
- GitHub
- EC2 (Amazon Linux) as development environment

## 📁 Branch Strategy
- `main`: Stable and production-ready code
- `dev`: Integration branch for tested features
- `feature/*`: Feature development branches

## 🔀 Git Workflow
1. Code is developed in `feature/*` branches.
2. Pull Requests (PRs) are created to merge `feature` → `dev`.
3. After testing, `dev` is merged into `main`.
4. Tags are used to mark releases.

## 🧾 Files Included
- `README.md`: Project overview
- `.gitignore`: Ignored files and folders
- `TASKS.md`: Task documentation in markdown
- `script.sh`: Sample script created for demo

## 📦 Versioning
We follow semantic versioning using Git tags:  
- v1.0 – Initial working version  
- v1.1 – Additional features, fixes, etc.

## 🚀 Getting Started
Clone this repo and run the script:

```bash
git clone https://github.com/<your-username>/devops-git-project.git
cd devops-git-project
chmod +x script.sh
./script.sh

