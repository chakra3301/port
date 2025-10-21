# Portfolio Website

A modern, minimal portfolio website inspired by Are.na's clean design aesthetic. Perfect for showcasing websites, art, and other creative works.

## Features

- **Clean, minimal design** inspired by Are.na
- **Responsive layout** that works on all devices
- **Smooth animations** and hover effects
- **Easy customization** with placeholder content
- **Modern typography** using Inter font
- **Accessible navigation** with keyboard support

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization Guide

### 1. Update Personal Information

Edit the following sections in `index.html`:

- **Hero section**: Change the title and subtitle
- **About section**: Update the description and skills
- **Contact section**: Add your email, GitHub, LinkedIn, and Instagram links

### 2. Add Your Projects

#### For Websites:
Replace the placeholder cards in the "Websites" section with your actual projects:

```html
<div class="card" data-category="websites">
    <div class="card-image">
        <img src="your-website-preview.jpg" alt="Project Name">
    </div>
    <div class="card-content">
        <h3 class="card-title">Your Project Name</h3>
        <p class="card-description">Project description</p>
        <div class="card-tags">
            <span class="tag">React</span>
            <span class="tag">CSS</span>
        </div>
    </div>
</div>
```

#### For Art:
Replace the placeholder cards in the "Art" section with your artwork:

```html
<div class="card" data-category="art">
    <div class="card-image">
        <img src="your-artwork.jpg" alt="Artwork Title">
    </div>
    <div class="card-content">
        <h3 class="card-title">Artwork Title</h3>
        <p class="card-description">Artwork description</p>
        <div class="card-tags">
            <span class="tag">Digital</span>
            <span class="tag">2024</span>
        </div>
    </div>
</div>
```

### 3. Using JavaScript Utilities

The website includes utility functions to help you add content programmatically:

```javascript
// Add a new project
PortfolioUtils.addProject(
    "Project Title",
    "Project description",
    "websites", // or "art"
    ["React", "CSS", "JavaScript"], // tags
    "image-url.jpg" // optional image
);

// Update contact information
PortfolioUtils.updateContact(
    "your.email@example.com",
    "your-github-username",
    "your-linkedin-username",
    "your-instagram-username"
);

// Update about section
PortfolioUtils.updateAbout("Your new about text here");
```

### 4. Styling Customization

Key CSS variables you can modify in `styles.css`:

- **Colors**: Update the color scheme by changing hex values
- **Typography**: Modify font sizes and weights
- **Spacing**: Adjust padding and margins
- **Animations**: Customize transition durations and effects

### 5. Adding Images

1. Create an `images` folder in your project directory
2. Add your project images and artwork
3. Update the `src` attributes in your HTML to point to the correct image paths

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- Optimized CSS with minimal dependencies
- Lazy loading for images
- Smooth scroll behavior
- Efficient JavaScript with event delegation

## License

This project is open source and available under the MIT License.

## Getting Started

1. Open `index.html` in your web browser
2. Start customizing the content with your own projects
3. Add your images to the project
4. Deploy to your preferred hosting platform

Enjoy building your portfolio! 🎨
