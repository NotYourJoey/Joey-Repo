# Joey's Portfolio

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design with caramel, Oxford blue, and white color scheme, smooth animations, and mobile-first responsive design.

## 🎨 Features

- **Modern Design**: Clean and professional layout with your preferred color scheme
- **Responsive**: Fully responsive design that works on all devices
- **Smooth Animations**: CSS animations and JavaScript interactions
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Scroll to Top**: Smooth scroll-to-top functionality
- **Modern Icons**: Font Awesome icons throughout the site
- **Performance Optimized**: Fast loading with optimized assets

## 🚀 Quick Start

1. **Clone or Download** the files to your local machine
2. **Open** `index.html` in your web browser
3. **Customize** the content to match your information
4. **Deploy** to your preferred hosting service

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎯 Customization Guide

### Personal Information

Edit the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>
<p class="hero-subtitle">Your Title & Description</p>
<p class="hero-description">
    Your personal description here.
</p>
```

#### About Section
```html
<p>
    Your personal story and background.
</p>
<div class="about-stats">
    <div class="stat">
        <i class="fas fa-project-diagram"></i>
        <h3>Your Number</h3>
        <p>Your Stat</p>
    </div>
    <!-- Add more stats as needed -->
</div>
```

#### Projects Section
Replace the example projects with your own:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-your-icon"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Your project description.</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i>
                View Code
            </a>
            <a href="your-demo-link" class="project-link">
                <i class="fas fa-external-link-alt"></i>
                Live Demo
            </a>
        </div>
    </div>
</div>
```

#### Skills Section
Update the skills to match your expertise:

```html
<div class="skill-item">
    <i class="fab fa-your-skill-icon"></i>
    <span>Your Skill</span>
</div>
```

#### Contact Section
Update your contact information:

```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your-email@example.com</span>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <span>Your Phone Number</span>
</div>
<div class="contact-item">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your Location</span>
</div>
```

### Social Links
Update the social media links in the contact section:

```html
<div class="social-links">
    <a href="your-github" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="your-linkedin" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <!-- Add more social links as needed -->
</div>
```

### Color Scheme

The portfolio uses CSS variables for easy color customization. Edit the `:root` section in `styles.css`:

```css
:root {
    --oxford-blue: #1a365d;        /* Main blue color */
    --oxford-blue-light: #2d5a8b;  /* Lighter blue */
    --caramel: #d69e2e;            /* Main accent color */
    --caramel-light: #f6ad55;      /* Lighter caramel */
    --caramel-dark: #b7791f;       /* Darker caramel */
    --white: #ffffff;              /* White */
    /* ... other colors */
}
```

## 🌐 Deployment Options

### GitHub Pages
1. Create a new repository on GitHub
2. Upload your portfolio files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your portfolio will be available at `https://yourusername.github.io/repository-name`

### Netlify
1. Drag and drop your portfolio folder to [Netlify](https://netlify.com)
2. Your site will be deployed instantly
3. Get a custom domain or use the provided Netlify URL

### Vercel
1. Connect your GitHub repository to [Vercel](https://vercel.com)
2. Vercel will automatically deploy your site
3. Get a custom domain or use the provided Vercel URL

### Traditional Hosting
Upload the files to any web hosting service via FTP or file manager.

## 🔧 Advanced Customization

### Adding New Sections
1. Add your HTML structure in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Add any JavaScript functionality in `script.js`

### Custom Animations
Add new CSS animations in `styles.css`:

```css
@keyframes yourAnimation {
    from {
        /* starting state */
    }
    to {
        /* ending state */
    }
}
```

### Form Integration
To make the contact form functional, you can:
- Use a service like Formspree
- Set up a backend API
- Use Netlify Forms
- Integrate with email services

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Modern icons
- **Google Fonts**: Inter font family

## 📄 License

This portfolio template is free to use and modify for personal and commercial projects.

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📞 Support

If you need help customizing your portfolio, check the comments in the code or create an issue in the repository.

---

**Happy coding! 🚀** 