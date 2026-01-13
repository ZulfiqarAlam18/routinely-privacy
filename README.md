# Routinely - Privacy & Legal Pages

This repository contains the privacy policy and account deletion pages for the **Routinely** habit tracking app, designed to be hosted on GitHub Pages.

## 📁 File Structure

```
routinely-privacy/
├── index.html           # Landing page with links to all pages
├── privacy-policy.html  # Full privacy policy
├── delete-account.html  # Account/data deletion instructions
├── styles.css           # Shared stylesheet
└── README.md            # This file
```

## 🚀 Deploy to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right and select **New repository**
3. Name your repository (e.g., `routinely-privacy` or `routinely`)
4. Set it to **Public** (required for GitHub Pages on free accounts)
5. Click **Create repository**

### Step 2: Upload Files

**Option A: Using GitHub Web Interface**
1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop all files from this folder (index.html, privacy-policy.html, delete-account.html, styles.css)
3. Add a commit message (e.g., "Add privacy pages")
4. Click **Commit changes**

**Option B: Using Git Command Line**
```bash
# Navigate to this folder
cd routinely-privacy

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Add privacy pages"

# Add your GitHub repository as remote (replace YOUR_USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/routinely-privacy.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (tab at the top)
3. Scroll down to **Pages** in the left sidebar (under "Code and automation")
4. Under **Source**, select **Deploy from a branch**
5. Under **Branch**, select **main** and **/ (root)**
6. Click **Save**

### Step 4: Access Your Site

After a few minutes, your site will be live at:
```
https://YOUR_USERNAME.github.io/routinely-privacy/
```

Your pages will be available at:
- **Home:** `https://YOUR_USERNAME.github.io/routinely-privacy/`
- **Privacy Policy:** `https://YOUR_USERNAME.github.io/routinely-privacy/privacy-policy.html`
- **Delete Account:** `https://YOUR_USERNAME.github.io/routinely-privacy/delete-account.html`

## ⚙️ Customization

### Update Contact Email
Replace `your-email@gmail.com` with your actual email address in:
- `privacy-policy.html` (2 occurrences)
- `delete-account.html` (2 occurrences)

### Update App Store Links (Optional)
If you want to add links to your app stores, edit `index.html` and add:
```html
<a href="YOUR_PLAY_STORE_LINK" class="btn">Get on Google Play</a>
<a href="YOUR_APP_STORE_LINK" class="btn">Get on App Store</a>
```

### Customize Colors
Edit `styles.css` and modify the gradient colors:
```css
/* Primary gradient - currently purple */
background: linear-gradient(135deg, #6366f1 0%, #8b5cf6 100%);
```

## 📱 Using with App Stores

When submitting your app to Google Play or Apple App Store, use these URLs:

- **Privacy Policy URL:** `https://YOUR_USERNAME.github.io/routinely-privacy/privacy-policy.html`
- **Data Deletion URL:** `https://YOUR_USERNAME.github.io/routinely-privacy/delete-account.html`

## 📄 License

This project is provided as-is for use with the Routinely app.

## 📧 Contact

For questions or support, contact: your-email@gmail.com
