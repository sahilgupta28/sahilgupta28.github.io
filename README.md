# Sahil Gupta - Professional Portfolio

A modern, fully responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- ✨ **Fully Responsive Design** - Works perfectly on all devices
- 🎨 **Modern UI/UX** - Clean and professional design
- 📱 **Mobile-First Approach** - Optimized for mobile devices
- ⚡ **Smooth Animations** - Engaging user experience
- 🔧 **Interactive Elements** - Hover effects and smooth scrolling
- 📧 **Contact Form** - Ready-to-use contact functionality
- 🎯 **SEO Optimized** - Proper meta tags and structure

## Sections Included

1. **Hero Section** - Introduction with profile picture
2. **About Section** - Personal information and statistics
3. **Skills Section** - Technical skills and technologies
4. **Projects Section** - Featured projects with descriptions
5. **Experience Section** - Work history timeline
6. **Contact Section** - Contact form and information

## File Structure

```
port/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── assets/
    └── images/
        └── profile.png # Your profile picture
```

## Customization Guide

### 1. Personal Information

Edit the following in `index.html`:

- **Name**: Replace "Sahil Gupta" with your name
- **Title**: Update the job title in the hero section
- **Description**: Modify the hero description
- **About Me**: Update the about section content
- **Contact Details**: Update email, phone, and location

### 2. Profile Picture

- Replace `assets/images/profile.png` with your own profile picture
- Recommended size: 300x300 pixels or larger
- Format: PNG, JPG, or WebP

### 3. Skills Section

Update the skills in `index.html`:

```html
<div class="skill-item">
    <i class="fab fa-html5"></i>
    <span>HTML5</span>
</div>
```

Add or remove skills as needed. Use Font Awesome icons for consistency.

### 4. Projects Section

Replace the sample projects with your own:

```html
<div class="project-card">
    <div class="project-image">
        <!-- Add project screenshot here -->
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="your-live-link" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live
            </a>
        </div>
    </div>
</div>
```

### 5. Experience Section

Update the timeline with your work experience:

```html
<div class="timeline-item">
    <div class="timeline-content">
        <div class="timeline-header">
            <h3>Your Job Title</h3>
            <span class="company">Company Name</span>
            <span class="duration">2023 - Present</span>
        </div>
        <p>Job description...</p>
        <ul>
            <li>Achievement 1</li>
            <li>Achievement 2</li>
        </ul>
    </div>
</div>
```

### 6. Social Links

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

### 7. Color Scheme

To change the color scheme, update the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #7c3aed;
    --accent-color: #fbbf24;
    --text-color: #1f2937;
    --light-bg: #f8fafc;
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Optimized images
- Minified CSS and JS (for production)
- Lazy loading for images
- Smooth scrolling
- Efficient animations

## Deployment

### Option 1: GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Option 2: Netlify
1. Drag and drop your project folder to Netlify
2. Your site will be deployed instantly
3. Get a custom domain if needed

### Option 3: Vercel
1. Connect your GitHub repository to Vercel
2. Automatic deployments on every push
3. Custom domain support

## Contact Form Setup

The contact form is currently set up to show a success message. To make it functional:

1. **Netlify Forms**: Add `netlify` attribute to the form
2. **Formspree**: Replace form action with Formspree endpoint
3. **Custom Backend**: Set up your own server endpoint

Example with Formspree:
```html
<form class="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
```

## SEO Optimization

The portfolio includes:
- Proper meta tags
- Semantic HTML structure
- Alt text for images
- Open Graph tags (add your own)
- Schema markup (optional)

## Accessibility

- Keyboard navigation support
- Screen reader friendly
- Proper heading hierarchy
- Color contrast compliance
- Focus indicators

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio, feel free to:
- Check the code comments
- Review the HTML structure
- Modify CSS variables for styling
- Add your own JavaScript functionality

## Credits

- Font Awesome for icons
- Google Fonts (Inter) for typography
- CSS Grid and Flexbox for layout
- Intersection Observer API for animations

---

**Happy coding! 🚀** 