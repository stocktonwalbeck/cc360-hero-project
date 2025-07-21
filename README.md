# Course Creator 360 Hero Component

This is a performance-optimized hero component for Course Creator 360, featuring:

## Features
- **Performance Optimized**: Uses preloading, lazy loading, and optimized images
- **Responsive Design**: Works on all screen sizes
- **Accessibility**: Proper ARIA labels and semantic HTML
- **Modern Animations**: Smooth hover effects and floating animations
- **SEO Friendly**: Proper meta tags and structured content

## File Structure
```
cc360-hero-project/
├── index.html                 # Main HTML file with the hero component
├── assets/
│   └── images/
│       ├── money-floating-transparent.svg      # Hero money icon
│       ├── course-page-mockup.svg              # Templates card image
│       └── milestone-blueprint-progress.svg    # Blueprints card image
└── README.md                  # This file
```

## How to Use

1. **Open the project**: Navigate to the project directory
2. **View in browser**: Open `index.html` in your web browser
3. **Customize**: Replace the SVG placeholder images with your actual images

## Image Replacements

The component currently uses SVG placeholders. To use your actual images:

1. Replace the SVG files in `assets/images/` with your actual images
2. Update the file extensions in `index.html` from `.svg` to your image format (e.g., `.webp`, `.png`, `.jpg`)
3. Update the preload links accordingly

## Performance Features

- **Preloading**: Critical images are preloaded for faster rendering
- **Lazy Loading**: Non-critical images load only when needed
- **Optimized CSS**: Minified and efficient styles
- **Deferred Scripts**: Third-party scripts load only after user interaction

## Browser Support

Works in all modern browsers including:
- Chrome/Edge (Chromium-based)
- Firefox
- Safari
- Mobile browsers

## Customization

The component uses CSS custom properties and is easily customizable. Key areas:
- Colors: Update the gradient values in `.cc360-hero`
- Typography: Modify font sizes and weights
- Animations: Adjust timing and effects
- Layout: Change spacing and grid settings 