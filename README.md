# Yario WhatsApp Business Automation

Official website for Facebook/Meta App Review process.

## 🌐 Live Website

**GitHub Pages URL:** `https://YOUR_USERNAME.github.io/yario-whatsapp/`

## 📄 Pages

| Page | URL | Purpose |
|------|-----|---------|
| Home | `/index.html` | Main landing page |
| Privacy Policy | `/privacy-policy.html` | **Required for Facebook App Review** |
| Terms of Service | `/terms-of-service.html` | **Required for Facebook App Review** |
| Data Deletion | `/data-deletion.html` | **Required for WhatsApp Business API** |
| Contact | `/contact.html` | Contact information |

## 🚀 Deploy to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `yario-whatsapp`
3. Set to **Public**
4. Click "Create repository"

### Step 2: Upload Files

**Option A: Using Git command line**
```bash
cd facebook_app_review/website
git init
git add .
git commit -m "Initial commit - Yario WhatsApp website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/yario-whatsapp.git
git push -u origin main
```

**Option B: Using GitHub web interface**
1. Open your new repository
2. Click "uploading an existing file"
3. Drag and drop all files from `website` folder
4. Click "Commit changes"

### Step 3: Enable GitHub Pages

1. Go to repository **Settings**
2. Click **Pages** in the left sidebar
3. Under "Source", select **Deploy from a branch**
4. Select branch: **main**
5. Select folder: **/ (root)**
6. Click **Save**

### Step 4: Wait for deployment

- GitHub will build your site (takes 1-2 minutes)
- Your site will be live at: `https://YOUR_USERNAME.github.io/yario-whatsapp/`

## 📋 URLs for Facebook App Review

After deploying, use these URLs in Facebook Developer Console:

| Field | URL |
|-------|-----|
| Privacy Policy URL | `https://YOUR_USERNAME.github.io/yario-whatsapp/privacy-policy.html` |
| Terms of Service URL | `https://YOUR_USERNAME.github.io/yario-whatsapp/terms-of-service.html` |
| Data Deletion Request URL | `https://YOUR_USERNAME.github.io/yario-whatsapp/data-deletion.html` |
| Website URL | `https://YOUR_USERNAME.github.io/yario-whatsapp/` |

## ✅ Facebook App Review Checklist

Before submitting for review, verify:

- [ ] Privacy Policy page loads correctly
- [ ] Terms of Service page loads correctly
- [ ] Data Deletion page loads with working form
- [ ] Contact page has valid email addresses
- [ ] All links between pages work
- [ ] Site is accessible via HTTPS (GitHub Pages provides this)

## 🔧 Customization

### Update contact information
Edit the following in each HTML file:
- `support@yario.ai` → Your support email
- `privacy@yario.ai` → Your privacy email
- Phone numbers
- Company address

### Update dates
Search and replace `August 21, 2025` with your current date in:
- `privacy-policy.html`
- `terms-of-service.html`

## 📱 Mobile Friendly

All pages are responsive and work on mobile devices (required by Facebook).

## 🛡️ SSL/HTTPS

GitHub Pages automatically provides HTTPS - no additional configuration needed.
