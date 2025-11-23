# Creative Key - Digital Agency Website

A modern, fully responsive website for Creative Key digital agency, built with HTML5, CSS3, and Bootstrap 5.3. This pixel-perfect implementation features a clean design with a professional blue color scheme, showcasing the agency's services in graphic design, web development, SEO, and hosting.

## 🎯 Project Overview

Creative Key is a complete multi-page website designed to showcase a digital agency's services and attract potential clients and partners. The website features a modern, professional design with smooth animations, responsive layouts, and an intuitive user experience.

## ✨ Features

- **Fully Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Pixel-Perfect Implementation** - Matches original PSD designs exactly
- **Modern UI/UX** - Clean, professional interface with smooth transitions
- **Bootstrap 5.3** - Latest Bootstrap framework for responsive grid system
- **Accessibility Compliant** - WCAG compliant with proper ARIA labels
- **Cross-Browser Compatible** - Works on all modern browsers
- **Fast Loading** - Optimized CSS and efficient code structure
- **SEO Friendly** - Semantic HTML5 structure

## 📁 Project Structure

```
Upproject/
│
├── index.html              # Home page
├── about.html              # About Us page
├── services.html           # Services page
├── partner.html            # Partner with us page
├── contact.html            # Contact Us page
├── README.md               # Project documentation
│
├── css/
│   └── style.css           # Main stylesheet with all custom styles
│
└── assets/                 # Images and media files (if needed)
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with CSS variables
- **Bootstrap 5.3** - Responsive grid system and components
- **Bootstrap Icons** - Icon library for UI elements
- **JavaScript** - Bootstrap's JavaScript for interactive components

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. **Clone or Download** the project files to your local machine

2. **Open the Website**
   - Simply open `index.html` in your web browser, OR
   - Use a local development server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. **Access the Website**
   - If using a server: Navigate to `http://localhost:8000`
   - If opening directly: Double-click `index.html`

## 📄 Pages Description

### 1. Home Page (`index.html`)
- Hero section with call-to-action buttons
- About Creative Key section
- Why Choose CreativeKey section (4 feature cards)
- Services preview (3 service cards)
- Statistics section (2.5K projects, 6+ team members, 99% satisfaction)
- Get Quote section
- Process steps (Discover & Plan, Design & Develop, Deliver & Support)
- Client testimonials
- Contact form

### 2. About Us Page (`about.html`)
- Hero section with breadcrumb navigation
- About section with team image and features
- Why Choose CreativeKey section (dark blue background)
- Our Approach section (6 approach cards)
- Testimonial and Mission section
- Partnership call-to-action section

### 3. Services Page (`services.html`)
- Hero section
- Introduction section
- Graphic Design service details
- Website Development service details
- SEO Services details
- Website Hosting Services details
- Why Choose CreativeKey section
- Contact form section

### 4. Partner with Us Page (`partner.html`)
- Hero section
- About Creative Key partnership section
- Why Partner with CreativeKey (6 benefit cards)
- Who Can Benefit section (5 target audience types)
- Partnership contact form

### 5. Contact Us Page (`contact.html`)
- Hero section
- Introduction text
- Contact information cards (Head Office, Branch Office, Working Hours)
- Contact form
- Embedded Google Maps

## 🎨 Design System

### Color Palette

```css
--primary-blue: #0d6efd    /* Primary brand color */
--dark-blue: #0a58ca        /* Dark blue for backgrounds */
--light-blue: #e7f1ff       /* Light blue for gradients */
--white: #ffffff            /* White backgrounds */
--dark-gray: #212529        /* Dark text */
--light-gray: #f8f9fa       /* Light backgrounds */
--text-gray: #6c757d        /* Secondary text */
```

### Typography

- **Font Family**: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
- **Headings**: Bold (700), various sizes (2.5rem - 3.5rem)
- **Body Text**: Regular weight, 1.6 line height
- **Badge Labels**: Uppercase, 0.75rem, letter-spacing 1.5px

### Spacing

- **Section Padding**: 5rem (80px) top and bottom
- **Card Padding**: 2rem (32px)
- **Button Padding**: 0.75rem 2rem

## 🔧 Customization Guide

### Changing Colors

Edit the CSS variables in `css/style.css`:

```css
:root {
  --primary-blue: #0d6efd;    /* Change primary color */
  --dark-blue: #0a58ca;       /* Change dark blue */
  --light-blue: #e7f1ff;      /* Change light blue */
}
```

### Updating Content

1. **Text Content**: Edit directly in HTML files
2. **Images**: Replace image URLs in `<img>` tags or add images to `assets/` folder
3. **Contact Information**: Update in all HTML files (top bar, footer, contact page)

### Adding New Sections

