# SADA Website - South African Discipline Academy

## Review
This is the official website for the South African Discipline Academy (SADA), a discipline and time management coaching programme for high school learners.

## Directory Structure

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

## CSS Architecture

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

##  Responsive Design
All styles use **flexbox** and **CSS Grid** with `flex-wrap: wrap` and `@media` queries for mobile responsiveness.

## HTML Structure Notes

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

## Key Features

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

## How to Use

1. **View Website**: Open `index.html` in a browser
2. **Edit Content**: Modify HTML files directly
3. **Style Changes**: Update `styles.css` for global styling

## 📝 Latest Updates (June 2026)

### Code Quality Enhancements
-  Eliminated CSS code duplication using reusable utility classes
-  Fixed HTML validation errors (typos in section/div attributes)
-  Added comprehensive documentation (COMPONENTS.md, IMPROVEMENTS.md)
-  Implemented .gitignore for professional GitHub sharing
-  All pages now follow consistent styling patterns

### Recent Fixes
- Fixed `services.html` section markup
- Fixed `about.html` class attribute case sensitivity
- Fixed `contact.html` spelling error (location)
- Created reusable CSS utility classes for box containers

For detailed improvement history, see [IMPROVEMENTS.md](IMPROVEMENTS.md)

##  Repository

GitHub: [majolasfiso2206-tech/sadaweb](https://github.com/majolasfiso2206-tech/sadaweb)
4. **Add Images**: Place in appropriate `/images/` subdirectory
5. **Share Code**: Push to GitHub using standard git workflow

##  Code Maintenance

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

##  Recent Fixes
-  Fixed CSS duplicate rules (footer styling)
-  Consolidated repeated box styling into utility classes
-  Fixed HTML typos (class attributes)
-  Added .gitignore for proper repo sharing

## Contact
**Email**: info@sadisciplineacademy.co.za  
**Phone**: +27 723 140 840  
**Hours**: Mon–Fri 8 AM – 5 PM | Sat 9 AM – 1 PM

 REFERENCES 
Figma (n.d.) Figma: The collaborative interface design tool. Available at: https://www.figma.com (Accessed: 
07 April 2026).   
Canva (n.d.) Canva: Online design and publishing tool. Available at: https://www.canva.com (Accessed: 08 
April 2026).   
Google Fonts (n.d.) Google Fonts. Available at: https://fonts.google.com  (Accessed: 10 April 2026).   
Afrihost (n.d.) Afrihost: Web hosting and internet services. Available at: https://www.afrihost.com 
(Accessed: 11 April 2026).   
Flaticon (n.d.) Free icons resource. Available at: https://www.flaticon.com (Accessed: 15 April 2026).   - FontAwesome (n.d.)Icon toolkit and library. Available at: https://fontawesome.com (Accessed: 15 April 
2026). 
Unsplash (n.d.) Free stock images. Available at: https://unsplash.com (Accessed: 15 April 2026).   - Pexels (n.d.) Free stock images. Available at: https://www.pexels.com (Accessed: 15 April 2026).
**Last Updated**: JUNE 22, 2026

