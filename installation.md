---
layout: default
title: Installation Guide - Objett Co theme
---

# 📦 Objett Co theme - Installation Guide

Complete guide to installing and setting up the Objett Co Shopify theme.

## 📋 Table of Contents
- [Before You Begin](#before-you-begin)
- [Installation Methods](#installation-methods)
- [Initial Setup](#initial-setup)
- [Post-Installation Checklist](#post-installation-checklist)
- [Troubleshooting](#troubleshooting)

---

## Before You Begin

### Requirements

**Shopify Account:**
- Active Shopify store (any plan)
- Admin access to your store
- Basic familiarity with Shopify admin

**Technical Requirements:**
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection
- (Optional) Shopify CLI for development

**Recommended Before Installing:**
- Back up your current theme (if replacing an existing one)
- Have your logo and brand assets ready
- Prepare product images (minimum 2000px width)
- Have your color scheme/brand colors ready

### What's Included

When you download Objett Co theme, you get:
- ✅ Complete theme files (assets, sections, templates, etc.)
- ✅ 30+ customizable sections
- ✅ Multiple page templates
- ✅ 4 style presets
- ✅ Documentation files
- ✅ Example configurations

---

## Installation Methods

### Method 1: Upload via Shopify Admin (Recommended)

**Best for:** Most users, non-developers, quick setup

**Step-by-Step:**

1. **Download the Theme**
   - Download `maison-theme.zip` file
   - Do NOT unzip the file
   - Save it somewhere you can easily find it

2. **Access Your Shopify Admin**
   - Log in to your Shopify admin panel
   - URL format: `yourstore.myshopify.com/admin`

3. **Navigate to Themes**
   - Click **Online Store** in the left sidebar
   - Click **Themes**

4. **Upload Theme**
   - Scroll down to **Theme Library** section
   - Click **Upload theme** button
   - Click **Choose File**
   - Select the `maison-theme.zip` file
   - Click **Upload**

5. **Wait for Upload**
   - Upload typically takes 30-60 seconds
   - Don't close the browser during upload
   - You'll see a success message when complete

6. **Preview Before Publishing**
   - Click **Actions** on the uploaded theme
   - Click **Preview**
   - Browse your store to check everything looks good
   - Test on mobile view

7. **Publish Theme**
   - Click **Actions** on Objett Co theme
   - Click **Publish**
   - Confirm when prompted
   - Your new theme is now live! 🎉

**⏱️ Estimated Time:** 5-10 minutes

---

### Method 2: Using Shopify CLI (For Developers)

**Best for:** Developers, version control, local development

**Prerequisites:**
- Node.js 16+ installed
- Shopify CLI installed
- Git (optional but recommended)

**Step-by-Step:**

1. **Install Shopify CLI**
   ```bash
   npm install -g @shopify/cli @shopify/theme
   ```

2. **Extract Theme Files**
   ```bash
   unzip maison-theme.zip -d maison-theme
   cd maison-theme
   ```

3. **Authenticate with Shopify**
   ```bash
   shopify auth login
   ```

4. **Connect to Your Store**
   ```bash
   shopify theme push --store yourstore.myshopify.com
   ```

5. **Choose Push Option**
   - **Push to unpublished theme** (recommended for first install)
   - Or push to development theme
   - Or replace existing theme

6. **Verify Installation**
   ```bash
   shopify theme list
   ```

7. **Publish When Ready**
   - Go to Shopify Admin → Online Store → Themes
   - Find the uploaded theme
   - Click **Publish**

**⏱️ Estimated Time:** 10-15 minutes

---

### Method 3: Development Setup (Advanced)

**Best for:** Theme development, customization, testing

**Step-by-Step:**

1. **Set Up Local Environment**
   ```bash
   # Clone or extract theme
   cd maison-theme
   
   # Install dependencies (if any)
   npm install
   ```

2. **Start Development Server**
   ```bash
   shopify theme dev --store yourstore.myshopify.com
   ```

3. **Access Development Preview**
   - CLI will provide a local URL (e.g., `http://127.0.0.1:9292`)
   - Changes auto-sync to Shopify
   - Hot reload enabled

4. **Push to Shopify When Ready**
   ```bash
   shopify theme push --unpublished
   ```

**⏱️ Estimated Time:** 15-20 minutes

---

## Initial Setup

After installation, configure these essential settings.

### Step 1: Basic Theme Settings

1. Go to **Themes → Customize**
2. Click **Theme settings** (gear icon)
3. Configure:

**Typography:**
- Heading font: Choose your brand font
- Body font: Choose readable body font
- Recommended pairs:
  - Playfair Display + Inter
  - Cormorant + Work Sans
  - Fraunces + DM Sans

**Colors:**
- Choose a style preset (Linen, Noir, Sage, Atelier)
- Or customize each color individually
- Ensure 4.5:1 contrast ratio for accessibility

**Layout:**
- Container width: 1200-1400px recommended
- Section spacing: 60-80px recommended
- Border radius: 0-12px based on your aesthetic

4. Click **Save**

---

### Step 2: Upload Logo & Favicon

**Logo:**
1. Theme Settings → Logo
2. Upload logo image (PNG or SVG recommended)
3. Set logo width: 120-200px for desktop
4. Set mobile logo width: 100-150px

**Logo Specs:**
- Format: PNG (transparent) or SVG
- Minimum width: 200px (400px for retina)
- Maximum height: 80px recommended
- File size: Under 200KB

**Favicon:**
1. Theme Settings → Favicon
2. Upload 32x32px icon
3. Format: .ico, .png, or .jpg
4. Shows in browser tabs

---

### Step 3: Configure Navigation

**Main Menu:**
1. Go to **Online Store → Navigation**
2. Edit **Main menu**
3. Add essential links:
   - Shop (link to main collection)
   - Collections (with dropdown subcategories)
   - About
   - Journal/Blog
   - Contact

**Example Structure:**
```
Home
Shop
  ├─ New Arrivals
  ├─ Ceramics
  ├─ Textiles
  └─ Furniture
About
Journal
Contact
```

**Footer Menu:**
1. Create new menu: "Footer - Customer Care"
2. Add links:
   - Shipping & Returns
   - FAQ
   - Contact Us
   - Privacy Policy
   - Terms of Service

---

### Step 4: Set Up Homepage

1. In theme editor, select **Home** template
2. Add these sections:

**Recommended Homepage Structure:**

1. **Hero Section** - Welcome banner with CTA
2. **Featured Object** - Showcase signature product
3. **New Objects** - Latest products collection
4. **Material Story** - Brand/craft story
5. **Room Scene** - Lifestyle imagery (optional)
6. **Maker Story** - Feature artisan/maker (optional)
7. **Press Strip** - Media mentions

3. Configure each section's content
4. Reorder by dragging sections
5. Preview on mobile
6. Click **Save**

---

### Step 5: Configure Social Media

1. Theme Settings → Social Media
2. Add your profile URLs:
   - Instagram: `https://instagram.com/yourusername`
   - Facebook: `https://facebook.com/yourpage`
   - Pinterest: `https://pinterest.com/yourusername`
   - TikTok: `https://tiktok.com/@yourusername`
   - YouTube: `https://youtube.com/channel`
3. Click **Save**

Icons automatically appear in footer.

---

### Step 6: Create Essential Pages

Create these pages in **Online Store → Pages**:

**About Page:**
- Template: `page.about`
- Add: Hero, Story, Studio, Values sections
- Tell your brand story

**Contact Page:**
- Template: `page.contact`
- Includes contact form
- Add store hours, address, email

**FAQ Page:**
- Template: `page.faq`
- Add common questions in accordion format

**Policies:**
- Template: `page.policies`
- Add: Shipping, Returns, Privacy, Terms

---

## Post-Installation Checklist

Use this checklist to ensure everything is set up correctly.

### ✅ Theme Configuration
- [ ] Logo uploaded and sized correctly
- [ ] Favicon uploaded
- [ ] Fonts selected and applied
- [ ] Colors customized or preset applied
- [ ] Container width and spacing set

### ✅ Navigation
- [ ] Main menu created and linked
- [ ] Footer menus created
- [ ] All menu links work correctly
- [ ] Dropdown menus display properly

### ✅ Homepage
- [ ] Hero section configured with image/video
- [ ] Featured product added
- [ ] Collections linked
- [ ] All sections have content
- [ ] Mobile view checked

### ✅ Products
- [ ] Sample products added
- [ ] Product images uploaded (2000px+)
- [ ] Product descriptions written
- [ ] Variants configured
- [ ] Collections created and populated

### ✅ Pages
- [ ] About page created
- [ ] Contact page created
- [ ] FAQ page created
- [ ] Policy pages created
- [ ] All pages linked in navigation

### ✅ Settings
- [ ] Social media links added
- [ ] Newsletter signup enabled
- [ ] Payment methods configured
- [ ] Shipping zones set up
- [ ] Tax settings configured

### ✅ Testing
- [ ] Tested on desktop browser
- [ ] Tested on mobile device
- [ ] Tested tablet view
- [ ] Placed test order
- [ ] Checked email notifications
- [ ] Tested all navigation links
- [ ] Verified forms work
- [ ] Checked 404 page

### ✅ SEO & Marketing
- [ ] Page titles set
- [ ] Meta descriptions written
- [ ] Alt text added to images
- [ ] Google Analytics connected (optional)
- [ ] Facebook Pixel added (optional)

---

## Troubleshooting

### Theme Upload Issues

**"Upload failed" Error:**
- Check file is still zipped (don't unzip)
- File size under 50MB
- Stable internet connection
- Try different browser
- Clear browser cache

**"Invalid theme" Error:**
- Download theme again (may be corrupted)
- Ensure you have the complete theme package
- Check you're uploading the correct ZIP file

**Upload Stuck/Frozen:**
- Wait 5 minutes (large themes take time)
- Refresh page and check if theme appeared
- Try upload again if not present
- Check internet connection speed

---

### Theme Not Displaying Correctly

**Sections Missing Content:**
- Add content to each section in theme editor
- Check section visibility settings
- Ensure blocks are added to sections
- Save after each change

**Images Not Showing:**
- Check images are uploaded to Shopify Files
- Verify file format (JPG, PNG, GIF, WebP)
- Ensure file size under 20MB
- Check image URLs in section settings

**Fonts Not Loading:**
- Clear browser cache
- Check font selections in Theme Settings
- Try different font family
- Wait for Google Fonts to load

**Colors Not Changing:**
- Check you're editing active theme
- Save after color changes
- Clear browser cache
- Check for section color overrides

---

### Navigation Issues

**Menu Not Appearing:**
- Check menu is created in Navigation
- Verify menu is selected in Header settings
- Ensure menu has items added
- Check header visibility settings

**Dropdown Not Working:**
- Nest menu items properly (indent to right)
- Check JavaScript is enabled
- Clear browser cache
- Test in different browser

**Mobile Menu Not Opening:**
- Check on actual mobile device (not just browser resize)
- Clear mobile browser cache
- Try different mobile browser
- Check JavaScript errors in console

---

### Performance Issues

**Slow Loading Times:**
- Optimize images (compress before upload)
- Reduce sections on page (8-10 max recommended)
- Remove unused apps
- Enable lazy loading for images

**Theme Editor Slow:**
- Close other browser tabs
- Clear browser cache
- Use Chrome or Firefox
- Check internet connection
- Try editing one section at a time

---

### Getting Help

**Before Contacting Support:**
1. Check this troubleshooting guide
2. Search Shopify Help Center
3. Review theme documentation
4. Try different browser
5. Clear cache and cookies

**When Contacting Support:**

Include:
- Store URL
- Screenshots of issue
- Steps to reproduce
- Browser and device info
- Error messages
- What you've already tried

**Support Channels:**
- 📧 Email: mdhyder402@gmail.com
- 📖 Documentation: [GitHub Docs](https://github.com/mdhyder-cmd/maison-theme-docs)
- 💬 Shopify Support: [help.shopify.com](https://help.shopify.com)

---

## Next Steps

After installation:

1. **Read Full Documentation**
   - Customization Guide
   - Checkout Settings
   - Section Reference

2. **Add Your Products**
   - Upload high-quality images
   - Write detailed descriptions
   - Set up collections
   - Configure variants

3. **Customize Your Store**
   - Apply your brand colors
   - Add your content
   - Customize sections
   - Create custom pages

4. **Test Everything**
   - Place test orders
   - Check mobile experience
   - Test all forms
   - Verify email notifications

5. **Launch!**
   - Remove password protection
   - Announce to your audience
   - Share on social media
   - Start selling!

---

**🎉 Congratulations!** Your Objett Co theme is installed and ready to customize. Start building your beautiful online store!
