# GoDaddy Upload Guide for Pee Aar Scaffolders Website

## 📋 Prerequisites
- GoDaddy hosting account
- Access to your GoDaddy control panel
- Your website files ready

## 🚀 Method 1: GoDaddy File Manager (Recommended)

### Step 1: Access GoDaddy Control Panel
1. Go to [godaddy.com](https://godaddy.com)
2. Sign in to your account
3. Go to "My Products" → "Web Hosting"
4. Click "Manage" next to your hosting plan

### Step 2: Open File Manager
1. In your hosting control panel, find "File Manager"
2. Click to open it
3. Navigate to the `public_html` folder (this is your website's root directory)

### Step 3: Upload Files
1. Click "Upload" or "Upload Files" button
2. Select these files from your computer:
   - `index.html`
   - `styles.css`
   - `script.js`
3. Upload them to the `public_html` folder
4. Make sure all files are in the same folder

### Step 4: Test Your Website
1. Go to your domain name (e.g., `yourdomain.com`)
2. Your website should now be live!

## 🔧 Method 2: FTP Upload (Advanced)

### Step 1: Get FTP Credentials
1. In GoDaddy control panel, go to "FTP Management"
2. Note down:
   - FTP Server: (usually your domain or ftp.yourdomain.com)
   - Username: (your FTP username)
   - Password: (your FTP password)

### Step 2: Use FTP Client
1. Download FileZilla (free FTP client)
2. Open FileZilla
3. Enter your FTP credentials:
   - Host: Your FTP server
   - Username: Your FTP username
   - Password: Your FTP password
   - Port: 21 (default)
4. Click "Quickconnect"

### Step 3: Upload Files
1. In the right panel (server), navigate to `public_html`
2. In the left panel (local), navigate to your website folder
3. Select all files and drag them to `public_html`

## 📁 File Structure on Server
Your files should be organized like this on GoDaddy:
```
public_html/
├── index.html
├── styles.css
├── script.js
└── README.md (optional)
```

## ✅ Verification Checklist
- [ ] All files uploaded to `public_html`
- [ ] `index.html` is in the root directory
- [ ] CSS and JS files are in the same folder as HTML
- [ ] Website loads without errors
- [ ] All links work properly
- [ ] Contact information displays correctly

## 🐛 Common Issues & Solutions

### Issue: Website shows "Index of" page
**Solution:** Make sure `index.html` is in the `public_html` folder

### Issue: Styling doesn't load
**Solution:** Check that `styles.css` is in the same folder as `index.html`

### Issue: JavaScript doesn't work
**Solution:** Verify `script.js` is uploaded and in the correct location

### Issue: Images don't display
**Solution:** If you add images later, upload them to the same folder

## 📞 GoDaddy Support
If you need help:
- GoDaddy Support: 1-866-938-1119
- Live Chat: Available in your GoDaddy account
- Help Center: help.godaddy.com

## 🌐 After Upload
Once uploaded, your website will be accessible at:
- `yourdomain.com` (if you have a domain)
- `yourdomain.com/index.html` (direct access)

## 🔄 Updates
To update your website later:
1. Make changes to your local files
2. Upload the updated files to replace the old ones
3. Clear browser cache to see changes

---
**Pee Aar Scaffolders Website** - Ready for GoDaddy hosting! 