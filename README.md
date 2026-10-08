
# Open Source Workshop
A hands-on introductory workshop to contributing to open source projects!

## Prerequisites
### Git
1. Download [Git](https://git-scm.com/install/) onto your device. Ensure you add Git to your PATH.
2. Create a [GitHub](https://github.com/signup) account. Use your personal email.
3. Open Bash and run these commands:
```
git config --global user.name "YourUsername"
git config --global user.email "YourEmail@example.com"
```
### VS Code
1. Download [VS Code](https://code.visualstudio.com/download?_exp_download=fb315fc982) onto your device.
2. Login to your GitHub account on VS Code.

### Python
1. Download the latest version of [Python](https://www.python.org/downloads/) onto your device.

## Setup
### Cloning the Repository
1. [Fork](https://github.com/ufosc/Open-Source-Workshop/fork) this GitHub repository.
2. Create a directory for GitHub repositories.
3. Open the directory you created for GitHub repositories in VS Code.
4. Open the terminal in VS Code.
5. Clone your forked repository:
```
// replace "your-username" with your username
git clone https://github.com/your-username/Open-Source-Workshop
```
6. Navigate to the cloned directory:
```
cd Open-Source-Workshop/
```
7. Optional: connect the fork to the original repository:
```
git remote add upstream https://github.com/ufosc/Open-Source-Workshop.git
// Verify remote connection
git remote -v
```
