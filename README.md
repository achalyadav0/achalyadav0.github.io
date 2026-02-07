# Achal Yadav - Portfolio Website

A modern, responsive portfolio website showcasing my expertise in Machine Learning, Deep Learning, and Embedded Systems.

## 🌟 Features

- **Responsive Design**: Optimized for all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, scroll animations, and dynamic content
- **Fast Loading**: Optimized performance with minimal dependencies
- **SEO Friendly**: Proper meta tags and semantic HTML
- **Accessible**: WCAG compliant with proper ARIA labels

## 🛠️ Technologies Used

- HTML5
- CSS3 (Custom Properties, Flexbox, Grid)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Syne, Space Mono)

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript functionality
├── photo.png           # Profile photo
└── README.md           # This file
```

## 🚀 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click on the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository: `achalyadav0.github.io` (or any name you prefer)
5. Make it public
6. Click "Create repository"

### Step 2: Upload Files

**Option A: Using GitHub Web Interface**

1. In your new repository, click "uploading an existing file"
2. Drag and drop all files:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `photo.png`
   - `README.md`
3. Scroll down and click "Commit changes"

**Option B: Using Git Command Line**

```bash
# Navigate to your portfolio folder
cd /path/to/your/portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial portfolio commit"

# Add remote repository (replace USERNAME with your GitHub username)
git remote add origin https://github.com/USERNAME/achalyadav0.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Your site will be published at: `https://USERNAME.github.io/REPO-NAME/`

### Step 4: Custom Domain (Optional)

If you have a custom domain:

1. In GitHub Pages settings, add your custom domain
2. Update your domain's DNS settings to point to GitHub Pages
3. Enable "Enforce HTTPS"

## 🎨 Customization

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #00d9ff;      /* Main accent color */
    --secondary-color: #ff006e;    /* Secondary accent */
    --accent-color: #ffbe0b;       /* Tertiary accent */
    --bg-dark: #0a0e27;            /* Background color */
    /* ... more colors ... */
}
```

### Updating Content

1. **Profile Photo**: Replace `photo.png` with your image
2. **Personal Information**: Edit `index.html` sections
3. **Projects**: Update the projects section in `index.html`
4. **Skills**: Modify skill levels in the skills section

### Adding Animations

The site includes smooth scroll animations. To add more:

```javascript
// In script.js
const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.classList.add('animate');
        }
    });
});
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🐛 Troubleshooting

### Issue: GitHub Pages not showing website

**Solution**: 
- Wait 5-10 minutes after enabling GitHub Pages
- Check that `index.html` is in the root directory
- Verify the branch selected in GitHub Pages settings

### Issue: Images not loading

**Solution**:
- Ensure image paths are relative (e.g., `photo.png` not `/photo.png`)
- Check file names match exactly (case-sensitive)
- Verify images are committed to the repository

### Issue: Fonts not displaying

**Solution**:
- Check internet connection (fonts load from Google Fonts CDN)
- Verify Font Awesome link in HTML is correct
- Clear browser cache

## 📞 Contact

- **Email**: achallamba0@gmail.com
- **LinkedIn**: [achal-yadav-7412151b8](https://linkedin.com/in/achal-yadav-7412151b8)
- **GitHub**: [achalyadav0](https://github.com/achalyadav0)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Inspiration from modern portfolio designs

---

**Made with ❤️ by Achal Yadav**
