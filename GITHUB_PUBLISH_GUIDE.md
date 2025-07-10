# GitHub Pages Publishing Guide for Pee Aar Scaffolders

## 🚀 Quick Start (5 Steps)

### Step 1: Create GitHub Account
1. Go to [github.com](https://github.com)
2. Click "Sign up" and create a free account

### Step 2: Create New Repository
1. Click the "+" icon in the top right
2. Select "New repository"
3. Name it: `pee-aar-scaffolders` (or any name you prefer)
4. Make it **Public** (required for free GitHub Pages)
5. Click "Create repository"

### Step 3: Upload Your Files
1. In your new repository, click "uploading an existing file"
2. Drag and drop these files:
   - `index.html`
   - `styles.css`
   - `script.js`
3. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to repository **Settings** (tab at the top)
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"

### Step 5: Your Website is Live!
- Your website will be available at: `https://yourusername.github.io/pee-aar-scaffolders`
- It may take a few minutes to deploy

## 📁 Detailed Step-by-Step Instructions

### Creating the Repository

1. **Sign in to GitHub**
   - Go to [github.com](https://github.com)
   - Sign in with your account

2. **Create New Repository**
   - Click the "+" icon → "New repository"
   - Repository name: `pee-aar-scaffolders`
   - Description: "Professional website for Pee Aar Scaffolders - Scaffolding & Shuttering Services"
   - Make it **Public** (important for free hosting)
   - Don't initialize with README (we'll upload our files)
   - Click "Create repository"

### Uploading Your Website Files

1. **Upload Files**
   - In your new repository, you'll see "uploading an existing file"
   - Click on it
   - Drag and drop these files from your computer:
     - `index.html`
     - `styles.css`
     - `script.js`
   - Add a commit message: "Initial website upload"
   - Click "Commit changes"

2. **Verify Files**
   - You should now see your files in the repository
   - Make sure all 3 files are there

### Enabling GitHub Pages

1. **Go to Settings**
   - Click the "Settings" tab in your repository

2. **Find Pages Section**
   - Scroll down to "Pages" in the left sidebar
   - Click on it

3. **Configure Pages**
   - Under "Source", select "Deploy from a branch"
   - Branch: select "main"
   - Folder: select "/ (root)"
   - Click "Save"

4. **Wait for Deployment**
   - GitHub will show "Your site is being built"
   - This usually takes 2-5 minutes
   - You'll see a green checkmark when ready

### Accessing Your Website

- **URL Format**: `https://yourusername.github.io/pee-aar-scaffolders`
- **Example**: If your username is "johnsmith", your site will be at `https://johnsmith.github.io/pee-aar-scaffolders`

## 🔧 Custom Domain Setup for www.peeaarscaffolders.com

Since you already own `www.peeaarscaffolders.com` on GoDaddy, here's how to connect it to GitHub Pages:

### Step 1: Deploy Website on GitHub Pages First
1. Follow the steps above to create repository and enable GitHub Pages
2. Your site will be live at `https://yourusername.github.io/pee-aar-scaffolders`
3. Test that everything works before connecting your domain

### Step 2: Add Custom Domain in GitHub
1. Go to your repository **Settings** → **Pages**
2. Scroll down to "Custom domain"
3. Enter: `www.peeaarscaffolders.com`
4. Click "Save"
5. Check "Enforce HTTPS" (recommended)

### Step 3: Configure DNS in GoDaddy
1. **Login to GoDaddy**
   - Go to [godaddy.com](https://godaddy.com)
   - Sign in to your account

2. **Access DNS Management**
   - Go to "My Products" → "Domains"
   - Find `peeaarscaffolders.com`
   - Click "DNS" or "Manage DNS"

3. **Add CNAME Record**
   - Click "Add" or "Add Record"
   - Type: `CNAME`
   - Name: `www`
   - Value: `yourusername.github.io` (replace with your actual GitHub username)
   - TTL: `600` (or default)
   - Click "Save"

4. **Add A Record (Optional but Recommended)**
   - Click "Add" or "Add Record"
   - Type: `A`
   - Name: `@` (or leave blank)
   - Value: `185.199.108.153`
   - TTL: `600`
   - Click "Save"

### Step 4: Wait for DNS Propagation
- DNS changes can take 24-48 hours to fully propagate
- Usually works within 1-2 hours
- You can check propagation at [whatsmydns.net](https://whatsmydns.net)

### Step 5: Verify Setup
1. Visit `www.peeaarscaffolders.com`
2. Your website should load
3. Check that HTTPS works: `https://www.peeaarscaffolders.com`

## 🔧 Custom Domain (Optional)

If you have a custom domain (like `pee-aar-scaffolders.com`):

1. **In GitHub Pages Settings**
   - Scroll down to "Custom domain"
   - Enter your domain name
   - Click "Save"

2. **Configure DNS**
   - Go to your domain registrar (GoDaddy, etc.)
   - Add a CNAME record:
     - Name: `@` or `www`
     - Value: `yourusername.github.io`

## 📝 Updating Your Website

### Method 1: Edit Online
1. Go to your repository on GitHub
2. Click on any file (e.g., `index.html`)
3. Click the pencil icon to edit
4. Make your changes
5. Click "Commit changes"

### Method 2: Upload New Files
1. Go to your repository
2. Click "Add file" → "Upload files"
3. Upload your updated files
4. Click "Commit changes"

## ✅ Verification Checklist

- [ ] GitHub account created
- [ ] Repository created and made public
- [ ] All files uploaded (`index.html`, `styles.css`, `script.js`)
- [ ] GitHub Pages enabled in settings
- [ ] Website loads at the GitHub Pages URL
- [ ] All links and functionality work
- [ ] Contact information displays correctly

## 🐛 Troubleshooting

### Issue: Website shows 404 error
**Solution:** 
- Make sure repository is public
- Check that `index.html` is in the root directory
- Wait 5-10 minutes for deployment

### Issue: Styling doesn't load
**Solution:** 
- Verify `styles.css` is uploaded
- Check file paths in HTML are correct
- Clear browser cache

### Issue: JavaScript doesn't work
**Solution:** 
- Verify `script.js` is uploaded
- Check browser console for errors
- Ensure file is in the same directory as HTML

### Issue: GitHub Pages not showing
**Solution:** 
- Go to Settings → Pages
- Make sure source is set to "Deploy from a branch"
- Select "main" branch and "/ (root)" folder

## 🌟 Benefits of GitHub Pages

- **Free hosting** forever
- **Custom domain** support
- **SSL certificate** included
- **Fast CDN** worldwide
- **Version control** for your website
- **Easy updates** through GitHub
- **Professional** and reliable

## 📞 Support

- **GitHub Help**: help.github.com
- **GitHub Pages Documentation**: pages.github.com
- **Community**: GitHub Discussions

## 🔄 Next Steps

1. **Test your website** thoroughly
2. **Share the URL** with potential customers
3. **Consider a custom domain** for branding
4. **Update content** as needed through GitHub

---

**Your Pee Aar Scaffolders website will be live at:**
`https://yourusername.github.io/pee-aar-scaffolders`

**Ready to go live with professional hosting! 🚀** 