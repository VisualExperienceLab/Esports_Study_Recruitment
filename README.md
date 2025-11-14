# Esports Configuration Study - Recruitment Page

**Professional recruitment landing page for esports configuration research study**

🎓 NC State University Visual Experience Lab | IRB #25527

---

## 🚀 Quick Setup

### 1. Add Your Hero Image

**IMPORTANT:** You need to add your custom esports characters image!

1. Save your AI-generated esports image as `hero.png`
2. Place it in the `images/` folder
3. Path should be: `images/hero.png`

**Image specs:**
- Recommended size: 1920x1080px or similar widescreen
- Format: PNG or JPG
- The image will be darkened with an overlay for text readability

---

## 📂 File Structure

```
recruitment-site/
├── index.html          ← Main recruitment page
├── images/
│   └── hero.png       ← ADD YOUR IMAGE HERE!
├── README.md          ← This file
└── .gitignore         ← Git configuration
```

---

## 🌐 Deploy to GitHub Pages

### Step 1: Add Your Image
```bash
# Save your esports characters image as hero.png
# Copy it to the images folder
cp ~/Downloads/your-esports-image.png images/hero.png
```

### Step 2: Initialize Git
```bash
cd recruitment-site
git init
git add .
git commit -m "Initial commit: Esports recruitment page"
```

### Step 3: Create GitHub Repository
1. Go to https://github.com/new
2. Name: `esports-config-recruitment`
3. Make it **Public**
4. Don't add README or .gitignore
5. Click "Create repository"

### Step 4: Push to GitHub
```bash
# Replace YOUR_USERNAME with your GitHub username
git remote add origin https://github.com/YOUR_USERNAME/esports-config-recruitment.git
git branch -M main
git push -u origin main
```

### Step 5: Enable GitHub Pages
1. Go to repository Settings
2. Click "Pages" in sidebar
3. Source: **main** branch, **/ (root)** folder
4. Click "Save"
5. Wait ~1 minute

### Your Site Will Be Live At:
```
https://YOUR_USERNAME.github.io/esports-config-recruitment/
```

---

## ✅ What's Included

- ✅ Professional academic design (HTML5 UP style)
- ✅ Clean white background with teal accents
- ✅ All 14 games listed (including FIFA and Street Fighter)
- ✅ Direct Qualtrics survey link
- ✅ Subtle prize information (no scammy appearance)
- ✅ Your contact info (Ashish Rajpurohit, arajpur@ncsu.edu)
- ✅ IRB compliance (#25527)
- ✅ Mobile responsive
- ✅ Fixed navigation
- ✅ Smooth scrolling

---

## 🎯 Changes From Previous Version

**Removed (For Professional Appearance):**
- ❌ All data files (IRB compliance)
- ❌ Large "$100" stat boxes (looked scammy)
- ❌ NVIDIA/Duke collaboration mentions
- ❌ Excessive prize emphasis

**Added/Updated:**
- ✅ Custom hero image support
- ✅ All 14 games (added FIFA/Street Fighter)
- ✅ Simplified to "18+" only
- ✅ Your contact information
- ✅ Subtle raffle mention in text
- ✅ Config file → additional raffle entry explanation
- ✅ Professional, academic appearance

---

## 📝 Content Overview

### Sections:
1. **Hero** - Eye-catching header with survey CTA
2. **What is Our Aim?** - Study overview
3. **Games We're Studying** - 14 games grid
4. **What Do You Need?** - Requirements + system info options + prize info
5. **Ready to Participate?** - Final CTA + study details

### Survey Link:
`https://ncsu.qualtrics.com/jfe/form/SV_3W8KwkVMOjMmzOu`

---

## 🛠️ Testing Locally

```bash
# Open the file directly in browser, or use a local server:
python3 -m http.server 8000

# Then visit: http://localhost:8000
```

---

## 📤 Sharing the Page

Once deployed, share this URL:

### On Reddit:
```
🎮 Participate in Esports Configuration Research

Help NC State understand how gamers configure their settings. 
Takes 10-15 minutes. Chance to win $100 gift cards!

https://YOUR_USERNAME.github.io/esports-config-recruitment/

Study approved by IRB #25527
```

### On Discord:
```
🎮 **Esports Research Study**

Help understand game configuration preferences!
- 18+ years old
- 10-15 minutes
- Chance to win $100

**Survey:** https://YOUR_USERNAME.github.io/esports-config-recruitment/
```

---

## 🔄 Updating Content

To update text, prizes, or any content:

1. Edit `index.html`
2. Commit and push:
```bash
git add index.html
git commit -m "Update: Changed prize description"
git push
```

Site updates automatically in ~1 minute!

---

## 🆘 Troubleshooting

**Image not showing?**
- Make sure image is named exactly `hero.png`
- Check it's in the `images/` folder
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)

**Page not loading on GitHub Pages?**
- Repository must be **Public**
- Wait 2-3 minutes after enabling Pages
- Check Settings → Pages shows "Your site is live"

**Want to change colors?**
- Edit the CSS in `index.html`
- Current accent color: `#4ecdc4` (teal)
- Change to your preferred color throughout the style section

---

## 📧 Contact

**Study Contact:** Ashish Rajpurohit  
**Email:** arajpur@ncsu.edu  
**Lab:** NC State Visual Experience Lab  
**IRB:** #25527

---

## 🎓 For Your Research

This recruitment page is designed for:
- ✅ Multi-game esports configuration study
- ✅ IRB-compliant participant recruitment
- ✅ Professional academic presentation
- ✅ Easy sharing on Reddit, Discord, gaming forums
- ✅ Mobile-friendly for on-the-go gamers

---

**Ready to deploy? Add your image and follow the steps above!** 🚀
