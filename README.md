# Cuong Huynh - Portfolio Website

A modern, responsive portfolio website showcasing research experience, projects, skills, and background as a Computer Science student at the University of Oklahoma.

## Features

✨ **Modern Design**
- Clean and professional layout
- Responsive design that works on all devices (mobile, tablet, desktop)
- Smooth animations and transitions
- Modern color scheme with gradient accents

🎯 **Key Sections**
- **Hero Section**: Eye-catching introduction with call-to-action buttons
- **About**: Education, honors, awards, and key statistics
- **Research**: Three major research projects in AI/ML and web development
- **Projects**: Featured projects including Hacklahoma 2026 and coursework
- **Skills**: Programming languages, frameworks, tools, and domains
- **Contact**: Contact information and message form

🚀 **Interactive Features**
- Smooth scrolling navigation
- Mobile-responsive hamburger menu
- Form validation for contact section
- Scroll-to-top button
- Scroll animations for cards
- Active navigation highlighting based on scroll position

📱 **Responsive**
- Desktop: Full navigation menu
- Tablet: Optimized layout with perfect spacing
- Mobile: Hamburger menu with collapsible navigation

## Project Structure

```
Portfolio_website/
├── index.html          # Main HTML file
├── styles.css          # Styling and responsive design
├── script.js           # JavaScript for interactivity
├── Resume.pdf          # Source resume document
└── README.md           # This file
```

## Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required (uses standard HTML, CSS, and JavaScript)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Rickie2k6/Portfolio_Website.git
cd Portfolio_Website
```

2. Open the website:
   - Simply double-click `index.html` in your file explorer, OR
   - Right-click `index.html` and select "Open with" your preferred browser

### Development Server (Optional)

If you want to run a local development server:

**Using Python 3:**
```bash
cd Portfolio_website
python3 -m http.server 8000
```

**Using Node.js (with http-server):**
```bash
cd Portfolio_website
npx http-server -p 8000
```

Then visit `http://localhost:8000` in your browser.

## Customization

### Modify Content
Edit `index.html` to:
- Update personal information
- Add or remove sections
- Change links and contact information
- Modify project details

### Modify Styling
Edit `styles.css` to:
- Change color scheme (see `:root` CSS variables)
- Adjust fonts and typography
- Modify spacing and layout
- Update responsive breakpoints

### Modify Functionality
Edit `script.js` to:
- Add custom animations
- Implement new interactive features
- Modify form handling
- Add third-party integrations

### Color Scheme
Default colors (in `styles.css` `:root`):
- Primary: `#6366f1` (Indigo)
- Secondary: `#8b5cf6` (Violet)
- Accent: `#ec4899` (Pink)

Change these variables to customize the entire color scheme.

## Features Explained

### Mobile Hamburger Menu
- Automatically appears on screens smaller than 768px
- Click to toggle navigation menu
- Automatically closes when a link is clicked

### Smooth Scrolling
- Navigation links smoothly scroll to corresponding sections
- Uses native CSS `scroll-behavior: smooth`

### Contact Form
- Validates all fields before submission
- Opens email client with pre-filled subject and message
- Shows success feedback to user

### Scroll-to-Top Button
- Appears after scrolling down 300px
- Smooth scroll back to top
- Hover effects for better UX

### Intersection Observer
- Cards animate in as they scroll into view
- Performance-optimized using Intersection Observer API

## Browser Support

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- Mobile browsers: Full support

## Performance Optimizations

- CSS animations use `transform` and `opacity` for smooth 60fps animations
- Lazy loading of scroll animations using Intersection Observer
- Optimized media queries for responsive design
- Minimal JavaScript for faster load times
- Font Awesome icons loaded from CDN

## Contact

For inquiries or feedback:
- **Email**: cuonghn.saigon@gmail.com
- **Phone**: +1 (405) 417-4729
- **LinkedIn**: [linkedin.com/in/cuong-huynh-43823434b](https://www.linkedin.com/in/cuong-huynh-43823434b/)
- **GitHub**: github.com/Rickie2k6

## License

This portfolio website is personal and intended for professional use.

## Future Enhancements

Possible additions:
- Blog section for technical writings
- Dark mode toggle
- Multi-language support
- CMS integration for easier content management
- SEO optimization and metadata
- LinkedIn integration for automatic profile updates
- Analytics tracking
- CDN optimization for faster loading

---

Created with ❤️ by Cuong Huynh | Last Updated: February 2026
