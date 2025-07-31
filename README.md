# Freelance Portfolio Website

A modern, responsive portfolio website designed for freelance professionals. Built with clean HTML, CSS, and JavaScript - no frameworks required.

## 🌟 Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Interactive Portfolio** - Clickable project cards with detailed modal popups
- **Skills Showcase** - Organized skill categories with visual tags
- **Contact Form** - Built-in contact form with form validation
- **Smooth Navigation** - Sticky navigation with smooth scrolling
- **Modern UI** - Clean design with subtle gradients and hover effects
- **Section Differentiation** - Subtle background colors to distinguish different sections

## 🎨 Design Highlights

- Clean, professional layout with modern typography
- Gradient color scheme (purple to blue)
- Card-based design elements
- Smooth transitions and hover effects
- Center-aligned skills section
- Section-specific background colors for visual flow

## 📁 Project Structure

```
├── test-site.html          # Main HTML file containing the complete website
└── README.md              # This file
```

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone [your-repo-url]
   cd [repo-name]
   ```

2. **Open the website**
   - Simply open `test-site.html` in any modern web browser
   - Or use a local server for development:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

3. **Customize the content**
   - Edit the HTML file to add your personal information
   - Update project details in the JavaScript section
   - Modify skills, services, and about sections

## ✏️ Customization Guide

### Personal Information
Update these sections in `test-site.html`:
- Header: Your name and professional title
- About section: Your background and experience
- Contact section: Your email address

### Skills
Modify the skills categories and tags in the Skills section:
```html
<div class="skill-category">
    <h3>Your Skill Category</h3>
    <div class="skill-tags">
        <span class="skill-tag">Skill 1</span>
        <span class="skill-tag">Skill 2</span>
    </div>
</div>
```

### Services
Update the services cards to reflect your offerings:
```html
<div class="service-card">
    <h3>Service Name</h3>
    <p>Service description...</p>
</div>
```

### Portfolio Projects
Edit the `projectData` object in the JavaScript section:
```javascript
const projectData = {
    project1: {
        title: "Your Project Title",
        description: "Project description...",
        details: ["Achievement 1", "Achievement 2"],
        techStack: ["Tech 1", "Tech 2"],
        links: {
            demo: "https://your-demo-url.com",
            github: "https://github.com/your-username/project"
        }
    }
};
```

### Color Scheme
The website uses a purple-to-blue gradient theme. To change colors, update these CSS variables:
- Primary gradient: `#667eea` to `#764ba2`
- Section backgrounds: `#ffffff`, `#f8f9fa`, `#f1f3f4`, `#e8f0fe`

## 🔧 Technical Details

### Built With
- **HTML5** - Semantic markup
- **CSS3** - Flexbox, Grid, Custom Properties, Animations
- **Vanilla JavaScript** - Modal functionality, smooth scrolling, form handling

### Browser Support
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

### Performance Features
- Single file architecture for fast loading
- Minimal dependencies (no external frameworks)
- Optimized CSS with efficient selectors
- Lightweight JavaScript

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and up
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🎯 Sections Overview

1. **Header** - Name and professional title with gradient background
2. **Navigation** - Sticky navigation bar with smooth scrolling
3. **About** - Personal introduction with profile placeholder
4. **Skills** - Categorized skills with visual tags
5. **Services** - Service offerings in card format
6. **Portfolio** - Interactive project showcase with modal details
7. **Contact** - Contact form and direct email
8. **Footer** - Copyright information

## 🚧 Future Enhancements

Potential improvements for future versions:
- [ ] Add blog/articles section
- [ ] Integrate with a CMS for easier content management
- [ ] Add testimonials section
- [ ] Implement dark mode toggle
- [ ] Add animations on scroll
- [ ] Integrate with email service for contact form
- [ ] Add Google Analytics tracking
- [ ] SEO optimization


