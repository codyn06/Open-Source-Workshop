# Contributing to Open Source Workshop

Thanks for contributing! This workshop is for first-time contributors, so no experience is needed. Follow the steps below to make your first open source contribution.

## 1. Find an Issue

All contributions start on the [Issues page](https://github.com/ufosc/Open-Source-Workshop/issues).

1. Browse the open issues and pick one that interests you.

> **Note:** In most real-world projects, you should comment on an issue to claim it and wait for a maintainer to assign it to you before starting work. This prevents two people from doing the same task. We skip that step for this workshop, but it's standard practice, so get in the habit when contributing elsewhere.

## 2. Fork and Clone

See the [README](README.md) for full setup instructions. In short:

```bash
# Fork the repo on GitHub first, then clone your fork (replace your-username)
git clone https://github.com/your-username/Open-Source-Workshop.git
cd Open-Source-Workshop

# Optional: connect to the original repo to pull in updates
git remote add upstream https://github.com/ufosc/Open-Source-Workshop.git
```

## 3. Create a Branch

Don't work directly on `main`. Create a branch for your change:

```bash
git checkout -b your-branch-name
```

## 4. Commit and Push Your Changes

Keep your change small and focused on the issue you picked. Then commit with a short, clear message and push your branch to your fork:

```bash
git add .
git commit -m "Short description of your change"
git push origin your-branch-name
```

## 5. Open a Pull Request

1. Go to your fork on GitHub and click **Compare & pull request**.
2. Write a short description of what you changed.
3. Link the issue by adding `Closes #123` (use your issue's number) to the description. GitHub will close the issue automatically when your PR is merged.

A maintainer will review your pull request. They may leave feedback. Push more commits to the same branch to update it.

## 6. Update Your Main Branch

Once your pull request has been merged, bring those changes into your own `main` branch so it's up to date for your next contribution.

### Option A: Sync with the original repo (recommended)

Your changes are now part of the original repository's `main`, so pull them down from `upstream`. This requires the `upstream` remote from the README setup.

```bash
git checkout main
git fetch upstream
git merge upstream/main
git push origin main
```

### Option B: Merge your branch into main yourself

If you want your branch's changes in your own `main` directly:

```bash
git checkout main
git merge your-branch-name
git push origin main
```

> **Note:** Option B only matches the original repo if your PR was merged as-is. If the maintainers changed your commits or squashed them, your `main` can drift from the original. Use Option A when in doubt.

### Clean up

Once your changes are in `main`, you can delete the branch:

```bash
git branch -d your-branch-name              # delete locally
git push origin --delete your-branch-name   # delete from your fork
```

## Need Help?

Comment on your issue or ask a facilitator. There are no silly questions, and everyone here started as a beginner.