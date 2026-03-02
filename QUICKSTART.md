# 🚀 QUICK START - Your 90s Website

Your maximalist, chaotic, beautiful 90s website is READY!

## 🏃 Run It Right Now

```bash
cd retro-chaos-site
npm install
npm start
```

Open: `http://localhost:8080`

## 🎨 What You Got

✅ **STARFIELD BACKGROUND** - Twinkling stars everywhere
✅ **HUGE ORANGE STRIPED TITLE** - Just like the PDF!
✅ **WINDOW-STYLE BOXES** - Windows 95 UI vibes
✅ **FLAME DIVIDERS** - Animated fire sections
✅ **3-COLUMN LAYOUT** - Left sidebar, center, right sidebar

### Sections Included:

**LEFT SIDEBAR:**
- 📚 Books I Read (with star ratings)
- ⚙️ Projects I'm Working On
- 💀 Projects I've Abandoned (for brutal honesty!)

**CENTER:**
- 👤 About Me section
- 🚨 RECRUITER ALERT with bookmark button
- 🎨 Graphics Collection (88x31 buttons)
- 🚧 Under Construction banner

**RIGHT SIDEBAR:**
- 🎮 Games I'm Playing
- ✅ Games I Finished (with ratings)
- 📝 Updates log
- 🎵 Media Player (Winamp style!)

## ⚡ Customize in 2 Minutes

### 1. Your Info
Edit `src/_data/site.json`:
```json
{
  "name": "YOUR SITE NAME",
  "author": "Your Name",
  "email": "your@email.com"
}
```

### 2. Add Your Content
Edit `src/index.md` - search for:
- "Book Title" → Add your books
- "Game Title" → Add your games
- "Project Name" → Add your projects
- About Me section → Write about yourself

### 3. Change Colors (Optional)
In `src/css/style.css`, line ~30:
```css
background: repeating-linear-gradient(
  0deg,
  #ff6600 0px,  ← Change these!
  #ff8800 2px,
  #ff6600 4px
);
```

Try:
- Purple: `#9900ff`, `#bb00ff`, `#9900ff`
- Cyan: `#00ffff`, `#00ddff`, `#00ffff`
- Pink: `#ff00ff`, `#ff66ff`, `#ff00ff`

## 🌐 Deploy to GitHub Pages

```bash
# Create repo: yourname.github.io
git init
git add .
git commit -m "My 90s website!"
git remote add origin https://github.com/yourname/yourname.github.io.git
git push -u origin main
```

Then:
1. Go to repo Settings → Pages
2. Select "GitHub Actions" as source
3. Done! Live at `yourname.github.io`

## 🎯 Key Features

### Recruiter Section
The big yellow box with "ARE YOU A RECRUITER?" 
- Blinks to get attention
- Has a bookmark button
- Shows you mean business!

### Books Section
Add your books:
```html
<div class="book-item">
  <strong>"Book Title"</strong>
  <span>by Author</span>
  <p>⭐⭐⭐⭐⭐</p>
</div>
```

### Projects
Shows what you're building AND what you abandoned (honesty!)

### Games
Two sections:
- Currently playing
- Finished (with star ratings)

## 📂 File Structure

```
src/
├── index.md       ← EDIT THIS for all content
├── css/style.css  ← ALL the styles
├── _data/
│   └── site.json  ← Your personal info
```

## 💡 Pro Tips

1. **Add GIFs** - Download from gifcities.org, put in `src/img/`
2. **More buttons** - Find 88x31 buttons at cyber.dabamos.de/88x31/
3. **Change everything** - It's your site, go wild!
4. **Under construction forever** - It's tradition 😄

## 🎨 The Aesthetic

This matches "Webpage 1990 Colourised":
- ✅ Starfield background
- ✅ Big striped orange title
- ✅ Window boxes
- ✅ Flame dividers
- ✅ Neon "OPEN 24 HRS" sign
- ✅ Chaotic maximalist layout
- ✅ Computer icons floating
- ✅ Under construction banner

## 🆘 Help

Full documentation in `README.md`

---

**GO MAKE IT YOURS!** 🌐🔥✨
