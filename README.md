# Git & GitHub Cheat Sheet README

This repository contains a comprehensive cheat sheet covering essential Git commands and GitHub workflows. It's designed to be a helpful reference for beginners and students learning version control.

## Table of Contents

- [Getting Started](#getting-started)
- [Essential Git Commands](#essential-git-commands)
- [Collaboration](#collaboration)
  - [Git CLI and GitHub Integration](#git-cli-and-github-integration)
  - [Visual Studio Code and GitHub](#visual-studio-code-and-github)
  - [GitHub Desktop](#github-desktop)
- [Working in a Group](#working-in-a-group)
  - [Merge Conflicts](#merge-conflicts)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

This guide covers the essential steps to get started with Git and GitHub:

1. [Install Git](https://git-scm.com/downloads)
2. [Set Up Git](https://github.com/NirYakov/git-github-cheat-sheet#2-set-up-git)
3. [Create a GitHub Account](https://github.com/join)

## Essential Git Commands

The cheat sheet includes the following essential Git commands:

1. `git init`
2. `git add`
3. `git remote`
4. `git commit`
5. `git push`
6. `git pull`
7. `git clone`
8. `git status`

You can find detailed explanations and usage examples for each command in the cheat sheet.

## Collaboration

Collaborating on projects is a crucial part of software development. Git and GitHub provide several tools and integrations to streamline the collaboration process.

### Git CLI and GitHub Integration

The Git command-line interface (CLI) is the primary way to interact with Git repositories. You can use the Git CLI to perform all the essential Git operations, such as cloning, committing, and pushing changes.

To get started with the Git CLI, open a terminal (e.g., Git Bash on Windows) and follow the steps in the [Getting Started](#getting-started) section.

### Visual Studio Code and GitHub

Visual Studio Code (VS Code) is a popular code editor that integrates seamlessly with Git and GitHub. You can manage your Git repositories, view commit histories, and resolve merge conflicts directly within VS Code.

To use VS Code with Git and GitHub, follow these steps:

1. Install [Visual Studio Code](https://code.visualstudio.com/)
2. Install the [Git extension](https://marketplace.visualstudio.com/items?itemName=KnisterPeter.vscode-github/) for VS Code
3. Sign in to your GitHub account within VS Code

### GitHub Desktop

GitHub Desktop is a graphical user interface (GUI) application that provides an alternative to the command-line Git interface. It offers a user-friendly way to manage your Git repositories and interact with GitHub.

To use GitHub Desktop, follow these steps:

1. Download and install [GitHub Desktop](https://desktop.github.com/)
2. Sign in to your GitHub account within the app
3. Clone your repositories or create new ones using the GitHub Desktop interface

## Working in a Group

When working on a project with a team, it's essential to understand how to handle merge conflicts and collaborate effectively.

### Merge Conflicts

Merge conflicts occur when two or more people make changes to the same part of a file, and Git is unable to automatically resolve the differences. To resolve a merge conflict:

1. Identify the conflicting changes in the file
2. Decide which changes to keep and which to discard
3. Manually edit the file to resolve the conflict
4. Add the resolved file to the staging area using `git add`
5. Commit the resolved conflict using `git commit`

Refer to the [Git documentation](https://git-scm.com/docs/git-merge#_how_conflicts_are_presented) for more information on resolving merge conflicts.

## Hiding Unwanted Files with .gitignore

The `.gitignore` file is used to specify which files or directories should be ignored by Git. This is particularly useful when you have files that should not be tracked, such as:

- Compiled or generated files (e.g., `.class`, `.pyc`)
- Editor or IDE files (e.g., `.vscode`, `.idea`)
- Log files and temporary files
- Sensitive information (e.g., API keys, database passwords)

To create a `.gitignore` file, you can either manually create the file in the root of your project directory and add the relevant file patterns, or you can use GitHub's collection of [gitignore templates](https://github.com/github/gitignore) for various programming languages and frameworks.

Here's an example of a basic `.gitignore` file:

```
# Compiled output
dist/
tmp/
out-tsc/
bazel-out/

# Node
node_modules/
npm-debug.log
yarn-error.log

# Java
*.class
*.jar
*.war
*.ear
*.zip
*.tar.gz
*.rar

# Python
*.py[cod]
*$py.class

# macOS
.DS_Store
```

By adding these patterns to your `.gitignore` file, Git will automatically ignore these files and directories, preventing them from being tracked and committed to your repository. This is especially important for protecting sensitive information and keeping your repository organized and focused on the relevant project files.

## Contributing

We welcome contributions to this cheat sheet! If you find any errors, typos, or have suggestions for improvements, please feel free to submit an issue or a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
