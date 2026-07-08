---
layout: default
title: Objett Co theme Documentation
---

# Objett Co theme Documentation

Complete guide to setting up and customizing your Objett Co theme.

---

## Table of Contents

1. [Quick Start: Recommended Sections](#quick-start-recommended-sections)
2. [Installation](#installation)
3. [Initial Setup](#initial-setup)
4. [Theme Settings](#theme-settings)
5. [Homepage Setup](#homepage-setup)
6. [Product Pages](#product-pages)
7. [Collection Pages](#collection-pages)
8. [Page Templates](#page-templates)
9. [Customization](#customization)
10. [Features Guide](#features-guide)
11. [Troubleshooting](#troubleshooting)

---

## Quick Start: Recommended Sections

**Need a quick overview? Here's what sections to use for each page type.**

### 🏠 Homepage (5 sections recommended)
1. **Hero** - Full-screen impact (REQUIRED)
2. **Featured Product** - Highlight best item
3. **Material Story** - Build trust
4. **New Arrivals** - Show products
5. **Maker Story** - Personal connection

[View detailed homepage guide →](#homepage-setup)

---

### 🛍️ Product Page (3 sections)
1. **Product Main** - Core info (REQUIRED)
   - Images, title, price, variants, buy button
2. **Product Material** - Craftsmanship story (OPTIONAL)
   - Only for artisan/handmade products
3. **Product Recommendations** - Upsell (REQUIRED)
   - Increases cart value

[View detailed product page guide →](#product-pages)

---

### 📚 Collection Page (Choose one template)

**Standard (Recommended):**
- Fast, conversion-focused
- Grid + filters + sorting
- Use for: Most collections

**Editorial (Special occasions):**
- Hero banner + storytelling
- Use for: Seasonal launches only

[View detailed collection guide →](#collection-pages)

---

### 📄 About Page (5 sections)
1. **About Hero** - Opening banner
2. **About Story #1** - Origin story
3. **About Values** - Core principles
4. **About Story #2** - Process/craft
5. **About Studio** - Team/workspace

[View detailed about page guide →](#page-templates)

---

### 📧 Contact Page (1 section)
1. **Contact Form** - Simple & effective

[View detailed contact guide →](#page-templates)

---

### ❓ FAQ Page (1 section)
1. **FAQ Accordion** - 8-15 questions organized by topic

[View detailed FAQ guide →](#page-templates)

---

### 📋 Other Pages

**Policies** - Use page.policies.json  
**General Content** - Use page.json  
**Maker Profiles** - Use page.maker-profile.json (if multi-maker brand)

[View all page templates →](#page-templates)

---

## Installation

### Step 1: Download Theme
1. Download the Objett Co theme ZIP file from Shopify Theme Store
2. Keep the ZIP file - don't unzip it

### Step 2: Upload to Shopify
1. Log in to your Shopify admin
2. Go to **Online Store > Themes**
3. Click **Upload theme** button
4. Select the ZIP file
5. Click **Upload**

### Step 3: Publish Theme
1. Once uploaded, click **Publish** to make it live
2. Or click **Customize** to set it up first before publishing

---

## Initial Setup

### Configure Basic Settings

1. **Go to Theme Editor**
   - Click **Customize** on your theme

2. **Set Up Navigation**
   - Go to **Online Store > Navigation**
   - Edit **Main menu** - Add your primary links
   - Edit **Footer menu** - Add footer links

3. **Add Your Logo**
   - In theme editor, go to **Header** section
   - Upload your logo image
   - Adjust logo width if needed

4. **Set Favicon**
   - In theme editor, go to **Theme Settings > Favicon**
   - Upload your site icon (32x32px or larger)

---

## Theme Settings

Access theme-wide settings by clicking **Theme Settings** in the theme editor sidebar.

### Typography Settings
- **Heading Font** - Choose from Shopify font library
- **Body Font** - Select body text font
- **Heading Scale** - Adjust heading sizes (80-130%)
- **Body Scale** - Adjust body text size (80-130%)
- **Navigation Scale** - Adjust menu text size
- **Button Scale** - Adjust button text size

### Color Settings
Customize your brand colors:
- **Background** - Main page background
- **Surface** - Secondary background (cards, sections)
- **Primary Text** - Main text color
- **Muted Text** - Secondary text color
- **Accent** - Highlight color (prices, CTAs)
- **Rules** - Border and divider lines
- **Dark Background** - For dark sections
- **Dark Text** - Text on dark sections

### Header Settings
- **Sticky Header** - Keep navigation visible when scrolling
- **Transparent Header on Homepage** - Overlay header on first section

### Social Media Settings
- **Organization Logo** - For SEO (600px wide)
- **Social Share Image** - Default image for social sharing (1200x630px)
- **Social Links** - Add Instagram, Facebook, Pinterest, TikTok, YouTube URLs

---

## Homepage Setup

### Recommended Section Layout ⭐

For maximum impact and conversions, use these sections in this order:

#### **1. Hero Section** (Full-screen)
- **What it does:** Creates immediate visual impact
- **Recommendation:** Use high-quality lifestyle image
- **Settings:**
  - Text position: center-center or bottom-left
  - Heading: 2-5 words max ("Timeless Home Objects")
  - Subtext: 5-10 words describing your brand
  - CTA: Action word ("Shop Collection", "Explore")
  - Show scroll indicator: Yes (guides users)

#### **2. Featured Product/Object**
- **What it does:** Highlights your best or newest product
- **Recommendation:** Choose your hero product
- **Settings:**
  - Eyebrow: "Featured" or "New Arrival"
  - Select your best-selling product
  - Add rich description (2-3 sentences)
  - Enable "View Product" CTA

#### **3. Material Story**
- **What it does:** Builds trust through craftsmanship story
- **Recommendation:** Show materials or creation process
- **Settings:**
  - Eyebrow: "Craftsmanship" or "Our Process"
  - Heading: "Made to Last" or "Natural Materials"
  - Image: Close-up of materials, hands crafting, raw materials
  - Body: 3-4 sentences about quality, origin, sustainability

#### **4. New Arrivals/Objects**
- **What it does:** Displays latest products in grid
- **Recommendation:** Link to "New" or "Latest" collection
- **Settings:**
  - Eyebrow: "Latest" or "New In"
  - Heading: "New Arrivals"
  - Collection: Create dedicated "New Arrivals" collection
  - Limit: 4-6 products for clean layout

#### **5. Maker/Brand Story** (Optional but Recommended)
- **What it does:** Personal connection with founder/artisan
- **Recommendation:** Authentic founder photo and story
- **Settings:**
  - Eyebrow: "Our Story" or "Meet the Maker"
  - Name: Founder name or brand name
  - Subtitle: "Founder" or role
  - Body: 3-4 sentences about passion and mission
  - CTA: "Learn More" → Link to About page

#### **6. Press Strip** (Optional - if you have press)
- **What it does:** Builds credibility through media mentions
- **Recommendation:** Only use if you have real press
- **Settings:**
  - Label: "As Featured In"
  - Upload press logos (PNG with transparency)
  - 3-5 logos max for credibility

### Adding/Removing Sections
1. In theme editor, select **Home page** template
2. Click **Add section** to add new sections
3. Click the eye icon to hide sections
4. Drag sections to reorder

### Sections to Disable Initially
- **Room Scene** - Only if you have styled room photography
- **Press Strip** - Only if you have media mentions
- Keep it simple: 4-5 sections is perfect for homepage

### Content Tips for Homepage
- **Hero:** Lifestyle image, not product close-up
- **Featured Product:** Multiple angles + lifestyle context
- **Material Story:** Authentic behind-the-scenes photos
- **New Arrivals:** High-quality, consistent product photos
- **Maker Story:** Real photo, not stock image

---

## Product Pages

### Recommended Layout ⭐

Keep product pages simple and focused on conversion:

#### **1. Product Main Section** (Always On)
This is the core of your product page. Configure these blocks in order:

**Essential Blocks (Keep these):**
1. **Vendor** - Brand name (shows trust)
2. **Title** - Product name
3. **Description** - Product details (use short subtitle)
4. **Price** - Current and sale pricing
5. **Variant Picker** - Size/color options
6. **Quantity Selector** - Amount to buy
7. **Buy Buttons** - Add to cart + dynamic checkout
8. **Wishlist** - Save for later

**Accordion Blocks (Detailed Info):**
1. **Description Accordion** - Full product story
   - Content: Detailed description, dimensions, weight
2. **Materials & Care Accordion** - Material details
   - Content: Material composition, care instructions, maintenance
3. **Shipping & Returns Accordion** - Logistics info
   - Content: Shipping time, return policy, warranty

#### **2. Product Material Section** (Optional - Enable for artisan products)
- **When to use:** Handmade, artisan, or craft products
- **What it shows:** Materials, process, craftsmanship details
- **Recommendation:** Enable if your products have unique materials/story
- **Settings:**
  - Eyebrow: "Materials" or "Craftsmanship"
  - Heading: "What Makes It Special"
  - Add 2-3 attribute blocks (e.g., "Origin: Portugal", "Material: Oak")

#### **3. Product Recommendations** (Always On)
- **What it does:** Shows related products, increases cart value
- **Recommendation:** Keep this enabled
- **Settings:**
  - Heading: "You May Also Consider" or "Complete the Look"
  - Shopify auto-recommends related products

### Product Templates Available

Choose the right template based on product type:

1. **product.json** - Standard products
   - Use for: Regular inventory items
   - Ships immediately

2. **product.made-to-order.json** - Custom/made-to-order
   - Use for: Items made after order
   - Shows "Made to Order" badge
   - Displays lead time (6-8 weeks)
   - Special notice in cart

3. **product.bundle.json** - Product sets
   - Use for: Multiple items sold together
   - Shows bundle pricing
   - Lists included items

### Assigning Templates to Products
1. Go to **Products** in Shopify admin
2. Open a product
3. Scroll to **Theme templates** section
4. Select appropriate template
5. **Save**

### Image Best Practices
- **Minimum:** 3-4 images per product
- **Recommended:** 5-6 images
- **Include:**
  1. Main product shot (white background)
  2. Angle view
  3. Detail/close-up
  4. Size/scale reference
  5. Lifestyle/in-use shot
  6. Packaging (optional)

### Description Writing Tips
- **Subtitle:** 1-2 sentence summary (shows on card)
- **Main Description:** 2-3 paragraphs
  - Paragraph 1: What it is, key features
  - Paragraph 2: Benefits, use cases
  - Paragraph 3: Materials, craftsmanship
- **Accordions:** Detailed specs in organized sections

### Product Page Settings

#### Product Main
Configure in theme editor:
- **Vendor Display** - Show/hide brand name
- **Title** - Product name
- **Description** - Product details
- **Price** - Including sale prices
- **Variant Picker** - Size, color options
- **Quantity Selector** - Amount to purchase
- **Buy Buttons** - Add to cart + dynamic checkout
- **Wishlist** - Save for later
- **Accordion Items** - Collapsible details (story, materials, shipping)

#### Product Material Section
- Showcase materials and craftsmanship
- Add custom attributes (origin, finish, care)
- Image with text overlay

#### Product Recommendations
- Shows related products
- Automatic or manual selection
- Customizable heading

### What NOT to Do
❌ Don't overcrowd with too many sections  
❌ Don't hide important info in accordions (price, variants)  
❌ Don't use low-quality or inconsistent images  
❌ Don't write novels (keep it scannable)  
❌ Don't forget mobile view (test on phone)

---

## Collection Pages

### Recommended Template Choice ⭐

Choose based on your collection type:

#### **Standard Collection (collection.json)** - RECOMMENDED for most
**Best for:** Regular browsing, large product catalogs  
**Features:**
- Clean product grid
- Filtering (price, vendor, tags)
- Sorting (best selling, price, newest)
- Fast loading
- Simple, conversion-focused

**When to use:**
- Main product categories
- "All Products" collection
- Any collection with 12+ products
- When speed matters

**Settings:**
- Products per page: 12-24 (12 recommended)
- Enable filtering: Yes
- Enable sorting: Yes

#### **Editorial Collection (collection.editorial.json)** - For special collections
**Best for:** Seasonal launches, curated selections, storytelling  
**Features:**
- Hero banner with image
- Collection description/story
- Product grid below
- More visual, editorial feel

**When to use:**
- "New Collection" launches
- Seasonal collections
- Curated/limited selections
- When storytelling matters

**Sections in order:**
1. **Collection Hero** - Full-width banner
   - Image: High-quality lifestyle photo
   - Heading: Collection name
   - Description: 1-2 sentences about the collection

2. **Collection Toolbar** - Filter + Sort controls
   - Standard filtering
   - Sort dropdown

3. **Collection Grid** - Product results
   - Responsive grid layout
   - Product cards

4. **Collection Maker Callout** (Optional)
   - Featured artisan mid-page
   - Breaks up product grid
   - Only use if relevant

5. **Collection Editorial** (Optional)
   - Text + image storytelling
   - Explains collection inspiration
   - Keep it concise

### Collection Features
- **Filtering** - By price, vendor, tags
- **Sorting** - Best selling, price, newest, alphabetical
- **Grid Layout** - Responsive 2-4 columns
- **Pagination** - Navigate multiple pages smoothly

### Setting Up Collections

#### 1. Create Collection
1. Go to **Products > Collections** in Shopify admin
2. Click **Create collection**
3. Enter:
   - **Title:** Collection name (e.g., "Ceramics", "New Arrivals")
   - **Description:** SEO-friendly description
   - **Collection type:** Manual or Automated
4. Add products (if manual)
5. **Save**

#### 2. Assign Template
1. Open the collection
2. Scroll to **Theme templates**
3. Choose:
   - **Default** (collection.json) - For regular collections
   - **Editorial** (collection.editorial.json) - For special collections
4. **Save**

#### 3. Customize in Theme Editor
1. Go to **Online Store > Themes > Customize**
2. Navigate to **Collections**
3. Select your collection
4. Adjust:
   - Products per page (12 recommended)
   - Filter settings
   - Sort options
   - Hero image (if editorial)

### Collection Image Best Practices

#### Collection Header Image:
- **Size:** 1600x600px minimum
- **Content:** Lifestyle shot or styled flat lay
- **NOT:** Individual product shots
- **Style:** Match your brand aesthetic

#### Product Card Images:
- **Consistency:** Same style across all products
- **Background:** White or consistent color
- **Aspect Ratio:** Square (1:1) or portrait (3:4)
- **Quality:** High-res, well-lit

### Collection Description Tips

**Standard Collection:**
- 1-2 sentences max
- Focus on benefits
- Include keywords for SEO
- Example: "Handcrafted ceramic pieces made from natural stoneware. Each piece is unique with subtle variations in color and texture."

**Editorial Collection:**
- 2-3 paragraphs OK
- Tell the story
- Explain inspiration
- Create desire

### Customizing Collections
1. Go to theme editor
2. Select **Collections > Default collection** template
3. Adjust:
   - Products per page (12, 16, or 24)
   - Filter settings (enable/disable)
   - Sort options (which ones to show)
   - Hero image (editorial template only)

### Filter Setup

**Recommended filters:**
1. **Price** - Always useful
2. **Vendor/Brand** - If you have multiple makers
3. **Material** - Use product tags (e.g., "ceramic", "wood", "linen")
4. **Color** - If relevant (use tags like "white", "natural", "black")

**How to add filter tags:**
1. Edit product
2. In **Tags** field, add: `material_ceramic`, `color_white`, etc.
3. Tags with underscores become filter groups
4. **Save**

### What NOT to Do
❌ Don't use editorial template for every collection (slows browsing)  
❌ Don't show too many products per page (12-16 is optimal)  
❌ Don't forget mobile view (filters must work on phone)  
❌ Don't use low-quality collection images  
❌ Don't disable sorting (users need control)

---

## Page Templates

### Recommended Page Setups ⭐

#### **About Page (page.about.json)** - RECOMMENDED ⭐
**Use for:** Your brand story, mission, values  
**Sections in recommended order:**

1. **About Hero** - Opening banner
   - **Image:** Team photo or studio shot
   - **Title:** "Our Story" or "About [Brand Name]"
   - **Tagline:** One sentence mission statement

2. **About Story** (First Block)
   - **Layout:** Image left, text right
   - **Image:** Founder photo or origin story image
   - **Content:** How you started (2-3 paragraphs)
   - **Topics:** Why you started, early days, inspiration
   - **Reverse:** No (image on left)

3. **About Values** - Core principles
   - **Layout:** 3-4 value cards in grid
   - **Content:** Quality, Sustainability, Craftsmanship, Community
   - **Per value:** Icon/image + title + 1-2 sentences
   - **Keep:** 3-4 values max (don't overwhelm)

4. **About Story** (Second Block)
   - **Layout:** Image right, text left
   - **Image:** Workshop, process, or product creation
   - **Content:** How products are made (2-3 paragraphs)
   - **Topics:** Materials, process, quality standards
   - **Reverse:** Yes (image on right)

5. **About Studio** - Team/workspace
   - **Image:** Studio/workshop photo or team
   - **Content:** Where you work, who you are
   - **CTA:** "Get in Touch" → Contact page

**Content Tips:**
- Be authentic (no corporate jargon)
- Use real photos (not stock)
- Tell YOUR story (what makes you different)
- Keep it personal but professional
- 2-3 paragraphs per section max

---

#### **Contact Page (page.contact.json)** - Simple & Effective
**Use for:** Customer inquiries, support  
**Sections:**

1. **Contact Section** (Only section needed)
   - **Contact Form:** Name, Email, Message fields
   - **Your Email:** Display your contact email
   - **Phone:** Optional phone number
   - **Response Time:** "We reply within 24 hours"
   - **Optional:** Embedded map if you have physical location

**Content Tips:**
- Keep form simple (3 fields max)
- Set clear expectations for response time
- Add reassuring copy ("We'd love to hear from you")
- Optional: Add FAQ link to reduce inquiries

---

#### **FAQ Page (page.faq.json)** - Answer Common Questions
**Use for:** Reduce support emails, build trust  
**Sections:**

1. **FAQ Section** (Accordion-style Q&A)
   - **Layout:** Collapsible questions
   - **Categories:** Group by topic
   - **Recommended topics:**
     - **Ordering & Payment** (3-4 questions)
     - **Shipping & Delivery** (3-4 questions)
     - **Returns & Exchanges** (2-3 questions)
     - **Product Care** (2-3 questions)
     - **About Our Products** (2-3 questions)

**Sample Questions:**
- "How long does shipping take?"
- "What's your return policy?"
- "How do I care for my [product]?"
- "Do you ship internationally?"
- "Are products made to order?"
- "What payment methods do you accept?"

**Content Tips:**
- Answer clearly and concisely
- Link to policies page for details
- Update based on actual customer questions
- 8-15 total questions is perfect

---

#### **Standard Page (page.json)** - General Content
**Use for:** Any other content pages  
**Examples:**
- Shipping Policy
- Return Policy
- Privacy Policy
- Terms & Conditions
- Care Instructions
- Sustainability Practices

**Sections:**
1. **Page Section** (Simple content)
   - **Heading:** Page title
   - **Body:** Your content
   - **Layout:** Single column, readable width

**Content Tips:**
- Use clear headings (H2, H3)
- Break into scannable sections
- Use bullet points for lists
- Keep paragraphs short (3-4 sentences)

---

#### **Maker Profile Page (page.maker-profile.json)** - Optional
**Use for:** If you feature multiple artisans/makers  
**Sections:**

1. **Maker Profile** - Individual artisan bio
   - **Photo:** Portrait of the maker
   - **Name & Title:** "Sarah Chen, Ceramicist"
   - **Bio:** 2-3 paragraphs about their work
   - **Products:** Link to their collection

**When to use:**
- You sell products from multiple makers
- You want to highlight artisan stories
- Maker identity is important to your brand

---

#### **Makers Directory (page.makers.json)** - Optional
**Use for:** If you have multiple featured makers  
**Sections:**

1. **Makers Grid** - Grid of maker cards
   - **Layout:** 2-3 columns
   - **Per maker:** Photo + name + specialty
   - **Links:** To individual maker profile pages

---

#### **Policies Page (page.policies.json)** - Legal/Required
**Use for:** Store policies, legal info  
**Sections:**

1. **Policies Section** - Tabbed or accordion layout
   - **Shipping Policy**
   - **Return Policy**
   - **Privacy Policy**
   - **Terms of Service**

**Content Tips:**
- Be clear and specific
- Include timeframes (e.g., "14-day returns")
- Explain processes step-by-step
- Link from footer for easy access

---

### Creating Pages
1. Go to **Online Store > Pages**
2. Click **Add page**
3. **Title:** Page name
4. **Content:** Your page content
5. **Theme template:** Select appropriate template
6. **Visibility:** Published
7. **Save**

### Page SEO Tips
- **Title:** Include keywords (max 60 characters)
- **Description:** Clear summary (max 160 characters)
- **URL:** Short and descriptive (`/about` not `/about-us-page-new`)
- **Content:** Use headers (H2, H3) for structure
- **Images:** Include alt text

### Navigation Setup
Add pages to menus:
1. Go to **Online Store > Navigation**
2. Edit **Main menu** or **Footer menu**
3. Click **Add menu item**
4. Select **Pages**
5. Choose your page
6. **Save menu**

**Recommended Footer Menu:**
- About
- Contact
- FAQ
- Shipping Policy
- Return Policy
- Privacy Policy

**Recommended Main Menu:**
- Collections (dropdown)
- About
- Journal/Blog (if you have one)
- Contact

---

## Customization

### Using Style Presets
Quick color scheme changes:

1. Go to theme editor
2. Click **Theme Settings**
3. At top, click **Presets**
4. Choose from:
   - **Linen** - Warm, natural tones
   - **Noir** - Dark, sophisticated
   - **Sage** - Fresh, organic palette
   - **Atelier** - Studio earth tones

### Custom Colors
Override preset colors:
1. Go to **Theme Settings > Colors**
2. Adjust individual colors
3. Changes save automatically

### Custom Fonts
1. Go to **Theme Settings > Typography**
2. Click font picker for heading or body
3. Choose from 100+ fonts in Shopify library
4. Adjust size scales as needed

---

## Features Guide

### Cart Drawer
- Slides from right on "Add to Cart"
- Shows cart contents without leaving page
- Free shipping progress bar
- Remove items or update quantities

### Search
- Click search icon in header
- Full-page overlay search
- Filters by products, collections
- Live search results

### Wishlist
- Heart icon on product cards
- Saves to browser (no login required)
- View saved items anytime

### Gift Cards
- Automatic QR code generation
- Print-friendly design
- Shows balance and code

---

## Troubleshooting

### Theme Not Displaying Correctly
1. Clear browser cache
2. Check if theme is published
3. Verify sections are not hidden

### Images Not Showing
1. Check image file formats (JPG, PNG, WebP)
2. Re-upload images
3. Ensure images are under 20MB

### Colors Not Changing
1. Make sure you're editing the live theme
2. Check if section has override settings
3. Try different browser

### Fonts Not Loading
1. Clear browser cache
2. Check internet connection
3. Try selecting different font

### Mobile View Issues
1. Check responsive preview in theme editor
2. Test on actual device
3. Clear mobile browser cache

---

## Need More Help?

**Can't find what you're looking for?**

📧 **Email Support:** [mdhyder402@gmail.com](mailto:mdhyder402@gmail.com)  
🕐 **Response Time:** 24-48 hours (business days)  
💬 **Support Page:** [Get Help](support)

When contacting support, please include:
- Your store URL
- Description of issue
- Screenshots if applicable
- Steps you've already tried

---

[← Back to Home](index) | [Get Support →](support)

---

<div style="text-align: center; margin-top: 3rem; padding-top: 2rem; border-top: 1px solid #D4CFC8; color: #7C7168;">
  <p><small>Objett Co theme Documentation by Mohammad Hyder</small></p>
</div>
