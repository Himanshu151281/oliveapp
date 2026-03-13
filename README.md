# Olive App - Clean Website Build

This is a complete, self-contained version of the Olive App website (oliveapp.com) with all resources properly organized and paths rewritten for local access.

## Folder Structure

```
oliveapp-clean/
├── index.html              # Main landing page (rewritten paths)
├── favicon.ico            # Website favicon
├── css/                   # Stylesheets
│   ├── 82391419a7931d5a.css  # Inter & DM Sans fonts
│   ├── c4285493f68f8ad0.css  # Tailwind CSS + styles
│   ├── 654014d0f6b531db.css  # Neuf font definitions
│   └── 65639f823e52f6bb.css  # Pall font definitions
├── js/                    # JavaScript files (36+ files)
│   ├── main-app-*.js      # Main app chunk
│   ├── webpack-*.js       # Webpack runtime
│   └── [chunk files]      # Code-split components
├── fonts/                 # Custom font files (9 files)
│   ├── *-s.p.ttf         # TTF fonts for Inter, DM Sans, Neuf
│   └── *-s.p.woff2       # WOFF2 fonts
├── images/               # Hero & background images (7 AVIF files)
└── assets/
    └── images/          # App feature images
        ├── benefits/     # Benefit images
        ├── how-to/       # How-to guide images (15+ products)
        ├── illustrations/# SVG illustrations (2 files)
        └── testimonials/ # User testimonials (6+ images)
```

## Quick Start

### Option 1: Open in Browser (Recommended)
1. Navigate to this `oliveapp-clean` folder
2. Double-click `index.html` to open in your default browser
3. The website will load with all styles, fonts, and images intact

### Option 2: Using VS Code Live Server
1. Open the `oliveapp-clean` folder in VS Code
2. Install the "Live Server" extension if not already installed
3. Right-click `index.html` → "Open with Live Server"
4. Enjoy live reload on file changes

### Option 3: Using Python HTTP Server
```bash
cd oliveapp-clean
python -m http.server 8000
```
Then visit: `http://localhost:8000`

### Option 4: Using Node.js Simple Server
```bash
cd oliveapp-clean
npx http-server
```

## What's Included

✅ Complete responsive HTML structure
✅ All Tailwind CSS styles (122 KB minified)
✅ Custom fonts (Inter, DM Sans, Neuf, Pall)
✅ All JavaScript chunks for app functionality
✅ High-quality AVIF hero images
✅ Feature & product images
✅ Testimonial images
✅ Properly rewritten relative paths for offline access

## File Statistics

- **Total Files**: 86
- **Total Size**: 6.6 MB
- **HTML**: 1 (main index)
- **CSS**: 4 files
- **JS**: 36+ chunks
- **Fonts**: 9 font files
- **Images**: 50+ images

## Important Notes

1. **Interactive Features**: Some interactive elements like links to non-existent pages (blog, restaurants, etc.) are set to `#` for anchor navigation
2. **App Store Links**: The "Get Olive" button links to the iTunes store
3. **Dynamic Content**: The website is a Next.js static export, so all dynamic server features are client-side rendered
4. **Browser Support**: Modern browsers (Chrome, Firefox, Safari, Edge) work best

## Rewriting Details

The original paths have been rewritten as follows:
- `./_next/static/css/***` → `css/***`
- `./_next/static/media/***` → `fonts/***`
- `./_next/static/chunks/***` → `js/***`
- `./images/***` → `images/***`
- `./assets/images/***` → `assets/images/***`
- `./favicon.ico` → `favicon.ico`

This makes the website completely portable and functional in any local environment without requiring a web server (though one is recommended for best performance).

## Offline Access

This website is fully functional offline. All assets, styles, and scripts are included locally. Simply open `index.html` in any modern web browser.

---

**Website**: https://oliveapp.com
**About**: Olive is a family nutrition ally and powerful food scanner app with a database of 1M+ products.
