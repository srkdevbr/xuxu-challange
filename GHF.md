# GitHub Foundations Exam Study Guide

## Domain 1: Introduction to Git and GitHub

### Git and GitHub Basics

#### Describe Version Control
Version control is a system that records changes to files over time so that you can recall specific versions later.

#### Define Distributed Version Control
Distributed version control systems (DVCS) like Git allow every contributor to have a full copy of the repository.

#### Describe Git
Git is a distributed version control system that tracks changes in source code during development.

#### Describe GitHub
GitHub is a web-based platform built around Git, offering collaboration tools and repository hosting.

#### Explain the Difference Between Git and GitHub
Git is the version control tool; GitHub is the cloud platform that hosts Git repositories.

#### Describe a GitHub Repository
A repository is a storage space for code, including history, branches, and collaboration tools.

#### Describe a Commit
A commit is a snapshot of code at a point in time, with a message and metadata.

#### Describe Branching
Branching allows independent development from the main codebase.

#### Define a Remote in Git Terminology
A remote is a hosted version of the repository, usually on GitHub.

#### Describe the GitHub Flow
A simple process: branch → commit → pull request → review → merge → deploy.

### GitHub Entities

#### GitHub Accounts
- Personal: individual users.
- Organization: for team collaboration.
- Enterprise: advanced management for large orgs.

#### GitHub Products for Personal Accounts
- Free: unlimited private/public repos.
- Pro: advanced tools and insights.

#### GitHub Products for Organizations
- Free for orgs: core features.
- Team: adds roles and permissions.

#### GitHub Enterprise Deployment Options
- Enterprise Cloud
- Enterprise Server

#### User Profile Features
Includes metadata, achievements, profile README, pinned repos, and stars.

### GitHub Markdown

#### Text Formatting Toolbar
Used in issues and PRs for formatting with buttons.

#### Markdown Basics
- `#` for headings
- `**bold**`, `*italic*`
- `-` lists, `[link](url)`
- Checkboxes: `- [ ]`
- Comments: `<!-- comment -->`

#### Slash Commands
Like `/assign`, `/label` to automate actions.

### GitHub Desktop

#### GitHub Desktop vs GitHub.com
Desktop is a GUI for Git; GitHub.com is the web interface.

#### GitHub Desktop Features
Clone, commit, push, create branches, resolve conflicts.

### GitHub Mobile

#### GitHub Mobile Features
Manage PRs, issues, notifications on mobile.

#### Notification Management
Push settings, custom subscriptions, thread control.

---

## Domain 2: Working with GitHub Repositories

### Understanding Repositories

#### Good README and Recommended Files
- `README.md`
- `LICENSE`
- `CONTRIBUTING.md`
- `CODEOWNERS`

#### Navigation
Tabs: Code, Issues, PRs, Actions, Insights.

#### Creating a New Repository
Via the “New” button, define name, privacy, and README.

#### Repository Templates
Pre-configured structure to bootstrap new projects.

#### Maintenance Features
Branch protection, labels, automation, review rules.

#### Cloning a Repository
`git clone https://...`

#### Creating a Branch
`git checkout -b feature-branch`

#### Adding Files
Via upload or terminal with `git add`, `git commit`.

#### Viewing Insights
Insights tab: contributors, commits, PR stats, traffic.

#### Starring Repositories
Click ⭐ to bookmark.

#### Feature Previews
Found in user settings → try beta features.

---

## Domain 3: Collaboration Features

### Issues

#### Link a PR to an Issue
Use `Closes #123` in PR description.

#### Create an Issue
Click “New Issue” in the repo, fill form.

#### Issue vs Discussion vs Pull Request
Issues: tasks. Discussions: general chat. PRs: code proposals.

#### Create Branch from Issue
Option in sidebar or use `gh` CLI.

#### Assigning Issues
Use the sidebar to assign collaborators.

#### Search and Filter Issues
Use filters like `is:open` or `label:bug`.

#### Pin an Issue
Use the `...` menu to pin.

#### Issue Management
Use labels, milestones, assignees, locking, closing.

#### Templates vs Forms
Markdown templates vs interactive structured forms.

#### Keywords in Issues
`Fixes`, `Closes` auto-link and close issues on merge.

### Pull Requests

#### What is a PR
A proposal to merge code from one branch into another.

#### Creating a PR
Compare branches, fill in form, submit.

#### Base vs Compare
Base = destination; Compare = source.

#### Commits in a PR
All commits from compare branch are included.

#### Draft PRs
Marked as “work in progress.”

#### PR Tabs
Conversation, Commits, Checks, Files changed.

#### Linking Activity
Mention issues, PRs, commits using `#` or SHA.

#### PR Statuses
Open, Closed, Merged, Approved, Changes Requested.

#### Commenting on Code
Click `+` on code lines in “Files Changed.”

#### Code Review with CODEOWNERS
Automatically assigns reviewers by file ownership.

#### Review Options
Comment, Approve, Request Changes, Suggested Changes.

### Discussions

#### Discussion vs Issue
Discussion = informal or open-ended. Issue = actionable.

