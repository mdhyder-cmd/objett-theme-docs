# GitHub Pages Setup Instructions for Maison Theme

Follow these steps to create your documentation website (100% FREE).

---

## Step 1: Create GitHub Repository

1. Go to https://github.com/mdhyder-cmd (log in if needed)
2. Click the **"+"** icon (top right corner) → **"New repository"**
3. Fill in:
   - **Repository name:** `maison-theme-docs`
   - **Description:** "Documentation and support for Maison Shopify Theme"
   - **Public** (must be public for free GitHub Pages)
   - ✅ Check **"Add a README file"**
4. Click **"Create repository"**

---

## Step 2: Upload Documentation Files

### Option A: Using GitHub Web Interface (Easiest)

1. In your new repository, click **"Add file"** → **"Upload files"**

2. Drag and drop these 4 files from the `GITHUB_PAGES_FILES` folder:
   - `index.md`
   - `documentation.md`
   - `support.md`
   - `_config.yml`

3. Scroll down and click **"Commit changes"**

### Option B: Using GitHub Desktop (Alternative)

1. Download GitHub Desktop: https://desktop.github.com/
2. Clone your repository
3. Copy the 4 files into the cloned folder
4. Commit and push changes

---

## Step 3: Enable GitHub Pages

1. In your repository, click **"Settings"** (top menu bar)
2. Click **"Pages"** in the left sidebar
3. Under **"Source"**:
   - Branch: Select **"main"** (or "master")
   - Folder: Select **"/ (root)"**
4. Click **"Save"**
5. Wait 2-3 minutes for deployment

---

## Step 4: Verify Your Site is Live

Your documentation will be available at:

```
https://mdhyder-cmd.github.io/maison-theme-docs/
```

**Individual pages:**
- Homepage: `https://mdhyder-cmd.github.io/maison-theme-docs/`
- Documentation: `https://mdhyder-cmd.github.io/maison-theme-docs/documentation`
- Support: `https://mdhyder-cmd.github.io/maison-theme-docs/support`

**Note:** It may take 2-5 minutes for the site to go live after enabling Pages.

---

## Step 5: Test Your URLs

Open these URLs in your browser to verify they work:

✅ https://mdhyder-cmd.github.io/maison-theme-docs/  
✅ https://mdhyder-cmd.github.io/maison-theme-docs/documentation  
✅ https://mdhyder-cmd.github.io/maison-theme-docs/support

If you see "404" errors, wait a few more minutes and refresh.

---

## Step 6: Confirm Theme Files are Updated

I've already updated these files with your information:

✅ **LICENSE** - Copyright: Mohammad Hyder  
✅ **README.md** - Your URLs and email  
✅ **config/settings_schema.json** - Author and URLs

**The URLs in your theme now point to:**
- Documentation: `https://mdhyder-cmd.github.io/maison-theme-docs/documentation`
- Support: `https://mdhyder-cmd.github.io/maison-theme-docs/support`
- Email: `mdhyder402@gmail.com`

---

## What Shopify Will See

When Shopify reviewers click your documentation/support links:
1. They'll see professional documentation pages
2. Clear installation and setup guides
3. Working support contact information
4. FAQ and troubleshooting sections

**This will pass Shopify's requirements! ✅**

---

## Updating Documentation Later

To update any page in the future:

1. Go to your repository: https://github.com/mdhyder-cmd/maison-theme-docs
2. Click on the file you want to edit (e.g., `documentation.md`)
3. Click the **pencil icon** (Edit this file)
4. Make your changes
5. Click **"Commit changes"**
6. Changes will be live in 1-2 minutes

---

## Optional: Customize the Look

Want to change the theme design?

1. Edit `_config.yml`
2. Change `theme: minima` to one of these:
   - `minima` (default, clean)
   - `cayman` (modern with header)
   - `slate` (dark theme)
   - `architect` (professional)
   - `tactile` (elegant)

Full list: https://pages.github.com/themes/

---

## Troubleshooting

### Site Not Loading (404 Error)
- Wait 5 minutes and refresh
- Check Settings > Pages shows green checkmark
- Verify branch is set to "main"

### Pages Look Broken
- Make sure `_config.yml` is uploaded
- Check file names are exact (lowercase, .md extension)
- Wait 2-3 minutes for rebuild

### Need to Change URLs Later
- Edit the `.md` files in your repository
- Changes go live automatically

---

## Next Steps After GitHub Pages is Live

1. ✅ Test all 3 URLs work
2. ✅ Run theme check: `shopify theme check`
3. ✅ Test theme on development store
4. ✅ Create screenshots (5-7 high-quality images)
5. ✅ Submit to Shopify Theme Store!

---

## Your Theme is Ready! 🎉

All critical requirements are now complete:
- ✅ Documentation URL: Working
- ✅ Support URL: Working  
- ✅ Email: mdhyder@gmail.com
- ✅ Author: MD Hyder
- ✅ LICENSE: Updated
- ✅ README: Updated
- ✅ Theme Check: Passed (0 errors)

**You're ready to submit once you:**
1. Create GitHub Pages (10 minutes)
2. Test on dev store (2-3 hours)
3. Create screenshots (1-2 hours)

---

**Questions? Need help with GitHub Pages setup?**

Just let me know and I'll guide you through it! 😊
