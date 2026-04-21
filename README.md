# Professional Portfolio Website

A modern, fully-responsive portfolio website showcasing 11+ projects across Web Development, AI/ML, and Educational Tech.

## 📋 Features

✅ **Responsive Design** - Works flawlessly on desktop, tablet, and mobile
✅ **Modern UI/UX** - Clean, professional design with smooth animations
✅ **11 Featured Projects** - Complete showcase of all your projects
✅ **Project Filtering** - Filter projects by category (All, AI/ML, Web Apps, Education, Desktop)
✅ **Skills Section** - Display all technologies and programming languages
✅ **Contact Form** - Interactive contact form with validation
✅ **Smooth Scrolling** - Smooth navigation between sections
✅ **Mobile Menu** - Responsive hamburger menu for mobile devices
✅ **Back to Top Button** - Quick navigation to page top
✅ **Section Animations** - Scroll-triggered animations for visual appeal

## 📁 Project Structure

```
portfolio-demo/
├── index.html              # Main HTML file with all sections
├── css/
│   └── styles.css          # Comprehensive responsive CSS
├── js/
│   └── script.js           # Interactive JavaScript functionality
└── README.md               # This file
```

## 🎯 Project Categories

### AI/ML Projects
- **Laptop Price Predictor** - ML-powered price prediction system
- **NedHub AI Chat** - AI chatbot using GitHub Models API

### Web Applications
- **CutNow** - Queue management system for salons/barbershops
- **Studymate** - Course management platform
- **Techastra** - Multi-feature educational platform
- **Web Dev Basics** - HTML/CSS fundamentals project
- **Portfolio Website** - This portfolio itself!

### Educational Platforms
- **CodeMentor** - Django-based mentoring platform
- **HedNud** - Study materials repository
- **Python Course Materials** - Comprehensive Python programming course

### Desktop Applications
- **Tkinter Notepad** - Desktop text editor

## 🛠️ Technologies Used

**Frontend:**
- HTML5
- CSS3 (with gradients, animations, and modern layouts)
- Vanilla JavaScript (no frameworks)

**Styling Features:**
- CSS Grid & Flexbox
- CSS Animations & Transitions
- Gradient Backgrounds
- Box Shadows & Effects
- Mobile-First Responsive Design

**JavaScript Features:**
- Smooth Scrolling
- Mobile Menu Toggle
- Project Filtering
- Form Validation
- Scroll Animations (Intersection Observer API)
- Counter Animations
- Active Navigation Link Highlighting

## 🎨 Color Scheme

```css
Primary: #2563eb (Blue)
Accent: #06b6d4 (Cyan)
Secondary: #0f172a (Dark Navy)
Light: #f8fafc (Light Gray)
White: #ffffff
```

## 📱 Responsive Breakpoints

- **Desktop**: Full layout
- **Tablet**: Adjusted grid (768px and below)
- **Mobile**: Single column, stacked layout (480px and below)

## 🚀 How to Use

### Opening the Portfolio

1. **Simple Method**: Double-click `index.html` to open in your default browser
2. **VS Code**: Right-click `index.html` → Open with Live Server (if installed)
3. **Terminal**: 
   ```bash
   cd portfolio-demo
   # On Windows
   start index.html
   # On Mac
   open index.html
   # On Linux
   firefox index.html
   ```

### Customizing the Portfolio

#### Update Personal Information
1. Open `index.html` in your text editor
2. Search and replace:
   - `your.email@example.com` → Your actual email
   - `+919876543210` → Your phone number
   - `Mumbai, India` → Your location

#### Update Project Links
In the project cards section, update the links:
```html
<a href="#" class="link-btn"><i class="fas fa-github"></i> Code</a>
<a href="#" class="link-btn"><i class="fas fa-external-link-alt"></i> Demo</a>
```

Replace `#` with actual GitHub URLs and live demo links.

#### Update Social Links
In the footer section, update social media links:
```html
<a href="https://github.com/yourusername"><i class="fab fa-github"></i></a>
<a href="https://linkedin.com/in/yourusername"><i class="fab fa-linkedin-in"></i></a>
```

