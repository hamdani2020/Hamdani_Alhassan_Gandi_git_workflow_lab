# Git Workflow Strategy Lab

This repository demonstrates the implementation of a Git Workflow Strategy, focusing on managing multiple branches for feature development, releases, ang hotfixes in a produciton environment.


## Project Overview
The Git Workflow Strategy utilizes two primary long-lived branches (`main` and `development`) along with supporting branches to organize different aspects of development work:
- Main Branch: Contains production-ready code
- Development Branch: houses ongoing development and feature integration
- Supporting Branches:
	- Feature Branches: for developing new features
	- Release Branches: for preparing new releases
	- Hotfix Branches: for addressing critical issues in produciton

## Prerequisites
- Git install on your local machine
- GitHub account
- Basic understanding of Git commands and GitHub operations

## Project Structure

```
<fullname>_git_workflow_lab/
├── main.txt              # Production code file
├── security_feature.txt  # Security feature implementation
└── README.md            # Project documentation
```

