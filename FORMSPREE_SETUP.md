# PHP Contact Form Setup

Your contact form now uses a PHP backend to send emails directly to mo.rahman610@gmail.com

## Requirements:
- Web hosting with PHP support (most hosting providers include this)
- PHP mail() function enabled

## Files:
- `contact.php` - Handles form submission and sends emails
- `script.js` - Submits form data to contact.php

## Testing Locally:
To test on your local machine, you need a local PHP server:

### Option 1: Using PHP Built-in Server
```bash
php -S localhost:8000
```
Then visit: http://localhost:8000

### Option 2: Using XAMPP/WAMP/MAMP
Install one of these local server environments that includes PHP.

## Deployment:
1. Upload all files to your web hosting
2. Ensure PHP is enabled (most hosts have this by default)
3. Test the contact form
4. Check mo.rahman610@gmail.com for submissions

## Troubleshooting:
- **Not receiving emails?** Check your spam folder
- **Emails from wrong address?** Some hosts override the From address
- **Form not working?** Check that contact.php is in the same directory as index.html

## Note:
Some hosting providers require additional configuration for the mail() function. If emails aren't sending, contact your hosting support to enable PHP mail or configure SMTP.

---
**Current Setup:** ✅ PHP backend email handler
**Your Email:** mo.rahman610@gmail.com
**No third-party services required!**

# FormSpree Setup Instructions

Your contact form is now configured to use FormSpree, which will send form submissions directly to your email address (mo.rahman610@gmail.com).

## Setup Steps:

### 1. Create a FormSpree Account
- Go to https://formspree.io/
- Sign up with your email address (mo.rahman610@gmail.com)
- Verify your email address

### 2. Create a New Form
- Click "New Form" in your FormSpree dashboard
- Name it "ScalableFutures Contact Form"
- Your email (mo.rahman610@gmail.com) will be automatically added as the recipient

### 3. Get Your Form ID
- After creating the form, you'll see a form endpoint like:
  `https://formspree.io/f/YOUR_FORM_ID`
- Copy the **YOUR_FORM_ID** part (it looks like: xpznqjyz or similar)

### 4. Update Your Website
- Open `script.js`
- Find this line:
  ```javascript
  const response = await fetch('https://formspree.io/f/YOUR_FORM_ID', {
  ```
- Replace `YOUR_FORM_ID` with your actual FormSpree form ID

### 5. Test Your Form
- Open your website
- Fill out the contact form
- Click "Send Message"
- Check your email (mo.rahman610@gmail.com) for the form submission

## FormSpree Features (Free Plan):

✅ 50 submissions per month
✅ Email notifications
✅ Spam filtering with reCAPTCHA
✅ File uploads (optional)
✅ Export submissions to CSV
✅ Auto-reply emails (optional)

## Optional: Add reCAPTCHA (Recommended)

To prevent spam, you can enable reCAPTCHA in your FormSpree dashboard:
1. Go to your form settings
2. Enable "reCAPTCHA Protection"
3. FormSpree will automatically add the reCAPTCHA widget

## Troubleshooting:

- **Form not working?** Make sure you replaced YOUR_FORM_ID with your actual ID
- **Not receiving emails?** Check your spam folder and verify your email in FormSpree
- **Need more submissions?** Upgrade to FormSpree Gold ($10/month) for unlimited submissions

## Alternative: EmailJS

If you prefer, you can also use EmailJS (also free):
- Go to https://www.emailjs.com/
- Offers 200 free emails per month
- Similar setup process

---

**Current Status:** ⚠️ Awaiting FormSpree setup
**Your Email:** mo.rahman610@gmail.com
**Website:** ScalableFutures Contact Form
