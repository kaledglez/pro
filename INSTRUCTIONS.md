# How to Access Your Personal Blog Webpage

## Option 1: Open Locally (Simplest)

1. **Download the files** from this repository
2. **Double-click `index.html`** - it will open in your default web browser
3. That's it! The webpage works completely offline

## Option 2: Using GitHub Pages (Online Hosting)

To publish your site online for free using GitHub Pages:

1. Go to your repository **Settings**
2. Scroll down to **Pages** section (in the left sidebar)
3. Under **Source**, select the branch: `copilot/create-personal-blog-page`
4. Click **Save**
5. Wait a few minutes, then your site will be live at:
   ```
   https://kaledglez.github.io/pro/
   ```

## Option 3: Local Web Server (For Testing)

If you want to test it with a local server:

```bash
# Navigate to the repository folder
cd /path/to/pro

# Start a simple web server (Python)
python3 -m http.server 8080

# Or using Python 2
python -m SimpleHTTPServer 8080

# Or using Node.js (if you have it installed)
npx serve .
```

Then open your browser and go to: `http://localhost:8080`

## Customization

To customize your webpage:

1. **Edit `index.html`** to update your personal information:
   - Contact details (email, phone)
   - Education details
   - Job descriptions
   - Projects
   - Skills

2. **Edit `styles.css`** to change colors, fonts, or styling:
   - Change color variables at the top of the file
   - Modify spacing, fonts, or layouts

3. **Replace stock images** with your own photos:
   - Replace the Unsplash URLs with your own image URLs
   - Or download images and reference them locally

## Browser Compatibility

The webpage works in all modern browsers:
- ✅ Chrome, Edge, Firefox, Safari
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)
- ⚠️ Note: External resources (Bootstrap, Font Awesome, Unsplash images) require an internet connection

## Need Help?

If you have any questions or need assistance, feel free to ask!
