# The Skilled Musician - Website

A professional music school website for "The Skilled Musician" based in Kenya. This website showcases music education services, courses, and connects students and clients with the school through multiple channels.

## 📋 Project Overview

**The Skilled Musician** is a premier music school website built with modern web technologies featuring:

- ✨ Responsive design (mobile, tablet, desktop)
- 🎵 Multiple pages for courses, services, and about information
- 🎥 Video lesson showcase on the About Us page
- 📱 Easy contact options (Email, WhatsApp, Phone, Social Media)
- 🎨 Professional design inspired by Conservatoire Kenya
- 📧 Contact form with validation
- 🌐 Social media integration
- ♿ Accessible and SEO-friendly

## 📁 Project Structure

```
The skilled musician/
├── index.html                 # Home page
├── css/
│   └── styles.css            # Main stylesheet (responsive)
├── js/
│   └── script.js             # JavaScript functionality
├── pages/
│   ├── about.html            # About Us page with video lessons
│   ├── courses.html          # Courses and pricing information
│   ├── services.html         # Services offered
│   └── contact.html          # Contact page with multiple contact methods
├── images/                   # (Directory for images - add your images here)
├── videos/                   # (Directory for video files - add your videos here)
└── README.md                 # This file
```

## 🚀 Getting Started

### Prerequisites

- A web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, etc.) for customization
- A local web server (optional, for testing locally)

### Installation

1. **Clone or Download the Project**
   - Download the project files to your computer
   - Or clone from your repository

2. **Open the Website**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js (if you have http-server installed)
     http-server
     ```
   - Then navigate to `http://localhost:8000`

## 📄 Pages Description

### 1. **Home Page** (`index.html`)
- Hero section with call-to-action
- Welcome section introducing the school
- Featured courses preview
- Call-to-action for getting in touch

### 2. **About Us** (`pages/about.html`)
- School story and mission
- Video lesson demonstrations (6 sample videos)
- Meet the instructors
- Why choose The Skilled Musician

**Video Sections:**
- Piano Fundamentals
- Guitar Basics
- Vocal Training
- Drum Rhythm
- Music Theory
- Performance Tips

*Note: Video placeholders are ready for you to embed actual video content from YouTube, Vimeo, or your own hosted videos.*

### 3. **Courses** (`pages/courses.html`)
- Comprehensive course listings
- Piano courses (Beginner, Intermediate, Advanced)
- Guitar courses (Acoustic, Electric, Advanced)
- Vocal training courses
- Drums & Percussion courses
- Music Theory courses
- Special programs (Kids classes, Ensembles, Exam prep)
- Pricing for each course

### 4. **Services** (`pages/services.html`)
- Private lessons
- Group classes
- Music therapy sessions
- Performance coaching
- Instrument rental & sales
- Composition & arrangement
- Music for special events
- Recording studio access
- Corporate training

### 5. **Contact** (`pages/contact.html`)
- Contact form with validation
- Multiple contact methods:
  - Email
  - Phone
  - WhatsApp
  - Social media links
- Business hours
- FAQ section
- Social media integration

## 🎨 Design Features

### Color Scheme
- **Primary Color:** #8B4513 (Brown)
- **Secondary Color:** #D2691E (Chocolate)
- **Accent Color:** #FFD700 (Gold)
- **Dark Color:** #2c3e50
- **Light Color:** #ecf0f1

### Responsive Breakpoints
- **Mobile:** < 480px
- **Tablet:** 480px - 768px
- **Desktop:** > 768px

### Key Components
- Sticky navigation bar
- Hero section with gradient
- Card-based layouts
- Grid systems
- Form validation
- Mobile hamburger menu
- Scroll-to-top button
- Social media links

## 🔧 Customization Guide

### 1. **Update Contact Information**
Replace these placeholders throughout the site:
- Email: `info@theskilledmusician.ke`
- Phone: `+254 (0) 700 000 000`
- WhatsApp: Update the WhatsApp number
- Social media links

**Files to update:**
- `index.html` - Footer contact info
- `pages/about.html` - Footer
- `pages/courses.html` - Footer
- `pages/services.html` - Footer
- `pages/contact.html` - Contact details and social links

### 2. **Add Your Logo**
1. Add your logo image to the `images/` folder
2. Update the logo in `index.html` and all pages:
   ```html
   <img src="images/your-logo.png" alt="Logo" class="logo-img">
   ```

### 3. **Add Videos**
Replace video placeholders with actual video content:

**Option 1: YouTube/Vimeo Embeds**
```html
<iframe width="100%" height="400" 
    src="https://www.youtube.com/embed/VIDEO_ID" 
    frameborder="0" allowfullscreen>
</iframe>
```

**Option 2: Local Video Files**
```html
<video width="100%" height="400" controls>
    <source src="../videos/lesson.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

### 4. **Add Images**
1. Place images in the `images/` folder
2. Reference them in HTML:
   ```html
   <img src="images/image-name.jpg" alt="Description">
   ```

### 5. **Update Course Pricing**
Edit the pricing in `pages/courses.html` in the course-item sections:
```html
<p class="price">Price: KES X,XXX</p>
```

### 6. **Modify Colors**
Edit the CSS variables in `css/styles.css`:
```css
:root {
    --primary-color: #8B4513;
    --secondary-color: #D2691E;
    --accent-color: #FFD700;
    /* ... other colors ... */
}
```

### 7. **Update Instructor Information**
Edit the instructor cards in `pages/about.html`:
```html
<div class="instructor-card">
    <div class="instructor-image">👨‍🎓</div>
    <h3>Instructor Name</h3>
    <p class="specialty">Specialty Here</p>
    <p>Biography and experience...</p>
