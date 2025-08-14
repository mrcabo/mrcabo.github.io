# Diego Cabo - Senior Software Engineer Portfolio

A modern, responsive portfolio website showcasing expertise in Robotics, Computer Vision, and AI systems. Built with HTML5, CSS3, and vanilla JavaScript, designed for GitHub Pages hosting.

![Portfolio Preview](https://via.placeholder.com/800x400/667eea/ffffff?text=Diego+Cabo+Portfolio)

## 🚀 Features

- **Modern Design**: Clean, professional layout with smooth animations and gradient effects
- **Fully Responsive**: Looks great on desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scrolling, hover effects, and dynamic typing animation
- **Performance Optimized**: Fast loading with efficient CSS and JavaScript
- **SEO Friendly**: Semantic HTML structure with proper meta tags
- **Contact Form**: Functional contact form with validation (ready for backend integration)
- **Professional Focus**: Tailored for robotics and AI engineering roles
- **GitHub Pages Ready**: Optimized for GitHub Pages hosting with no build process needed

## 📋 Sections

1. **Hero Section**: Professional introduction with animated typing effect showcasing roles
2. **About**: Background in AI, robotics, and team leadership experience
3. **Skills**: Technical expertise in C++, Python, Robotics, Computer Vision, and AI
4. **Experience**: Career timeline from Bright AI, ArcBest Technologies, and academia
5. **Projects**: Featured work in edge computing, autonomous systems, and AI research
6. **Contact**: Direct contact information and LinkedIn profile integration

## 🛠️ Setup Instructions

### Option 1: GitHub Pages (Recommended)

1. **Fork or Clone**: Fork this repository or clone it to your local machine
   ```bash
   git clone https://github.com/yourusername/mrcabo.github.io.git
   ```

2. **Rename Repository**: If you forked, rename the repository to `yourusername.github.io`

3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click Save

4. **Access Your Site**: Visit `https://yourusername.github.io`

### Option 2: Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/mrcabo.github.io.git
   cd mrcabo.github.io
   ```

2. **Open with Live Server**: Use any local server solution:
   - **VS Code**: Install "Live Server" extension and click "Go Live"
   - **Python**: Run `python -m http.server 8000`
   - **Node.js**: Install `http-server` globally and run `http-server`

3. **View in Browser**: Open `http://localhost:8000` (or your server's URL)

## 🎨 Customization Guide

### Personal Information

#### Basic Details
Update the following in `index.html`:

```html
<!-- Page title is already updated -->
<title>Diego Cabo - Senior Software Engineer</title>

<!-- Navigation logo is already correct -->
<a href="#home" class="nav-logo">Diego Cabo</a>

<!-- Hero section is already updated -->
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Diego Cabo</span>
</h1>
```

#### Contact Information
Update contact details in the contact section:

```html
<!-- Email -->
<a href="mailto:dcabogolvano@gmail.com" class="contact-method">
    <i class="fas fa-envelope"></i>
    <span>dcabogolvano@gmail.com</span>
</a>

<!-- Phone -->
<a href="tel:+14793978536" class="contact-method">
    <i class="fas fa-phone"></i>
    <span>+1 (479) 397-8536</span>
</a>

<!-- Location -->
<a href="#" class="contact-method">
    <i class="fas fa-map-marker-alt"></i>
    <span>San Jose, CA</span>
</a>
```

### Content Updates

#### About Section
Replace placeholder content in the about section:

```html
<p class="about-description">
    Senior Software Engineer with 7+ years of experience specializing in robotics, 
    computer vision, and AI systems. Expert in leading technical teams and delivering 
    cutting-edge autonomous systems and edge computing solutions.
</p>

<!-- Update statistics -->
<div class="stat">
    <span class="stat-number">7+</span>
    <span class="stat-label">Years Experience</span>
</div>
```

#### Skills Section
Add/remove skills in each category:

```html
<div class="skill-items">
    <span class="skill-item">C++</span>
    <span class="skill-item">Python</span>
    <span class="skill-item">Rust</span>
    <span class="skill-item">Computer Vision</span>
    <!-- Skills are already updated in the HTML -->
</div>
```

#### Experience Timeline
Update your work experience:

```html
<div class="timeline-content">
    <div class="timeline-header">
        <h3 class="timeline-title">Senior Software Engineer</h3>
        <span class="timeline-company">Bright AI</span>
        <span class="timeline-date">April 2025 - Present</span>
    </div>
    <p class="timeline-description">
        Architected portable edge computing systems for drone inspection workflows. 
        Developed containerized edge-API middleware and collaborated on AI model 
        deployment achieving production-level accuracy.
    </p>
    <div class="timeline-skills">
        <span class="timeline-skill">Edge Computing</span>
        <span class="timeline-skill">Computer Vision</span>
    </div>
</div>
```

#### Projects Section
Update project information:

```html
<div class="project-content">
    <h3 class="project-title">Edge Computing Drone Inspection</h3>
    <p class="project-description">
        Portable edge computing system for drone inspection workflows that processes 
        imagery and generates AI-powered defect reports directly in the field without 
        cloud connectivity.
    </p>
    <div class="project-tech">
        <span class="tech-tag">C++</span>
        <span class="tech-tag">Computer Vision</span>
    </div>
    <div class="project-links">
        <a href="#" class="project-link">
            <i class="fas fa-info-circle"></i>
            Confidential
        </a>
        <a href="#" class="project-link">
            <i class="fas fa-building"></i>
            Bright AI
        </a>
    </div>
</div>
```

### Social Media Links

Update social media URLs in the contact section:

```html
<div class="social-links">
    <a href="https://www.linkedin.com/in/diegocabogolvano/" class="social-link" title="LinkedIn" target="_blank">
        <i class="fab fa-linkedin-in"></i>
    </a>
    <a href="https://github.com/mrcabo" class="social-link" title="GitHub" target="_blank">
        <i class="fab fa-github"></i>
    </a>
    <a href="#" class="social-link" title="Twitter">
        <i class="fab fa-twitter"></i>
    </a>
</div>
```

### Color Scheme

Customize colors by updating CSS variables in `styles.css`:

```css
:root {
    --primary-color: #667eea;      /* Main brand color */
    --secondary-color: #764ba2;    /* Secondary brand color */
    --accent-color: #f093fb;       /* Accent color */
    --text-dark: #2d3748;          /* Dark text */
    --text-light: #718096;         /* Light text */
    /* Update other colors as needed */
}
```

### Adding Your Photo

Replace the icon avatars with your photo:

1. Add your photo to the root directory (e.g., `diego-profile.jpg`)
2. Replace the hero avatar:
   ```html
   <div class="hero-avatar">
       <img src="diego-profile.jpg" alt="Diego Cabo" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
   </div>
   ```

### Typography

Change fonts by updating the Google Fonts import in `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

Then update the font family in `styles.css`:

```css
body {
    font-family: 'YourFont', sans-serif;
}
```

## 📧 Contact Form Setup

The contact form is currently set up with client-side validation. To make it functional:

### Option 1: Formspree (Recommended for beginners)

1. Sign up at [Formspree](https://formspree.io/)
2. Create a new form and get your form endpoint
3. Update the form action in `index.html`:
   ```html
   <form class="contact-form" id="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

### Option 2: Netlify Forms (if hosting on Netlify)

1. Add `netlify` attribute to your form:
   ```html
   <form class="contact-form" id="contact-form" netlify>
   ```

### Option 3: Custom Backend

Replace the form submission logic in `script.js` with your API endpoint:

```javascript
// Replace the setTimeout simulation with actual API call
fetch('/api/contact', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json',
    },
    body: JSON.stringify({
        name, email, subject, message
    })
})
.then(response => response.json())
.then(data => {
    showNotification('Message sent successfully!', 'success');
})
.catch(error => {
    showNotification('Error sending message. Please try again.', 'error');
});
```

## 🔧 Advanced Customization

### Adding New Sections

1. Create HTML structure in `index.html`
2. Add navigation link
3. Style the section in `styles.css`
4. Update JavaScript for smooth scrolling

### Performance Optimization

- Optimize images (use WebP format when possible)
- Minify CSS and JavaScript for production
- Enable gzip compression on your server
- Use a CDN for faster font loading

### SEO Optimization

- Update meta descriptions and titles
- Add Open Graph tags for social media sharing
- Create a sitemap.xml
- Add schema.org structured data

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you have suggestions for improvements, please open an issue or submit a pull request.

## 📞 Support

If you need help customizing your portfolio or run into any issues:

1. Check the existing issues on GitHub
2. Create a new issue with detailed information
3. Reach out via email at dcabogolvano@gmail.com

---

**Happy coding!** 🚀 Don't forget to star ⭐ this repository if you found it helpful!