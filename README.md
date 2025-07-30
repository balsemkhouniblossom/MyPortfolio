# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and excellent user experience across all devices.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, scroll animations, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Seamless navigation between sections
- **Loading Animation**: Professional loading screen
- **SEO Optimized**: Semantic HTML structure for better search engine visibility

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Setup Instructions

1. **Download/Clone** the files to your local machine
2. **Open** `index.html` in your web browser
3. **Customize** the content as needed (see customization guide below)
4. **Deploy** to your preferred hosting service

## 🎨 Customization Guide

### 1. Personal Information

Edit the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>
<p class="hero-subtitle">Full Stack Developer & Creative Problem Solver</p>
```

#### About Section
```html
<p>
    I'm a passionate developer with a love for creating meaningful digital experiences. 
    With expertise in modern web technologies, I bring ideas to life through clean, 
    efficient code and intuitive design.
</p>
```

#### Contact Information
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
<div class="contact-item">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your City, Country</span>
</div>
```

### 2. Skills & Technologies

Update the skills section in `index.html`:

```html
<div class="skill-items">
    <div class="skill-item">
        <i class="fab fa-html5"></i>
        <span>HTML5</span>
    </div>
    <!-- Add or remove skills as needed -->
</div>
```

### 3. Projects

Replace the project cards with your own projects:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-laptop-code"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description goes here...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-demo-link" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
        </div>
    </div>
</div>
```

### 4. Social Media Links

Update the social links in the contact section:

```html
<div class="social-links">
    <a href="your-github-url" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="your-linkedin-url" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <!-- Add more social links as needed -->
</div>
```

### 5. Statistics

Update your experience statistics in the about section:

```html
<div class="about-stats">
    <div class="stat">
        <h3>3+</h3>
        <p>Years Experience</p>
    </div>
    <div class="stat">
        <h3>20+</h3>
        <p>Projects Completed</p>
    </div>
    <div class="stat">
        <h3>15+</h3>
        <p>Happy Clients</p>
    </div>
</div>
```

### 6. Colors & Styling

To customize colors, edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #7c3aed;
    --accent-color: #fbbf24;
    --text-color: #1f2937;
    --light-bg: #f8fafc;
}
```

## 🌐 Deployment

### GitHub Pages
1. Create a new repository on GitHub
2. Upload your portfolio files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your portfolio will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your portfolio folder to [Netlify](https://netlify.com)
2. Your site will be deployed instantly
3. Customize the URL in the site settings

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Navigate to your portfolio folder
3. Run `vercel` and follow the prompts

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🔧 Technical Details

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family
- **Responsive Design**: Mobile-first approach

## 📞 Contact Form Setup

The contact form is currently set up for demonstration. To make it functional:

1. **Formspree** (Recommended for beginners):
   - Sign up at [formspree.io](https://formspree.io)
   - Replace the form action with your Formspree endpoint

2. **Netlify Forms**:
   - Add `netlify` attribute to the form
   - Deploy to Netlify for automatic form handling

3. **Custom Backend**:
   - Modify the form submission in `script.js`
   - Connect to your preferred backend service

## 🎯 Performance Tips

- Optimize images before adding them
- Compress CSS and JavaScript files for production
- Use a CDN for external resources
- Enable gzip compression on your server

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## 📞 Support

If you need help customizing your portfolio or have questions, feel free to reach out!

---

**Happy coding! 🚀** 