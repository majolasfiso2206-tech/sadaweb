# SADA Website - South African Discipline Academy

## 📋 Project Overview
This is the official website for the South African Discipline Academy (SADA), a discipline and time management coaching programme for high school learners.

## 🗂️ Directory Structure

```
sadaweb/
├── index.html                    # Home page
├── about.html                    # About us & team page
├── services.html                 # Services & packages page
├── contact.html                  # Contact form & information
├── portal.html                   # Student portal
├── Detailed Breakdown.html       # Service details
├── styles.css                    # Main stylesheet (all pages)
├── css/                          # Additional CSS files
│   └── style.css/
├── js/                           # JavaScript files
│   └── script.js/
├── images/                       # Image assets
│   ├── hero/                     # Hero section images (logo, team)
│   ├── services/                 # Service package images
│   ├── portal/                   # Portal-related images
│   └── icons/                    # Icon files (email, phone, social media)
├── fonts/                        # Font files
├── README.md                     # This file
└── .gitignore                    # Git ignore rules
```

## 🎨 CSS Architecture

### Utility Classes (Reusable)
- `.box-container` - Standard box styling (background, padding, border-radius)
- `.box-container-large` - Large box width (1000px max)
- `.box-container-medium` - Medium box width (900px max)
- `.section-title` - Section heading styling

### Component Classes
- `.navbar` - Navigation bar
- `.welcome-box` - Hero section box
- `.mission-box` - Mission/Vision section
- `.testimonials` - Student testimonials section
- `.service-box` - Service package boxes
- `.team-box` - Team member cards
- `.breakdown-box` - Package breakdown cards
- `.contact-*` - Contact page elements
- `.portal-*` - Portal/form elements

### Color Scheme
- **Primary Orange**: `#F9751A` (Ecstasy) - Headings & accents
- **Secondary Blue**: `#739FCA` (Glacier) - Hover states & secondary headings
- **Dark Blue**: `#060B39` (Deep Cove) - Navbar & footer
- **Light Blue**: `#043283` (Catalina Blue) - Background gradient
- **Semi-transparent White**: `rgba(255,255,255,0.1)` - Content boxes

## 📱 Responsive Design
All styles use **flexbox** and **CSS Grid** with `flex-wrap: wrap` and `@media` queries for mobile responsiveness.

## 🔧 HTML Structure Notes

### Shared Components
All pages include:
1. **Navigation Bar** (`.navbar`) - Contains links to all pages
2. **Welcome Box** (`.welcome-box`) - Page header section
3. **Footer** - Contact links, social media, quick links

### Best Practices Used
- Semantic HTML5 structure
- Accessible alt text for images
- Proper form labeling
- Mobile viewport meta tag

## ✨ Key Features

### Navigation
- Consistent navbar across all pages
- Easy navigation between sections
- Quick links in footer

### Services
- Three package tiers displayed clearly
- Banking details for payments
- Contact form for inquiries

### Team Display
- Founder, manager, mentors, and staff profiles
- Team member photos and descriptions

### Contact Options
- Contact form (mailto:)
- Google Maps embed (location)
- Phone and email links
- Social media links (Facebook, WhatsApp)

## 🚀 How to Use

1. **View Website**: Open `index.html` in a browser
2. **Edit Content**: Modify HTML files directly
3. **Style Changes**: Update `styles.css` for global styling
4. **Add Images**: Place in appropriate `/images/` subdirectory
5. **Share Code**: Push to GitHub using standard git workflow

## 📝 Code Maintenance

### Common Updates
- **Add Page**: Create new `.html` file with navbar/footer template
- **Change Colors**: Update color variables in `styles.css`
- **Update Team**: Edit team member info in `about.html`
- **Modify Services**: Update package details in `services.html`

### Before Sharing Code
1. Check all links work correctly
2. Test responsive design (mobile, tablet, desktop)
3. Validate HTML with W3C validator
4. Test form submissions
5. Commit changes with clear messages

## 🐛 Recent Fixes
- ✅ Fixed CSS duplicate rules (footer styling)
- ✅ Consolidated repeated box styling into utility classes
- ✅ Fixed HTML typos (class attributes)
- ✅ Added .gitignore for proper repo sharing

## 📞 Contact
**Email**: info@sadisciplineacademy.co.za  
**Phone**: +27 723 140 840  
**Hours**: Mon–Fri 8 AM – 5 PM | Sat 9 AM – 1 PM

---
**Last Updated**: May 29, 2026

