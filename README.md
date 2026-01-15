# Growth Leder Website - Deployment Guide

## How to Go Live (Deploy Your Website)

### Option 1: GitHub Pages (FREE & EASY) ⭐ Recommended

1. **Create a GitHub Account** (if you don't have one)
   - Go to https://github.com
   - Sign up for free

2. **Create a New Repository**
   - Click "New" or "+" → "New repository"
   - Name it: `growthleder-website` (or any name)
   - Make it **Public**
   - Don't initialize with README
   - Click "Create repository"

3. **Upload Your Files**
   - Open your `haseeb-services-website` folder
   - Drag and drop ALL files into the GitHub repository
   - Or use Git commands:
     ```bash
     cd haseeb-services-website
     git init
     git add .
     git commit -m "Initial commit"
     git branch -M main
     git remote add origin https://github.com/YOUR-USERNAME/growthleder-website.git
     git push -u origin main
     ```

4. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click **Settings** tab
   - Scroll to **Pages** section (left sidebar)
   - Under "Source", select **main** branch
   - Click **Save**
   - Your site will be live at: `https://YOUR-USERNAME.github.io/growthleder-website/`

---

### Option 2: Netlify (FREE & EASY) ⭐ Also Recommended

1. **Go to Netlify**
   - Visit https://www.netlify.com
   - Sign up for free (can use GitHub account)

2. **Deploy**
   - Drag and drop your `haseeb-services-website` folder onto Netlify
   - Or connect to GitHub for automatic deployments
   - Your site will be live instantly with a free `.netlify.app` domain

3. **Custom Domain** (Optional)
   - Add your own domain in Netlify settings
   - Update DNS records as instructed

---

### Option 3: Vercel (FREE & EASY)

1. **Go to Vercel**
   - Visit https://vercel.com
   - Sign up for free

2. **Deploy**
   - Import your project from GitHub
   - Or drag and drop your folder
   - Site goes live automatically

---

### Option 4: Traditional Web Hosting

If you have web hosting (cPanel, FTP, etc.):

1. **Upload Files via FTP**
   - Use FileZilla or similar FTP client
   - Upload all files from `haseeb-services-website` folder
   - Upload to `public_html` or `www` folder

2. **Access Your Site**
   - Your site will be at: `http://yourdomain.com`

---

## Quick Checklist Before Going Live

- [ ] Update Formspree endpoint in `contact.html` (replace `your-form-id`)
- [ ] Verify all social media links are correct
- [ ] Test all pages and links
- [ ] Check mobile responsiveness
- [ ] Test contact form

---

## Need Help?

- **GitHub Pages**: https://pages.github.com
- **Netlify**: https://docs.netlify.com
- **Vercel**: https://vercel.com/docs

---

## File Structure

```
haseeb-services-website/
├── index.html
├── accounting.html
├── lead-generation.html
├── seo-services.html
├── linkedin-outreach.html
├── web-outreach.html
├── contact.html
├── style.css
├── script.js
├── logo.svg
├── logo-white.svg
└── favicon.svg
```

All files should be in the same folder when deploying!
