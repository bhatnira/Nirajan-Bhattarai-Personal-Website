# Nirajan Bhattarai's Personal Website

[![Live Website](https://img.shields.io/badge/Website-Live-success?style=for-the-badge)](https://bhatnira.github.io/)
[![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-blue?style=for-the-badge&logo=github)](https://github.com/bhatnira/bhatnira.github.io)

Personal website showcasing research, publications, projects, and professional journey in AI-driven drug discovery and computational pharmaceutical sciences.

🌐 **Live Site:** [https://bhatnira.github.io/](https://bhatnira.github.io/)

---

## 📋 Table of Contents

- [Quick Start](#-quick-start)
- [Website Structure](#-website-structure)
- [Adding Content](#-adding-content)
- [Deployment](#-deployment)
- [File Structure](#-file-structure)
- [Customization](#-customization)

---

## 🚀 Quick Start

### Local Development

**Option 1: Python (Recommended)**
```bash
python3 -m http.server 8000
# Visit: http://localhost:8000/
```

**Option 2: VS Code Live Server**
1. Install "Live Server" extension
2. Right-click `index.html`
3. Select "Open with Live Server"

---

## 📂 Website Structure

### Main Pages
- **Home** - Landing page with profile
- **About** (`#impact`) - Professional background
- **Research** (`#research`) - Research areas
- **Publications** (`#publications`) - Academic papers
- **Contact** (`#contact`) - Contact info

### Content Sections
- **Material** (`#materials`) - Teaching resources
- **Teaching** (`#teaching`) - Courses and workshops
- **Projects** (`#projects`) - Research projects
- **Blog** (`#news`) - Blog posts
- **Code** (`#code`) - GitHub repositories
- **Announcements** (`#announcements`) - News and awards
- **Media/Talks** (`#media`) - Presentations
- **Personal** (`#personal`) - Personal interests

---

## ✏️ Adding Content

All content is managed in `/src/app.js`. Find the appropriate array and add your data:

### Publications
```javascript
const PUBLICATIONS = [
  {
    title: 'Paper Title',
    authors: 'Bhattarai, N., et al.',
    journal: 'Journal Name',
    year: 2025,
    doi: 'https://doi.org/10.xxxx/xxxxx',
    type: 'Journal Article'
  }
];
```

### Blog Posts
```javascript
const BLOG_POSTS = [
  {
    title: 'Blog Post Title',
    date: 'January 21, 2026',
    summary: 'Brief description...',
    tags: ['AI', 'Research']
  }
];
```

### Projects
```javascript
const PROJECTS = [
  {
    title: 'Project Name',
    description: 'Project description...',
    technologies: ['Python', 'TensorFlow'],
    status: 'Completed',
    github: 'https://github.com/user/repo'
  }
];
```

**For detailed templates, see:** [`docs/CONTENT_GUIDE.md`](docs/CONTENT_GUIDE.md)

---

## 🚀 Deployment

### Automatic
Every push to `main` deploys automatically via GitHub Actions.

```bash
git add .
git commit -m "Update content"
git push origin main
# Live in 1-2 minutes!
```

### Check Status
[View deployment status](https://github.com/bhatnira/bhatnira.github.io/actions)

---

## 📁 File Structure

```
bhatnira.github.io/
├── index.html          # Main entry point
├── assets/            # Images, PDFs, files
│   ├── images/       # Profile, project images
│   └── Nirajan_Bhattarai_CV.pdf
├── src/              # Source files
│   ├── app.js       # ⭐ EDIT THIS for content
│   └── styles.css   # Styling
├── public/          # Local development
├── docs/            # Documentation
│   ├── CONTENT_GUIDE.md
│   ├── CV_CUSTOMIZATION_SUMMARY.md
│   └── ...
├── archive/         # Old files
├── .github/
│   └── workflows/   # Auto-deployment
└── README.md        # This file
```

---

## 🎨 Customization

### Colors
Edit `src/styles.css`:
```css
:root {
  --primary: #2563eb;
  --text: #1f2937;
  --bg: #f9fafb;
}
```

### Images
- Replace `assets/images/Nirajan.jpg` with your photo
- Add project images to `assets/images/`

### CV
- Replace `assets/Nirajan_Bhattarai_CV.pdf`

---

## 🛠 Technologies

- HTML5, CSS3, Vanilla JavaScript
- GitHub Pages (Hosting)
- GitHub Actions (Deployment)
- **No build process required!**

---

## 📝 Documentation

- **[Content Guide](docs/CONTENT_GUIDE.md)** - Detailed guide for adding content
- **[Navigation Structure](docs/NAVIGATION_STRUCTURE.md)** - Navigation layout
- **[CV Customization](docs/CV_CUSTOMIZATION_SUMMARY.md)** - CV-based customization
- **[Dynamic Content](docs/DYNAMIC_CONTENT_SUMMARY.md)** - Dynamic system overview

---

## 📧 Contact

- **Email:** nbhatta1@uthsc.edu
- **GitHub:** [@bhatnira](https://github.com/bhatnira)
- **Website:** [https://bhatnira.github.io/](https://bhatnira.github.io/)

---

**Last Updated:** January 21, 2026
