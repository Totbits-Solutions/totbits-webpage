# Totbits Solutions - Repository Documentation

## Project Overview

This is the official website for **Totbits Solutions**, a technology consulting and software development company. The website is built as a static HTML/CSS application showcasing the company's services, portfolio, and contact information.

**Language**: Spanish
**Type**: Static Website
**Company Focus**: Digital transformation, software development, consulting, and technology services

## Repository Structure

```
/web
├── index.html                   # Main landing page
├── banco-talento.html           # Talent/Team page
├── aviso-legal.html             # Legal notice
├── politica-privacidad.html     # Privacy policy
├── terminos-servicio.html       # Terms of service
├── style.css                    # Main stylesheet
├── logo-v2.svg                  # Company logo (SVG format)
└── .zencoder/                   # Zencoder configuration
```

## Pages

### 1. **index.html** (Main Landing Page)
The primary website entry point featuring:
- **Header**: Navigation bar with logo and menu (responsive design)
- **Hero Section**: Company value proposition and CTAs
- **Services Section**: Two main categories
  - **Custom Software Development**: Application development, solution architecture, AI/ML/Blockchain, enterprise integration
  - **Consulting & Strategy**: Digital strategy, cybersecurity, cloud computing, managed support
- **Portfolio Section**: Three case studies showcasing completed projects
  - High-performance B2B e-commerce platform
  - Intelligent logistics management system
  - Secure fintech mobile application
- **Values Section**: Key differentiators (strategic vision, constant innovation, excellence & transparency)
- **Footer/Contact Section**: Contact information, legal links

**Features**:
- Responsive navigation with mobile menu toggle
- Smooth scrolling between sections
- Modal contact form
- Social media links (WhatsApp integration)

### 2. **banco-talento.html** (Talent/Team Page)
Information about the company's talent pool and team members.

### 3. **aviso-legal.html** (Legal Notice)
Spanish legal disclaimer and company information.

### 4. **politica-privacidad.html** (Privacy Policy)
GDPR-compliant privacy policy for website visitors.

### 5. **terminos-servicio.html** (Terms of Service)
Service terms and conditions.

## Technologies Used

### Frontend
- **HTML5**: Semantic markup for content structure
- **CSS3**: Modern styling with:
  - CSS Variables for theming
  - Flexbox and Grid layouts
  - Responsive design with media queries
  - Animations and transitions
- **JavaScript (Vanilla)**: 
  - Mobile menu toggle functionality
  - Smooth scrolling behavior
  - Event handling for menu interactions

### External Libraries
- **Font Awesome 6.0**: Icon library via CDN
- **Google Fonts**: Poppins font family (weights: 300, 400, 600, 700)

### Assets
- **logo-v2.svg**: Company logo in SVG format

## Key Features

### Responsive Design
- Mobile-first approach
- Hamburger menu for mobile devices
- Flexible grid layouts (service cards, portfolio grid)
- Adaptive typography and spacing

### Interactive Elements
- Mobile menu toggle with smooth animation
- Menu closure on link click or outside click
- Smooth scrolling navigation
- Hover effects on interactive elements
- Modal contact form functionality

### Accessibility
- ARIA labels for interactive elements
- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images

## Color Scheme (CSS Variables)
- Primary color: Tech-focused accent color
- Background colors: Dark professional palette
- Text colors: Light text on dark backgrounds for readability
- Hover states: Smooth color transitions

## Styling Approach

The stylesheet (`style.css`) uses:
- CSS custom properties (variables) for consistent theming
- Mobile-first responsive design
- Container-based max-width for content
- Semantic class naming conventions
- Professional spacing and typography scales

## Contact Information (Placeholder)

The site includes sections for:
- **Address**: `[Tu Dirección/Sede Principal]`
- **Phone**: `+34 XXX XX XX XX`
- **Email**: `contacto@totbits.com`
- **WhatsApp**: Dynamic link via `wa.me/` API

*Note: Some contact details are placeholder values and should be updated with actual company information.*

## Services Offered

1. **Custom Software Development**
   - Web, mobile, and desktop applications
   - Solution architecture
   - AI/ML and blockchain integration
   - Enterprise system integration

2. **Consulting & Strategy**
   - Digital transformation strategy
   - Cybersecurity and compliance
   - Cloud infrastructure optimization
   - Managed IT support

## Browser Support

The site uses modern HTML5 and CSS3 features compatible with:
- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Setup & Deployment

### Local Development
Simply open `index.html` in a web browser. No build process or dependencies required.

### Deployment
As a static website, it can be deployed to:
- Traditional web hosting
- Static site hosting (GitHub Pages, Netlify, Vercel, etc.)
- CDN services (CloudFront, Cloudflare, etc.)

No backend server or build step is required.

## File Sizes

- `index.html`: ~16.3 KB
- `banco-talento.html`: ~16.6 KB
- `aviso-legal.html`: ~11.3 KB
- `politica-privacidad.html`: ~12.8 KB
- `terminos-servicio.html`: ~14.8 KB
- `style.css`: ~36.7 KB
- `logo-v2.svg`: ~8.5 KB

**Total**: ~116.8 KB (uncompressed)

## Notes

- The website is fully responsive and mobile-optimized
- All internal links use anchor navigation (#sections)
- External resources (fonts, icons) are loaded via CDN
- The design emphasizes professionalism and technological innovation
- Contact forms and complex functionality would require backend integration
