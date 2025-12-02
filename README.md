# Bhadresh Kotadiya - Portfolio Website

A modern, responsive portfolio website showcasing my work as a Laravel Developer. Built with pure HTML, CSS, and JavaScript with a focus on performance, SEO, and user experience.

🌐 **Live Site**: [https://bhadreshkotadiya.github.io/](https://bhadreshkotadiya.github.io/)

---

## ✨ Features

### 🎨 Design & UI/UX
- **Modern Glassmorphism Design** - Beautiful glassmorphism effects throughout
- **Dark/Light Mode Toggle** - Seamless theme switching with localStorage persistence
- **Fully Responsive** - Optimized for all devices (mobile, tablet, desktop)
- **Smooth Animations** - Scroll-triggered animations and micro-interactions
- **Animated Background** - Floating code symbols and technology logos
- **Typing Animation** - Dynamic typing effect for the hero section

### 🚀 Performance
- **Optimized Loading** - Preconnect and DNS-prefetch for external resources
- **Lazy Loading Images** - Below-the-fold images load on demand
- **Minimal Dependencies** - Pure vanilla JavaScript, no heavy frameworks
- **Fast Load Times** - Optimized CSS and efficient animations

### 📱 Sections
- **Hero Section** - Animated introduction with statistics counter
- **About Me** - Professional background and expertise
- **Skills & Expertise** - Technical skills organized by category
- **Experience** - Work history timeline
- **Education** - Academic qualifications
- **Portfolio** - Showcase of projects with tech stacks
- **Blog** - Featured blog articles
- **Contact** - Interactive contact form with celebration animation

### 🎯 SEO Optimized
- **Structured Data (JSON-LD)** - Person, WebPage, and Portfolio schemas
- **Meta Tags** - Comprehensive Open Graph and Twitter Card tags
- **Semantic HTML** - Proper use of semantic elements
- **Sitemap & Robots.txt** - Search engine optimization
- **Geographic Targeting** - Location-specific meta tags

### 💫 Interactive Elements
- **Contact Form** - Formspree integration with success celebration
- **Smooth Scrolling** - Enhanced navigation experience
- **Mobile Menu** - Hamburger menu for mobile devices
- **Scroll Animations** - Elements animate on scroll
- **Hover Effects** - Interactive hover states throughout

---

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables
- **JavaScript (ES6+)** - Vanilla JavaScript, no frameworks
- **Font Awesome 6.4.0** - Icon library
- **Google Fonts (Poppins)** - Typography

### Tools & Services
- **Formspree** - Contact form handling
- **GitHub Pages** - Hosting
- **Google Search Console** - SEO verification

---

## 📁 Project Structure

```
bhadreshkotadiya.github.io-main/
│
├── index.html              # Main HTML file
├── styles.css              # All styles and animations
├── robots.txt              # Search engine crawler instructions
├── sitemap.xml             # XML sitemap for SEO
├── README.md               # This file
│
└── assets/
    ├── favicon.ico         # Site favicon
    ├── image.png           # Logo image
    ├── developer-character.png  # About section image
    ├── blog_1.jpg          # Blog post image 1
    ├── blog_2.png          # Blog post image 2
    ├── blog_3.webp         # Blog post image 3
    └── Bhadresh -CV.pdf    # Resume/CV download
```

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, etc.)
- Git (optional, for version control)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/bhadreshkotadiya/bhadreshkotadiya.github.io.git
   cd bhadreshkotadiya.github.io
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. **View the site**
   - Navigate to `http://localhost:8000` (or the port you specified)

---

## 🎨 Customization

### Changing Colors
Edit CSS variables in `styles.css`:
```css
:root {
  --primary-color: #14b8a6;    /* Teal/Cyan accent */
  --secondary-color: #27272a;  /* Darker background */
  --bg-color: #18181b;         /* Main background */
  --text-color: #e4e4e7;       /* Light text */
}
```

### Updating Content
- **Personal Info**: Edit the HTML sections in `index.html`
- **Projects**: Update portfolio items in the Portfolio section
- **Skills**: Modify the Skills section with your expertise
- **Contact**: Update contact information and form endpoint

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Update navigation menu if needed

---

## 📧 Contact Form Setup

The contact form uses Formspree. To set up your own:

1. **Sign up** at [Formspree.io](https://formspree.io)
2. **Create a form** and get your form endpoint
3. **Update the form action** in `index.html`:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

---

## 🌐 Deployment

### GitHub Pages (Current)
1. Push code to GitHub repository
2. Go to Settings → Pages
3. Select source branch (usually `main`)
4. Site will be live at `https://yourusername.github.io`

### Other Hosting Options
- **Netlify** - Drag and drop deployment
- **Vercel** - Connect GitHub repository
- **Cloudflare Pages** - Free hosting with CDN
- **Traditional Web Hosting** - Upload files via FTP

---

## 🔧 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

---

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: Below 480px

---

## 🎯 Key Features Explained

### Typing Animation
The hero section features a typing animation for the name using vanilla JavaScript with smooth character-by-character rendering.

### Theme Toggle
Dark/light mode toggle with:
- LocalStorage persistence
- Smooth transitions
- Icon updates (moon/sun)

### Scroll Animations
Elements animate into view using Intersection Observer API for performance.

### Contact Form Celebration
On successful form submission, a confetti animation plays using pure CSS and JavaScript.

---

## 📊 Performance Metrics

- **Lighthouse Score**: Optimized for 90+ scores
- **Core Web Vitals**: Optimized for LCP, FID, CLS
- **Image Optimization**: Lazy loading and proper sizing
- **CSS Optimization**: Efficient selectors and animations

---

## 🔒 SEO Features

- ✅ Semantic HTML5
- ✅ Meta tags (title, description, keywords)
- ✅ Open Graph tags
- ✅ Twitter Card tags
- ✅ Structured data (JSON-LD)
- ✅ Sitemap.xml
- ✅ Robots.txt
- ✅ Canonical URLs
- ✅ Geographic meta tags

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Bhadresh Kotadiya**
- 🌐 Website: [bhadreshkotadiya.github.io](https://bhadreshkotadiya.github.io/)
- 💼 LinkedIn: [bhadresh-kotadiya-7b36911b6](https://www.linkedin.com/in/bhadresh-kotadiya-7b36911b6/)
- 💻 GitHub: [@bhadreshkotadiya](https://github.com/bhadreshkotadiya)
- 📧 Email: kotadiyabhadresh123@gmail.com

---

## 🙏 Acknowledgments

- **Font Awesome** - For the icon library
- **Google Fonts** - For Poppins font family
- **Formspree** - For contact form handling
- **GitHub Pages** - For free hosting

---

## 📈 Future Enhancements

- [ ] Add blog functionality
- [ ] Implement dark mode preference detection
- [ ] Add more interactive animations
- [ ] Create project detail pages
- [ ] Add testimonials section
- [ ] Implement analytics tracking

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/bhadreshkotadiya/bhadreshkotadiya.github.io/issues).

---

## ⭐ Show Your Support

If you like this project, please give it a ⭐ on GitHub!

---

**Last Updated**: December 2025
**Version**: 1.0.0
**Status**: ✅ Production Ready

