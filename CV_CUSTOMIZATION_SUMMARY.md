# Website Customization Based on CV

## ✅ Changes Made (Home Page NOT Modified)

### 1. **Publications Section - Completely Redesigned** 📄

**What Changed:**
- Replaced hardcoded placeholder publications with dynamic data system
- Added `PUBLICATIONS` array at the top of `src/app.js`
- Publications now render from data, not hardcoded HTML

**How to Add Your Publications:**
1. Open `src/app.js`
2. Find the `PUBLICATIONS` array (around line 20)
3. Copy the template and add each publication from your CV:

```javascript
const PUBLICATIONS = [
  {
    title: 'Your Paper Title',
    authors: 'Bhattarai, N., Co-author, A.',
    journal: 'Journal Name',
    year: 2025,
    volume: '15',  // Optional
    pages: '123-145',  // Optional
    doi: 'https://doi.org/10.xxxx/xxxxx',
    pmid: '12345678',  // Optional
    pdf: 'assets/publications/paper.pdf',  // Optional
    type: 'Journal Article'  // Or 'Conference', 'Preprint', 'Book Chapter'
  },
];
```

**Features:**
- Publication type badges (Journal Article, Conference, etc.)
- Numbered list (auto-generated)
- Links to DOI, PubMed, and PDF
- Clean, professional formatting
- Instructions on page for easy updates

### 2. **CV Added to Website** 📑

**What Was Done:**
- `Nirajan_Bhattarai_CV.pdf` copied to `/assets/` and `/public/assets/`
- CV is now accessible at: `https://bhatnira.github.io/Nirajan-Bhattarai-Personal-Website/assets/Nirajan_Bhattarai_CV.pdf`
- Can be linked from any page

**To Add Download Button (Optional):**
You can add a CV download link to any page. Example for Contact or About page:
```html
<a href="assets/Nirajan_Bhattarai_CV.pdf" target="_blank" class="button">📄 Download CV</a>
```

### 3. **Content Sections Ready for CV Data**

All these sections are ready for you to extract information from your CV:

#### **Teaching Section** (from CV Education/Teaching Experience):
```javascript
const TEACHING = [
  {
    title: 'Course Name',
    role: 'Instructor',  // or 'Teaching Assistant', 'Guest Lecturer'
    institution: 'University Name',
    date: 'Fall 2025',
    description: 'Course description...',
  },
];
```

#### **Code Section** (from CV Projects/GitHub):
```javascript
const CODE = [
  {
    title: 'Repository Name',
    description: 'What it does...',
    language: 'Python',
    github: 'https://github.com/yourusername/repo',
    tags: ['Machine Learning', 'Drug Discovery']
  },
];
```

#### **Announcements** (from CV Awards/Honors):
```javascript
const ANNOUNCEMENTS = [
  {
    title: 'Award or Achievement',
    date: 'January 2026',
    content: 'Details...',
    type: 'Award',  // or 'Publication', 'Talk', 'News'
  },
];
```

#### **Media & Talks** (from CV Presentations):
```javascript
const MEDIA_TALKS = [
  {
    title: 'Talk Title',
    event: 'Conference Name',
    date: 'January 2026',
    type: 'Talk',  // or 'Poster', 'Interview'
    description: 'Brief description...',
    slides: 'URL',  // Optional
    video: 'URL',  // Optional
  },
];
```

## 📋 Next Steps - Extract From Your CV:

1. **Publications** ⭐ PRIORITY
   - Open your CV PDF
   - Copy each publication to the `PUBLICATIONS` array
   - Include DOI links if available

2. **Teaching Experience**
   - List courses you've taught or assisted with
   - Add to `TEACHING` array

3. **Awards & Honors**
   - Add to `ANNOUNCEMENTS` array as achievements

4. **Conference Presentations**
   - Add to `MEDIA_TALKS` array

5. **GitHub Repositories/Projects**
   - Add to `CODE` array

6. **Research Projects**
   - Add detailed projects to `PROJECTS` array

## 🎯 What Stayed the Same (As Requested):

✅ **Home Page** - NOT modified (as you requested)
- Profile section unchanged
- Research interests list unchanged
- Contact information unchanged

## 📁 Files Modified:

1. `src/app.js`
   - Added `PUBLICATIONS` array (line ~20)
   - Updated `renderPublications()` function
   - Publications now data-driven, not hardcoded

2. `assets/Nirajan_Bhattarai_CV.pdf` (NEW)
   - Your CV is now part of the website
   - Can be downloaded by visitors

3. `public/assets/Nirajan_Bhattarai_CV.pdf` (NEW)
   - Same CV for local development

## 🚀 Deployment Status:

✅ All changes committed and pushed to GitHub
✅ Website will update in 1-2 minutes at: https://bhatnira.github.io/Nirajan-Bhattarai-Personal-Website/

## 💡 Recommendations:

1. **Start with Publications** - This is what visitors look for most
2. **Add 1-2 sections at a time** - Don't try to fill everything at once
3. **Use your CV as the source of truth** - Copy information directly
4. **Keep it updated** - Add new publications, talks, etc. as they happen

## 📝 How to Update Publications (Step-by-Step):

1. Open `src/app.js`
2. Scroll to the top (around line 20)
3. Find `const PUBLICATIONS = [`
4. For each publication in your CV, add:
   ```javascript
   {
     title: 'Copy title from CV',
     authors: 'Copy authors from CV',
     journal: 'Copy journal name',
     year: 2025,
     doi: 'https://doi.org/...',
     type: 'Journal Article'
   },
   ```
5. Save the file
6. Run: `git commit -am "Add publications from CV" && git push`
7. Wait 1-2 minutes for deployment

---

**Questions?** All data arrays are clearly labeled at the top of `src/app.js` with templates and examples!