1. Create HTML structure following Bootstrap grid system
2. Add custom CSS classes in `css/style.css`
3. Follow existing naming conventions

### Modifying Navigation

Edit the navigation menu in all HTML files:

```html
<ul class="navbar-nav ms-auto align-items-center">
  <li class="nav-item">
    <a class="nav-link" href="your-page.html">Your Page</a>
  </li>
</ul>
```

## 📱 Responsive Breakpoints

- **Desktop**: 992px and above
- **Tablet**: 768px - 991px
- **Mobile**: Below 768px
- **Small Mobile**: Below 576px

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 📝 Key Components

### Buttons
- Primary buttons: Blue background with white text
- Outline buttons: Blue border with blue text
- Hover effects: Slight lift and shadow

### Cards
- White background
- Rounded corners (1rem)
- Box shadow for depth
- Hover effects with lift animation

### Forms
- Rounded input fields
- Blue focus states
- Required field indicators (*)
- Responsive grid layout

### Icons
- Bootstrap Icons library
- Consistent sizing and colors
- Accessible with ARIA labels

## 🔍 SEO Features

- Semantic HTML5 structure
- Proper heading hierarchy (h1, h2, h3)
- Meta tags (add in `<head>` section)
- Alt text for images
- Descriptive link text

## ♿ Accessibility Features

- ARIA labels on icon-only links
- Proper heading structure
- Keyboard navigation support
- Screen reader friendly
- High contrast color scheme
- Focus indicators on interactive elements

## 📞 Contact Information

**Head Office:**
- Address: Pirojpur, Kamojora, Raiganj, Uttar Dinajpur, West Bengal 733130
- Phone: +91 8276895715
- Email: hello@creativekey.net

**Branch Office:**
- Address: 3A Kalibari Road, Santoshpur, Kolkata, West Bengal 700075
- Phone: +91 8276895715
- Email: hello@creativekey.net

**Working Hours:**
- Monday - Friday: 10AM - 7PM
- Saturday: 10AM - 2PM
- Sunday: Closed

## 🎯 Services Offered

1. **Graphic Design**
   - Pre-Press & Print Design
   - Branding & Logo Design
   - Digital Graphics

2. **Website Development**
   - Custom Website Design & Development
   - E-commerce Solutions
   - Landing Pages & Business Websites

3. **SEO Services**
   - On-Page & Off-Page SEO
   - Local SEO
   - Technical SEO

4. **Website Hosting**
   - Shared Hosting
   - SSL Security & Backups
   - 24/7 Support

## 🚀 Deployment

### Static Hosting Options

1. **GitHub Pages**
   - Push to GitHub repository
   - Enable GitHub Pages in settings
   - Access via `username.github.io/repository-name`

2. **Netlify**
   - Drag and drop project folder
   - Automatic deployment
   - Free SSL certificate

3. **Vercel**
   - Connect GitHub repository
   - Automatic deployments
   - Global CDN

4. **Traditional Web Hosting**
   - Upload files via FTP
   - Ensure `index.html` is in root directory

### Pre-Deployment Checklist

- [ ] Update all contact information
- [ ] Replace placeholder images with actual images
- [ ] Update Google Maps embed with correct location
- [ ] Test all forms (add backend integration if needed)
- [ ] Test on multiple browsers and devices
- [ ] Optimize images for web
- [ ] Add meta tags for SEO
- [ ] Set up Google Analytics (if needed)

## 🐛 Troubleshooting

### Images Not Loading
- Check image URLs are correct
- Ensure images are in the correct directory
- Verify image file names match exactly

### Styles Not Applying
- Clear browser cache
- Check CSS file path is correct: `css/style.css`
- Verify Bootstrap CDN is loading

### Navigation Not Working
- Ensure Bootstrap JavaScript is loaded
- Check for JavaScript errors in browser console
- Verify all links have correct file paths

## 📚 Resources

- [Bootstrap 5.3 Documentation](https://getbootstrap.com/docs/5.3/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [HTML5 Reference](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS3 Reference](https://developer.mozilla.org/en-US/docs/Web/CSS)

## 📄 License

This project is created for Creative Key digital agency. All rights reserved.

## 👥 Credits

- **Design**: Creative Key
- **Development**: Built with HTML5, CSS3, and Bootstrap 5.3
- **Icons**: Bootstrap Icons
- **Images**: Unsplash (placeholder images - replace with actual images)

## 🔄 Version History

- **v1.0.0** (Current)
  - Initial release
  - All 5 pages implemented
  - Fully responsive design
  - Accessibility features added

## 📧 Support

For support, email hello@creativekey.net or visit the contact page.

---

**Built with ❤️ for Creative Key Digital Agency**

