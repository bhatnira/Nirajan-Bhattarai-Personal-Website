# Updated Navigation Structure

## ✅ Navigation Menu Updated

Your website navigation has been reorganized with the following pages:

### Top Navigation Bar (Quick Access):
1. **Material** - Research materials, datasets, slides
2. **Teaching** - Courses, workshops, tutorials
3. **Projects** - Research projects
4. **Blog** - Blog posts and articles
5. **Code** - GitHub repositories and tools
6. **Announcements** - News, awards, updates
7. **Media, Talks** - Presentations, interviews
8. **Personal** - Hobbies and interests

### Full Navigation (Main Menu):
- Home
- About
- Research
- Material
- Teaching
- Projects
- Blog
- Code
- Announcements
- Media, Talks
- Personal
- Publications
- Contact

## 📝 How to Add Content

Edit `/src/app.js` and find these data arrays:

### 1. MATERIALS (around line 55)
```javascript
const MATERIALS = [
  {
    title: 'Dataset Name',
    type: 'Dataset',
    description: 'Description...',
    date: 'January 2026',
    link: 'https://...',
    size: '5 MB',
    format: 'CSV',
    tags: ['QSAR', 'Data']
  },
];
```

### 2. TEACHING (around line 70)
```javascript
const TEACHING = [
  {
    title: 'Course Name',
    role: 'Instructor',
    institution: 'University Name',
    date: 'Fall 2025',
    description: 'Course description...',
    link: 'https://...',
    materials: 'https://...'
  },
];
```

### 3. PROJECTS (around line 40)
```javascript
const PROJECTS = [
  {
    title: 'Project Name',
    description: 'Description...',
    technologies: ['Python', 'TensorFlow'],
    status: 'Completed',
    date: 'January 2026',
    github: 'https://github.com/...',
    paper: 'https://doi.org/...',
    demo: 'https://...'
  },
];
```

### 4. BLOG_POSTS (around line 20)
```javascript
const BLOG_POSTS = [
  {
    title: 'Blog Post Title',
    date: 'January 2026',
    summary: 'Summary...',
    link: 'https://medium.com/...',
    tags: ['AI', 'Drug Discovery']
  },
];
```

### 5. CODE (around line 85)
```javascript
const CODE = [
  {
    title: 'Repository Name',
    description: 'What it does...',
    language: 'Python',
    stars: 42,
    github: 'https://github.com/...',
    demo: 'https://...',
    tags: ['Machine Learning', 'Tools']
  },
];
```

### 6. ANNOUNCEMENTS (around line 100)
```javascript
const ANNOUNCEMENTS = [
  {
    title: 'Announcement Title',
    date: 'January 2026',
    content: 'Announcement details...',
    type: 'Award',  // 'Award', 'Publication', 'Talk', 'News'
    link: 'https://...'
  },
];
```

### 7. MEDIA_TALKS (around line 115)
```javascript
const MEDIA_TALKS = [
  {
    title: 'Talk Title',
    event: 'Conference Name',
    date: 'January 2026',
    type: 'Talk',  // 'Talk', 'Poster', 'Interview', 'Podcast', 'Video'
    description: 'Description...',
    slides: 'https://...',
    video: 'https://youtube.com/...',
    location: 'City, Country'
  },
];
```

### 8. PERSONAL (around line 130)
```javascript
const PERSONAL = [
  {
    title: 'Hobby/Interest',
    description: 'Description...',
    image: 'assets/images/hobby.jpg',
    link: 'https://...'
  },
];
```

## 🎯 Page URLs

Access pages directly:
- Material: `#materials`
- Teaching: `#teaching`
- Projects: `#projects`
- Blog: `#news`
- Code: `#code`
- Announcements: `#announcements`
- Media, Talks: `#media`
- Personal: `#personal`

## 🚀 Deployment

Changes automatically deploy when you push to GitHub:
```bash
git add src/app.js
git commit -m "Add new content"
git push origin main
```

Your website will update in 1-2 minutes at:
https://bhatnira.github.io/Nirajan-Bhattarai-Personal-Website/

## 📋 Current Status

All pages are set up and ready for content:
- ✅ Material page (empty - waiting for content)
- ✅ Teaching page (empty - waiting for content)
- ✅ Projects page (empty - waiting for content)
- ✅ Blog page (empty - waiting for content)
- ✅ Code page (empty - waiting for content)
- ✅ Announcements page (empty - waiting for content)
- ✅ Media, Talks page (empty - waiting for content)
- ✅ Personal page (empty - waiting for content)

Start adding content to any of these arrays in `/src/app.js`!
