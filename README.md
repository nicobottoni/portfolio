# Nico Bottoni - Professional Portfolio

A modern, responsive portfolio website showcasing professional experience, skills, and projects as a Senior ICT System Administrator.

## 🌐 Live Website

Visit your portfolio at: `https://nicobottoni.github.io/portfolio`

## 📋 Sections

- **About Me**: Professional summary highlighting 10+ years of experience in enterprise IT
- **Skills**: Core competencies including Microsoft 365, Active Directory, Identity Management, and Automation
- **Experience**: Career progression at Würth IT Switzerland AG from 1st to 3rd level support
- **Projects**: Showcase of your notable projects (ready to customize)
- **Personal Work**: Learning projects, GitHub repositories, and certifications
- **Contact**: Links to reach out via email, LinkedIn, and GitHub

## 🎨 Features

- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Modern, professional UI with smooth animations
- ✅ Blue gradient color scheme with accent colors
- ✅ Interactive navigation with mobile hamburger menu
- ✅ Scroll-to-top button
- ✅ Intersection observer for scroll animations
- ✅ SEO friendly structure
- ✅ Font Awesome icons (6.4.0)
- ✅ Smooth scrolling navigation
- ✅ Timeline visualization for career progression

## 🔧 Customization Guide

### 1. Update Contact Information
Edit the Contact section in `index.html`:
```html
<a href="mailto:your.email@example.com">your.email@example.com</a>
<a href="https://linkedin.com/in/nicobottoni" target="_blank">linkedin.com/in/nicobottoni</a>
<a href="https://github.com/nicobottoni" target="_blank">github.com/nicobottoni</a>
```

### 2. Add Your Projects
In the **Projects** section, replace placeholder cards:
- Project title
- Description (what problem it solved, technologies used)
- Links to GitHub repository or live demo
- Relevant technology tags

### 3. Add Personal Work
In the **Personal Work** section:
- Add links to your GitHub repositories
- Links to technical blog posts or articles
- List of certifications earned
- Learning initiatives or courses completed

### 4. Customize Colors
Edit CSS variables in `style.css`:
```css
:root {
    --primary-color: #0066cc;      /* Main brand color */
    --secondary-color: #00a6ff;    /* Accent color */
    --accent-color: #ff6b6b;       /* Call-to-action */
    --text-dark: #1a1a1a;          /* Main text */
    --text-light: #666666;         /* Secondary text */
    --bg-light: #f8f9fa;           /* Light background */
    --bg-white: #ffffff;           /* White background */
}
```

### 5. Update Social Links
Ensure all social media links point to your actual profiles:
- LinkedIn profile URL
- GitHub username
- Email address

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css          # Comprehensive stylesheet
├── script.js          # Interactive features
├── README.md          # This documentation
└── .gitignore         # Git configuration
```

## 🚀 Getting Started

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/nicobottoni/portfolio.git
   cd portfolio
   ```

2. Open locally for testing:
   - Open `index.html` directly in your browser
   - Or use Live Server extension in VS Code for live reload

### Deploy to GitHub Pages
1. Push your changes to the repository:
   ```bash
   git add .
   git commit -m "Initial portfolio setup"
   git push origin main
   ```

2. Enable GitHub Pages:
   - Go to Repository Settings → Pages
   - Select `main` branch as source
   - Your portfolio will be live at: `https://nicobottoni.github.io/portfolio`

## 💡 Tips for Optimization

### Content Enhancement
- Update the About section with your latest professional focus
- Add real projects with descriptions and links
- Include links to actual GitHub repositories
- Add your certifications and learning paths

### SEO Optimization
- Update meta tags in HTML `<head>` section
- Add meaningful page title and description
- Use semantic HTML structure (already done)
- Include keywords relevant to your profession

### Performance
- The site is optimized for fast loading
- Minimal external dependencies (only Font Awesome icons)
- CSS and JavaScript are inline-optimized
- Mobile-first responsive design

### Professional Polish
- Keep content up-to-date regularly
- Add new projects as you complete them
- Share portfolio in your CV/resume
- Link to it in professional profiles

## 🔐 Privacy & Security

- This is a public portfolio - only include information you're comfortable sharing
- No backend server or database
- All static content served by GitHub Pages
- No user data collection

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Next Steps

1. **Customize Contact Info**: Update email, LinkedIn, and GitHub URLs
2. **Add Your Projects**: Replace placeholder projects with real work
3. **Update Personal Work**: Add GitHub repos, blog posts, certifications
4. **Review Content**: Ensure all information is current and accurate
5. **Share**: Add portfolio link to your CV, LinkedIn, and professional profiles

## 📞 Support

For questions about GitHub Pages deployment, visit: [GitHub Pages Documentation](https://docs.github.com/en/pages)

---

**Built with**: HTML5, CSS3, JavaScript
**Hosted on**: GitHub Pages
**Last Updated**: 2024

Made with ❤️ by Nico Bottoni