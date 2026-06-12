# Amar Agrawal - Professional Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript, optimized for GitHub Pages deployment.

## 🚀 Features

- **Modern Design**: Clean, professional layout with gradient hero section
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **SEO Optimized**: Meta tags, structured data, and search engine friendly
- **Interactive Elements**: Smooth animations, hover effects, and micro-interactions
- **Contact Form**: Functional contact form (requires Formspree setup)
- **Performance**: Optimized loading with lazy loading and efficient CSS
- **Accessibility**: Semantic HTML5 structure with proper ARIA labels

## 📁 Project Structure

```
amar-agrawal-portfolio/
├── index.html          # Main HTML file
├── style.css          # Complete styling
├── script.js          # Interactive JavaScript
├── README.md          # This file
└── Amar_Agrawal_Resume.pdf  # Resume (to be added)
```

## 🛠 Technologies Used

- **HTML5**: Semantic markup with proper structure
- **CSS3**: Modern features including Grid, Flexbox, and animations
- **JavaScript (ES6+)**: Interactive features and smooth scrolling
- **Font Awesome**: Professional icons
- **Google Fonts**: Inter font family for optimal readability

## 📱 Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About**: Professional summary with key highlights
3. **Experience**: Timeline-based work history
4. **Skills**: Categorized technical skills with tags
5. **Achievements**: Awards and key accomplishments
6. **Contact**: Contact form and professional details

## 🚀 Deployment Instructions

### Option 1: GitHub Pages (Free)

1. **Create GitHub Repository**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/amaragrawal/amaragrawal.github.io.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: main / (root)
   - Save

3. **Visit Your Site**:
   - Your site will be available at: `https://amaragrawal.github.io`

### Option 2: Custom Domain

1. **Purchase Domain**: Buy from GoDaddy, Namecheap, etc.
2. **Configure DNS**: Add CNAME record pointing to `amaragrawal.github.io`
3. **Update GitHub Settings**: Add custom domain in repository Settings → Pages
4. **Add CNAME File**: Create `CNAME` file with your domain name

### Option 3: Netlify (Free Alternative)

1. **Drag and Drop**: Visit netlify.com and drag the folder
2. **Get URL**: Instant deployment with random URL
3. **Custom Domain**: Add custom domain for free

## 📝 Customization

### Personal Information

Update these sections in `index.html`:

```html
<!-- Hero Section -->
<h1 class="hero-title">Your Name</h1>
<h2 class="hero-subtitle">Your Title</h2>

<!-- Contact Info -->
<span>your.email@gmail.com</span>
<span>+91 XXXXXXXXXX</span>
```

### Colors and Styling

Update these CSS variables in `style.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #764ba2;
    --text-color: #333;
    --background-color: #f8f9fa;
}
```

### Skills Section

Update skill tags in the HTML:

```html
<div class="skill-tags">
    <span class="skill-tag">Your Skill</span>
    <span class="skill-tag">Another Skill</span>
</div>
```

## 📊 SEO Optimization

The website includes:

- **Meta Tags**: Title, description, keywords, and Open Graph
- **Structured Data**: Proper HTML5 semantic structure
- **Performance**: Optimized images and lazy loading
- **Mobile-Friendly**: Responsive design for all devices

## 📧 Contact Form Setup

1. **Sign up for Formspree**: Visit formspree.io
2. **Create New Form**: Get your form endpoint
3. **Update Form Action**: Replace `your-form-id` in `index.html`:

```html
<form action="https://formspree.io/f/your-form-id" method="POST">
```

## 🔄 Maintenance

- **Content Updates**: Edit HTML files directly
- **Style Changes**: Modify CSS variables
- **New Features**: Add to JavaScript file
- **Performance**: Regularly check Google PageSpeed Insights

## 📈 Analytics (Optional)

Add Google Analytics to track visitors:

```html
<!-- Add before closing </head> tag -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🎯 Performance Tips

1. **Optimize Images**: Use WebP format with proper sizing
2. **Minify CSS/JS**: Use build tools for production
3. **Enable Caching**: Configure proper cache headers
4. **CDN**: Use Cloudflare for faster loading

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🐛 Troubleshooting

### Common Issues:

1. **Form Not Working**: Check Formspree configuration
2. **Images Not Loading**: Verify file paths
3. **Mobile Layout Issues**: Check viewport meta tag
4. **Slow Loading**: Optimize images and enable caching

### Debug Mode:

Add to `script.js`:

```javascript
// Enable debug mode
const DEBUG = true;
if (DEBUG) console.log('Debug mode enabled');
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create feature branch
3. Commit changes
4. Push to branch
5. Create Pull Request

---

**Made with ❤️ by Amar Agrawal**

For any questions or support, reach out at amar.agrawal2087@gmail.com
