# Mrs. Tournier Women's Health - Landing Page

A static landing page for Mrs. Tournier Women's Health, featuring natural wellness supplements for women.

## 🚀 Deployment Guide for Cloudflare Pages

### Prerequisites
- A Cloudflare account (free at [cloudflare.com](https://cloudflare.com))
- A GitHub, GitLab, or direct upload option

### Method 1: Direct Upload (Quickest)

1. **Build the site locally** (if needed)
   - The site is already built (static HTML/CSS/JS)
   - No build step required

2. **Go to Cloudflare Pages**
   - Log in to your Cloudflare account
   - Navigate to **Pages** in the sidebar
   - Click **Create a project**
   - Select **Direct Upload**

3. **Upload your files**
   - Click **Select folder** or drag and drop
   - Upload the entire project folder containing:
     - `index.html`
     - `styles.css`
     - `img/` directory with all images

4. **Configure and deploy**
   - Give your project a name (e.g., `mrstournier-site`)
   - Click **Deploy site**
   - Your site will be live at `https://[project-name].pages.dev`

### Method 2: Git Integration (Recommended for updates)

1. **Push to GitHub/GitLab**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/[your-username]/mrstournier-site.git
   git push -u origin main
   ```

2. **Connect to Cloudflare Pages**
   - Go to Cloudflare Pages dashboard
   - Click **Create a project**
   - Select **Connect to Git**
   - Choose your Git provider and authorize
   - Select your repository

3. **Configure build settings**
   - **Framework preset**: None
   - **Build command**: (leave empty)
   - **Build output directory**: `/`
   - **Root directory**: `/`

4. **Deploy**
   - Click **Save and Deploy**
   - Future pushes to your repository will auto-deploy

### Custom Domain Setup

1. **Add custom domain**
   - Go to your Pages project
   - Navigate to **Custom domains** tab
   - Click **Set up a custom domain**
   - Enter your domain (e.g., `mrstournier.com`)

2. **Configure DNS**
   - If domain is on Cloudflare: Auto-configured
   - If external: Add CNAME record pointing to `[project-name].pages.dev`

3. **SSL Certificate**
   - Automatically provisioned by Cloudflare
   - HTTPS enabled by default

### Environment Variables (Not needed for this static site)
This is a static site with no build process or environment variables required.

### Performance Optimizations (Automatic)
Cloudflare Pages automatically provides:
- Global CDN distribution
- HTTP/3 support
- Brotli compression
- Image optimization
- Minification

### Deployment Status
Check deployment status at:
```
https://dash.cloudflare.com/[account-id]/pages/view/[project-name]
```

## 📁 Project Structure

```
mrstournier-site/
├── index.html          # Main HTML file
├── styles.css          # CSS stylesheet
├── img/               # Images directory
│   ├── hero.png
│   ├── logo.png
│   ├── img1.png
│   ├── img2.png
│   ├── img3.png
│   ├── img4.png
│   ├── ourvalues-hero.png
│   └── ourvalues2.png
└── README.md          # This file
```

## 🔗 External Links
- **Live Store**: https://mrstournier.myshopify.com
- **Amazon Product**: https://www.amazon.com/Mrs-Tournier-Saffron-88-5mg-Menstrual/dp/B0F3JXCVN4

## 📧 Contact
Email: info@mrstournier.com

## 📄 License
© 2025 Mrs. Tournier Women's Health. All rights reserved.