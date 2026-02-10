# Cloud Projects

## Resetting a User Password in Active Directory

1. Access the user management section in Active Directory.

2. Search for the user whose password needs to be reset (e.g., 'Bob Rich') and select the user from the list.

3. Right-click on the selected user and choose 'Reset Password' option from the menu.

4. Enter a new secure password for the user ensuring it meets security requirements.

5. A confirmation message will indicate that the password has been changed and you can now notify your user they can log in with new password.

---

## Pushing Your Project to GitHub

### Step 1: Create a new repository on GitHub
- Go to https://github.com/keenannkelly
- Click the green "New" button (or the "+" icon → "New repository")
- Name your repository (e.g., "cloud-projects" or whatever you'd like)
- Leave it empty (don't check "Initialize with README")
- Click "Create repository"

### Step 2: In your terminal, navigate to your project folder
```bash
cd /path/to/your/project
```

### Step 3: Initialize git and add your files
```bash
git init
git add .
git commit -m "Initial commit"
```

### Step 4: Connect to your GitHub repository
Replace `your-repo-name` with whatever you named it in Step 1:
```bash
git remote add origin https://github.com/keenannkelly/your-repo-name.git
git branch -M main
git push -u origin main
```

### Step 5: Enter your credentials
When prompted, enter:
- Username: `keenannkelly`
- Password: Your GitHub personal access token (not your actual password)

If you don't have a token yet:
- Go to https://github.com/settings/tokens
- Click "Generate new token" → "Generate new token (classic)"
- Give it a name, select "repo" scope
- Copy the token and use it as your password

Your project will be live at `https://github.com/keenannkelly/your-repo-name`
