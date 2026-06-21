#  Code Components & Templates

## Shared Navigation Bar Component

This component appears on **every page** and should remain identical for consistency.

### HTML Template (Copy to all pages):
```html
<div class="navbar">
  <nav>
    <a href="index.html">HOME</a> 
    <a href="about.html">ABOUT US</a> 
    <a href="services.html">SERVICES</a> 
    <a href="contact.html">CONTACT US</a> 
    <a href="portal.html">STUDENT PORTAL</a>
  </nav>
</div>
```

### CSS (in styles.css):
```css
.navbar {
  background-color: #060B39;
  padding: 1rem;
}

.navbar nav {
  display: flex;
  justify-content: center;
  gap: 2rem;
}

.navbar a {
  color: #F9751A;
  font-weight: 600;
  text-decoration: none;
  transition: color 0.3s ease;
}

.navbar a:hover {
  color: #739FCA;
}
```

---

## Shared Footer Component

This component appears on **every page** and should remain identical for consistency.

### HTML Template (Copy to all pages):
```html
<footer>
  <div>
    <h3>South African Discipline Academy™</h3>
    <p>Discipline Rooted in South Africa, Success Beyond Borders</p>
  </div>

  <div>
    <h4>Quick Links</h4>
    <a href="Detailed Breakdown.html">Detailed Breakdown of Our Offers</a><br>
    <a href="https://docs.google.com/forms/d/e/1FAIpQLSfvO3RG-C7baYHBlSkjq3OkxenrDCZ-SoeYzi7Da3I5WyfHOg/viewform" target="_blank">
      Schools Register Now for Workshops
    </a>
  </div>

  <div>
    <h4>Contact Us</h4>
    <a href="mailto:info@sadisciplineacademy.co.za">
      <img src="images/icons/gmail.png" alt="Email" width="30" height="30">
    </a>
    <a href="tel:+27 723 140 840">
      <img src="images/icons/phone.png" alt="Phone" width="30" height="30">
    </a>
    <p>Working Hours: Mon–Fri 8 AM – 5 PM  | Sat 9 AM – 1 PM</p>
  </div>

  <div>
    <h4>Follow Us</h4>
    <a href="https://www.facebook.com/share/1HBwMJVQP3/">
      <img src="images/icons/facebook.png" alt="Facebook" width="30" height="30">
    </a>
    <a href="https://wa.me/qr/XKIOKYFAFIOEA1">
      <img src="images/icons/whatsapp.png" alt="WhatsApp" width="30" height="30">
    </a>
  </div>
</footer>
```

### CSS (in styles.css):
```css
footer {
  background-color: #060B39;
  color: #FFFFFF;
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  padding: 2rem;
  gap: 1.5rem;
  margin-top: 3rem;
}

footer a {
  color: #F9751A;
  text-decoration: none;
}

footer a:hover {
  color: #739FCA;
}

footer img {
  margin: 0 0.5rem;
}
```

---

## Reusable Box Styling

### CSS Utility Classes:
```css
.box-container {
  background: rgba(255,255,255,0.1);
  padding: 2rem;
  border-radius: 10px;
  margin: 2rem auto;
}

.box-container-large {
  max-width: 1000px;
}

.box-container-medium {
  max-width: 900px;
}

.section-title {
  font-size: 1.8rem;
  color: #F9751A;
  margin-bottom: 1rem;
}
```

### Usage in HTML:
```html
<!-- Using utility classes for DRY code -->
<section class="mission-box box-container box-container-medium">
  <h2 class="section-title">MISSION</h2>
  <p class="mission-text">...</p>
</section>
```

---

## Welcome Box Pattern

### HTML Template:
```html
<div class="welcome-box">
  <h1>Page Title</h1>
  <h3>Page Subtitle</h3>
</div>
```

### CSS:
```css
.welcome-box {
  text-align: center;
  padding: 4rem 2rem;
  background-color: rgba(6, 11, 57, 0.8);
  border-radius: 10px;
  margin: 2rem auto;
  max-width: 900px;
}

.welcome-box h1 {
  font-size: 2rem;
  color: #F9751A;
  line-height: 1.4;
}
```

---

## Common HTML Patterns

### Service/Package Box:
```html
<div class="service-box">
  <h3>Service Title</h3>
  <img src="path/to/image.png" width="600" height="auto" alt="Description">
  <p>Service description here...</p>
</div>
```

### Team Member Card:
```html
<div class="team-box">
  <div class="team-image">
    <img src="path/to/image.jpg" alt="Name">
  </div>
  <div class="team-info">
    <h2>POSITION</h2>
    <p>Member description...</p>
  </div>
</div>
```

---

##  Checklist for New Pages

When creating a new page, include:

- [ ] Proper DOCTYPE and HTML structure
- [ ] Meta tags (charset, viewport)
- [ ] Link to `styles.css`
- [ ] Navigation bar (`.navbar`) at top
- [ ] Welcome box (`.welcome-box`) with page title
- [ ] Main content section(s)
- [ ] Footer at bottom
- [ ] Semantic HTML5 elements (`<section>`, `<header>`, `<article>`)
- [ ] Alt text for all images
- [ ] Test responsive design

---

## Naming Conventions

### CSS Classes
- Use kebab-case: `.welcome-box`, `.service-section`
- Descriptive names: `.contact-form`, `.team-image`
- Avoid single letters or abbreviations

### IDs (use sparingly)
- Reserved for unique interactive elements
- Use kebab-case: `#submit-button`

### File/Folder Names
- Lowercase with hyphens for multi-word: `detailed-breakdown.html`
- Use underscores for image files: `WhatsApp_icon.png`

---

##  Common Mistakes to I need to Avoid

1.  Copy-pasting instead of using utility classes
2.  Inconsistent navbar/footer across pages
3.  Inline styles instead of CSS classes
4.  Missing alt text on images
5.  Not testing mobile responsiveness
6.  Typos in class names (check carefully!)
7.  Unused CSS rules cluttering the stylesheet

---

##  Best Practices

1.  Use semantic HTML (`<section>`, `<article>`, `<nav>`)
2.  Keep related CSS rules together
3.  Use comments for major sections
4.  Test all links before deployment
5.  Use descriptive class names
6.  Group responsive media queries at the end
7.  Use consistent indentation (2 spaces)

---

Last Updated: May 29, 2026
