# WordPress Developer Portfolio

A modern, elegant portfolio website showcasing WordPress development expertise and projects.

## 🚀 Quick Start

### Deploy to GitHub Pages

1. **Create a new repository**
   - Go to GitHub and create a new repository named `your-username.github.io` (replace `your-username` with your GitHub username)
   - Or create any repository name like `portfolio` if you prefer

2. **Upload files**
   - Upload `index.html` to your repository
   - Commit the file

3. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Under "Source", select "Deploy from a branch"
   - Select `main` branch and `/ (root)` folder
   - Click Save

4. **Access your site**
   - Your site will be live at `https://your-username.github.io/` (or `https://your-username.github.io/repository-name/`)
   - It may take a few minutes for the first deployment

## ✏️ Customization Guide

### 1. Update Personal Information

Replace the placeholder content with your actual information:

**Hero Section** (around line 180):
```html
<div class="hero-label">WordPress Developer</div>
<h1>Your Name</h1>
<p class="hero-description">Your personalized tagline...</p>
```

**Stats** (around line 190):
- Update the numbers to reflect your experience
- 4+ Years Experience
- Projects Delivered count
- Client Satisfaction percentage

### 2. Add Your Projects

Replace the 6 project templates with your actual projects. For each project:

```html
<div class="project-card fade-in">
    <div class="project-image">🎨</div> <!-- Change emoji or add image -->
    <div class="project-content">
        <span class="project-tag">Project Type</span>
        <h3 class="project-title">Project Name</h3>
        <p class="project-description">
            Brief description of the project, challenges solved, and results achieved.
        </p>
        <div class="project-tech">
            <span class="tech-badge">Technology 1</span>
            <span class="tech-badge">Technology 2</span>
            <!-- Add more badges as needed -->
        </div>
        <a href="YOUR_PROJECT_URL" class="project-link">View Project →</a>
    </div>
</div>
```

**To add project images instead of emojis:**
```html
<!-- Replace this: -->
<div class="project-image">🎨</div>

<!-- With this: -->
<div class="project-image" style="background-image: url('path/to/image.jpg'); background-size: cover; background-position: center;">
</div>
```

### 3. Update Contact Information

Find the Contact Section (around line 430) and update:

```html
<a href="mailto:your.email@example.com" class="contact-btn">
    📧 Get In Touch
</a>
<a href="https://github.com/yourusername" class="contact-btn secondary">
    💻 GitHub
</a>
<a href="https://linkedin.com/in/yourprofile" class="contact-btn secondary">
    💼 LinkedIn
</a>
```

### 4. Customize Skills

Update the skills sections (around line 350) with your specific expertise:
- Core Development skills
- Tools & Technologies
- Frontend & Design capabilities
- Performance & DevOps knowledge

### 5. Color Customization

Change the color scheme by modifying CSS variables (around line 15):

```css
:root {
    --bg-dark: #0a0a0a;           /* Main background */
    --bg-card: #151515;           /* Card backgrounds */
    --accent-gold: #d4af37;       /* Primary accent */
    --accent-blue: #4a9eff;       /* Secondary accent */
    --text-light: #f5f5f5;        /* Primary text */
    --text-muted: #a0a0a0;        /* Secondary text */
    --border-subtle: #2a2a2a;     /* Borders */
}
```

## 📸 Adding Images

### Option 1: Upload to Repository
1. Create an `images` folder in your repository
2. Upload your project screenshots
3. Reference them: `<img src="images/project1.jpg" alt="Project Name">`

### Option 2: Use External Hosting
- Upload to Imgur, Cloudinary, or similar
- Use the direct image URL

### Option 3: Keep Emojis
- The template uses emojis as placeholders (🎨 📱 🚀 ✨ 🏢 📰)
- These work well for a minimalist look and require no images

## 🎨 Design Features

- **Elegant Typography**: Playfair Display for headings, DM Sans for body text
- **Smooth Animations**: Fade-in effects on scroll
- **Responsive Design**: Looks great on all devices
- **Dark Theme**: Professional dark color scheme with gold/blue accents
- **Performance Optimized**: Clean, efficient code
- **Accessibility Focused**: Semantic HTML and proper contrast ratios

## 📱 Responsive

The site is fully responsive and tested on:
- Desktop (1920px and above)
- Laptop (1280px - 1919px)
- Tablet (768px - 1279px)
- Mobile (320px - 767px)

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - No dependencies required
- **Google Fonts** - Playfair Display & DM Sans
- **Intersection Observer API** - For scroll animations
- **CSS Grid & Flexbox** - Modern layout techniques
- **CSS Variables** - Easy theme customization

## 📝 Project Structure

```
portfolio/
│
├── index.html          # Main HTML file
└── README.md          # This file
```

For images (optional):
```
portfolio/
│
├── index.html
├── images/
│   ├── project1.jpg
│   ├── project2.jpg
│   └── ...
└── README.md
```

## 🔄 Updating Your Portfolio

1. Edit `index.html` with your changes
2. Commit and push to GitHub
3. Changes will be live within a few minutes

## 💡 Tips

- Keep project descriptions concise (2-3 sentences)
- Use high-quality images (1200x800px recommended)
- Update regularly with new projects
- Add real metrics when possible (load time improvements, user growth, etc.)
- Link to live sites or GitHub repositories when available

## 🌟 Customization Ideas

- Add a blog section
- Include testimonials from clients
- Add a resume/CV download button
- Integrate a contact form
- Add social media feeds
- Include video demos of projects
- Add a dark/light mode toggle

## 📄 License

Free to use for personal portfolios. Customize as needed!

## 🤝 Support

For issues or questions, feel free to reach out or open an issue in this repository.

---

**Built with care for WordPress developers who want to showcase their work professionally.**
