# Quick Customization Guide

## Essential Changes to Make

### 1. Personal Information (index.html)

**Line 8**: Change the title
```html
<title>Your Name - Portfolio</title>
```

**Line 25**: Update your name
```html
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Actual Name</span></h1>
```

**Line 26**: Update your title/role
```html
<p class="hero-subtitle">Your Job Title Here</p>
```

**Line 27-29**: Update your description
```html
<p class="hero-description">
    Your personal description here...
</p>
```

### 2. About Section (index.html)

**Lines 85-95**: Update your about text
```html
<p>
    Your personal story and background...
</p>
```

**Lines 96-110**: Update your statistics
```html
<div class="stat">
    <h3>5+</h3>
    <p>Years Experience</p>
</div>
```

### 3. Resume Section (index.html)

**Lines 130-150**: Update your work experience
```html
<div class="timeline-content">
    <h4>Your Job Title</h4>
    <h5>Company Name</h5>
    <p>Your job description...</p>
</div>
```

### 4. Projects Section (index.html)

**Lines 180-220**: Update your projects
```html
<div class="project-content">
    <h3>Your Project Name</h3>
    <p>Your project description...</p>
    <div class="project-tech">
        <span>Technology 1</span>
        <span>Technology 2</span>
    </div>
    <div class="project-links">
        <a href="your-demo-link" class="btn btn-small">Live Demo</a>
        <a href="your-github-link" class="btn btn-small btn-outline">GitHub</a>
    </div>
</div>
```

### 5. Skills Section (index.html)

**Lines 250-280**: Update your skills and percentages
```html
<div class="skill-item">
    <div class="skill-name">Your Skill</div>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 85%"></div>
    </div>
</div>
```

### 6. Education Section (index.html)

**Lines 320-340**: Update your education
```html
<div class="education-details">
    <h3>Your Degree</h3>
    <h4>Your University</h4>
    <p>Your education details...</p>
</div>
```

### 7. Achievements Section (index.html)

**Lines 370-390**: Update your achievements
```html
<div class="achievement-card">
    <div class="achievement-icon">
        <i class="fas fa-trophy"></i>
    </div>
    <h3>Your Achievement</h3>
    <p>Description of your achievement...</p>
    <span class="achievement-year">2024</span>
</div>
```

### 8. Contact Section (index.html)

**Lines 430-450**: Update your contact information
```html
<div class="contact-details">
    <h3>Email</h3>
    <p>your.email@example.com</p>
</div>
```

**Lines 480-490**: Update social media links
```html
<div class="footer-social">
    <a href="your-github" class="social-link"><i class="fab fa-github"></i></a>
    <a href="your-linkedin" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="your-twitter" class="social-link"><i class="fab fa-twitter"></i></a>
</div>
```

## Color Customization (styles.css)

**Primary Colors** (around line 300):
```css
/* Change these colors to match your brand */
--primary-color: #3498db;    /* Main blue */
--secondary-color: #f39c12;  /* Orange accent */
--dark-color: #2c3e50;       /* Dark text */
--light-color: #f8f9fa;      /* Light background */
```

## Profile Picture

Replace the user icon in the hero section with your actual photo:

1. Add your photo to the project folder
2. Replace this in index.html:
```html
<div class="profile-image">
    <img src="your-photo.jpg" alt="Your Name">
</div>
```

3. Update the CSS for the image:
```css
.profile-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 50%;
}
```

## Quick Start Checklist

- [ ] Update your name and title
- [ ] Add your personal description
- [ ] Update contact information
- [ ] Add your actual projects
- [ ] Update skills and percentages
- [ ] Add your work experience
- [ ] Update education details
- [ ] Add your achievements
- [ ] Update social media links
- [ ] Add your profile picture
- [ ] Customize colors if desired

## Testing Your Changes

1. Open `index.html` in your browser
2. Test all navigation links
3. Test the contact form
4. Test on mobile devices
5. Check all your links work

## Deployment

Once customized, you can deploy to:
- GitHub Pages (free)
- Netlify (free)
- Vercel (free)
- Any web hosting service

Your portfolio is now ready to showcase your skills and experience! 