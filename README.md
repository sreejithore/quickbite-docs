# QuickBite Docs 🍔📄

## 📌 Overview
QuickBite Docs is a collaborative documentation repository created as part of a Git workflow simulation at DevStream Technologies. The project demonstrates real-world version control practices using Git and GitHub, involving multiple contributors working across different environments.

---

## 🎯 Objective
The goal of this repository is to simulate a professional collaborative development workflow, including:
- Branching strategies
- Pull Requests (PRs)
- Code reviews
- Conflict resolution
- Multi-user collaboration

---

## 🧩 Project Structure
quickbite-docs/
│
├── README.md # Project overview
├── overview.md # Detailed project description
├── contributors.md # Contributors information
├── changelog.md # Project changes and updates

---

## 🚀 Workflow Followed

### 1. Repository Setup
- Created a GitHub repository
- Added collaborator access
- Configured `dev` as the default working branch

### 2. Feature Development
- Created feature branches:
  - `feature/project-overview`
  - `feature/contributors-list`
  - `feature/changelog`
- Each feature was developed independently

### 3. Pull Requests & Reviews
- PRs were created for every feature branch
- Reviews included:
  - Requested changes
  - Suggestions
  - Approval before merging

### 4. Conflict Resolution
- Simulated merge conflict in `changelog.md`
- Resolved manually by merging latest changes and editing conflicts

### 5. Release Management
- Final release branch: `release/v1.0`
- Merged into `main` after completion

---

## 👥 Contributors

| Name        | Role               | Environment        |
|------------|--------------------|--------------------|
| Account A  | Repository Owner   | Primary Machine    |
| Account B  | Collaborator       | WSL / VM           |

---
