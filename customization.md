---
layout: default
title: Customization Guide - Objett Co theme
---

# 🎨 Objett Co theme - Complete Customization Guide

Welcome to the Objett Co theme customization guide! This comprehensive guide will help you customize every aspect of your store without touching any code.

## 📋 Table of Contents
- [Getting Started](#getting-started)
- [Theme Settings](#theme-settings)
- [Customizing the Header](#customizing-the-header)
- [Customizing the Footer](#customizing-the-footer)
- [Working with Sections](#working-with-sections)
- [Style Presets](#style-presets)
- [Typography & Colors](#typography--colors)
- [Product Pages](#product-pages)
- [Collection Pages](#collection-pages)
- [Adding Social Media Links](#adding-social-media-links)
- [Advanced Customization](#advanced-customization)
- [Common Questions](#common-questions)

---

## Getting Started

### Accessing the Theme Editor

1. Log in to your **Shopify Admin** (`yourstore.myshopify.com/admin`)
2. Click **Online Store** in the left sidebar
3. Click **Themes**
4. Find your active theme (Maison) and click **Customize**

You're now in the Theme Editor where you can make all your customizations!

### Understanding the Interface

The Theme Editor has three main areas:
- **Left Sidebar**: Shows all sections and blocks you can customize
- **Center Preview**: Live preview of your store
- **Right Panel**: Settings for the selected section or theme settings
- **Top Bar**: Save, preview, and publish buttons

---

## Theme Settings

Access global theme settings that apply across your entire store.

### Accessing Theme Settings
1. In the Theme Editor, click the **⚙️ icon** in the top left
2. Or scroll to the bottom of the left sidebar and click **Theme settings**

### Available Theme Settings

#### Typography Settings
- **Heading font**: Choose from Google Fonts or Shopify's font library
- **Body font**: Set your body text font
- **Font size scale**: Adjust overall text sizing (80-120%)
- **Heading weight**: Control heading boldness
- **Body weight**: Control body text weight

#### Color Settings
- **Background color**: Main site background
- **Text color**: Primary text color
- **Secondary text**: Muted text color
- **Border color**: Lines and borders
- **Accent color**: Buttons and CTAs
- **Error color**: Error messages
- **Success color**: Success messages
- **Dark mode background**: For dark sections
- **Dark mode text**: Text on dark backgrounds

#### Layout Settings
- **Container width**: Maximum content width (1000-1600px)
- **Section spacing**: Padding between sections
- **Grid gap**: Space between grid items
- **Border radius**: Rounded corners (0-20px)

#### Cart Settings
- **Cart type**: Drawer (slide-out) or Page
- **Show free shipping bar**: Enable/disable progress bar
- **Free shipping threshold**: Amount needed for free shipping

#### Favicon
- Upload your 32x32px site icon (.png or .ico file)

---

## Customizing the Header

### Logo Configuration

**Using a Text Logo:**
1. In the Theme Editor, click **Header** section
2. Find **Logo text** setting
3. Type your store name
4. Adjust **Logo font size** if needed
5. Click **Save**

**Using an Image Logo:**
1. In the Theme Editor, click **Header** section
2. Find **Logo image** setting
3. Click **Select image** and upload your logo file (PNG or SVG recommended)
4. Adjust **Logo width** slider to resize (50-300px)
5. **Mobile logo width**: Separate sizing for mobile devices
6. Click **Save**

**Logo Tips:**
- Use PNG with transparent background for best results
- Minimum width: 200px for desktop, 150px for mobile
- SVG format is ideal for crisp rendering at any size
- Keep logo height under 80px for optimal header proportion

### Navigation Menu

The header navigation is controlled by menus in your Shopify admin.

**Step 1: Create or Edit Your Menu**
1. From your Shopify Admin, go to **Online Store → Navigation**
2. Look for **Main menu** (or create a new one)
3. Click on the menu name to edit it
4. Click **Add menu item** to add new links
   - **Name**: What customers will see (e.g., "Shop", "About")
   - **Link**: Destination (search for pages, collections, or paste URL)
5. Drag and drop to reorder items
6. **Create dropdowns**: Drag items slightly to the right to nest them under parent items
7. Click **Save menu**

**Step 2: Connect the Menu to Your Header**
1. Go back to the **Theme Editor**
2. Click on the **Header** section in the left sidebar
3. Find the **Menu** dropdown setting
4. Select your menu from the list
5. Click **Save**

### Header Settings

**Sticky Header**
- **Enable sticky header**: Header stays visible when scrolling
- **Sticky on mobile**: Enable/disable for mobile devices

**Transparent Header**
- **Transparent on homepage**: Makes header overlay hero section
- **Logo color on transparent**: Choose light or dark logo version

**Announcement Bar**
1. In the Header section, find **Announcement bar** block
2. Configure:
   - **Text**: Your announcement message
   - **Link**: Optional URL for click-through
   - **Background color**: Bar background
   - **Text color**: Text and icon colors
   - **Show close button**: Allow customers to dismiss
3. Click **Save**

### Search Settings
- **Show search icon**: Enable/disable search in header
- **Search placeholder**: Hint text in search box

### Cart Icon
- **Show cart icon**: Enable/disable cart in header  
- **Cart icon style**: Choose icon design
- **Show item count**: Display number of items in cart

---

## Customizing the Footer

The footer uses a flexible **block system** - you can add, remove, and rearrange sections easily!

### Footer Branding

**Logo & Text:**
1. In the Theme Editor, click **Footer** section
2. **Logo image**: Upload your footer logo (optional)
3. **Logo width**: Adjust size (50-200px)
4. **Brand name**: Text fallback if no logo image
5. **Tagline**: Short brand description
6. **Bottom tagline**: Secondary tagline at footer bottom

**Copyright:**
- **Copyright text**: Additional text (appears after "© 2026 Your Store")
- Automatically includes current year and store name

### Adding Footer Blocks

1. In the Theme Editor, scroll down and click **Footer** section
2. In the **Blocks** section, click **Add block**
3. Choose from these block types:
   - **Menu Column**: Display a list of links
   - **Newsletter**: Email signup form
   - **Text Block**: Custom text or information
   - **Contact Information**: Store address and contact details

### Menu Column Block

Perfect for "Customer Care", "Quick Links", "Shop" sections.

1. Add a **Menu Column** block
2. Configure:
   - **Heading**: Column title (e.g., "Customer Care", "Shop")
   - **Menu**: Select which menu to show (create menus in **Navigation**)
   - **Maximum links**: How many links to display (3-15)
3. Click **Save**

**Creating Footer Menus:**
1. Go to **Online Store → Navigation**
2. Click **Add menu**
3. Name it (e.g., "Footer - Customer Care")
4. Add menu items
5. Go back to Footer block and select this menu

### Newsletter Block

Collect email addresses from customers.

1. Add a **Newsletter** block
2. Configure:
   - **Heading**: Title (e.g., "Stay Informed", "Join Our Community")
   - **Subheading**: Description text
   - **Email placeholder**: Input hint (e.g., "Your email address")
   - **Button text**: Submit button label (e.g., "Subscribe", "Join")
   - **Success message**: Text shown after signup
3. Click **Save**

**Note:** Signups are stored in **Customers** in your Shopify admin. Connect to email marketing apps like Klaviyo or Mailchimp for automation.

### Text Block

Add any custom text, store hours, mission statement, or other information.

1. Add a **Text Block**
2. Configure:
   - **Heading**: Block title
   - **Text**: Your content (supports basic formatting)
   - **Rich text**: Use the editor for bold, italics, links
3. Click **Save**

### Contact Information Block

Display your store's contact details.

1. Add a **Contact Information** block
2. Configure:
   - **Heading**: Block title (e.g., "Visit Us", "Contact")
   - **Address**: Physical address (supports line breaks)
   - **Phone**: Phone number with international format
   - **Email**: Contact email address
   - **Show map link**: Enable "Get Directions" button
3. Click **Save**

### Reordering Footer Blocks

1. In the Theme Editor, click **Footer** section
2. In the **Blocks** list, drag and drop blocks to reorder them
3. Blocks appear left-to-right on desktop, top-to-bottom on mobile
4. Click **Save**

### Footer Styling

Customize footer appearance:

1. In **Footer** section, scroll to **Styling** settings
2. **Background color**: Footer background (leave blank for theme default)
3. **Text color**: Footer text color
4. **Heading size**: Adjust percentage (50-150%)
5. **Heading color**: Custom color for headings
6. **Body text size**: Adjust percentage (50-150%)
7. **Link color**: Color for footer links
8. **Link hover color**: Color when hovering over links
9. **Spacing**: Top/bottom padding
10. Click **Save**

### Payment Icons

Show accepted payment methods:

1. In **Footer** section, find **Payment icons** setting
2. **Show payment icons**: Enable/disable
3. Icons automatically display based on your enabled payment methods in **Settings → Payments**

---

## Adding Social Media Links

Social icons appear in the footer automatically when you add your social media URLs.

1. From the Theme Editor, click the **⚙️ icon** in the top left to access **Theme settings**
2. Scroll down and click **Social media** section
3. Paste your full profile URLs:
   - **Instagram**: `https://instagram.com/yourusername`
   - **Facebook**: `https://facebook.com/yourpage`
   - **Pinterest**: `https://pinterest.com/yourusername`
   - **TikTok**: `https://tiktok.com/@yourusername`
   - **YouTube**: `https://youtube.com/yourchannel`
   - **Twitter/X**: `https://twitter.com/yourusername`
   - **Snapchat**: `https://snapchat.com/add/yourusername`
   - **Tumblr**: `https://yourusername.tumblr.com`
   - **Vimeo**: `https://vimeo.com/yourusername`
4. Click **Save**

The footer will automatically show icons for any social networks you've added!

**Customizing Social Icons:**
- Icons inherit the footer text color
- Hover effects are automatic
- Icons are accessible with keyboard navigation and screen readers

---

## Working with Sections

Sections are the building blocks of your pages. Each section type has unique settings and can be reordered.

### Homepage Sections

Build your homepage with these sections:

#### Hero Section (`ms-hero`)
Large banner with image or video background
- **Layout**: Full width or boxed
- **Height**: Small, medium, large, or custom
- **Image**: Background image
- **Video**: Background video URL (YouTube or Vimeo)
- **Overlay opacity**: Darken background for text readability
- **Heading**: Main headline
- **Text**: Supporting copy
- **Button**: CTA button with link
- **Text alignment**: Left, center, or right
- **Text color**: Light or dark

#### Featured Object (`ms-featured-object`)
Showcase a signature product
- **Product**: Select from your products
- **Image position**: Left or right
- **Show price**: Display product price
- **Show description**: Show product description
- **Button text**: CTA button label
- **Background color**: Section background

#### New Objects (`ms-new-objects`)
Display your latest products
- **Heading**: Section title
- **Collection**: Link to a collection
- **Products to show**: Number of products (3-12)
- **Products per row**: Grid columns (2-4)
- **Show vendor**: Display brand/vendor name
- **Show price**: Display prices
- **Enable quick view**: Popup product details

#### Material Story (`ms-material-story`)
Tell your material/craft story
- **Image**: Hero image
- **Image position**: Left or right
- **Heading**: Story title
- **Text**: Story content (rich text)
- **Button**: Optional CTA
- **Color scheme**: Light or dark

#### Maker Story (`ms-maker-story`)
Feature your makers/artisans
- **Image**: Maker photo
- **Image position**: Left or right
- **Name**: Maker name
- **Title**: Maker role/specialty
- **Story**: Maker bio/story
- **Button**: Link to full profile
- **Color scheme**: Light or dark

#### Room Scene (`ms-room-scene`)
Lifestyle imagery with product hotspots
- **Image**: Room/lifestyle photo
- **Hotspot blocks**: Add multiple product hotspots
  - **Position X**: Horizontal position (%)
  - **Position Y**: Vertical position (%)
  - **Product**: Linked product
  - **Label**: Hotspot label text

#### Press Strip (`ms-press-strip`)
Show press mentions and awards
- **Heading**: Section title (e.g., "As Featured In")
- **Logo blocks**: Add press logos
  - **Image**: Press logo
  - **Link**: Article URL
  - **Alt text**: Description for accessibility
- **Background color**: Section background

### Adding/Removing/Reordering Sections

**Add a Section:**
1. In the Theme Editor, click **Add section** button
2. Browse available sections
3. Click on the section type to add it
4. Configure section settings
5. Click **Save**

**Remove a Section:**
1. Click on the section in the left sidebar
2. Click **Remove section** button at bottom
3. Confirm deletion
4. Click **Save**

**Reorder Sections:**
1. In the left sidebar, drag the section by its handle
2. Drop it in the desired position
3. Preview changes in the center panel
4. Click **Save**

### Section Visibility

Control section visibility by device:

1. Click on any section
2. Scroll to bottom of section settings
3. **Hide on mobile**: Check to hide on mobile devices
4. **Hide on desktop**: Check to hide on desktop
5. Click **Save**

---

## Style Presets

Quickly apply cohesive color schemes with built-in presets.

### Applying a Style Preset

1. Go to **Theme Settings → Colors**
2. Click **Load preset** button
3. Choose from 4 presets:

#### Linen Preset
Warm, natural aesthetic
- Background: Soft beige (#F5F1E8)
- Text: Warm dark brown (#2C2420)
- Accent: Terracotta (#C67B5C)
- Perfect for: Home goods, textiles, ceramics

#### Noir Preset
Dark, sophisticated aesthetic
- Background: Charcoal (#1A1A1A)
- Text: Soft white (#F8F8F8)
- Accent: Gold (#D4AF37)
- Perfect for: Luxury goods, jewelry, fashion

#### Sage Preset
Fresh, organic palette
- Background: Soft white (#FAFAF9)
- Text: Deep green-gray (#2F3E34)
- Accent: Sage green (#7A9B76)
- Perfect for: Wellness, plants, sustainable products

#### Atelier Preset
Studio-inspired earth tones
- Background: Warm white (#FAF8F5)
- Text: Charcoal (#3A3632)
- Accent: Rust red (#B85C38)
- Perfect for: Art, maker goods, craft supplies

4. Click **Apply**
5. Customize individual colors if desired
6. Click **Save**

**Note:** Applying a preset overwrites your current colors. Save a backup if needed!

---

## Typography & Colors

### Customizing Typography

1. Go to **Theme Settings → Typography**
2. **Heading font**:
   - Click to browse Google Fonts or Shopify fonts
   - Preview fonts in the selector
   - Popular choices: Playfair Display, Cormorant, Fraunces (serif); Inter, Work Sans, DM Sans (sans-serif)
3. **Body font**:
   - Choose a readable font for body text
   - Consider pairing serif headings with sans-serif body
4. **Font size scale**: Adjust overall sizing (80-120%)
5. **Font weights**:
   - Heading weight: Normal, medium, semibold, bold
   - Body weight: Light, normal, medium
6. **Letter spacing**: Tight, normal, loose
7. Click **Save**

### Color Customization

1. Go to **Theme Settings → Colors**
2. Click any color swatch to open color picker
3. Choose color using:
   - **Visual picker**: Click and drag
   - **Hex code**: Enter 6-digit code
   - **RGB sliders**: Adjust red, green, blue
   - **Opacity**: Adjust transparency (0-100%)
4. **Color roles**:
   - **Background**: Main page background
   - **Text**: Primary text color
   - **Secondary text**: Muted/less important text
   - **Border**: Lines and dividers
   - **Accent**: Buttons, links, CTAs
   - **Error**: Error messages and alerts
   - **Success**: Success messages
   - **Dark background**: For dark mode sections
   - **Dark text**: Text on dark backgrounds
5. Click **Save**

### Color Tips

- **Contrast**: Maintain 4.5:1 ratio for accessibility
- **Consistency**: Use accent color sparingly for CTAs
- **Testing**: Preview on different screens and lighting
- **Brand alignment**: Match your brand guidelines
- **Dark sections**: Test light text on dark backgrounds

---

## Product Pages

Configure how products are displayed.

### Product Templates

Choose appropriate templates for different product types:

**Standard Product** (`product.json`)
- Default template for most products
- Image gallery with zoom
- Variant selectors
- Add to cart button
- Product description tabs
- Related products
- Reviews integration

**Made-to-Order Product** (`product.made-to-order.json`)
- Special badge: "Made to Order"
- Lead time display
- Custom ordering information
- All standard product features

**Bundle Product** (`product.bundle.json`)
- "Bundle & Save" badge
- Bundle pricing display
- Individual item listing
- Savings calculation
- All standard features

### Assigning Templates

1. In Shopify Admin, go to **Products**
2. Click on a product to edit
3. Scroll down to **Theme templates** section
4. Click **Change** next to Template
5. Select the desired template
6. Click **Save**

### Product Section Settings

#### Product Gallery
- **Gallery layout**: Grid, slider, or stacked
- **Enable zoom**: Click to zoom product images
- **Enable lightbox**: Full-screen image viewer
- **Thumbnail position**: Below or beside main image
- **Thumbnail size**: Small, medium, large

#### Product Information
- **Show vendor**: Display brand name
- **Show SKU**: Display product SKU
- **Show quantity selector**: Let customers choose quantity
- **Show dynamic checkout buttons**: Apple Pay, Google Pay, etc.
- **Show share buttons**: Social sharing options

#### Product Details
- **Show tabs**: Accordion for description, shipping, returns
- **Tab 1 heading**: Customize tab names
- **Tab 1 content**: Add custom content
- **Add more tabs**: Up to 5 custom tabs

#### Product Recommendations
- **Show recommendations**: Enable "You may also like"
- **Heading**: Section title
- **Products to show**: Number of recommendations (3-8)
- **Products per row**: Grid columns (2-4)

---

## Collection Pages

Showcase your product collections.

### Collection Templates

**Standard Collection** (`collection.json`)
- Clean product grid
- Filtering and sorting toolbar
- Pagination
- Responsive grid

**Editorial Collection** (`collection.editorial.json`)
- Hero image banner
- Rich text description
- All standard features
- Story-driven layout

### Assigning Collection Templates

1. In Shopify Admin, go to **Products → Collections**
2. Click on a collection
3. Scroll down to **Theme templates**
4. Click **Change** next to Template
5. Select the desired template
6. Click **Save**

### Collection Settings

#### Collection Hero (Editorial template only)
- **Show hero image**: Enable/disable banner
- **Hero image**: Upload collection image
- **Hero height**: Small, medium, large
- **Show description**: Display collection description
- **Overlay opacity**: Darken image for text readability

#### Product Grid
- **Products per row (desktop)**: 2, 3, or 4 columns
- **Products per row (mobile)**: 1 or 2 columns
- **Products per page**: 12, 24, 36, or 48
- **Image ratio**: Square, portrait, or landscape
- **Show vendor**: Display brand names
- **Show second image on hover**: Alternate product image
- **Enable quick view**: Popup product details

#### Filtering & Sorting
- **Enable filtering**: Show filter sidebar
- **Filter by**: Tag, vendor, price, availability
- **Show product count**: Display number of products
- **Enable sorting**: Price, name, newest, best-selling
- **Sticky filters**: Filters stay visible when scrolling (desktop)

#### Collection Maker Callout
- **Show maker callout**: Feature a maker in this collection
- **Maker name**: Name of featured maker
- **Maker image**: Photo of maker
- **Maker story**: Brief bio
- **Button**: Link to full maker profile

---

## Common Questions

### General Questions

**Q: How do I add a link to my header navigation?**
A: Go to **Online Store → Navigation** in your Shopify admin, edit the "Main menu", add your links, then make sure that menu is selected in **Theme Editor → Header → Menu** setting.

**Q: Can I have different menus in the header?**
A: Yes! Create a new menu in **Navigation**, then select it in **Theme Editor → Header → Menu** dropdown.

**Q: How do I create a dropdown menu in the header?**
A: In **Online Store → Navigation**, click on your main menu, then drag a menu item slightly to the right under another item to create a dropdown. The indented items become dropdown options.

**Q: Where do newsletter signups go?**
A: Newsletter signups are stored in **Customers** in your Shopify admin. You can export them or connect to email marketing apps like Klaviyo or Mailchimp for automation.

**Q: Can I show different content on mobile vs desktop?**
A: Yes! Each section has visibility settings at the bottom: "Hide on mobile" and "Hide on desktop". The theme also automatically optimizes layouts for mobile devices.

### Header Questions

**Q: My logo looks too big/small. How do I resize it?**
A: In **Theme Editor → Header**, adjust the **Logo width** slider (50-300px for desktop). Use **Mobile logo width** for separate mobile sizing.

**Q: How do I make the header transparent on my homepage?**
A: In **Theme Editor → Header**, enable **Transparent header on homepage**. Adjust **Logo color on transparent** to ensure visibility.

**Q: Can I make the header sticky (fixed when scrolling)?**
A: Yes! In **Theme Editor → Header**, enable **Sticky header**. You can also toggle **Sticky on mobile** separately.

**Q: How do I change the header background color?**
A: The header inherits the theme background color from **Theme Settings → Colors → Background**. For a different header color, you'll need custom CSS.

### Footer Questions

**Q: How do I change the order of footer blocks?**
A: In the Theme Editor, click **Footer**, then drag and drop blocks in the **Blocks** list to reorder them.

**Q: Can I remove the newsletter signup from the footer?**
A: Yes! In the Theme Editor, click **Footer**, find the Newsletter block in the **Blocks** list, and click the trash icon to delete it.

**Q: How many footer columns can I have?**
A: The footer automatically adjusts to fit your blocks (typically 2-5 columns on desktop). On mobile, blocks stack vertically.

**Q: Can I use HTML in footer text blocks?**
A: Yes! The text blocks support basic HTML and Liquid code. Use the rich text editor for formatting, or switch to HTML mode for custom code.

**Q: Why aren't my payment icons showing?**
A: Payment icons appear based on your enabled payment methods in **Settings → Payments**. Enable **Show payment icons** in **Footer** section settings.

### Product & Collection Questions

**Q: How do I assign a product to the "Made-to-Order" template?**
A: Edit the product in your admin, scroll to **Theme templates**, click **Change**, select `product.made-to-order`, and save.

**Q: Can I change the product grid from 3 to 4 columns?**
A: Yes! In collection pages, adjust **Products per row (desktop)** in the collection section settings (2, 3, or 4 columns available).

**Q: How do I enable product filtering?**
A: In **Theme Editor**, edit a collection page, find the **Collection grid** section, and enable **Enable filtering**. Make sure products have tags for filtering to work.

**Q: Product images look stretched/cropped. How do I fix this?**
A: In collection settings, change **Image ratio** to match your product photos (Square, Portrait, or Landscape). Or use consistent image dimensions for all products.

**Q: How do I show product reviews?**
A: Install a review app from the Shopify App Store (Judge.me, Yotpo, Loox). The app will automatically integrate with your product pages.

### Customization Questions

**Q: Can I change fonts?**
A: Yes! Go to **Theme Settings → Typography** and select from Google Fonts or Shopify's font library for headings and body text.

**Q: How do I change the button color?**
A: Go to **Theme Settings → Colors** and change the **Accent color**. This controls buttons, links, and CTAs throughout your site.

**Q: Can I use my brand colors?**
A: Absolutely! Go to **Theme Settings → Colors** and customize all colors. Use your brand's hex codes for exact color matching.

**Q: How do I remove rounded corners from buttons?**
A: Go to **Theme Settings → Layout → Border radius** and set it to 0. Or use Custom CSS: `.btn { border-radius: 0; }`

**Q: Can I change the container width?**
A: Yes! Go to **Theme Settings → Layout → Container width** and adjust the slider (1000-1600px).

### Technical Questions

**Q: How do I duplicate my theme before making changes?**
A: Go to **Online Store → Themes**, find your theme, click **Actions → Duplicate**. Make changes on the duplicate, then publish when ready.

**Q: Can I undo changes in the theme editor?**
A: Use browser undo (Ctrl+Z or Cmd+Z) while in the editor. For published changes, restore from **Actions → Download theme file** backup or revert to a previous version.

**Q: How do I add custom code without breaking the theme?**
A: Use **Theme Settings → Custom CSS** for styles. For more advanced customizations, duplicate your theme first, then edit code carefully.

**Q: Why aren't my changes showing on my live site?**
A: Make sure you clicked **Save** in the theme editor. If still not showing, clear your browser cache (Ctrl+Shift+R or Cmd+Shift+R) or try incognito mode.

**Q: Can I export my theme settings?**
A: Yes! Go to **Online Store → Themes → Actions → Download theme file**. This includes all your settings in `config/settings_data.json`.

### Performance Questions

**Q: How do I optimize images for faster loading?**
A: Upload images at the size they'll be displayed (2000px max width for products). Use JPG for photos, PNG for graphics with transparency. Shopify automatically optimizes images.

**Q: Why is my site slow?**
A: Common causes: Too many sections on pages, large unoptimized images, too many apps. Limit homepage to 8-10 sections, optimize images, and review app impact.

**Q: Does the theme work with all browsers?**
A: Yes! The theme supports all modern browsers (Chrome, Firefox, Safari, Edge) and mobile browsers (iOS Safari, Chrome for Android).

---

## Need More Help?

### Resources

- **📖 Theme Documentation**: Comprehensive guides and tutorials
- **💬 Shopify Help Center**: [help.shopify.com](https://help.shopify.com)
- **👥 Shopify Community**: [community.shopify.com](https://community.shopify.com)
- **🎥 Video Tutorials**: Coming soon
- **📧 Email Support**: mdhyder402@gmail.com

### Getting Support

When contacting support, please include:
1. Your Shopify store URL
2. Theme version number
3. Description of the issue with screenshots
4. Steps to reproduce the problem
5. Browser and device information

---

**💡 Tip:** Most customization happens in the Shopify Theme Editor or Admin. You don't need to edit code files for basic customizations!


## Advanced Customization

### Custom CSS

Add your own styles to customize beyond theme settings.

1. Go to **Theme Settings**
2. Scroll to **Custom CSS** section
3. Add your CSS code
4. Click **Save**

**Example Custom CSS:**
```css
/* Change button border radius */
.btn {
  border-radius: 0; /* Sharp corners */
}

/* Adjust heading letter spacing */
h1, h2, h3 {
  letter-spacing: 0.05em;
}

/* Custom accent color hover effect */
.btn-primary:hover {
  background-color: #your-color;
  transform: translateY(-2px);
}

/* Hide specific section on mobile */
@media (max-width: 767px) {
  .custom-section {
    display: none;
  }
}
```

### Using CSS Variables

The theme includes CSS variables for easy customization:

```css
:root {
  --color-background: #FAFAFA;
  --color-text: #2C2C2C;
  --color-accent: #C67B5C;
  --font-heading: 'Playfair Display', serif;
  --font-body: 'Inter', sans-serif;
  --border-radius: 8px;
  --section-spacing: 80px;
}

/* Override variables */
:root {
  --color-accent: #your-new-color;
  --border-radius: 0; /* Remove all rounded corners */
}
```

### Liquid Code Customization

For developers comfortable with code:

1. Go to **Online Store → Themes**
2. Click **Actions → Edit code** on your theme
3. Navigate to files:
   - `sections/` - Section files
   - `snippets/` - Reusable components
   - `layout/theme.liquid` - Main layout file
   - `assets/` - CSS, JS, images
4. Edit files carefully
5. Click **Save**

**⚠️ Warning:** Editing code can break your theme. Always duplicate your theme before making code changes!

### App Integrations

Enhance your theme with Shopify apps:

**Popular Apps for Maison:**
- **Klaviyo**: Email marketing and automation
- **Yotpo**: Product reviews and ratings
- **Loox**: Photo reviews
- **Privy**: Email popups and forms
- **Judge.me**: Customer reviews
- **Growave**: Wishlist and reviews
- **Searchanise**: Advanced search and filtering
- **Bold Product Options**: Custom product options

Most apps automatically integrate with your theme. Follow each app's installation instructions.

---
