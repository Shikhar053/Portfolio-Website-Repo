# Shikhar's Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This website showcases your professional experience, skills, and provides a way for visitors to get in touch with you.

## Features

- **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Resume Download**: Direct download link to your resume
- **Mobile-First**: Optimized for mobile devices with hamburger navigation
- **Smooth Animations**: CSS animations and JavaScript-powered interactions
- **Progress Bar**: Visual scroll progress indicator

## File Structure

```
Portfolio website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── Documents/          # Your resume folder
│   └── Resume Shikhar.pdf
└── README.md           # This file
```

## Quick Start

1. **Open the website**: Double-click on `index.html` to open it in your web browser
2. **Local Development**: For development, you can use a local server:
   - Python: `python -m http.server 8000`
   - Node.js: `npx serve .`
   - VS Code: Use the "Live Server" extension

## Customization Guide

### 1. Personal Information

Edit the following sections in `index.html`:

#### Hero Section

```html
<h1 class="hero-title">Hi, I'm [Your Name]</h1>
<p class="hero-subtitle">[Your Title] & [Your Specialty]</p>
<p class="hero-description">[Your personal description]</p>
```

#### About Section

```html
<div class="about-stats">
  <div class="stat">
    <h3>[X]+</h3>
    <p>Years Experience</p>
  </div>
  <div class="stat">
    <h3>[X]+</h3>
    <p>Projects Completed</p>
  </div>
  <div class="stat">
    <h3>[X]+</h3>
    <p>Technologies</p>
  </div>
</div>
```

### 2. Experience Section

Update the timeline items with your actual work experience:

```html
<div class="timeline-item">
  <div class="timeline-content">
    <h3>[Job Title]</h3>
    <h4>[Company Name]</h4>
    <p class="timeline-date">[Start Date] - [End Date]</p>
    <ul>
      <li>[Achievement/Responsibility 1]</li>
      <li>[Achievement/Responsibility 2]</li>
      <li>[Achievement/Responsibility 3]</li>
    </ul>
  </div>
</div>
```

### 3. Skills Section

Modify the skills to match your expertise:

```html
<div class="skill-category">
  <h3>Frontend</h3>
  <div class="skill-items">
    <span class="skill-item">[Skill 1]</span>
    <span class="skill-item">[Skill 2]</span>
    <!-- Add more skills -->
  </div>
</div>
```

### 4. Contact Information

Update your contact details:

```html
<div class="contact-item">
  <i class="fas fa-envelope"></i>
  <div>
    <h3>Email</h3>
    <p>[your.email@example.com]</p>
  </div>
</div>
<div class="contact-item">
  <i class="fas fa-phone"></i>
  <div>
    <h3>Phone</h3>
    <p>[Your Phone Number]</p>
  </div>
</div>
<div class="contact-item">
  <i class="fas fa-map-marker-alt"></i>
  <div>
    <h3>Location</h3>
    <p>[Your City, State/Country]</p>
  </div>
</div>
```

### 5. Social Media Links

Update the footer social links:

```html
<div class="social-links">
  <a href="[Your GitHub URL]" class="social-link"
    ><i class="fab fa-github"></i
  ></a>
  <a href="[Your LinkedIn URL]" class="social-link"
    ><i class="fab fa-linkedin"></i
  ></a>
  <a href="[Your Twitter URL]" class="social-link"
    ><i class="fab fa-twitter"></i
  ></a>
</div>
```

### 6. Resume Download

The resume download button is already configured to point to your PDF file:

```html
<a href="Documents/Resume Shikhar.pdf" download class="btn btn-secondary">
  <i class="fas fa-download"></i> Download Resume
</a>
```

## Color Scheme

The website uses a blue-based color scheme. To change colors, edit the CSS variables in `styles.css`:

```css
/* Primary colors */
--primary-color: #2563eb;
--primary-dark: #1d4ed8;
--accent-color: #667eea;
--accent-secondary: #764ba2;
```

## Adding Your Photo

To replace the placeholder profile icon with your photo:

1. Add your photo to the project folder
2. Update the hero section in `index.html`:

```html
<div class="hero-image">
  <img src="[path-to-your-photo]" alt="[Your Name]" class="profile-photo" />
</div>
```

3. Add CSS for the photo in `styles.css`:

```css
.profile-photo {
  width: 300px;
  height: 300px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid rgba(255, 255, 255, 0.2);
}
```

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- **Lazy Loading**: Images load only when needed
- **Smooth Scrolling**: Optimized scroll behavior
- **CSS Animations**: Hardware-accelerated animations
- **Responsive Images**: Optimized for different screen sizes

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://[username].github.io/[repository-name]`

### Netlify

1. Drag and drop your project folder to Netlify
2. Your site will be deployed automatically
3. Custom domain can be added in settings

### Vercel

1. Connect your GitHub repository to Vercel
2. Automatic deployments on every push
3. Custom domain support included

## Customization Tips

1. **Keep it Simple**: Don't overcrowd the design
2. **Use High-Quality Images**: Ensure photos are clear and professional
3. **Regular Updates**: Keep your experience and skills current
4. **Test on Mobile**: Always test the mobile experience
5. **SEO Optimization**: Add meta tags and descriptions

## Support

If you need help customizing your portfolio website:

1. Check the HTML comments for guidance
2. Review the CSS structure for styling changes
3. Modify JavaScript functions for interactive features
4. Test changes in different browsers

## License

This portfolio template is free to use and modify for personal and commercial projects.

---

**Happy Coding! 🚀**

Your portfolio website is now ready to showcase your skills and experience to the world!

