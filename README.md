# 🎨 Swaleh's Portfolio

A modern, responsive, and interactive portfolio website showcasing projects, skills, and experience.

## ✨ Features

- **Responsive Design**: Fully responsive across all devices (mobile, tablet, desktop)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Navigation**: Smooth scrolling navigation with mobile menu toggle
- **Hero Section**: Eye-catching hero with animated gradient background
- **About Section**: Personal information with statistics
- **Projects Showcase**: Grid layout displaying featured projects with details
- **Skills Section**: Organized skill categories with icons
- **Contact Form**: Functional contact form for visitor inquiries
- **Social Links**: Quick access to social media profiles
- **Performance**: Optimized for fast loading and smooth interactions

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with gradients, animations, and flexbox/grid
- **JavaScript**: Interactive features and animations
- **Font Awesome**: Icon library for visual elements

## 📁 File Structure

```
Portfolio/
├── index.html      # Main HTML file
├── styles.css      # All styling and responsive design
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## 🚀 Getting Started

### Option 1: View Live (GitHub Pages)
1. Go to repository settings
2. Enable GitHub Pages
3. Select main branch as source
4. Visit the provided GitHub Pages URL

### Option 2: Local Development
1. Clone the repository
```bash
git clone https://github.com/swaleh4154-alt/Portfolio.git
```

2. Navigate to the project directory
```bash
cd Portfolio
```

3. Open `index.html` in your browser
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Or use a local server:
```bash
# Python 3
python -m http.server 8000

# Node.js (with http-server package)
http-server
```

## 🎯 Customization

### Update Personal Information
Edit the following in `index.html`:
- Name and title in the hero section
- Email address in the contact section
- Social media links
- Project details and descriptions

### Modify Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f5576c;
    /* ... other colors ... */
}
```

### Add New Projects
Add new project cards by copying and modifying the project-card div in the projects section.

### Update Skills
Modify the skill categories in the skills section with your own technologies.

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎨 Color Palette

- Primary: `#667eea` (Purple Blue)
- Secondary: `#764ba2` (Deep Purple)
- Accent: `#f5576c` (Pink)
- Dark: `#2d3436` (Dark Gray)
- Light: `#f8f9fa` (Light Gray)

## ✅ Features Included

- ✅ Smooth scroll navigation
- ✅ Mobile responsive menu
- ✅ Animated hero section
- ✅ Project showcase grid
- ✅ Skills display with categories
- ✅ Contact form (client-side)
- ✅ Social media links
- ✅ Intersection Observer animations
- ✅ Counter animations for statistics
- ✅ Typewriter effect for subtitle

## 🔧 Customization Tips

1. **Add Real Projects**: Replace placeholder projects with your actual work
2. **Update Skills**: Modify the skill categories to match your expertise
3. **Connect Forms**: Integrate form submission with a backend service (Formspree, EmailJS, etc.)
4. **Add More Sections**: Extend the portfolio with additional sections as needed
5. **Custom Domain**: Configure a custom domain in GitHub Pages settings

## 🚀 Deployment

### GitHub Pages
1. Push changes to main branch
2. Go to Settings > Pages
3. Select main branch as source
4. Your site will be live at `https://swaleh4154-alt.github.io/Portfolio`

### Other Platforms
This portfolio can be deployed on:
- Netlify
- Vercel
- Firebase Hosting
- AWS S3 + CloudFront
- Any static hosting service

## 📧 Contact Integration

To enable email functionality, integrate one of these services:
- [Formspree](https://formspree.io/)
- [EmailJS](https://www.emailjs.com/)
- [Basin](https://usebasin.com/)

## 📝 License

This portfolio template is free to use and modify for personal use.

## 🤝 Contributing

Feel free to fork this repository and create your own portfolio!

## 💡 Tips for Best Results

1. Use high-quality project screenshots
2. Keep descriptions concise and impactful
3. Regularly update projects and skills
4. Maintain consistent branding and colors
5. Test on multiple devices before deploying
6. Use meaningful meta tags for SEO

---

Made with ❤️ by Swaleh