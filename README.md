# Battle Royale Championship (BRC) Website

Welcome to the **Battle Royale Championship** website repository! This is the official promotional website for the world's first real-world humanoid robot battle royale competition.

![BRC Logo](assets/brc-logo.png)

## 🤖 What is This?

This is a **single-page website** that showcases the Battle Royale Championship concept - an innovative sporting entertainment event where humanoid robots compete in a last-bot-standing competition across global arenas.

The website presents:
- The vision and format of BRC
- Technology infrastructure
- Arena locations (Playas)
- Market opportunity
- Frequently asked questions

## ✨ Features

- **Single HTML File** - No complex setup required
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Rich Media** - Promotional videos and high-quality images
- **No External Dependencies** - Pure HTML and CSS, no frameworks needed
- **Fast Loading** - Optimized images with lazy loading
- **Modern Design** - Clean, tech-forward aesthetic with monospace typography

## 📁 Project Structure

```
BRC website Code/
│
├── index.html          # Main website file (the entire website!)
│
└── assets/             # All images and videos
    ├── brc-logo.png
    ├── Robotic_Warfare_Simulation_Drone_Shot.mp4
    ├── BRCicon1.png, BRCicon2.png, BRCicon3.png
    ├── BRCTech1.png, BRCTech2.png, BRCTech3.png
    └── [other images]
```

## 🚀 How to Use (For Non-Technical Users)

### Option 1: View Locally on Your Computer

1. **Download the files** from this repository
2. **Open the folder** where you saved the files
3. **Double-click `index.html`** - The website will open in your web browser!

That's it! No installation, no setup required.

### Option 2: Make Changes to the Website

**You don't need to know coding!** Here's how to make simple changes:

#### Changing Text:
1. **Right-click `index.html`** and select "Open with Notepad" (Windows) or "TextEdit" (Mac)
2. **Find the text** you want to change (use Ctrl+F or Cmd+F to search)
3. **Edit the text** between the `>` and `<` symbols
4. **Save the file** (Ctrl+S or Cmd+S)
5. **Refresh your browser** to see the changes

**Example:**
```html
<h1>Battle Royale Championship</h1>
```
Just change "Battle Royale Championship" to whatever you want!

#### Changing Images:
1. **Add your new image** to the `assets` folder
2. **Open `index.html`** in Notepad or TextEdit
3. **Find** the old image filename (use Ctrl+F or Cmd+F)
4. **Replace** the filename with your new image name
5. **Save and refresh** your browser

**Example:**
```html
<img src="assets/old-image.png" alt="Description">
```
Change `old-image.png` to `new-image.png`

### Option 3: Publish Online (Free!)

#### Using GitHub Pages (Recommended):
1. The website is already on GitHub at: `https://github.com/PravaigDynamics/battleroyalechampionship`
2. Go to **Settings** → **Pages**
3. Under "Source", select **main branch**
4. Click **Save**
5. Your website will be live at: `https://pravaigdynamics.github.io/battleroyalechampionship/`

*Note: It may take a few minutes to go live.*

#### Other Free Hosting Options:
- **Netlify**: Drag and drop your folder at [netlify.com/drop](https://netlify.com/drop)
- **Vercel**: Sign up at [vercel.com](https://vercel.com) and import your GitHub repository
- **Cloudflare Pages**: Connect your GitHub at [pages.cloudflare.com](https://pages.cloudflare.com)

## 📱 Website Sections

The website includes these main sections (accessible from the top navigation):

1. **Executive** - Hero video and vision statement
2. **Format** - How the competition works
3. **Playas** - Arena locations around the world
4. **Technology** - Infrastructure and tech stack
5. **FAQ** - Common questions answered

Additional sections:
- Market Opportunity
- Problem We Solve
- Why Now
- Safety & Compliance
- Contact & Next Steps

## 🎨 Customization Guide

### Changing Colors

Find this section in `index.html` (around line 7-51):

```css
<style>
  body { background-color: #ffffff; } /* Page background */
  hr { border: 1px solid #000; }      /* Divider lines */
  /* ... and more */
</style>
```

Change `#ffffff` (white) to any color code you want. [Get color codes here](https://htmlcolorcodes.com/)

### Adding New Sections

1. Find where you want to add the section
2. Copy an existing section's structure
3. Change the content
4. Add a link in the navigation menu at the top

### Updating the Hero Video

1. Add your video to the `assets` folder
2. Find this line (around line 73):
```html
<source src="assets/Robotic_Warfare_Simulation_Drone_Shot.mp4" type="video/mp4">
```
3. Change the filename to your video's name
4. Save and refresh!

## 💡 Tips for Non-Technical Users

- **Always make a backup** before editing (copy the file and save it as `index-backup.html`)
- **Test locally first** - Open the file in your browser before publishing
- **Use simple text editors** - Notepad (Windows) or TextEdit (Mac) work great
- **Don't delete the `<` and `>` symbols** - These are HTML tags that make the website work
- **Save often** - Press Ctrl+S or Cmd+S frequently while editing
- **Check on mobile** - Open the website on your phone to see how it looks

## 🆘 Common Issues & Solutions

### The website looks broken after editing:
- **Solution**: You might have accidentally deleted a `<` or `>` symbol. Use your backup file and try again carefully.

### Images aren't showing:
- **Check**: Are the images in the `assets` folder?
- **Check**: Did you spell the filename exactly right (including .png or .jpg)?
- **Check**: Filenames are case-sensitive! `Image.png` ≠ `image.png`

### Changes aren't showing:
- **Solution**: Do a "hard refresh" - Press Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)

### Video won't play:
- **Solution**: Make sure the video is in MP4 format. Convert it using free tools like [CloudConvert](https://cloudconvert.com/)

## 🛠️ For Developers

If you're a developer looking for technical details:

- **Tech Stack**: Pure HTML5 and CSS3 (no JavaScript)
- **Styling**: Inline CSS with responsive media queries
- **Layout**: Flexbox and CSS Grid
- **Images**: Lazy loading enabled
- **Video**: HTML5 video with autoplay, mute, and loop
- **No Build Process**: Zero dependencies, no npm/webpack/bundler needed
- **Browser Support**: Works in all modern browsers (Chrome, Firefox, Safari, Edge)

### Quick Commands for Developers:

```bash
# Clone the repository
git clone https://github.com/PravaigDynamics/battleroyalechampionship.git

# Navigate to folder
cd battleroyalechampionship

# Open in browser (or just double-click index.html)
# Mac:
open index.html

# Windows:
start index.html

# Linux:
xdg-open index.html
```

## 📞 Contact & Support

**For questions or collaboration opportunities:**

📧 Email: **contact@thebrc.co**

**Found a bug or want to suggest a feature?**
- Open an [Issue](https://github.com/PravaigDynamics/battleroyalechampionship/issues)
- Or submit a [Pull Request](https://github.com/PravaigDynamics/battleroyalechampionship/pulls)

## 📄 License

This project is part of the Battle Royale Championship initiative by Pravaig Dynamics.

---

## 🎯 Quick Start Checklist

- [ ] Download or clone this repository
- [ ] Open `index.html` in your browser
- [ ] Make your changes in a text editor
- [ ] Save and refresh to see updates
- [ ] Publish to GitHub Pages or other hosting

---

**Made with ❤️ for the future of robot combat sports**

*Battle Royale Championship - Where technology meets entertainment*
