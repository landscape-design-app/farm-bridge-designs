# Deployment Instructions

## Quick Start - Get Your Site Live in 5 Minutes!

### Option 1: GitHub Pages (Recommended - FREE!)

1. **Create GitHub Account** (if you don't have one)
   - Go to https://github.com
   - Sign up for free

2. **Create New Repository**
   - Click "New repository"
   - Name it: `bridge-abutment-docs` (or any name you want)
   - Make it Public
   - Don't initialize with README (we have one)

3. **Upload Your Files**
   
   **Method A: GitHub Web Interface (Easiest)**
   - Click "uploading an existing file"
   - Drag and drop the entire `bridge-abutment-project` folder contents
   - Commit changes

   **Method B: Git Command Line**
   ```bash
   cd bridge-abutment-project
   git init
   git add .
   git commit -m "Initial commit - Bridge abutment documentation"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/bridge-abutment-docs.git
   git push -u origin main
   ```

4. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Source: Select "Deploy from a branch"
   - Branch: Select `main`
   - Folder: Select `/docs`
   - Click Save

5. **Your Site is Live!**
   - URL: `https://YOUR-USERNAME.github.io/bridge-abutment-docs/`
   - Takes 2-5 minutes to build
   - Updates automatically when you push changes

---

### Option 2: Test Locally First

Want to preview before publishing?

1. **Install Ruby & Jekyll**
   
   **On Mac:**
   ```bash
   brew install ruby
   gem install bundler jekyll
   ```
   
   **On Ubuntu/Debian:**
   ```bash
   sudo apt-get install ruby-full build-essential zlib1g-dev
   gem install bundler jekyll
   ```
   
   **On Windows:**
   - Download from https://rubyinstaller.org/
   - Install Jekyll: `gem install bundler jekyll`

2. **Install Dependencies**
   ```bash
   cd bridge-abutment-project/docs
   bundle install
   ```

3. **Serve Locally**
   ```bash
   bundle exec jekyll serve
   ```
   
4. **View Site**
   - Open: http://localhost:4000
   - Auto-refreshes when you edit files

---

## 📂 Repository Structure

```
bridge-abutment-project/
├── README.md                  # GitHub repository homepage
├── DEPLOYMENT.md             # This file
├── .gitignore                # Git ignore rules
└── docs/                     # Jekyll site (THIS is what GitHub builds)
    ├── _config.yml           # Site configuration
    ├── index.md              # Homepage
    ├── Gemfile               # Ruby dependencies
    ├── downloads.md          # Downloads page
    ├── 404.md                # Error page
    ├── _design/              # Design documentation
    │   └── index.md
    ├── _construction/        # Construction guides
    │   └── index.md
    ├── _materials/           # Materials lists
    │   └── index.md
    ├── _inspection/          # Inspection checklists
    │   └── index.md
    └── assets/               # Images, downloads, etc.
        ├── images/
        │   └── abutment-rebar-3d.png
        └── downloads/
            ├── *.stl files
            └── complete-design-package.md
```

---

## 🎨 Customization

### Change Site Title/Description

Edit `docs/_config.yml`:
```yaml
title: "Your Project Name"
description: "Your description"
author: "Your Name"
email: your-email@example.com
```

### Change Theme

Edit `docs/_config.yml`:
```yaml
theme: jekyll-theme-cayman  # Current theme

# Other options:
# theme: minima
# theme: jekyll-theme-minimal
# theme: jekyll-theme-architect
# theme: jekyll-theme-slate
```

Browse themes: https://pages.github.com/themes/

### Add Your Own Content

1. Create new markdown file in `docs/`
2. Add front matter:
   ```markdown
   ---
   layout: default
   title: My Page
   ---
   
   # Content here
   ```
3. Link from other pages

### Add Images

1. Place in `docs/assets/images/`
2. Reference in markdown:
   ```markdown
   ![Description](/assets/images/your-image.png)
   ```

---

## 🔧 Troubleshooting

### Site Not Building?

**Check build status:**
- GitHub → Your Repo → Actions tab
- Look for error messages

**Common issues:**
- Typo in `_config.yml` (YAML is sensitive!)
- Missing closing quotes or brackets
- Wrong folder selected in Pages settings

**Solution:**
- Fix the error
- Git commit and push
- GitHub rebuilds automatically

### Links Not Working?

**If links show "404 Not Found":**
1. Check `_config.yml` - `baseurl` should be empty:
   ```yaml
   baseurl: ""  # Leave empty for GitHub Pages
   ```
2. Links should start with `/`:
   ```markdown
   [Design](/design/)  # Correct
   [Design](design/)   # Wrong
   ```

### Images Not Loading?

**Check image paths:**
```markdown
![Image](/assets/images/image.png)  # Correct (starts with /)
![Image](assets/images/image.png)   # Wrong
```

---

## 🚀 Updates & Maintenance

### To Update Content:

1. **Edit files locally** or on GitHub web interface
2. **Commit changes:**
   ```bash
   git add .
   git commit -m "Updated construction guide"
   git push
   ```
3. **GitHub automatically rebuilds** (takes 2-5 minutes)

### Backup Your Site:

Your GitHub repository IS the backup! But also:
- Download as ZIP from GitHub
- Clone to multiple locations
- Fork the repository

---

## 📱 Share With Team

### Share Options:

1. **Direct Link**: `https://YOUR-USERNAME.github.io/bridge-abutment-docs/`

2. **QR Code**: Generate at https://www.qr-code-generator.com/

3. **Custom Domain** (optional, ~$12/year):
   - Buy domain from Namecheap/GoDaddy
   - Add CNAME file to `docs/`:
     ```
     yourdomain.com
     ```
   - Configure DNS with your registrar
   - GitHub guide: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

4. **Print to PDF**:
   - Open any page
   - Browser Print → Save as PDF
   - Share PDF for offline viewing

---

## 💡 Pro Tips

### Make it Searchable

Add to `docs/_config.yml`:
```yaml
plugins:
  - jekyll-seo-tag
```

This adds meta tags for Google/social media.

### Add Analytics

Sign up for Google Analytics, then add to `_config.yml`:
```yaml
google_analytics: UA-XXXXXXXXX-X
```

### Collaborate with Team

- Add team members as collaborators in GitHub
- They can edit directly on GitHub (no Git knowledge needed!)
- Or they can fork and submit pull requests

### Version Control

Git automatically tracks all changes:
```bash
git log                 # See history
git diff                # See changes
git checkout -- file    # Undo changes
```

---

## 📞 Support

### Need Help?

1. **Jekyll Docs**: https://jekyllrb.com/docs/
2. **GitHub Pages Docs**: https://docs.github.com/en/pages
3. **Markdown Guide**: https://www.markdownguide.org/

### Common Questions:

**Q: Is this really free?**
A: Yes! GitHub Pages is completely free for public repositories.

**Q: Can I make it private?**
A: Yes, but GitHub Pages for private repos requires GitHub Pro ($4/month).

**Q: Can I use my own domain?**
A: Yes! See "Custom Domain" section above.

**Q: How do I update?**
A: Just edit files and push to GitHub. Automatically rebuilds.

---

## ✅ Final Checklist

Before sharing your site:

- [ ] All content reviewed and accurate
- [ ] Images loading correctly
- [ ] All links working
- [ ] Mobile responsive (test on phone)
- [ ] Contact info updated
- [ ] Spelling/grammar checked
- [ ] Test on multiple browsers
- [ ] Share URL with team!

---

## 🎉 You're Done!

Your professional documentation site is now live and accessible to your entire team!

**Next Steps:**
1. Share the URL with your project helper
2. Review content together
3. Make any updates needed
4. Start building!

---

*Questions? The documentation is fully open source - feel free to modify anything!*
