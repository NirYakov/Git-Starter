# Git & GitHub Command Cheat Sheet

This guide covers essential Git commands to help you get started with version control in Git and GitHub.

---

## Getting Started with Git

### 1. Install Git

- **Download**: Download the latest version of Git for Windows from [git-scm.com](https://git-scm.com).
- **Install**: Run the installer and follow the setup steps. The default options work well for most users, but you can customize them if needed.
- **Open Git Bash**: After installation, open the Git Bash terminal, which provides a command-line interface for Git on Windows.

### 2. Set Up Git

- **Configure Username and Email**: Open Git Bash and enter the following commands to set your name and email. These settings are required for tracking your commits.

  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "your-email@example.com"
  ```

### 3. Create a GitHub Account (if needed)

- **Sign Up**: Visit [GitHub](https://github.com/) and create an account if you don't already have one. Verify your email address.
- **Repository Types**: GitHub offers both public and private repositories, so you can manage who can view your code.

---

## Essential Git Commands

### 1. **git init**

**Description:** Initializes a new Git repository in your project folder.
**Usage:**

```bash
git init
```

**Example:** Run this in a project directory to start tracking files with Git.

### 2. **git add**

**Description:** Prepares changes (new files, modifications, or deletions) for the next commit.
**Usage:**

```bash
git add <file>
```

To add all changes:

```bash
git add .
```

**Example:** `git add index.html` stages `index.html` for the next commit.

### 3. **git remote**

**Description:** Links your local repository to a remote one, such as a repository on GitHub.
**Usage:**

```bash
git remote add origin https://github.com/username/repo-name.git
```

**Example:** Use this command to add a remote repository with the name `origin` (a common default).

### 4. **git commit**

**Description:** Records changes to the repository with a message describing the changes.
**Usage:**

```bash
git commit -m "Your commit message"
```

**Example:** `git commit -m "Added new feature"` commits your changes with a descriptive message.

### 5. **git push**

**Description:** Sends your committed changes to the remote repository.
**Usage:**

```bash
git push origin main
```

**Example:** `git push origin main` pushes changes from your local `main` branch to GitHub.

### 6. **git pull**

**Description:** Updates your local branch with changes from the corresponding branch on the remote repository.
**Usage:**

```bash
git pull origin main
```

**Example:** `git pull origin main` fetches and merges changes from the `main` branch on GitHub into your local branch.

### 7. **git clone**

**Description:** Creates a local copy of a remote repository.
**Usage:**

```bash
git clone https://github.com/username/repo-name.git
```

**Example:** `git clone https://github.com/username/repo-name.git` clones the repository from GitHub to your computer.

### 8. **git status**

**Description:** Displays the status of the working directory and staging area, showing which files are modified, staged, or untracked.
**Usage:**

```bash
git status
```

**Example:** Run `git status` to view any uncommitted changes or newly added files in the repository.

---

## References

### AI:

- Claude
- ChatGPT

### Websites:

- [Git Documentation](https://git-scm.com/docs)
- [Atlassian Git Glossary](https://www.atlassian.com/git/glossary#commands)
- [GitHub Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

This cheat sheet should help you navigate basic Git commands and workflows. Happy coding!
