# How to Push Your Unity Project to GitHub (Browser/GUI Method)

## 🎯 Easiest Method: GitHub Desktop (No Command Line Needed!)

### Step 1: Download and Install GitHub Desktop

1. Go to: https://desktop.github.com/
2. Click "Download for Windows"
3. Install the application
4. Open GitHub Desktop and sign in with your GitHub account

### Step 2: Add Your Project to GitHub Desktop

1. In GitHub Desktop, click **File** → **Add Local Repository**
2. Click **Choose...** and navigate to: `C:\Users\ghuka\OneDrive\Desktop\2D-Platformer-Unity-main`
3. Click **Add repository**

### Step 3: Create Your First Commit

1. You'll see all your project files listed
2. At the bottom, type a commit message like: "Initial commit: 2D Platformer Unity project"
3. Click **Commit to main** (or the branch name shown)

### Step 4: Publish to GitHub

1. Click **Publish repository** button (top right)
2. Choose:
   - **Name**: Your repository name (e.g., "2D-Platformer-Unity")
   - **Description**: (Optional) Add a description
   - **Keep this code private**: Check if you want a private repo, or leave unchecked for public
3. Click **Publish Repository**

**Done!** Your project is now on GitHub! 🎉

---

## Alternative: Using GitHub Web Interface (Limited)

**Note:** GitHub's web interface doesn't support uploading entire folders. You can only upload individual files, which is not practical for Unity projects. Use GitHub Desktop instead (method above).

---

## Command Line Method (If You Prefer)

If you want to use command line instead:

```powershell
cd "C:\Users\ghuka\OneDrive\Desktop\2D-Platformer-Unity-main"
git init
git add .
git commit -m "Initial commit: 2D Platformer Unity project"
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
git branch -M main
git push -u origin main
```

## Important Notes:

- The `.gitignore` file will automatically exclude Library/, Temp/, Logs/, etc.
- GitHub Desktop handles all the Git commands for you - no need to learn command line!
- Your project files will be visible on GitHub after publishing