#### Types of Discussions
Ideas, Q&A, Show and Tell, Polls, Announcements.

#### Marking Answers
In Q&A, mark a comment as answer.

#### Convert to Issue
Convert discussion comment to an issue.

#### Pinning a Discussion
Pin important discussions to top of tab.

### Notifications

#### Managing Subscriptions
Customize in Settings → Notifications.

#### Subscribing to Threads
Click “Subscribe” on issues, PRs, discussions.

#### @mentions
View in notifications panel → Participating/@mentioned.

#### Filtering
By repo, reason, read/unread.

#### Config Options
Push/email, watch levels (all, participating, ignore).

### Gists, Wikis, GitHub Pages

#### Gists
Quick code snippets, public or secret.

#### Fork and Clone Gists
Like repos: `git clone https://gist.github.com/...`

#### Wikis
Version-controlled project documentation.

#### Managing Wiki Pages
Create/edit/delete via Wiki tab.

#### Wiki Visibility
Public if repo is public. Private for private repos.

#### GitHub Pages
Static site hosting from repo content.

---

## Domain 4: Modern Development

### GitHub Actions

#### What is GitHub Actions
Automation and CI/CD platform on GitHub.

#### Events
Push, PR, issue, schedule, workflow_dispatch, etc.

#### Finding Actions
Use GitHub Marketplace to explore existing ones.

### GitHub Copilot

#### What is Copilot
AI code completion from GitHub + OpenAI.

#### Individual vs Business
Business includes admin controls, telemetry settings.

#### Getting Started
Install extension, login, enable in settings.

### GitHub Codespaces

#### What is Codespaces
Cloud-based, containerized dev environment.

#### Start a Codespace
Open repo → Code → New Codespace.

#### Lifecycle
Create → Start → Suspend → Delete.

#### Customizations
Dotfiles, themes, extensions, preinstalled tools.

#### Dev Containers
Define env with `.devcontainer/devcontainer.json`.

#### Share Deep Link
Click Share to copy URL to state or file.

#### github.dev Editor
Press `.` on any repo to launch editor.

#### github.dev vs Codespaces

| Feature        | github.dev         | Codespaces             |
|----------------|--------------------|-------------------------|
| Backend        | No (read-only)     | Yes (full env)         |
| Runtime        | No execution       | Code can run           |
| Customization  | Limited            | Full dev containers    |
| Cost           | Free               | Billed by usage        |

---

## Domain 5: Project Management

### GitHub Projects

#### What are Projects
Track and organize work using boards/tables.

#### Layouts
Board, Table, Roadmap (beta).

#### Config Options
Fields, filters, grouping, automation.

#### Projects vs Projects Classic
Classic = fixed columns. New = flexible, powerful.

#### Labels
Used to categorize issues/PRs.

#### Milestones
Group work toward a deadline or release.

#### Template Repos
Used to scaffold new projects.

#### Saved Replies
Reusable comment snippets for fast responses.

#### Adding Assignees
Sidebar → Assignees section.

#### Workflows in Projects
Automate field changes and card movement.

#### Project Insights
Progress bars, burnup charts, activity stats.

---

## Domain 6: Privacy, Security, Administration

### Authentication and Security

#### 2FA
Adds second verification step to login.

#### Access Permissions
Read, Triage, Write, Maintain, Admin.

#### EMUs
Enterprise-managed users tied to identity providers.

### GitHub Administration

#### Enabling/Disabling Features
In Settings → toggle features like Issues, Pages.

#### Permission Levels
From Read to Admin — fine-grained control.

#### Repo Visibility
Public, Private, Internal (enterprise).

#### Branch Protections and Security Settings
CODEOWNERS, review requirements, disallow force pushes.

#### Security Tab
Dependency graph, scanning, alerts.

#### Repository Insights
Trends, stats, health metrics.

#### Collaborators
Invite users, assign roles, manage access.

---

## Domain 7: Benefits of the GitHub Community

### Open Source and Community

#### Benefits
Community review, innovation, visibility, shared knowledge.

#### What is Open Source
Public code with permissive licensing.

#### GitHub Sponsors
Donate to devs. GitHub covers fees.

#### Advancing Open Source
Tools like Actions, Sponsors, Code scanning.

#### Following People and Orgs
Track updates and discover repos.

### GitHub Marketplace

#### What is Marketplace
Installable apps and tools that extend GitHub.

### InnerSource

#### What is InnerSource
Using open source methods internally.

#### InnerSource vs Open Source

| Aspect       | Open Source   | InnerSource     |
|--------------|----------------|------------------|
| Visibility   | Public         | Private          |
| Access       | Anyone         | Org members      |
| License      | OSS licenses   | None needed      |

### Repos and Contribution Tools

#### Forking
Creates copy of repo to your account.

#### Discoverable Repos
README, LICENSE, CONTRIBUTING, tags, metadata.

#### Issue & PR Templates
Structure user input and code submissions.

### Organization Management

#### Org Settings
Manage members, integrations, billing, security.

#### Members, Teams, Roles
Member, Owner, Team Maintainer.

---
