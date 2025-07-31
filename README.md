# Alberto Marín - Portfolio Website

A modern, responsive portfolio website showcasing Alberto Marín's work as a Full Stack & Flutter Developer.

## 🌟 Features

- **Modern Dark Theme**: Sleek dark design with cyan accents
- **Responsive Design**: Fully responsive across all devices
- **Smooth Animations**: AOS (Animate On Scroll) animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Professional Layout**: Clean, organized sections for easy navigation
- **Code Showcase**: Interactive code window in hero section
- **Project Gallery**: Featured projects with technology tags
- **Skills Visualization**: Animated skill bars and tech stack
- **Contact Integration**: Social links and contact information

## 🚀 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Bootstrap 5**: Responsive framework
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Inter & JetBrains Mono)
- **AOS Library**: Scroll animations

## 📁 Project Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # Custom CSS styles
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🎨 Design Features

### Color Scheme
- **Primary**: #00d4ff (Cyan)
- **Secondary**: #0099cc (Dark Cyan)
- **Background**: #0a0a0a (Dark)
- **Text**: #e0e0e0 (Light Gray)
- **Accent**: #ffffff (White)

### Typography
- **Primary Font**: Inter (Clean, modern)
- **Code Font**: JetBrains Mono (Developer-friendly)

## 📱 Sections

1. **Hero Section**: Introduction with animated code window
2. **About**: Personal background and statistics
3. **Skills**: Technical skills with progress bars
4. **Projects**: Featured GitHub projects
5. **Contact**: Contact information and social links

## 🔧 Customization

### Adding New Projects
To add a new project, duplicate the project card structure in `index.html`:

```html
<div class="col-lg-6 mb-4" data-aos="fade-up" data-aos-delay="700">
  <div class="project-card">
    <div class="project-image">
      <i class="fab fa-[technology-icon]"></i>
    </div>
    <div class="project-content">
      <h3>Project Name</h3>
      <p>Project description...</p>
      <div class="project-tech">
        <span class="tech-tag">Technology</span>
      </div>
      <div class="project-links">
        <a href="[github-link]" target="_blank" class="btn btn-sm btn-outline-primary">
          <i class="fab fa-github me-1"></i>View Code
        </a>
      </div>
    </div>
  </div>
</div>
```

### Modifying Skills
Update the skill bars in the skills section by modifying the width percentage:

```html
<div class="skill-progress" style="width: 85%"></div>
```

### Changing Colors
Modify the CSS custom properties in `styles.css`:

```css
:root {
  --primary-color: #00d4ff;
  --secondary-color: #0099cc;
  --background-color: #0a0a0a;
  --text-color: #e0e0e0;
}
```

## 🚀 Getting Started

1. **Clone or Download**: Get the project files
2. **Open**: Open `index.html` in a web browser
3. **Customize**: Modify content, colors, and styling as needed
4. **Deploy**: Upload to your web hosting service

## 📋 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🎯 Performance Features

- **Optimized Images**: WebP format support
- **Minified CSS/JS**: Production-ready code
- **Lazy Loading**: Images load as needed
- **Smooth Scrolling**: Native CSS scroll behavior
- **Debounced Events**: Optimized scroll handlers

## 🔗 External Dependencies

- Bootstrap 5.3.0 (CDN)
- Font Awesome 6.4.0 (CDN)
- Google Fonts (CDN)
- AOS 2.3.1 (CDN)

## 📞 Contact Information

- **Email**: alberx1965@gmail.com
- **GitHub**: [@amarin95](https://github.com/amarin95)
- **LinkedIn**: [Alberto Marín](https://www.linkedin.com/in/amarin95/)
- **Location**: Vigo, Spain

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Bootstrap Team**: For the responsive framework
- **Font Awesome**: For the beautiful icons
- **AOS Library**: For smooth scroll animations
- **Google Fonts**: For typography

---

**Built with ❤️ and lots of ☕ by Alberto Marín**

*Last updated: January 2025* 