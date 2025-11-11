# ReviewBoost - Smart Review Management System

A professional website for a smart review management platform that helps businesses enhance their digital reputation through intelligent QR code-based feedback collection and review routing.

## Features

### Customer-Facing Features
- **Unique QR Code Generation** - Custom branded QR codes for each business location
- **5-Star Rating System** - Simple, intuitive customer rating interface
- **Smart Review Routing** - Automatically directs customers based on their rating:
  - Low ratings (≤3 stars) → Internal feedback form with compensation
  - High ratings (≥4 stars) → Google Maps/social media review with rewards

### Business Dashboard Features
- **Analytics & Insights** - Track ratings, feedback trends, and customer sentiment
- **Offer Management** - Create and adjust discount codes and promotions
- **Multi-Location Support** - Manage QR codes across multiple branches
- **AI-Powered Automation** - Automated responses to reviews and feedback
- **Real-time Monitoring** - Live dashboard with key metrics

## Technology Stack

- **HTML5** - Semantic markup with accessibility features
- **CSS3** - Modern styling with CSS Grid, Flexbox, and animations
- **Vanilla JavaScript** - No dependencies, pure ES6+ code
- **Responsive Design** - Mobile-first approach, works on all devices

## File Structure

```
├── index.html                      # Main landing page (English)
├── README.md                       # Documentation
├── css/                            # Stylesheets
│   ├── styles.css                  # Main website styling
│   ├── styles-rtl.css              # RTL styles for Arabic
│   ├── cms-styles.css              # CMS-specific styling
│   ├── review-styles.css           # Review page styling
│   └── review-styles-rtl.css       # Review page RTL styles
├── js/                             # JavaScript files
│   ├── script.js                   # Landing page functionality
│   ├── cms-script.js               # CMS dashboard functionality
│   ├── review-script.js            # Review page functionality (English)
│   └── review-script-ar.js         # Review page functionality (Arabic)
├── pages/                          # Additional pages
│   ├── cms.html                    # Content Management System dashboard
│   ├── review.html                 # Customer review page (English)
│   └── ar/                         # Arabic pages
│       ├── index-ar.html           # Main landing page (Arabic)
│       └── review-ar.html          # Customer review page (Arabic)
└── assets/                         # Images, fonts, and other assets
```

## Sections Overview

### Landing Page (index.html)
1. **Homepage/Hero** - Compelling introduction with CTA buttons
2. **Testimonials** - Social proof from satisfied businesses
3. **How It Works** - Step-by-step process explanation
4. **Features** - Detailed feature showcase with icons
5. **Dashboard Preview** - Business dashboard mockup and capabilities
6. **Pricing** - Three-tier pricing structure (Basic, Professional, Enterprise)
7. **Contact** - Contact form and support resources
8. **Footer** - Links, newsletter signup, and social media

### Customer Review Page (review.html)
1. **Business Header** - Shows business logo, name, and location
2. **Star Rating** - Interactive 5-star rating system with labels
3. **Name Field** - Required field for customer name or username
4. **Email Field** - Optional email for verification/contact
5. **Review Title** - Short summary of the review (required)
6. **Review Text** - Detailed feedback with character counter (required)
7. **Photo Upload** - Optional photo upload (up to 5 photos, 5MB each)
8. **Smart Routing** - Automatically routes based on rating:
   - ≤3 stars: Shows apology message with discount code
   - ≥4 stars: Encourages Google Maps review with reward

### CMS Dashboard (cms.html)
1. **Overview** - Key metrics, recent activity, and performance summary
2. **QR Code Generator** - Create custom branded QR codes for each location
3. **Customer Ratings** - View rating distribution and recent customer ratings
4. **Feedback Management** - Handle low ratings (≤3 stars) with apology messages and discounts
5. **Review Tracking** - Monitor positive reviews and Google Maps integration
6. **Offers & Discounts** - Create and manage promotional codes and rewards
7. **Analytics** - Deep dive into performance metrics with charts and AI insights
8. **Settings** - Configure business profile and notification preferences

## Multilingual Support

The website is fully available in **English** and **Arabic** with:
- Complete translations of all pages
- RTL (Right-to-Left) support for Arabic
- Language switcher on all pages
- Proper Arabic typography with Cairo font
- Culturally appropriate content

