# Bayard Sheppard-Holt Art Gallery

A beautiful, responsive single-page art gallery website designed for GitHub Pages. This site showcases artwork with descriptions, medium information, and creation dates.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Image Gallery**: Grid layout showcasing artwork with descriptions
- **Interactive Elements**: Hover effects and smooth transitions
- **Easy Customization**: Simple HTML structure for easy content updates

## How to Use

### Adding Your Artwork

1. **Replace Placeholder Images**: 
   - Click on any placeholder image area to upload your artwork
   - Or manually replace the placeholder divs with `<img>` tags pointing to your images

2. **Update Artwork Information**:
   - Edit the artwork titles, descriptions, mediums, and years in the HTML
   - Each artwork is contained in a `.artwork` div

3. **Add Images to Assets**:
   - Place your image files in the `assets/images/` folder
   - Reference them in the HTML like: `<img src="assets/images/your-artwork.jpg" alt="Description">`

### Customizing the Site

#### Colors and Styling
- Edit the CSS variables in the `<style>` section
- The main gradient background can be changed in the `body` selector
- Card colors, shadows, and hover effects can be customized

#### Layout
- Adjust the grid layout by modifying the `.gallery` CSS
- Change the number of columns by updating `grid-template-columns`
- Modify card sizes by adjusting the `minmax()` values

#### Content
- Update the header title and subtitle
- Modify artwork descriptions and metadata
- Add or remove artwork cards as needed

### File Structure

```
j4holt.github.io/
├── index.html          # Main gallery page
├── _config.yml         # Jekyll configuration
├── assets/
│   └── images/         # Your artwork images
└── README.md           # This file
```

## Deployment

This site is configured for GitHub Pages and will automatically deploy when you push changes to the main branch. The `_config.yml` file is already set up with the minimal Jekyll theme.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Customization Examples

### Adding a New Artwork

```html
<div class="artwork">
    <div class="artwork-image">
        <img src="assets/images/new-artwork.jpg" alt="New Artwork">
    </div>
    <div class="artwork-content">
        <h3 class="artwork-title">Your Artwork Title</h3>
        <p class="artwork-description">
            Your artwork description goes here...
        </p>
        <div class="artwork-meta">
            <span class="artwork-medium">Your Medium</span>
            <span class="artwork-year">2024</span>
        </div>
    </div>
</div>
```

### Changing the Color Scheme

Edit the CSS in the `<style>` section:

```css
body {
    background: linear-gradient(135deg, #your-color-1 0%, #your-color-2 100%);
}
```

## License

This project is open source and available under the MIT License.

---

**Note**: This site is optimized for GitHub Pages and uses Jekyll for static site generation. Make sure your repository is named `username.github.io` for automatic deployment.
