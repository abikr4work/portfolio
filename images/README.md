# Images Directory

This directory is for storing your portfolio images. Here's how to organize them:

## Recommended Structure

```
images/
├── eudia/
│   ├── dashboard-main.jpg
│   ├── filters-panel.jpg
│   └── report-preview.jpg
├── chromeos/
│   ├── app-launcher.jpg
│   ├── quick-settings.jpg
│   ├── game-interface.jpg
│   └── ...
├── android/
│   ├── process-flow.jpg
│   ├── sign-in.jpg
│   └── ...
├── android2/
│   ├── phone-mockup.jpg
│   ├── real-usage.jpg
│   └── ...
└── previous/
    ├── google-admin.jpg
    ├── bing-search.jpg
    └── ...
```

## Image Guidelines

- **Format**: Use WebP for best performance, with JPG/PNG fallbacks
- **Size**: Optimize for web (under 500KB per image)
- **Dimensions**: 
  - Thumbnails: 80x60px
  - Project images: 400x300px minimum
  - Main images: 800x600px minimum

## How to Replace Placeholder Images

1. Add your images to the appropriate subdirectories
2. Update the HTML to use `<img>` tags instead of placeholder divs
3. Example:

```html
<!-- Replace this -->
<div class="placeholder-image">🌍 World Map Dashboard</div>

<!-- With this -->
<img src="images/eudia/dashboard-main.jpg" alt="Eudia Dashboard" class="project-image">
```

## CSS for Real Images

Add this CSS to make real images look great:

```css
.project-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 8px;
}
```
