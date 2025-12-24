# GymTrackerApp Website

A beautiful, modern landing page for GymTrackerApp - Your personal fitness companion.

## Features

- 🎨 Modern gradient design with smooth animations
- 📱 Fully responsive layout
- ⚡ Fast and lightweight
- 🔒 Privacy-focused
- ♿ Accessible

## Structure

```
GymTrackerApp-Website/
├── index.html          # Main landing page
├── privacy.html        # Privacy policy page
├── css/
│   └── style.css       # All styles with animations
├── js/
│   └── script.js       # Interactive features
├── images/             # App screenshots and assets
└── README.md
```

## Adding Screenshots

To complete the website, add the following images to the `images/` folder:

### Required Images

1. **hero-screen.png** - Home screen showing personal records (from screenshot 1)
   - Size: 828x1792px (iPhone dimensions)

2. **screenshot-1.png** - Home screen with personal records
   - From: Your first screenshot

3. **screenshot-2.png** - Weekly workouts screen
   - From: Your second screenshot

4. **screenshot-3.png** - Exercise details screen
   - From: Your third screenshot

5. **screenshot-4.png** - Customize workout screen
   - From: Your fourth screenshot

6. **screenshot-5.png** - Challenges screen
   - From: Your fifth screenshot

7. **download-screen.png** - Any attractive screen for download section
   - Recommended: Home screen or Weekly workouts

### Image Guidelines

- Format: PNG with transparent background preferred
- Quality: High resolution (2x or 3x)
- Dimensions: Original iPhone screenshot size (828x1792px for standard)
- Optimization: Compress images for web using tools like TinyPNG

### Quick Setup

1. Take screenshots from your iOS simulator or device
2. Rename them according to the list above
3. Place them in the `images/` folder
4. Refresh the website - images will load automatically!

## Customization

### Colors

Edit CSS variables in `css/style.css`:

```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --secondary-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
    /* ... */
}
```

### Content

- Edit text in `index.html` and `privacy.html`
- Update contact email: `kathayatsubodh@gmail.com`
- Modify stats in hero section

### App Store Link

When your app is published, replace the `#` in the Download button with your App Store URL:

```html
<a href="https://apps.apple.com/app/..." class="store-button apple">
```

## Deployment

### GitHub Pages

1. Push to your GitHub repository
2. Go to Settings → Pages
3. Select source branch (usually `main` or `master`)
4. Your site will be live at `https://yourusername.github.io/GymTrackerApp-Website/`

### Custom Domain

1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Update GitHub Pages settings

### Other Platforms

- **Netlify**: Drag and drop the folder
- **Vercel**: Import from GitHub
- **Cloudflare Pages**: Connect your repository

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Optimized animations with CSS transforms
- Lazy loading ready
- Minimal JavaScript
- Fast page load times

## License

© 2025 GymTrackerApp. All rights reserved.

## Contact

**Subodh Kathayat**
Email: kathayatsubodh@gmail.com

---

Made with ❤️ for fitness enthusiasts worldwide
