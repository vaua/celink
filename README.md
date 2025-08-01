# Celink Systems AB - Information Security Consulting

A professional, minimalistic website for an independent information security consultant. Built with HTML, CSS, and JavaScript. Perfect for GitHub Pages deployment.

## 🌟 Features

- **Professional Design**: Clean, minimalistic design with a focus on security expertise
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scrolling, hover effects, and form validation
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Fast Loading**: Optimized for performance with minimal dependencies
- **Accessibility**: Built with accessibility best practices

## 📁 File Structure

```
celink_web/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## 🚀 Quick Start

1. **Clone or download** this repository
2. **Open `index.html`** in your web browser to view the website locally
3. **Customize** the content, colors, and branding to match your company
4. **Deploy** to your preferred hosting platform

## 🎨 Customization

### Colors and Branding

The website uses a professional dark blue/gray theme. To customize:

1. **Primary Colors**: Edit the CSS variables in `styles.css`:
   ```css
   /* Main gradient colors */
   background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
   ```

2. **Company Information**: Update the following in `index.html`:
   - Company name and tagline
   - Contact information
   - Services and descriptions
   - About section content

### Content Updates

#### Company Information
- **Company Name**: Update "Celink Systems AB" throughout the HTML
- **Contact Details**: Update email, phone, and address in the contact section
- **Social Media**: Add your actual social media links

#### Services
The website includes 6 security-focused service categories:
- Security Assessments
- Compliance Consulting
- Incident Response
- Security Architecture
- Security Training
- Security Strategy

Customize these to match your actual services.

#### Statistics
Update the statistics in the About section:
- Years in security
- Professional certifications
- Service approach (independent consultant)

## 🌐 Deployment Options

### 1. GitHub Pages (Recommended)

1. **Create a new repository** on GitHub
2. **Upload all files** to the repository
3. **Go to Settings** → Pages
4. **Select source**: Deploy from a branch
5. **Choose branch**: `main` or `master`
6. **Save** - Your site will be available at `https://yourusername.github.io/repository-name`

### 2. Netlify

1. **Sign up** for a free Netlify account
2. **Drag and drop** your website folder to Netlify
3. **Custom domain** (optional): Add your domain in the site settings

### 3. Vercel

1. **Sign up** for a free Vercel account
2. **Import your repository** from GitHub
3. **Deploy** - Vercel will automatically build and deploy your site

### 4. Traditional Web Hosting

1. **Upload files** to your web hosting provider
2. **Ensure** `index.html` is in the root directory
3. **Test** the website functionality

## 📱 Mobile Optimization

The website is fully responsive and includes:
- Mobile-first design approach
- Touch-friendly navigation
- Optimized images and layouts
- Fast loading on mobile networks

## 🔧 Technical Details

### Dependencies
- **Font Awesome 6.4.0**: For icons (loaded via CDN)
- **Google Fonts (Inter)**: Modern typography (loaded via CDN)
- **No build process required**: Pure HTML, CSS, and JavaScript

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

### Performance Features
- Optimized CSS and JavaScript
- Minimal external dependencies
- Efficient animations using CSS transforms
- Lazy loading for better performance

## 📧 Contact Form

The contact form includes:
- **Client-side validation**
- **Success/error notifications**
- **Email format validation**
- **Required field checking**

**Note**: The form currently shows a success message but doesn't actually send emails. To make it functional, you'll need to:

1. **Add a backend service** (like Formspree, Netlify Forms, or your own server)
2. **Update the form action** in `index.html`
3. **Configure email handling** on your server

### Quick Form Integration Options:

#### Formspree
```html
<form action="https://formspree.io/f/your-form-id" method="POST">
```

#### Netlify Forms
```html
<form name="contact" netlify>
```

## 🎯 SEO Optimization

The website includes:
- **Meta tags** for description and keywords
- **Semantic HTML** structure
- **Proper heading hierarchy**
- **Alt text** for images (when added)
- **Fast loading times**

## 🔄 Updates and Maintenance

### Regular Updates
- **Content**: Keep company information current
- **Services**: Update service offerings as needed
- **Contact**: Ensure contact information is accurate
- **Performance**: Monitor loading times and user experience

### Adding New Sections
1. **Create HTML structure** in `index.html`
2. **Add CSS styles** in `styles.css`
3. **Include JavaScript** functionality in `script.js` if needed
4. **Update navigation** to include new sections

## 🛠️ Development

### Local Development
1. **Clone the repository**
2. **Open `index.html`** in your browser
3. **Use a local server** for testing (recommended):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

### Code Structure
- **HTML**: Semantic structure with proper accessibility
- **CSS**: Modular design with responsive breakpoints
- **JavaScript**: Vanilla JS with modern ES6+ features

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📞 Support

For questions or support, please contact:
- **Email**: info@celinksystems.se
- **Website**: [Your deployed website URL]

---

**Built with ❤️ for Celink Systems AB** 