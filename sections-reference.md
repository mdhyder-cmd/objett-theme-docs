---
layout: default
title: Sections Reference - Maison Craft theme
---

# 📐 Maison Craft theme - Sections Reference Guide

Complete reference for all 30+ sections available in the Maison Craft theme.

## 📋 Table of Contents
- [Hero & Featured Sections](#hero--featured-sections)
- [Product Sections](#product-sections)
- [Collection Sections](#collection-sections)
- [Content & Storytelling](#content--storytelling)
- [Blog/Journal Sections](#blogjournal-sections)
- [Utility Sections](#utility-sections)

---

## Hero & Featured Sections

### Hero Section (`ms-hero`)

Large banner section for homepage or landing pages.

**Use Cases:**
- Homepage welcome banner
- Campaign announcements
- Seasonal promotions
- Brand storytelling

**Settings:**
- **Layout**: Full width, boxed, or split
- **Height**: Small (400px), Medium (600px), Large (800px), or Custom
- **Background**: Image or video
- **Image**: Upload background image (2400px+ recommended)
- **Video URL**: YouTube or Vimeo URL for video background
- **Mobile image**: Different image for mobile devices
- **Overlay opacity**: 0-100% to darken background for text readability
- **Heading**: Main headline text
- **Subheading**: Supporting text
- **Button text**: CTA button label
- **Button link**: URL for button
- **Text alignment**: Left, center, or right
- **Text color**: Light or dark
- **Color scheme**: Choose from theme color schemes

**Best Practices:**
- Use high-quality images (2400px width minimum)
- Keep text concise (5-8 words for headline)
- Ensure text is readable with overlay
- Test on mobile devices
- Use video sparingly (impacts performance)

**Example Use:**
```
Heading: "Objects for Considered Living"
Subheading: "Handcrafted ceramics and textiles for the modern home"
Button: "Shop New Arrivals"
Background: Hero image of curated home scene
```

---

### Featured Object (`ms-featured-object`)

Spotlight a signature product with image and details.

**Use Cases:**
- Highlight new product launch
- Feature best-selling item
- Showcase seasonal product
- Product storytelling

**Settings:**
- **Product**: Select from your products
- **Image position**: Left or right
- **Show price**: Display/hide product price
- **Show description**: Display product description
- **Show vendor**: Display brand/maker name
- **Button text**: CTA button label (default: "View Product")
- **Button link**: Automatically links to product
- **Background color**: Section background
- **Text color**: Light or dark
- **Spacing**: Top/bottom padding

**Best Practices:**
- Choose visually striking products
- Use high-resolution product images
- Write compelling product descriptions
- Update seasonally
- Test image orientation (portrait/landscape)

---

### Room Scene (`ms-room-scene`)

Lifestyle imagery with interactive product hotspots.

**Use Cases:**
- Show products in context
- Lifestyle photography
- Shoppable room scenes
- Visual storytelling

**Settings:**
- **Image**: Upload room/lifestyle photo (2400px+ recommended)
- **Image height**: Small, Medium, Large, or Full viewport
- **Heading**: Section title (optional)
- **Hotspot blocks**: Add multiple product hotspots
  - **Position X**: Horizontal position (0-100%)
  - **Position Y**: Vertical position (0-100%)
  - **Product**: Link to product
  - **Label**: Hotspot label text (optional)
  - **Icon style**: Dot, plus, or pulse

**Best Practices:**
- Use high-quality lifestyle photography
- Limit to 3-5 hotspots per image
- Position hotspots near actual products in photo
