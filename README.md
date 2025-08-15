# 🚀 Akshat Shukla - Futuristic Portfolio Website

A stunning, space-themed portfolio website showcasing AI, cybersecurity, and blockchain projects with cutting-edge animations and interactive elements.

![Portfolio Preview](assets/1920x1080.jpg)

## ✨ Features

### 🎨 Design & Visual Effects
- **Futuristic Space Theme** with black hole and cosmic backgrounds
- **Parallax Scrolling** with multiple video layers
- **Particle Effects** with floating elements
- **Smooth Animations** and micro-interactions
- **Responsive Design** for all devices
- **Dark Theme** with neon cyan accents

### 🎬 Video Backgrounds
- **Hero Section**: Blackhole video with parallax effects
- **About Section**: Aqua Blue Supernova video
- **Skills Section**: Blackhole variation video
- **Projects Section**: AI Takeover themed video
- **Contact Section**: Blackhole video

### 🎯 Interactive Elements
- **Loading Screen** with animated logo and progress bar
- **Floating Elements** with parallax movement
- **Skill Bars** with animated progress
- **Statistics Counters** with smooth counting animation
- **Project Cards** with hover effects and overlays
- **Contact Form** with validation and notifications
- **Custom Cursor** with interactive effects

### 📱 Responsive Features
- **Mobile-First Design** with optimized layouts
- **Touch-Friendly** navigation and interactions
- **Performance Optimized** for mobile devices
- **Progressive Enhancement** for older browsers

## 🛠️ Technologies Used

- **HTML5** - Semantic structure and accessibility
- **CSS3** - Advanced animations and responsive design
- **Vanilla JavaScript** - Interactive features and animations
- **Google Fonts** - Orbitron and Rajdhani typography
- **Font Awesome** - Icon library
- **CSS Grid & Flexbox** - Modern layout techniques

## 📁 File Structure

```
p_dp/
├── index.html          # Main HTML structure
├── styles.css          # All styling and animations
├── script.js           # Interactive features and effects
├── README.md           # This file
└── assets/             # Media files
    ├── Black and Blue 3D Y2k Fashion Logo.png
    ├── 092719_mt_blackhole_feat.webp
    ├── 1920x1080.jpg
    ├── Blackhole_Video_Generation.mp4
    ├── Blackhole_Video_Generation (3).mp4
    ├── Aqua_Blue_Supernova_Video_Generation.mp4
    └── Futuristic_AI_Takeover_Video_Generated.mp4
```

## 🚀 Quick Start

1. **Clone or Download** the project files
2. **Open `index.html`** in your web browser
3. **Enjoy** the futuristic portfolio experience!

### Local Development Server

For the best experience, run a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 🎨 Customization Guide

### Personal Information

Edit the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">
    <span class="title-line">YOUR</span>
    <span class="title-line">NAME</span>
</h1>
<p class="hero-subtitle">Your Title & Role</p>
<p class="hero-description">Your tagline or description</p>
```

#### About Section
```html
<div class="bio-card">
    <h3>Your Professional Title</h3>
    <p>Your bio and description...</p>
</div>
```

#### Statistics
```html
<div class="stat-number" data-target="50">0</div>
<div class="stat-label">Your Metric</div>
```

### Projects

Update the projects section with your own:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-overlay">
            <div class="project-links">
                <a href="YOUR_PROJECT_URL" target="_blank" class="project-link">
                    <i class="fas fa-external-link-alt"></i>
                </a>
            </div>
        </div>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
    </div>
</div>
```

### Contact Information

Update contact details and social links:

```html
<a href="mailto:your.email@example.com">your.email@example.com</a>
<a href="YOUR_LINKEDIN_URL" target="_blank" class="social-link">
    <i class="fab fa-linkedin"></i>
    <span>LinkedIn</span>
</a>
```

### Color Scheme

Modify the color variables in `styles.css`:

```css
/* Primary Colors */
--primary-color: #00ffff;    /* Cyan */
--secondary-color: #0080ff;  /* Blue */
--accent-color: #0040ff;     /* Dark Blue */

/* Background Colors */
--bg-dark: #000000;
--bg-darker: #001122;
```

### Skills

Update skills in the skills section:

```html
<div class="skill-item" data-skill="Your Skill">
    <div class="skill-icon">
        <i class="fas fa-icon-name"></i>
    </div>
    <div class="skill-info">
        <h4>Skill Name</h4>
        <div class="skill-bar">
            <div class="skill-progress" data-width="95"></div>
        </div>
    </div>
</div>
```

## 🎬 Video Assets

The portfolio uses several space-themed videos:

- **Hero Video**: `Blackhole_Video_Generation.mp4` - Main blackhole effect
- **About Video**: `Aqua_Blue_Supernova_Video_Generation.mp4` - Blue supernova
- **Skills Video**: `Blackhole_Video_Generation (3).mp4` - Blackhole variation
- **Projects Video**: `Futuristic_AI_Takeover_Video_Generated.mp4` - AI theme

### Adding Your Own Videos

1. Place your video files in the `assets/` folder
2. Update the video sources in `index.html`:
```html
<video autoplay muted loop class="hero-video">
    <source src="assets/YOUR_VIDEO.mp4" type="video/mp4">
</video>
```

## 📱 Mobile Optimization

The website is fully optimized for mobile devices:

- **Responsive Grid Layouts** that adapt to screen size
- **Touch-Friendly** navigation and buttons
- **Optimized Video Loading** for mobile bandwidth
- **Reduced Particle Effects** on mobile for better performance
- **Simplified Animations** on smaller screens

## 🔧 Performance Features

- **Lazy Loading** for videos and images
- **Throttled Scroll Events** for smooth performance
- **Intersection Observer** for efficient animations
- **CSS Optimizations** with hardware acceleration
- **Minimal JavaScript** footprint

## 🌐 Browser Support

- **Chrome** 60+
- **Firefox** 55+
- **Safari** 12+
- **Edge** 79+
- **Mobile Browsers** (iOS Safari, Chrome Mobile)

## 📧 Contact Form

The contact form includes:

- **Form Validation** for all fields
- **Email Format Validation**
- **Success/Error Notifications**
- **Responsive Design**
- **Accessibility Features**

Note: The form currently shows a success message. To make it functional, you'll need to add backend processing or integrate with a service like Formspree, Netlify Forms, or your own server.

## 🎯 SEO Optimization

The website includes:

- **Meta Tags** for search engines
- **Structured Data** markup
- **Semantic HTML** structure
- **Optimized Images** with alt text
- **Fast Loading** times

## 🔒 Security Features

- **Content Security Policy** headers
- **XSS Protection** in form handling
- **Secure External Links** with `target="_blank"`
- **Input Sanitization** in contact form

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to Netlify
2. Or connect your GitHub repository
3. Your site will be deployed automatically

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts to deploy

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements, consider sharing them!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Google Fonts** for the beautiful typography
- **Font Awesome** for the icon library
- **Space-themed videos** for the cosmic atmosphere
- **CSS Grid and Flexbox** for modern layouts

## 📞 Support

If you need help customizing this portfolio or have questions, feel free to reach out!

---

**Built with ❤️ for the tech community**

*This portfolio showcases the perfect blend of creativity and technology, creating an unforgettable digital experience.*
#   p o r t f o l i o  
 