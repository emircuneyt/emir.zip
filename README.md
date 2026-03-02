# 🌐 90s Maximalist Personal Website

A chaotic, maximalist personal website inspired by Geocities, old-school web design, and the golden age of the internet. Built with 11ty, deployed on GitHub Pages.

## ✨ Features

- 🎨 **Full 90s Aesthetic** - Starfield background, orange striped title, neon signs
- 💻 **Window-Style Boxes** - Classic Windows 95/98 UI elements
- 🔥 **Flame Dividers** - Animated fire separators
- 📚 **Books Section** - Show what you're reading with ratings
- 🎮 **Gaming Sections** - Currently playing + finished games
- ⚙️ **Projects** - Active projects + abandoned projects (for honesty!)
- 🚨 **Recruiter Alert** - Special section with bookmark reminder
- 🎵 **Media Player** - Classic Winamp-style player interface
- 📝 **Updates Log** - Changelog sidebar
- 🖼️ **88x31 Buttons** - Classic web button collection

## 🚀 Quick Start

### Install and Run

```bash
npm install
npm start
```

Visit: `http://localhost:8080`

### Build for Production

```bash
npm run build
```

## 🎨 Customize Your Site

### 1. Update Basic Info

Edit `src/_data/site.json`:
```json
{
  "name": "YOUR WEBSITE NAME",
  "subtitle": "COLOURISED",
  "author": "Your Name",
  "email": "your@email.com",
  "github": "https://github.com/yourname"
}
```

### 2. Change Colors

Edit `src/css/style.css` - find these variables:

**Main Title Color** (currently orange stripes):
```css
background: repeating-linear-gradient(
  0deg,
  #ff6600 0px,   /* Change these colors */
  #ff8800 2px,
  #ff6600 4px
);
```

Popular alternatives:
- **Purple**: `#9900ff`, `#bb00ff`, `#9900ff`
- **Cyan**: `#00ffff`, `#00ddff`, `#00ffff`
- **Green**: `#00ff00`, `#00ff88`, `#00ff00`
- **Pink**: `#ff00ff`, `#ff66ff`, `#ff00ff`

### 3. Add Your Content

All content is in `src/index.md`:

**Books Section:**
```html
<div class="book-item">
  <strong>"Your Book Title"</strong>
  <span>by Author Name</span>
  <p>⭐⭐⭐⭐⭐</p>
</div>
```

**Projects:**
```html
<div class="project-item">
  <h4>Project Name</h4>
  <p>Project description here</p>
</div>
```

**Games:**
```html
<li>Game Title ⭐⭐⭐⭐⭐</li>
```

### 4. Customize Sections

The homepage has:
- **Left Sidebar**: Books, Active Projects, Abandoned Projects
- **Center**: About Me, Recruiter Alert, Graphics
- **Right Sidebar**: Games Playing, Games Finished, Updates, Media Player

Rearrange, add, or remove sections by editing `src/index.md`!

## 🌐 Deploy to GitHub Pages

### Step 1: Create Repository

Create a repo named `yourname.github.io`

### Step 2: Push Code

```bash
git init
git add .
git commit -m "Initial commit - 90s website"
git branch -M main
git remote add origin https://github.com/yourname/yourname.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to repository **Settings**
2. Click **Pages** in sidebar
3. Under "Build and deployment", select **GitHub Actions**
4. Workflow file is already included!

Your site will be live at: `https://yourname.github.io`

## 📁 Project Structure

```
retro-chaos-site/
├── src/
│   ├── _data/
│   │   └── site.json          # Your info
│   ├── _includes/
│   │   └── layouts/
│   │       └── base.njk       # Base HTML template
│   ├── css/
│   │   └── style.css          # ALL THE STYLES
│   ├── js/
│   │   └── main.js            # Simple JS
│   └── index.md               # HOMEPAGE - edit this!
├── .eleventy.js               # 11ty config
├── .github/
│   └── workflows/
│       └── deploy.yml         # Auto-deploy
├── package.json
└── README.md
```

## 🎯 Design Elements Explained

### Starfield Background
Created with CSS radial gradients and animated twinkling

### Orange Striped Title
Uses `repeating-linear-gradient` with text clipping

### Window Boxes
Classic Windows 95 styled with gradients and borders

### Flame Divider
Gradient animation that flickers like real fire

### Neon Text
Multiple text-shadows create the glow effect

### Media Player
Styled like classic Winamp/Windows Media Player

## 💡 Customization Ideas

### Add More Sections

Copy any window box and modify:
```html
<div class="window-box">
  <div class="window-title">
    <span>📌 Your Section Title</span>
    <div class="window-buttons">
      <div class="window-button">_</div>
      <div class="window-button">□</div>
      <div class="window-button">×</div>
    </div>
  </div>
  <div class="window-content">
    Your content here!
  </div>
</div>
```

### Add Animated GIFs

Download from sites like:
- gifcities.org
- giphy.com (search "pixel art")

Add to your page:
```html
<img src="/img/your-gif.gif" alt="cool gif">
```

### Add More 88x31 Buttons

Find buttons at:
- cyber.dabamos.de/88x31/
- anlucas.neocities.org/88x31Buttons

Add to graphics section:
```html
<a href="URL" class="button-88x31">BUTTON TEXT</a>
```

### Change Fonts

Current fonts:
- Title: `Press Start 2P` (pixel font)
- Body: `Comic Sans MS` (maximum nostalgia)

Change in `style.css`:
```css
@import url('https://fonts.googleapis.com/css2?family=YOUR_FONT&display=swap');

body {
  font-family: 'YOUR_FONT', cursive;
}
```

## 🎮 Adding Interactive Elements

### Visitor Counter

Use services like:
- cutercounter.com
- freecounterstat.com

### Guestbook

Use:
- 123guestbook.com
- smartgb.com

### Music Player

Embed Spotify playlist:
```html
<iframe src="your-spotify-embed-url" width="300" height="80"></iframe>
```

## 📚 Resources

- [Neocities](https://neocities.org/) - Free hosting alternative
- [Gifcities](https://gifcities.org/) - Geocities GIF archive
- [88x31 Buttons](https://cyber.dabamos.de/88x31/) - Web button collection
- [Internet Archive](https://web.archive.org/) - Old website inspiration

## 🛠️ Tech Stack

- **11ty** - Static site generator
- **Nunjucks** - Templating
- **Pure CSS** - No frameworks, just chaos
- **GitHub Pages** - Free hosting

## ⚡ Performance

Despite the chaotic design:
- Fast loading (static HTML)
- No heavy JavaScript
- Optimized CSS animations
- Works on all browsers

## 📝 License

MIT - Do whatever you want with it!

## 🤝 Contributing

Found a bug? Have ideas? Open an issue or PR!

## ❤️ Credits

Inspired by:
- Geocities (RIP 2009)
- Webpage 1990 Colourised
- The beautiful chaos of the early web

---

**Welcome to the 90s!** 🌐✨ Now go make something weird and wonderful!
