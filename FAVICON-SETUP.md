# 🎨 Favicon & Social Card Setup Guide

## Quick Start

Your website now has placeholder favicon and social sharing tags configured! Follow these steps to complete the setup.

## 📦 What's Already Done

✅ Created `favicon.svg` - Modern SVG favicon
✅ Added all meta tags to `index.html` for social sharing
✅ Created `site.webmanifest` for PWA support
✅ Created `social-card.html` - Template for your social share image
✅ Created `favicon-generator.html` - Helper tool with instructions

## 🚀 Next Steps

### Step 1: Generate Favicon Files

**Option A - Use Online Generator (Easiest):**

1. Go to **https://favicon.io/favicon-converter/**
2. Upload your `evolvelogo.jpeg` file
3. Click "Download" to get a ZIP file
4. Extract the ZIP and copy these files to your website root:
   - `favicon.ico`
   - `favicon-16x16.png`
   - `favicon-32x32.png`
   - `apple-touch-icon.png`
   - `android-chrome-192x192.png`
   - `android-chrome-512x512.png`

**Option B - Use RealFaviconGenerator (More Control):**

1. Go to **https://realfavicongenerator.net/**
2. Upload `evolvelogo.jpeg`
3. Customize settings for each platform
4. Download and extract files to your website root

### Step 2: Create Social Share Card

**Option A - Use Canva (Recommended):**

1. Go to **https://www.canva.com**
2. Create custom size: **1200 × 630 pixels**
3. Design your card:
   - Use gradient background: `#0b7fab` → `#34d399`
   - Add your logo (`evolvelogo.jpeg`)
   - Add text: "Evolve360Wellness"
   - Add tagline: "Transform Your Life with Compassionate Mental Health & Wellness Services"
   - Add features: "Licensed Professionals • Compassionate Care • Flexible Scheduling"
   - Add URL: "evolve360wellness.com"
4. Download as `og-image.jpg` or `og-image.png`
5. Place in your website root folder

**Option B - Use the Template:**

1. Open `social-card.html` in your browser
2. Take a screenshot at exactly 1200×630 pixels
3. Save as `og-image.jpg`
4. Place in your website root

**Option C - Quick Screenshot Tool:**

1. Open `social-card.html` in Chrome
2. Press F12 (Developer Tools)
3. Click device toolbar (or Ctrl+Shift+M)
4. Set dimensions: 1200 × 630
5. Screenshot the card
6. Save as `og-image.jpg`

### Step 3: Upload Everything

Upload these files to your website root (same folder as `index.html`):

```
evolve360wellness/
├── favicon.ico
├── favicon.svg
├── favicon-16x16.png
├── favicon-32x32.png
├── apple-touch-icon.png
├── android-chrome-192x192.png
├── android-chrome-512x512.png
├── og-image.jpg (or .png)
└── site.webmanifest
```

## ✅ Testing

### Test Favicon:
1. Clear browser cache
2. Visit your website
3. Check the browser tab - you should see your favicon

### Test Social Sharing:

**Facebook:**
- Go to: https://developers.facebook.com/tools/debug/
- Enter your URL: `https://evolve360wellness.com`
- Click "Scrape Again"
- Verify image and text appear correctly

**Twitter:**
- Go to: https://cards-dev.twitter.com/validator
- Enter your URL: `https://evolve360wellness.com`
- Click "Preview card"
- Verify image and text appear correctly

**LinkedIn:**
- Go to: https://www.linkedin.com/post-inspector/
- Enter your URL: `https://evolve360wellness.com`
- Click "Inspect"
- Verify image and text appear correctly

## 🎨 Design Specifications

### Favicon Sizes Needed:
- `favicon.ico` - 16×16, 32×32, 48×48 (multi-size ICO file)
- `favicon-16x16.png` - 16×16 pixels
- `favicon-32x32.png` - 32×32 pixels
- `apple-touch-icon.png` - 180×180 pixels
- `android-chrome-192x192.png` - 192×192 pixels
- `android-chrome-512x512.png` - 512×512 pixels

### Social Share Card:
- **Size:** 1200 × 630 pixels (exact)
- **Format:** JPG or PNG
- **File size:** Under 5MB (ideally under 1MB)
- **Safe zone:** Keep text/logos 40px from edges
- **Text size:** Minimum 32px for readability

## 📝 Current Meta Tags

Your `index.html` already includes:

✅ Open Graph tags (Facebook, LinkedIn)
✅ Twitter Card tags
✅ Theme color for mobile browsers
✅ Apple touch icon reference
✅ Web manifest for PWA
✅ Canonical URL

## 🔧 Troubleshooting

**Favicon not showing:**
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Check file names match exactly
- Verify files are in root directory
- Wait a few minutes for CDN/cache to clear

**Social card not showing:**
- Make sure `og-image.jpg` is in root directory
- Check file size is under 5MB
- Use absolute URL (not relative)
- Clear social media cache using testing tools above
- Images must be publicly accessible (not behind login)

**Image shows broken on social media:**
- Verify URL is correct: `https://evolve360wellness.com/og-image.jpg`
- Check file exists and is accessible
- Ensure image dimensions are exactly 1200×630
- Use testing tools to validate

## 🌟 Pro Tips

1. **Use your actual logo:** Replace the placeholder with your real logo
2. **Keep it simple:** Don't clutter the social card
3. **High contrast:** Ensure text is readable
4. **Test everywhere:** Check on mobile, desktop, and different social platforms
5. **Update regularly:** Refresh social cache when you update images
6. **Optimize file size:** Compress images to load faster

## 📞 Need Help?

If you run into issues:
1. Check the testing tools links above
2. Verify all files are uploaded correctly
3. Clear all caches
4. Wait 24 hours for DNS/CDN propagation

---

**Files included in this setup:**
- `favicon.svg` - Modern SVG favicon
- `social-card.html` - Template for creating your social share image
- `favicon-generator.html` - Helper tool with visual guide
- `site.webmanifest` - PWA configuration
- `FAVICON-SETUP.md` - This guide
