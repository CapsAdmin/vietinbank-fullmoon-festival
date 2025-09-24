# 🚀 GitHub Pages Deployment Guide

## Quick Setup (5 minutes)

### Step 1: Create Repository
1. Go to [GitHub.com](https://github.com) and create a new repository
2. Name it anything you like (e.g., `moon-festival-invitation`)
3. Make sure it's **Public** (required for free GitHub Pages)
4. Don't initialize with README (you already have one)

### Step 2: Upload Files
1. Click "uploading an existing file"
2. Drag and drop all files from this folder:
   - `index.html`
   - `README.md`
   - `.gitignore`
   - All your image files (see IMAGE_REQUIREMENTS.md)

### Step 3: Enable GitHub Pages
1. Go to your repository Settings tab
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"

### Step 4: Access Your Site
Your invitation will be live at:
```
https://yourusername.github.io/repository-name
```

**Note**: It may take a few minutes for the site to become available.

## Custom Domain (Optional)

If you have your own domain:

1. Create a `CNAME` file in your repository with your domain name
2. In your domain's DNS settings, create a CNAME record pointing to `yourusername.github.io`
3. In GitHub Pages settings, enter your custom domain

## Troubleshooting

### Site Not Loading
- Wait 5-10 minutes after enabling Pages
- Check that all files uploaded correctly
- Verify repository is public
- Make sure `index.html` is in the root directory

### Images Not Showing
- Ensure all image files are uploaded
- Check image file names match exactly (case-sensitive)
- Verify images are in the same folder as `index.html`

### Font Not Loading
- The site uses Google Fonts (Cherry Bomb One)
- Make sure visitors have internet connection
- Font will fallback to Arial if unavailable

## Updates and Changes

To make changes:
1. Edit files directly on GitHub (click the pencil icon)
2. Or clone the repository, edit locally, and push changes
3. Changes will be live within minutes

---

**Need help?** Check the [GitHub Pages documentation](https://docs.github.com/en/pages)