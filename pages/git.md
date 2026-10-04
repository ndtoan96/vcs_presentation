---
layout: image-right
image: '/images/GitKraken.png'
---

# Version control system
## git - overview

- `git` is a free and open source **distributed version control system** designed to handle everything from small to very large projects with speed and efficiency.

- `git` is lightning fast and has a huge ecosystem of GUIs, hosting services, and command-line tools.

---
layout: default
---

# Version control system
## git - Concepts

### Storage & Workspaces

- **Repository (Repo)**: The storage location containing all project files, history, and configuration.
- **Working Directory (Working Tree)**: The local filesystem where you actively edit, create, or delete files.
- **Staging Area (Index)**: An intermediate preview area. Changes added here (via `git add`) are prepped to be recorded into the next commit.

---

### History & Branching

- **Commit**: A lightweight snapshot of your project's state at a specific point in time, identified by a unique SHA-1 hash.
- **Branch**: A movable pointer pointing to a specific commit, representing an independent line of development (e.g., main, feature/login).
- **HEAD**: A special reference pointer indicating the current branch or commit you are currently working on.
- **Tag**: A fixed pointer attached to a specific commit, typically used to mark release milestones (e.g., v1.0.0, v2.1.0-beta).
- **Stash**: A temporary shelf where you can safely save uncommitted, ongoing changes so you can switch branches without losing your work.

---
layout: two-cols-header
---

# Version control system
## git - Commonly used commands

::left::

**Repository**:
- `git init`: Initialize repository
- `git clone`: Clone a remote repository

**Change**:
- `git add`: Stage the changes
- `git commit`: Record changes to the repository

**History & state**
- `git status`: Show the working tree status
- `git log`: Show commit logs
- `git checkout`: Restore working tree to a specific commit

::right::

**Branch**:
- `git switch`: Switch branches
- `git branch`: List, create, delete branches

**Collaborate**:
- `git pull`: Download changes from remote repository
- `git push`: Push changes to remote repository

---
layout: statement
---

# Demo