# National Anthem App – Git & GitHub Workshop

## 1. Project Overview

The National Anthem App is a simple web application developed using Python and Flask. It displays the Indian National Anthem through a clean and user-friendly web interface.

This project was developed as part of a Git and GitHub workshop to practise version control, collaboration, branching, merging and conflict resolution.

## 2. Project Objectives

- Develop a simple web application using Flask.
- Understand Git version control.
- Practise creating and managing branches.
- Collaborate using GitHub.
- Understand pull requests and merging.
- Learn how to identify and resolve merge conflicts.
- Practise recovering files and undoing changes.

## 3. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Application programming |
| Flask | Web framework |
| HTML | Web page structure |
| CSS | Styling and layout |
| Git | Version control |
| GitHub | Repository hosting and collaboration |

## 4. Application Features

- Displays the Indian National Anthem.
- Uses a simple and readable interface.
- Includes the anthem's author attribution.
- Uses CSS for styling.
- Runs locally through a Flask development server.

## 5. Project Structure

```text
national-anthem-app/
│
├── app.py
├── anthem-draft.txt
├── requirements.txt
├── README.md
│
├── templates/
│   └── index.html
│
└── static/
    └── style.css
```

## 6. Installation and Execution

### Prerequisites

- Python 3
- Git
- A code editor
- Internet connection for installing dependencies

### Step 1: Clone the repository

```bash
git clone https://github.com/manasamahadi2006/national-anthem-app.git
```

### Step 2: Navigate to the project folder

```bash
cd national-anthem-app
```

### Step 3: Install dependencies

```bash
python -m pip install -r requirements.txt
```

### Step 4: Run the application

```bash
python app.py
```

### Step 5: Open the application

Visit the following address in your browser:

```text
http://127.0.0.1:5000
```

## 7. Team Members and Responsibilities

| Team Member | Role | Responsibility |
|---|---|---|
| Aditi | Team Lead | Coordinating the workflow and managing Git collaboration |
| Manasa | Developer | Developing and maintaining the application |
| Chandana | Tester | Reviewing and verifying application content |

## 8. Git and GitHub Workshop Exercises

The following exercises were practised as part of the workshop.

### 8.1 Repository Cloning

Cloned the remote GitHub repository to the local system.

```bash
git clone <git clone https://github.com/manasamt2006-beep/national-anthem-app.git>
```

### 8.2 Branch Creation

Created separate branches to practise working independently.

```bash
git switch -c feature-branch
```

### 8.3 Adding and Committing Changes

```bash
git add .
git commit -m "Add changes"
```

### 8.4 Branch Merging

Merged changes from one branch into another.

```bash
git switch main
git merge feature-branch
```

### 8.5 Merge Conflict Resolution

Created two branches with conflicting changes to the same file.

Git identified the conflict during merging. The conflicting content was manually resolved, staged and committed.

```bash
git add conflict.txt
git commit -m "Resolve merge conflict"
```

### 8.6 Push Exercise

Practised pushing a branch to a separate local bare Git remote and verified the pushed branch.

```bash
git push practice-remote conflict-one
git ls-remote practice-remote
```

This was a local practice remote, not the shared GitHub repository.

### 8.7 File Recovery

Practised restoring a deleted file using:

```bash
git restore recovery.txt
```

### 8.8 Undoing a Commit

Practised undoing an incorrect commit while preserving Git history.

```bash
git revert HEAD
```

## 9. Useful Git Commands

| Command | Description |
|---|---|
| `git status` | Checks the working tree |
| `git branch` | Lists branches |
| `git switch` | Switches branches |
| `git add` | Stages changes |
| `git commit` | Records changes |
| `git merge` | Merges branches |
| `git push` | Pushes commits to a remote |
| `git pull` | Fetches and integrates remote changes |
| `git log --oneline` | Displays commit history |
| `git restore` | Restores file changes |
| `git revert` | Creates a commit that reverses another commit |

## 10. Learning Outcomes

Through this workshop, the following concepts were practised:

- Understanding version control using Git.
- Managing branches and commits.
- Working with remote repositories.
- Understanding collaborative development through GitHub.
- Resolving merge conflicts.
- Recovering deleted files.
- Safely undoing commits.

## 11. Repository

GitHub Repository:

https://github.com/manasamahadi2006/national-anthem-app

---

Project: National Anthem App  
Workshop: Git and GitHub  
Framework: Flask
