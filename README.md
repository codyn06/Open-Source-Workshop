# Open Source Workshop

A hands-on introductory workshop to contributing to open source projects!

By the end of this workshop you will have forked a repository, made a change on your own branch, and opened your first pull request.

## Quick Start

1. [Install the prerequisites](#prerequisites)
2. [Set up your fork](#setup)
3. Follow [CONTRIBUTING.md](CONTRIBUTING.md) to make your first contribution

## Prerequisites

### Git

1. Download and install [Git](https://git-scm.com/install/). Make sure Git is added to your PATH.
2. Create a [GitHub](https://github.com/signup) account using your personal email.
3. Open Bash (Git Bash on Windows, Terminal on macOS/Linux) and tell Git who you are:

   ```bash
   git config --global user.name "YourUsername"
   git config --global user.email "YourEmail@example.com"
   ```

### VS Code

1. Download and install [VS Code](https://code.visualstudio.com/download).
2. Sign in to your GitHub account in VS Code.

## Setup

### 1. Fork the repository

[Fork this repository](https://github.com/ufosc/Open-Source-Workshop/fork) to your own GitHub account.

### 2. Clone your fork

1. Create a folder for your GitHub projects.
2. Open that folder in VS Code.
3. Open the VS Code terminal.
4. Clone your fork, replacing `your-username` with your GitHub username:

   ```bash
   git clone https://github.com/your-username/Open-Source-Workshop
   ```

5. Move into the cloned folder:

   ```bash
   cd Open-Source-Workshop/
   ```

### 3. Connect to the original repository (optional)

Adding an `upstream` remote lets you pull in updates from the original repository later:

```bash
git remote add upstream https://github.com/ufosc/Open-Source-Workshop.git

# Verify the connection (you should see both origin and upstream)
git remote -v
```

## Next Steps

You're set up! Head to [CONTRIBUTING.md](CONTRIBUTING.md) to find an issue and open your first pull request.

## License

See the [LICENSE](LICENSE) file for details.