</div>
```

### 8. **Add Google Analytics**
Add this before `</head>` tag in all HTML files:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_ID"></script>
<script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'GA_ID');
</script>
```

## 📱 JavaScript Features

### Built-in Functionality:
1. **Mobile Menu Toggle** - Hamburger menu for mobile devices
2. **Form Validation** - Contact form with email validation
3. **Scroll Animations** - Cards fade in as they scroll into view
4. **Smooth Scrolling** - Anchor links scroll smoothly
5. **Active Navigation** - Shows which page is currently active
6. **Scroll-to-Top Button** - Quick return to top of page
7. **Alert Notifications** - User feedback for form submissions
8. **Event Tracking** - Track user interactions (ready for Google Analytics)
9. **Lazy Loading** - Optimized image loading

### JavaScript File: `js/script.js`
- Mobile navigation handling
- Contact form submission
- Email validation
- Alert system
- Scroll animations
- Event tracking
- Scroll-to-top functionality

## 🌐 Deployment

### Deploy to Web Hosting

#### Option 1: GitHub Pages
1. Push your files to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Website will be live at `username.github.io/repository-name`

#### Option 2: Traditional Web Hosting
1. Upload files via FTP to your web hosting
2. Ensure `index.html` is in the root directory
3. Visit your domain to see the live site

#### Option 3: Netlify
1. Connect your GitHub repository
2. Set build settings (no build needed for static site)
3. Deploy with one click

#### Option 4: Vercel
1. Import project from GitHub
2. Deploy automatically
3. Get a live URL instantly

## 📧 Contact Form Setup

### To Make the Contact Form Functional:

#### Option 1: Email Link (Current - Basic)
Current setup creates a mailto link. Users click send and their email client opens.

#### Option 2: FormSubmit (Recommended)
1. Visit [formsubmit.co](https://formsubmit.co)
2. Update form action:
```html
<form action="https://formsubmit.co/your-email@example.com" method="POST">
    <!-- form fields -->
</form>
```

#### Option 3: Netlify Forms
If deployed on Netlify, add `netlify` attribute:
```html
<form name="contact" method="POST" netlify>
    <!-- form fields -->
</form>
```

#### Option 4: Custom Backend
Create a backend service using Node.js, Python, PHP, etc. to handle form submissions.

## 🔐 Security Notes

1. **Never commit API keys** to version control
2. **Validate all form inputs** on backend
3. **Use HTTPS** on production
4. **Keep sensitive information** out of client-side code
5. **Update dependencies** regularly

## ⚡ Performance Tips

1. **Optimize Images**
   - Use responsive images
   - Compress images before uploading
   - Use modern formats (WebP)

2. **Minimize CSS/JS**
   - Use minified versions for production
   - Remove unused CSS

3. **Cache Strategy**
   - Enable browser caching
   - Use CDN for static assets

4. **Mobile Performance**
   - Test on real devices
   - Use mobile-first design (already implemented)
   - Minimize animations on mobile

## 📞 WhatsApp Integration

The website includes WhatsApp contact links:
- General WhatsApp link: `https://wa.me/254700000000`
- Pre-filled message: `https://wa.me/254700000000?text=Hello%20The%20Skilled%20Musician`

Replace `254700000000` with your actual WhatsApp business number.

## 🐛 Troubleshooting

### Navigation not working
- Check file paths are correct
- Ensure CSS is loading (check browser console)
- Verify HTML structure is intact

### Styles not applying
- Clear browser cache (Ctrl+Shift+Delete)
- Check CSS file path is correct
- Verify no CSS errors in console

### Form not submitting
- Check browser console for JavaScript errors
- Verify email validation is passing
- Ensure form fields have required attributes

### Mobile menu not working
- Check JavaScript is enabled
- Verify hamburger icon is visible on mobile
- Check for JavaScript errors in console

### Videos not displaying
- Verify video source paths are correct
- Check video format is supported
- Test with different video formats
- Check CORS settings if using external sources

## 📚 Resources

- [HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Responsive Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
- [Web Accessibility](https://www.w3.org/WAI/fundamentals/accessibility-intro/)

## 📝 License

This project is provided as-is for The Skilled Musician music school. 

## 👤 Credits

- **Design Inspiration:** Conservatoire Kenya (conservatoire.co.ke)
- **School:** The Skilled Musician - Kenya
- **Year:** 2026

## 🎯 Next Steps

1. **Customize with Your Content**
   - Add actual instructor photos
   - Update all contact information
   - Add your video lessons
   - Update course pricing

2. **Set Up Backend**
   - Configure contact form to send emails
   - Add booking/enrollment system
   - Set up email notifications

3. **Deploy Your Site**
   - Choose a hosting provider
   - Configure domain name
   - Set up SSL certificate
   - Enable monitoring

4. **Marketing & SEO**
   - Add Google Analytics
   - Submit sitemap to search engines
   - Optimize meta descriptions
   - Add structured data (schema.org)

5. **Maintenance**
   - Keep content updated
   - Monitor for broken links
   - Update courses and pricing regularly
   - Respond to contact form submissions

---

**For more information or support with your website, contact your web developer.**

**Last Updated:** February 7, 2026
