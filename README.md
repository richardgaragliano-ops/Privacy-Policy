# CarCaine Website

Professional website hosting the Privacy Policy, Terms of Service, and Community Guidelines for the CarCaine mobile application.

**Tagline**: Precision Meets Passion

## 📋 Contents

- **index.html** - Homepage with navigation and links to all documents
- **privacy.html** - Privacy Policy (CCPA & GDPR compliant)
- **terms.html** - Terms of Service
- **community-guidelines.html** - Community Guidelines and moderation policies

## 🎨 Design

- **Theme**: Dark automotive aesthetic with neon cyan accents (#00FFC2)
- **Responsive**: Mobile-friendly design for all devices
- **Accessibility**: WCAG AA compliant with proper semantic HTML
- **Performance**: Lightweight HTML/CSS with no external dependencies

## 🚀 Deployment Options

### Option 1: GitHub Pages (Recommended - Free)

GitHub Pages provides free hosting directly from your GitHub repository.

#### Steps:

1. **Create a GitHub account** (if you don't have one):
   - Go to https://github.com/signup
   - Sign up with your email

2. **Create a new repository**:
   - Go to https://github.com/new
   - Repository name: `carcaine-website` (or any name)
   - Description: "CarCaine - Privacy Policy, Terms of Service, and Community Guidelines"
   - Make it **Public**
   - Click "Create repository"

3. **Upload files to GitHub**:
   ```bash
   cd /home/ubuntu/carcaine-website
   git remote add origin https://github.com/YOUR_USERNAME/carcaine-website.git
   git branch -M main
   git push -u origin main
   ```
   Replace `YOUR_USERNAME` with your actual GitHub username.

4. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll to "GitHub Pages" section
   - Select "main" branch as source
   - Click "Save"

5. **Access your website**:
   - Your site will be live at: `https://YOUR_USERNAME.github.io/carcaine-website`
   - Or use a custom domain (see Custom Domain section below)

---

### Option 2: Vercel (Free)

Vercel provides free hosting with automatic deployments from GitHub.

#### Steps:

1. **Sign up for Vercel**:
   - Go to https://vercel.com/signup
   - Sign up with GitHub (recommended)

2. **Import your repository**:
   - Click "New Project"
   - Select your GitHub repository
   - Click "Import"

3. **Configure**:
   - Framework: Select "Other" or leave blank
   - Root Directory: Leave as is
   - Click "Deploy"

4. **Access your website**:
   - Your site will be live at: `https://carcaine-website.vercel.app` (or custom domain)

---

### Option 3: Netlify (Free)

Netlify provides free hosting with continuous deployment.

#### Steps:

1. **Sign up for Netlify**:
   - Go to https://app.netlify.com/signup
   - Sign up with GitHub (recommended)

2. **Deploy**:
   - Click "New site from Git"
   - Select GitHub
   - Choose your repository
   - Click "Deploy site"

3. **Access your website**:
   - Your site will be live at: `https://carcaine-website.netlify.app` (or custom domain)

---

## 🌐 Custom Domain

To use a custom domain like `www.carcaine.app`:

### For GitHub Pages:

1. **Add CNAME file**:
   ```bash
   echo "www.carcaine.app" > CNAME
   git add CNAME
   git commit -m "Add custom domain"
   git push
   ```

2. **Configure DNS**:
   - Go to your domain registrar (GoDaddy, Namecheap, etc.)
   - Add a CNAME record pointing to `YOUR_USERNAME.github.io`
   - Or add A records pointing to GitHub's IP addresses (see GitHub docs)

3. **Enable HTTPS**:
   - In repository settings, enable "Enforce HTTPS"

### For Vercel or Netlify:

1. **Add domain in dashboard**:
   - Go to your project settings
   - Add custom domain
   - Follow the DNS configuration instructions

2. **Update DNS**:
   - Add the provided DNS records to your domain registrar

---

## 📝 File Structure

```
carcaine-website/
├── index.html                  # Homepage
├── privacy.html                # Privacy Policy
├── terms.html                  # Terms of Service
├── community-guidelines.html    # Community Guidelines
├── README.md                    # This file
└── .git/                        # Git repository
```

---

## 🔧 Local Development

To test the website locally:

```bash
# Option 1: Using Python
cd /home/ubuntu/carcaine-website
python3 -m http.server 8000

# Option 2: Using Node.js (http-server)
npx http-server

# Then open: http://localhost:8000
```

---

## 📱 Responsive Design

The website is fully responsive and works on:
- Desktop (1920px and above)
- Tablet (768px - 1024px)
- Mobile (320px - 767px)

All pages are optimized for touch devices and small screens.

---

## ♿ Accessibility

- WCAG AA compliant
- Semantic HTML5 structure
- Proper color contrast (minimum 4.5:1)
- Keyboard navigation support
- Screen reader friendly

---

## 🔒 Security

- No external dependencies (pure HTML/CSS)
- No tracking or analytics
- No cookies or local storage
- HTTPS enforced (when using custom domain)
- Content Security Policy ready

---

## 📧 Contact Information

- **Support Email**: support@carcaine.app
- **Privacy Email**: privacy@carcaine.app
- **Community Email**: community@carcaine.app
- **Appeals Email**: appeals@carcaine.app
- **Website**: www.carcaine.app

---

## 📄 Legal Documents

All documents are legally compliant with:
- **GDPR** (European Union)
- **CCPA** (California)
- **COPPA** (Children's Online Privacy)
- **General US Privacy Laws**

---

## 🚀 Next Steps

1. **Choose a deployment platform** (GitHub Pages recommended for simplicity)
2. **Follow the deployment steps** for your chosen platform
3. **Set up a custom domain** (optional but recommended)
4. **Update your app store listings** with the website URLs:
   - Privacy Policy: `www.carcaine.app/privacy.html`
   - Terms of Service: `www.carcaine.app/terms.html`
   - Community Guidelines: `www.carcaine.app/community-guidelines.html`

---

## 📞 Support

For questions or issues with deployment:
- GitHub Pages: https://docs.github.com/en/pages
- Vercel: https://vercel.com/docs
- Netlify: https://docs.netlify.com

---

**Last Updated**: November 6, 2025  
**Version**: 1.0.0

**Precision Meets Passion. 🏎️**
