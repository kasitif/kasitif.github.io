# Quick Setup Guide

## Step 1: Create GitHub Repository

1. Go to [github.com](https://github.com) and log in
2. Click "+" icon → "New repository"
3. **Repository name:** `kasitif.github.io` (MUST match your username)
4. Make it **Public**
5. **Do NOT** initialize with README
6. Click "Create repository"

## Step 2: Upload Files

### Option A: Web Upload (Easiest)

1. On repository page, click "uploading an existing file"
2. Drag ALL files and folders from this directory
3. Commit message: "Initial commit"
4. Click "Commit changes"

### Option B: Git Command Line

```bash
cd path/to/kasitif.github.io
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/kasitif/kasitif.github.io.git
git push -u origin main
```

## Step 3: Add Your Files

### Required: Profile Photo
1. Go to repository → `images/` folder
2. Click "Add file" → "Upload files"
3. Upload your photo named `profile.jpg`
4. Size: 400x400 pixels
5. Commit changes

### Required: CV PDF
1. Go to repository → `files/` folder
2. Click "Add file" → "Upload files"
3. Upload your CV PDF named `cv.pdf`
4. Commit changes

## Step 4: Wait for Build

1. Go to repository Settings → Pages
2. GitHub Pages will be enabled automatically
3. Wait 2-5 minutes for site to build
4. Visit: **https://kasitif.github.io**

## Done! 🎉

Your site is now live with:
- ✅ Professional sidebar layout (like Shubham's site)
- ✅ Bio, Publications, CV, Consultancy, Projects pages
- ✅ Responsive mobile design
- ✅ SEO optimized

## Customization

### Update Your Info

Edit `_config.yml`:
```yaml
author:
  name: "Your Name"
  bio: "Your title"
  location: "Your Location"
  email: "your.email@example.com"
  googlescholar: "your-scholar-url"
  github: "your-github"
  linkedin: "your-linkedin"
```

### Modify Pages

Edit files in `_pages/`:
- `about.md` - Bio page
- `cv.md` - CV
- `publications.md` - Publications
- `consultancy.md` - Consultancy
- `projects.md` - Projects

### Change Navigation

Edit `_data/navigation.yml` to add/remove menu items.

## Troubleshooting

### Site Not Building

1. Check Actions tab for build errors
2. Verify all file names are correct
3. Check `_config.yml` syntax

### Images Not Showing

1. Ensure file is named exactly `profile.jpg`
2. Check it's in `images/` folder
3. Wait 2 minutes after upload

## Need Help?

- [Academic Pages Docs](https://github.com/academicpages/academicpages.github.io)
- [GitHub Pages Help](https://docs.github.com/en/pages)

---

**Total Time:** ~5 minutes to deploy!
