# Web3Forms Setup & Deployment Guide

Your contact form now uses Web3Forms - a free service that requires NO signup! Just get an access key and add it to your form.

## Step 1: Get Your Web3Forms Access Key (2 minutes)

1. Go to **https://web3forms.com/**
2. Scroll down to "Get Your Access Key"
3. Enter your email: **mo.rahman610@gmail.com**
4. Click "Get Access Key"
5. Check your email and copy the access key (looks like: a1b2c3d4-e5f6-7g8h-9i0j-k1l2m3n4o5p6)

## Step 2: Add Access Key to Your Website

1. Open `index.html` in a text editor
2. Find this line near the top of the contact form:
   ```html
   <input type=\"hidden\" name=\"access_key\" value=\"YOUR_ACCESS_KEY_HERE\">
   ```
3. Replace `YOUR_ACCESS_KEY_HERE` with your actual access key
4. Save the file

## Step 3: Deploy Your Website

Now you can deploy to ANY hosting (even free static hosting):

### Option A: InfinityFree (Free Hosting)
1. Go to **https://www.infinityfree.net/** and sign up
2. Create a website with your chosen subdomain
3. Upload ALL files to `htdocs` folder via File Manager
4. Done!

### Option B: GitHub Pages (Free Static Hosting)
1. Create a GitHub account if you don't have one
2. Create a new repository named "scalablefutures"
3. Upload all files
4. Enable GitHub Pages in repository settings
5. Your site will be live at: username.github.io/scalablefutures

### Option C: Netlify (Free, Easiest)
1. Go to **https://www.netlify.com/**
2. Drag and drop your entire folder
3. Done! Instant deployment

## Step 4: Test Your Contact Form

1. Visit your live website
2. Fill out the contact form
3. Submit it
4. Check **mo.rahman610@gmail.com** for the email!

---

# Deploy ScalableFutures Website to InfinityFree

Follow these steps to deploy your website with free PHP hosting:

## Step 1: Create Free Hosting Account

1. Go to **https://www.infinityfree.net/**
2. Click "Sign Up Now"
3. Create an account (free, no credit card required)
4. Choose a subdomain name (e.g., scalablefutures.great-site.net) or use your own domain

## Step 2: Create Your Website

1. After signing up, go to your control panel
2. Click "Create Account" to set up a new website
3. Choose your subdomain or enter your domain name
4. Wait for account activation (usually instant)

## Step 3: Upload Your Files

### Option A: Using File Manager (Easiest)
1. In your control panel, click "File Manager"
2. Navigate to the `htdocs` folder
3. Delete any default files (like default.php)
4. Click "Upload" button
5. Upload ALL your files:
   - index.html
   - styles.css
   - script.js
   - contact.php
   - images folder (with photo-1506905925346-21bda4d32df4.jpg)
   - FORMSPREE_SETUP.md (optional)

### Option B: Using FTP (Alternative)
1. Get FTP credentials from control panel
2. Use FileZilla (free FTP client)
3. Connect and upload all files to htdocs folder

## Step 4: Test Your Website

1. Visit your website URL (e.g., http://scalablefutures.great-site.net)
2. Test the contact form by submitting a message
3. Check mo.rahman610@gmail.com for the email

## Step 5: Optional - Use Custom Domain

If you have your own domain:
1. Go to control panel > Addon Domains
2. Add your domain name
3. Update your domain's nameservers to InfinityFree's:
   - ns1.byet.org
   - ns2.byet.org

## Troubleshooting

**Contact form not working?**
- Make sure contact.php is uploaded
- Check that all files are in htdocs (not in a subfolder)
- Wait 5-10 minutes after upload for changes to take effect

**Images not loading?**
- Verify the images folder is uploaded
- Check file names match exactly (case-sensitive)

**404 Error?**
- Make sure index.html is in htdocs root
- Clear your browser cache

## Alternative Free Hosting Options

If InfinityFree doesn't work:
- **000webhost.com** - Similar free PHP hosting
- **AwardSpace.com** - Free PHP hosting with ads
- **FreeHosting.com** - Basic free hosting

---

## Your Website Files Checklist:
- ✅ index.html
- ✅ styles.css
- ✅ script.js
- ✅ contact.php
- ✅ images/photo-1506905925346-21bda4d32df4.jpg

## Contact Info (Already Configured):
- Email: mo.rahman610@gmail.com
- Phone: (313) 241-7031

---

**Estimated Time:** 10-15 minutes
**Cost:** FREE (Forever)
**PHP Support:** ✅ Included
**Storage:** 5GB
**Bandwidth:** Unlimited

Need help with any step? Let me know!