#### Modify Colors
In `css/styles.css`, update the color variables in `:root`:
```css
:root {
    --primary: #2563eb;      /* Change primary color */
    --accent: #06b6d4;       /* Change accent color */
    --secondary: #0f172a;    /* Change secondary color */
    /* ... other colors */
}
```

## 🎬 JavaScript Features Explained

### Mobile Menu
- Toggle menu on mobile devices
- Auto-close when a link is clicked

### Smooth Scrolling
- Click any navigation link for smooth scroll animation

### Active Navigation Link
- Highlights current section as you scroll
- Updates based on scroll position

### Project Filter
- Click filter buttons to show/hide projects
- Smooth transition animations

### Form Validation
- Checks for empty fields
- Validates email format
- Shows success message on submission

### Scroll Animations
- Elements fade and slide in when scrolled into view
- Uses Intersection Observer API for performance

### Back to Top Button
- Appears after scrolling down 300px
- Smooth scroll back to top

### Counter Animation
- Animates statistics numbers on page load

## 🔗 Sections

1. **Header** - Fixed navigation with logo and menu
2. **Hero** - Eye-catching introduction with CTA buttons
3. **About** - Brief bio and highlights
4. **Skills** - Categorized technology stack
5. **Projects** - 11 featured projects with filtering
6. **Statistics** - Key metrics and achievements
7. **Contact** - Contact form and methods
8. **Footer** - Links and social media

## ✨ Optional Enhancements

The JavaScript file includes commented-out optional features:

### Theme Toggle (Dark Mode)
Uncomment `initThemeToggle()` in `script.js` to enable dark mode toggle.

### Typing Animation
Uncomment `typeWriter()` in `script.js` to add typing animation to hero heading.

## 📊 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔍 SEO Features

- Proper semantic HTML structure
- Meta tags for viewport and character encoding
- Descriptive page title
- Organized content hierarchy

## 📦 Dependencies

This portfolio uses:
- **Font Awesome Icons** (CDN): For icons
- **Google Fonts**: Poppins and Source Code Pro
- **Vanilla JavaScript**: No external libraries required

## 🐛 Troubleshooting

**Icons not showing:**
- Check internet connection (Font Awesome is loaded from CDN)
- Verify Font Awesome CDN link in HTML

**Styling looks broken:**
- Clear browser cache (Ctrl+Shift+Delete)
- Refresh page (F5 or Ctrl+R)
- Check that CSS file path is correct

**Mobile menu not working:**
- Ensure JavaScript is enabled in browser
- Check browser console for errors (F12)

**Form not submitting:**
- Check email validation
- Ensure all fields are filled
- Check browser console for JavaScript errors

## 📝 License

This portfolio template is free to use and modify. Feel free to customize it for your personal use.

## 🎯 Next Steps

1. **Update Personal Information** - Add your name, email, phone, location
2. **Add Project Links** - Update GitHub and demo URLs for each project
3. **Update Social Links** - Add your GitHub, LinkedIn, Twitter profiles
4. **Customize Colors** - Match your personal brand
5. **Add More Projects** - Duplicate project cards and update details
6. **Deploy** - Host on GitHub Pages, Netlify, or Vercel

## 📞 Support

For issues or questions, feel free to:
- Check the code comments in HTML, CSS, and JavaScript
- Validate HTML/CSS on W3C validators
- Check browser console for error messages

## 🚀 Deployment Options

### GitHub Pages
```bash
# Push to GitHub repository
# Enable GitHub Pages in repository settings
# Your portfolio will be live at: https://username.github.io/portfolio-demo
```

### Netlify
```bash
# Drag and drop the portfolio-demo folder
# or connect your GitHub repository
# Get a free custom domain
```

### Vercel
```bash
# Deploy from GitHub repository
# Automatic deployments on push
# Free SSL certificate included
```

---

**Built with passion and clean code! 🎨💻**

Version: 1.0 | Last Updated: 2024
