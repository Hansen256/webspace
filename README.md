# WebSpace Uganda

> Professional web development services with a dedicated team of experts transforming digital presence across Uganda and beyond.

![Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 🌟 Overview

WebSpace Uganda is a comprehensive web development service provider offering end-to-end digital solutions. Our website showcases our 15+ specialized team roles and provides a streamlined onboarding process for potential clients to submit project inquiries.

**Live Site:** [hansen256.github.io/webspace](https://hansen256.github.io/webspace/)

## ✨ Features

### 🎨 Modern Design

- Responsive glass-morphism design
- Smooth scroll animations and parallax effects
- Mobile-first responsive layout
- Custom gradient color scheme with purple and cyan accents

### 👥 Team Showcase

- 15 specialized team roles displayed in interactive cards
- Hover effects and scroll reveal animations
- Clear role descriptions and responsibilities

### 📝 Client Onboarding

- Comprehensive project inquiry form
- Real-time form validation
- Privacy consent requirement with GDPR compliance
- Transparent data handling policies

### 🔒 Security & Privacy

- Content Security Policy (CSP) headers
- XSS protection and frame options
- Comprehensive Privacy Policy
- Detailed Terms of Service
- Data protection transparency

### 📞 Contact Information

- Multiple contact channels (email, phone)
- Business location and hours
- Verified business information

## 🚀 Technology Stack

- **HTML5** - Semantic markup with accessibility features
- **CSS3** - Custom properties, Flexbox, Grid, animations
- **Vanilla JavaScript** - ES6+, Intersection Observer API
- **Google Fonts** - Inter font family
- **GitHub Pages** - Hosting platform

## 📂 Project Structure

```txt
webspace/
├── index.html                      # Main landing page
├── privacy-policy.html             # Privacy policy (GDPR compliant)
├── terms-of-service.html           # Terms of service
├── styles.css                      # Main stylesheet
├── script.js                       # Interactive functionality
├── google613eb2589abcace2.html    # Google Search Console verification
├── SECURITY-FIXES.md              # Security compliance documentation
└── README.md                       # Project documentation
```

## 🎯 Key Sections

### 1. Hero Section

Eye-catching hero with value proposition and call-to-action button leading to the onboarding form.

### 2. Team Section

Showcase of 15 specialized roles:

- Project Coordinator / Lead Web Developer
- Marketing & Client Relations
- Technical Support & Website Maintenance
- Accounts & Finances
- Graphic Design & Branding
- SEO & Online Marketing
- Customer Support & Feedback Management
- Research & Market Analysis
- Photography & Product Visualization
- Social Media Ads Specialist & Content Creation
- Sales & Client Acquisition
- Event Planning & Promotions
- Content Writing & Blogging
- Logistics & Field Support
- IT Security & Data Protection

### 3. Onboarding Form

Comprehensive form collecting:

- Personal information (name, email, phone)
- Company details (optional)
- Project type and budget range
- Timeline preferences
- Detailed specifications
- Reference websites (optional)
- Required privacy consent

### 4. Contact Section

Business information including:

- Email addresses (info@, support@)
- Phone number
- Physical location (Kampala, Uganda)
- Business hours

## 🔐 Security Features

- **Security Headers**: CSP, X-Frame-Options, X-XSS-Protection
- **Privacy Compliance**: GDPR-compliant privacy policy
- **Consent Management**: Required privacy consent before form submission
- **Data Transparency**: Clear explanation of data usage
- **Secure Forms**: Input validation and sanitization
- **Browser Compatibility**: Safari vendor prefixes for backdrop-filter

## 🎨 Design System

### Color Palette

```css
--primary-dark: #0a0a1f
--primary-purple: #6366f1
--primary-cyan: #06b6d4
--accent-pink: #ec4899
--accent-orange: #f97316
```

### Typography

- **Font Family**: Inter (Google Fonts)
- **Weights**: 400, 500, 600, 700, 800, 900

### Effects

- Glass-morphism backgrounds
- Gradient overlays
- Smooth transitions
- Scroll-triggered animations
- Parallax hero section

## 📱 Responsive Breakpoints

- **Desktop**: > 768px (full layout)
- **Tablet**: ≤ 768px (adjusted grid)
- **Mobile**: ≤ 480px (single column, simplified navigation)

## 🚀 Getting Started

### Local Development

1. **Clone the repository**

   ```bash
   git clone https://github.com/Hansen256/webspace.git
   cd webspace
   ```

2. **Open in browser**

   ```bash
   # Simply open index.html in your browser
   # Or use a local server:
   npx serve
   ```

3. **Make changes**
   - Edit HTML files for content
   - Modify `styles.css` for styling
   - Update `script.js` for functionality

### Deployment

The site is automatically deployed via GitHub Pages when changes are pushed to the `main` branch.

## 🔧 Configuration

### Form Backend Integration

The form currently includes a placeholder for backend integration. To connect to your backend:

1. Open `script.js`
2. Find the `handleFormSubmission()` function
3. Replace the placeholder with your API endpoint:

```javascript
fetch('https://api.webspaceuganda.com/inquiries', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json',
    },
    body: JSON.stringify(data)
})
.then(response => response.json())
.then(result => resolve(result))
.catch(error => reject(error));
```

### Contact Information

Update contact details in:

- `index.html` - Contact section
- `privacy-policy.html` - Contact section
- `terms-of-service.html` - Contact section

## 📊 Google Search Console

The site includes Google Search Console verification file (`google613eb2589abcace2.html`).

### Addressing Security Warnings

If Google flags the site, follow the comprehensive fixes outlined in `SECURITY-FIXES.md`:

- Privacy Policy ✓
- Terms of Service ✓
- Security Headers ✓
- Privacy Consent ✓
- Data Transparency ✓

## 🎯 Performance Optimizations

- Minimal external dependencies
- Optimized CSS with custom properties
- Efficient JavaScript with Intersection Observer
- Lazy-loaded animations
- Compressed assets

## 🌐 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari 9+ (with vendor prefixes)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Compliance

### GDPR Compliance

- Clear data collection policies
- User consent requirements
- Right to access, correct, and delete data
- Data retention policies
- Contact information for privacy concerns

### Accessibility

- Semantic HTML structure
- Keyboard navigation support
- ARIA labels where appropriate
- Sufficient color contrast
- Responsive font sizing

## 🤝 Contributing

While this is a business website, if you find any issues:

1. Check existing issues
2. Create a new issue with details
3. Fork and create a pull request if you have a fix

## 📄 License

Copyright © 2025 WebSpace Uganda. All rights reserved.

## 📞 Contact

- **Website**: [hansen256.github.io/webspace](https://hansen256.github.io/webspace/)
- **Email**: info@webspaceuganda.com <!--markdownlint-disable-line-->
- **Support**: support@webspaceuganda.com <!--markdownlint-disable-line-->
- **Phone**: +256 700 000 000
- **Location**: Kampala, Uganda

## 🙏 Acknowledgments

- **Design Inspiration**: Modern glass-morphism trends
- **Fonts**: Google Fonts (Inter)
- **Hosting**: GitHub Pages
- **Icons**: Unicode emoji characters

---

**Built with ❤️ in Uganda** | Crafting Digital Excellence | Protecting Your Privacy
