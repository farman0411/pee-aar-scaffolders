# GoDaddy DNS Setup for GitHub Pages
## Connecting www.peeaarscaffolders.com to GitHub Pages

This guide will help you connect your existing GoDaddy domain `www.peeaarscaffolders.com` to your GitHub Pages website.

## 📋 Prerequisites
- GoDaddy account with `peeaarscaffolders.com` domain
- GitHub account with website deployed
- Your GitHub username (needed for DNS configuration)

## 🚀 Step-by-Step DNS Configuration

### Step 1: Get Your GitHub Pages URL
1. After deploying your website on GitHub Pages
2. Your site will be at: `https://yourusername.github.io/pee-aar-scaffolders`
3. Note down your GitHub username (replace `yourusername` in the URL)

### Step 2: Access GoDaddy DNS Management
1. **Login to GoDaddy**
   - Go to [godaddy.com](https://godaddy.com)
   - Sign in to your account

2. **Find Your Domain**
   - Go to "My Products" → "Domains"
   - Find `peeaarscaffolders.com` in your domain list
   - Click "DNS" or "Manage DNS"

### Step 3: Configure DNS Records

#### A. Add CNAME Record for www
1. Click "Add" or "Add Record"
2. Configure as follows:
   - **Type**: `CNAME`
   - **Name**: `www`
   - **Value**: `yourusername.github.io` (replace with your actual GitHub username)
   - **TTL**: `600` (or leave default)
3. Click "Save"

#### B. Add A Record for Root Domain (Optional)
1. Click "Add" or "Add Record"
2. Configure as follows:
   - **Type**: `A`
   - **Name**: `@` (or leave blank)
   - **Value**: `185.199.108.153`
   - **TTL**: `600` (or leave default)
3. Click "Save"

#### C. Add Additional A Records (Recommended)
Add these A records for better reliability:
1. **Second A Record**:
   - **Type**: `A`
   - **Name**: `@`
   - **Value**: `185.199.109.153`
   - **TTL**: `600`

2. **Third A Record**:
   - **Type**: `A`
   - **Name**: `@`
   - **Value**: `185.199.110.153`
   - **TTL**: `600`

3. **Fourth A Record**:
   - **Type**: `A`
   - **Name**: `@`
   - **Value**: `185.199.111.153`
   - **TTL**: `600`

### Step 4: Configure GitHub Pages

1. **Go to GitHub Repository**
   - Open your repository on GitHub
   - Go to **Settings** tab

2. **Enable Custom Domain**
   - Scroll down to "Pages" in left sidebar
   - Under "Custom domain", enter: `www.peeaarscaffolders.com`
   - Click "Save"

3. **Enable HTTPS**
   - Check "Enforce HTTPS" (recommended)
   - This provides SSL certificate automatically

### Step 5: Final DNS Configuration Summary

Your GoDaddy DNS should have these records:

| Type | Name | Value | TTL |
|------|------|-------|-----|
| CNAME | www | yourusername.github.io | 600 |
| A | @ | 185.199.108.153 | 600 |
| A | @ | 185.199.109.153 | 600 |
| A | @ | 185.199.110.153 | 600 |
| A | @ | 185.199.111.153 | 600 |

## ⏱️ DNS Propagation

### What to Expect
- **Initial**: 1-2 hours for basic functionality
- **Full propagation**: 24-48 hours worldwide
- **Check status**: [whatsmydns.net](https://whatsmydns.net)

### Testing Your Setup
1. **Immediate test**: Visit `www.peeaarscaffolders.com`
2. **HTTPS test**: Visit `https://www.peeaarscaffolders.com`
3. **Root domain test**: Visit `peeaarscaffolders.com` (should redirect to www)

## ✅ Verification Checklist

- [ ] CNAME record added for www
- [ ] A records added for root domain
- [ ] Custom domain configured in GitHub Pages
- [ ] HTTPS enabled in GitHub Pages
- [ ] Website loads at www.peeaarscaffolders.com
- [ ] HTTPS works properly
- [ ] All website functionality works

## 🐛 Troubleshooting

### Issue: Website doesn't load
**Solutions:**
- Wait 1-2 hours for DNS propagation
- Check DNS records are correct
- Verify GitHub Pages is enabled
- Clear browser cache

### Issue: HTTPS doesn't work
**Solutions:**
- Enable "Enforce HTTPS" in GitHub Pages settings
- Wait for SSL certificate to be issued (can take up to 24 hours)
- Check that custom domain is properly configured

### Issue: www works but root domain doesn't
**Solutions:**
- Make sure A records are added for root domain
- Check that all 4 A records are configured
- Wait for DNS propagation

### Issue: DNS propagation taking too long
**Solutions:**
- Check DNS propagation at [whatsmydns.net](https://whatsmydns.net)
- Contact GoDaddy support if issues persist
- Verify DNS records are correctly configured

## 📞 Support

### GoDaddy Support
- Phone: 1-866-938-1119
- Live Chat: Available in your GoDaddy account
- Help Center: help.godaddy.com

### GitHub Support
- GitHub Help: help.github.com
- GitHub Pages Documentation: pages.github.com

## 🌐 Final Result

After setup, your website will be accessible at:
- **Primary URL**: `https://www.peeaarscaffolders.com`
- **Alternative**: `https://peeaarscaffolders.com` (redirects to www)
- **GitHub URL**: `https://yourusername.github.io/pee-aar-scaffolders` (still works)

## 🔄 Updates

Once connected, you can update your website by:
1. Making changes in your GitHub repository
2. Changes automatically deploy to your custom domain
3. No additional DNS configuration needed for updates

---

**Your Pee Aar Scaffolders website will be live at:**
`https://www.peeaarscaffolders.com`

**Professional hosting with your custom domain! 🚀** 