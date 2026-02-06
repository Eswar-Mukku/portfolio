# 📧 Contact Form Setup Instructions

## Quick Setup (5 minutes)

Your portfolio now uses **Web3Forms** - a free service that sends contact form submissions directly to your email!

### Step 1: Get Your Free Access Key

1. Go to: **https://web3forms.com**
2. Enter your email: **eswarmukku2176@gmail.com**
3. Click "Get Access Key"
4. Check your email and copy the access key they send you

### Step 2: Add the Access Key to Your Portfolio

1. Open `index.html`
2. Find this line (around line 240):
   ```html
   <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">
   ```
3. Replace `YOUR_ACCESS_KEY_HERE` with your actual access key from Web3Forms

### Step 3: Test It!

1. Refresh your portfolio page
2. Fill out the contact form
3. Click "Send Message"
4. You should receive an email at **eswarmukku2176@gmail.com**!

## How It Works

✅ **Completely Free** - No limits, no paid plans
✅ **No Backend Needed** - Works with static sites
✅ **Spam Protection** - Built-in honeypot and reCAPTCHA support
✅ **Email You Directly** - Messages go straight to your inbox

## Before Setup

Until you add your access key, the form will show a fallback message with your email address, so visitors can still contact you.

## Alternative Services

If you prefer other options:

- **Formspree**: https://formspree.io (50 submissions/month free)
- **EmailJS**: https://emailjs.com (200 emails/month free)
- **Getform**: https://getform.io (50 submissions/month free)

## Need Help?

Just let me know if you need any assistance setting this up!