### Available Languages:
- **English**: index.html, review.html
- **Arabic (العربية)**: index-ar.html, review-ar.html

## Key Functionalities

### Interactive Elements
- Smooth scrolling navigation
- Animated elements on scroll (Intersection Observer API)
- Mobile-responsive hamburger menu
- Interactive star rating demo
- Animated dashboard statistics
- Form validation and submission handling
- Language switcher with persistent selection

### User Experience
- Fast loading with optimized CSS
- Accessible design (ARIA labels, semantic HTML)
- Clear call-to-action buttons throughout
- Professional color scheme and typography
- Hover effects and transitions for better engagement

## Getting Started

1. **Open the website**: Simply open `index.html` in a modern web browser
2. **No build process required**: Pure HTML/CSS/JS - works immediately
3. **Customize**: Edit the content, colors, and branding to match your needs

## Project Organization

The project follows a clean, organized structure:

### Root Level
- `index.html` - Main entry point (English landing page)
- `README.md` - Project documentation

### CSS Folder (`/css`)
All stylesheets are organized here:
- Main styles for landing page
- RTL (Right-to-Left) styles for Arabic
- Component-specific styles (CMS, Review pages)

### JavaScript Folder (`/js`)
All JavaScript files are centralized:
- Interactive functionality for each page
- Language-specific scripts for Arabic pages

### Pages Folder (`/pages`)
Secondary pages and language variants:
- CMS dashboard
- Review submission pages
- `/ar` subfolder for Arabic translations

### Assets Folder (`/assets`)
Place for images, fonts, icons, and other media files

## Customization Guide

### Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;
    --primary-dark: #4f46e5;
    --secondary-color: #8b5cf6;
    /* ... more variables */
}
```

### Content
- Update business name: Search for "ReviewBoost" in `index.html`
- Modify pricing: Edit the pricing section in `index.html`
- Change testimonials: Update the testimonial cards
- Add your logo: Replace the text logo with an image

### Integration Points

The website includes placeholder functions for:
- Form submissions (contact and newsletter)
- CTA button actions (signup, demo requests)
- Live chat integration
- Analytics tracking

To integrate with your backend:
1. Uncomment the `fetch()` calls in `script.js`
2. Update API endpoints to match your backend
3. Add authentication as needed

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Minimal external dependencies (only Google Fonts)
- Optimized CSS with efficient selectors
- Lazy loading animations
- Fast initial page load

## Best Practices Implemented

✅ Semantic HTML5 markup
✅ Accessible design (WCAG compliant)
✅ Mobile-first responsive design
✅ SEO-friendly structure
✅ Performance optimized
✅ Cross-browser compatible
✅ Clean, maintainable code
✅ Progressive enhancement
✅ Security best practices (form validation)

## CMS Features in Detail

### 1. QR Code Generation
- Custom branded QR codes with business logo
- Multi-location support
- Downloadable in PNG/SVG formats
- Track scans per location
- Easy management and editing

### 2. Smart Rating System
- Real-time rating monitoring
- Visual rating distribution charts
- Customer sentiment tracking
- Automated routing based on rating

### 3. Low Rating Management (≤3 Stars)
- Automatic apology message display
- Internal feedback collection
- Discount code generation
- Prevent negative public reviews
- Track and resolve issues

### 4. Positive Review Encouragement (≥4 Stars)
- Redirect to Google Maps for reviews
- Offer additional rewards
- Track conversion rates
- Monitor review performance

### 5. Offers & Discounts
- Create percentage, fixed, or free item offers
- Set expiry dates
- Track usage statistics
- Separate offers for low/high ratings
- Easy activation/deactivation

### 6. Analytics & Insights
- Rating trends over time
- QR code scan analytics
- Review conversion metrics
- AI-powered insights
- Customizable time periods

## Future Enhancements

Consider adding:
- Backend API integration
- User authentication system
- Real-time data synchronization
- Payment processing integration
- Email/SMS automation
- Advanced chart libraries (Chart.js, D3.js)
- Export reports (PDF, CSV)
- Multi-language support
- Mobile app version
- Integration with other review platforms (Yelp, TripAdvisor)

## License

This project is provided as-is for your business use.

## Support

For questions or customization help, refer to the contact section of the website.
