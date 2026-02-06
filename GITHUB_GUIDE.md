# How to Push Your Portfolio to GitHub 🚀

It looks like **Git is not installed** on your computer. You need Git to push code to GitHub.

## Option 1: Automatic Install (Recommended)
I can try to install Git for you using the Windows Package Manager (Winget).
**Command to Run:**
```powershell
winget install --id Git.Git -e --source winget
```
*Note: You may need to restart your terminal (or VS Code) after installation.*

## Option 2: Manual Install
1. **Download**: Go to [git-scm.com/download/win](https://git-scm.com/download/win)
2. **Install**: Run the installer. You can click "Next" through all the default options.
3. **Restart**: Close and reopen VS Code to let it recognize Git.

---

## After Installing Git:

### Step 1: Configure Git (First time only)
Run these commands in your terminal (replacing with your details):
```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

### Step 2: Initialize & Commit
```bash
git init
git add .
git commit -m "Initial portfolio setup"
```

### Step 3: Connect to GitHub
1. Create a **New Repository** on GitHub (don't add README/gitignore yet).
2. Copy the **HTTPS URL** (e.g., `https://github.com/username/repo-name.git`).
3. Run these commands:
```bash
git branch -M main
git remote add origin YOUR_GITHUB_URL
git push -u origin main
```
