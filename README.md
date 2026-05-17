# Saichithra Saravanan - Portfolio Website

A modern, professional portfolio website showcasing embedded systems and UAV engineering expertise.

## 🌟 Features

- **Futuristic Design**: Cyber-themed aesthetic with animated grid background and gradient accents
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **AI Voice Assistant**: Interactive voice feature with Optimus Prime-inspired characteristics
- **Smooth Animations**: Professional scroll-triggered animations and hover effects
- **Complete Profile**: Showcases experience, projects, skills, education, and certifications
- **Easy Navigation**: Smooth scrolling navigation with clear sections

## 🚀 Live Demo

Once deployed, your website will be live at: `https://[your-username].github.io/[repository-name]`

## 📋 Deployment Instructions

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the **"+"** icon in the top right → **"New repository"**
3. Repository settings:
   - **Repository name**: `portfolio` (or any name you prefer)
   - **Description**: "Professional portfolio showcasing embedded systems and UAV engineering projects"
   - **Public** repository (required for free GitHub Pages)
   - ✅ Check **"Add a README file"** (optional)
4. Click **"Create repository"**

### Step 2: Upload Files

**Option A: Using GitHub Web Interface** (Easiest)

1. In your repository, click **"Add file"** → **"Upload files"**
2. Drag and drop the `index.html` file
3. Scroll down and click **"Commit changes"**

**Option B: Using Git Command Line**

```bash
# Initialize repository (if not already done)
git init

# Add your files
git add index.html

# Commit changes
git commit -m "Initial commit: Add portfolio website"

# Add remote repository (replace with your URL)
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** tab
3. Scroll down to **"Pages"** in the left sidebar
4. Under **"Source"**, select:
   - Branch: **main**
   - Folder: **/ (root)**
5. Click **"Save"**
6. Wait 1-2 minutes for deployment
7. Your site will be live at: `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

### Step 4: Verify Deployment

1. Visit your GitHub Pages URL
2. Check all sections load correctly
3. Test the AI voice assistant button (bottom right)
4. Verify mobile responsiveness

## 🎨 Customization Guide

### Updating Personal Information

Open `index.html` and modify these sections:

**Contact Information** (search for "Get In Touch"):
```html
<a href="mailto:saichithrasaravanan@gmail.com">your-email@example.com</a>
<a href="tel:+919353572750">+91-YOUR-NUMBER</a>
<a href="https://linkedin.com/in/your-profile">Connect with me</a>
```

**Projects** (search for "Projects Section"):
- Add new project cards by copying existing `<div class="project-card">` blocks
- Update titles, descriptions, and tech tags

**Experience** (search for "Experience Section"):
- Add new experiences by copying existing `<div class="experience-card">` blocks

**Skills** (search for "Skills Section"):
- Add new skills by copying `<span class="skill-item">` tags

### Color Scheme

Modify the CSS variables at the top of `<style>`:

```css
:root {
    --primary-cyan: #00ffff;        /* Main accent color */
    --primary-electric: #0af;       /* Secondary accent */
    --deep-space: #0a0e27;          /* Background color */
    --accent-orange: #ff6b35;       /* Orange accent */
    --accent-purple: #a855f7;       /* Purple accent */
}
```

### AI Voice Assistant

The voice assistant text can be modified (search for `const introText`):

```javascript
const introText = `Your custom introduction text here...`;
```

Voice characteristics (search for `utterance.rate`):
```javascript
utterance.rate = 0.85;  // Speed (0.1 to 10)
utterance.pitch = 0.7;  // Pitch (0 to 2)
utterance.volume = 1.0; // Volume (0 to 1)
```

## 📱 Mobile Optimization

The website is fully responsive with breakpoints at:
- Desktop: > 768px
- Tablet/Mobile: ≤ 768px

Mobile features:
- Simplified navigation
- Adjusted font sizes
- Optimized button sizes
- Single-column layouts

## 🔧 Browser Compatibility

Tested and working on:
- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

Note: AI Voice Assistant requires browser speech synthesis support (available in all modern browsers)

## 📄 Adding New Sections

To add a new section, copy this template:

```html
<section id="your-section-id">
    <h2 class="section-title">Your Section Title</h2>
    <p class="section-subtitle">Your subtitle</p>
    <div class="your-content">
        <!-- Your content here -->
    </div>
</section>
```

Don't forget to add navigation link:
```html
<li><a href="#your-section-id">Your Section</a></li>
```

## 🎯 SEO Optimization

To improve search engine visibility:

1. **Update Meta Tags** (add inside `<head>`):
```html
<meta name="description" content="Saichithra Saravanan - Embedded Systems & UAV Engineer. Portfolio showcasing projects in robotics, autonomous systems, and avionics.">
<meta name="keywords" content="embedded systems, UAV engineering, robotics, firmware, avionics">
<meta name="author" content="Saichithra Saravanan">
```

2. **Add Open Graph Tags** for social sharing:
```html
<meta property="og:title" content="Saichithra Saravanan | Embedded Systems Engineer">
<meta property="og:description" content="Professional portfolio showcasing embedded systems and UAV engineering projects">
<meta property="og:type" content="website">
<meta property="og:url" content="https://YOUR-USERNAME.github.io/portfolio/">
```

3. **Custom Domain** (Optional):
   - Purchase a domain (e.g., from Namecheap, GoDaddy)
   - Add `CNAME` file to repository root with your domain
   - Update DNS settings at your domain registrar
   - Enable HTTPS in GitHub Pages settings

## 🐛 Troubleshooting

### Website Not Loading
- Check GitHub Pages is enabled in Settings → Pages
- Ensure `index.html` is in the root directory
- Wait 2-3 minutes after pushing changes

### Voice Assistant Not Working
- Check browser console for errors (F12)
- Ensure HTTPS is enabled (required for speech synthesis)
- Test in Chrome/Edge first (best compatibility)

### Animations Not Smooth
- Disable browser hardware acceleration
- Test in different browser
- Check CSS animation performance

## 📞 Support

For questions or issues:
- Email: saichithrasaravanan@gmail.com
- GitHub Issues: Create an issue in this repository

## 📝 License

This portfolio website is open source and available for personal use.

## 🙏 Credits

- **Design & Development**: Custom-built portfolio
- **Fonts**: Google Fonts (Orbitron, Syne, JetBrains Mono)
- **Icons**: SVG custom icons
- **Inspiration**: Futuristic cyber aesthetics

---

**Built with precision & passion** 🚀

Last Updated: May 2026
