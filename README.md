# Sonya Freeney - Portfolio Website

Professional portfolio site built with HTML/CSS for GitHub Pages deployment.

## Features

- Clean, modern design using TARDIS color palette
- Fully responsive (mobile, tablet, desktop)
- Projects showcase with live demo links
- About, expertise, and contact sections
- Zero dependencies - pure HTML/CSS

## Setup Instructions

### Option 1: Quick Deploy to GitHub Pages

1. **Create a new repository** on GitHub:
   - Name it `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
   - Make it public
   - Don't initialize with README

2. **Upload these files**:
   - Click "uploading an existing file"
   - Drag and drop `index.html`, `style.css`, and this `README.md`
   - Commit the files

3. **Enable GitHub Pages**:
   - Go to Settings → Pages
   - Under "Source", select `main` branch and `/ (root)` folder
   - Click Save
   - Wait ~1 minute

4. **Visit your site** at `https://yourusername.github.io`

### Option 2: Using Git Command Line

```bash
# Clone your repo
git clone https://github.com/yourusername/yourusername.github.io.git
cd yourusername.github.io

# Copy these files into the repo folder
# Then commit and push
git add .
git commit -m "Initial portfolio site"
git push origin main
```

## Customization

### Update Your Information

Open `index.html` and replace:

1. **Contact Links** (bottom of file):
   - Line ~140: Add your LinkedIn URL
   - Line ~141: Add your GitHub username
   - Line ~142: Add your email

2. **Project Links**:
   - Line ~48: Your CS Playbook Generator GitHub repo
   - Line ~59: Your Job Tracker GitHub repo  
   - Line ~68: Link to your Strategic Workbook (if deployed)

3. **Personal Info**:
   - Update the intro text in the hero section
   - Modify the "About Me" section to match your voice
   - Add/remove projects as needed
   - Update expertise areas to reflect your focus

### Color Customization

The TARDIS palette is defined in `style.css` at the top:

```css
:root {
    --slate-blue: #3d5a73;
    --slate-blue-dark: #2a4560;
    --cream: #dccdb4;
    --cream-light: #e8dcc8;
    /* ... */
}
```

To change colors, just update these hex values.

### Adding Images

To add a profile photo or project screenshots:

1. Create an `images` folder in your repo
2. Upload your images there
3. Reference them in HTML like: `<img src="images/your-photo.jpg" alt="Description">`

## Testing Locally

Want to preview before pushing to GitHub?

1. Open `index.html` directly in your browser, or
2. Use a simple local server:
   ```bash
   # If you have Python installed:
   python -m http.server 8000
   
   # Then visit: http://localhost:8000
   ```

## License

Feel free to use this template for your own portfolio. No attribution required.

## Notes

- No build process needed - it's just HTML and CSS
- Works on all modern browsers
- Loads fast (no frameworks, no JavaScript)
- Easy to maintain and update

---

Built with intention, not templates.
