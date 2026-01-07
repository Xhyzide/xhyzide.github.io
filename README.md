# Personal Website

A simple, responsive personal portfolio website hosted on GitHub Pages.

## Setup Instructions

### 1. Create GitHub Repository
1. Go to GitHub and create a new repository named `username.github.io` (replace with your actual GitHub username)
2. Make sure it's public

### 2. Clone & Setup Locally
```bash
git clone https://github.com/username/username.github.io.git
cd username.github.io
```

### 3. Add Files
Copy the files from this folder (`index.html`, `styles.css`) into your repository folder.

### 4. Customize
Edit `index.html` and replace:
- "Your Name" with your actual name
- Bio and description
- Add your projects in the Portfolio section
- Update social links with your profiles
- Change the email in the contact section

### 5. Deploy
```bash
git add .
git commit -m "initial commit"
git push origin main
```

Your site will be live at `https://username.github.io` within a few minutes.

## Customization Tips

- **Colors**: Edit the CSS color values in `styles.css` (look for hex codes like `#667eea`)
- **Add More Sections**: Copy a section block in HTML and modify
- **Add Images**: Create an `images` folder and link to images with `<img src="images/photo.jpg">`
- **Custom Domain**: GitHub Pages supports custom domains (Settings → Pages)

## Next Steps
- Add a blog section
- Integrate contact form
- Add animations
- Implement dark mode
