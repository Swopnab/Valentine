# 💖 Valentine's Day Special Website

A beautiful, interactive Valentine's Day website with romantic animations and special effects!

## 🌟 Features

- ✨ **Falling Hearts & Rose Petals** - Continuous romantic animations
- 💫 **Sparkle Trail** - Mouse cursor leaves magical sparkles
- 🎊 **Confetti Explosion** - Celebratory burst when she says YES!
- 🎆 **Fireworks Display** - Multiple fireworks launch across the screen
- 🎵 **Background Music** - Romantic music with toggle control
- 📸 **Photo Slideshow** - Auto-rotating memories carousel  
- 💌 **Floating Love Notes** - Sweet messages appear randomly
- 💕 **Hearts Converging** - Two hearts meet in the middle animation
- 📅 **Days Counter** - Shows days you've been together
- 🌟 **Twinkling Stars** - Beautiful starry background
- 📱 **Fully Responsive** - Works perfectly on all devices

## 🎯 How to Personalize

### 1. **Replace Photos**

Replace these 3 placeholder photos with your own memories:

- `photo1.png`
- `photo2.png`
- `photo3.png`

💡 **Tip**: Use square photos (400x400px or similar ratio) for best results!

### 2. **Update the Start Date**

In `index.html`, find this line (around line 964):

```javascript
const startDate = new Date('2024-01-01'); // CHANGE THIS DATE
```

Change `'2024-01-01'` to your actual relationship start date!

### 3. **Customize Love Notes** (Optional)

In `index.html`, find the `LOVE_NOTES` array (around line 507) and add your own sweet messages!

### 4. **Change Background Music** (Optional)

Replace the music URL in the `<audio>` tag with your preferred romantic song URL.

## 🚀 Deploy to GitHub Pages

### Step 1: Create Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it whatever you like (e.g., `valentine-surprise`)
3. Make it Public or Private (both work with GitHub Pages)

### Step 2: Upload Files

```bash
cd Valentine-1
git init
git add .
git commit -m "💖 First commit - Valentine's surprise!"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings**
3. Scroll to **Pages** in the left sidebar
4. Under **Source**, select `main` branch
5. Click **Save**
6. Wait 1-2 minutes for deployment

### Step 4: Get Your URL

Your site will be live at:

```
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
```

## 📝 Important Notes

### ✅ GitHub Pages Compatible Features

- **Music**: Uses CDN-hosted romantic music (works on GitHub Pages)
- **Photos**: Uses relative paths (just add your images to the repo)
- **All Animations**: Pure JavaScript/CSS (no external dependencies)
- **Icons & Emojis**: Built-in Unicode emojis (no image files needed)

### 🎨 Customization Tips

- All colors are easily changeable in the CSS
- Adjust animation speeds by modifying the `animation` properties
- Change emoji symbols in the JavaScript arrays
- Modify the celebration message in the `handleYes()` function

## 💝 Long-Distance Relationship Mode

This website includes subtle touches perfect for long-distance relationships:

- "Every moment with you is worth the wait!"
- "Here's to being together this Valentine's Day!"
- Days counter shows how long you've been making it work
- No direct mention of distance, just heartfelt appreciation

## 🎵 Music Controls

- Click the 🎵 button in the bottom-right corner to toggle music
- Music auto-plays when she clicks "Yes"
- Button pulses when music is playing

## 📱 Mobile Friendly

- All animations work on touch devices
- Responsive design adapts to any screen size
- Touch-friendly buttons
- Optimized performance on mobile

## 🛠️ Technical Stack

- Pure HTML5
- Vanilla CSS3
- Vanilla JavaScript
- HTML5 Canvas for animations
- No frameworks or libraries needed!

## ❤️ Features Breakdown

### On "Yes" Click

1. Confetti explosion 🎊
2. Fireworks display 🎆
3. Hearts converging animation 💖
4. Photo slideshow appears 📸
5. Days counter reveals 📅
6. Music starts playing 🎵
7. Sweet message displays 💌

### Background Animations (Always Active)

- Falling hearts from top
- Floating rose petals
- Twinkling stars
- Sparkle mouse trail
- Floating love notes every 5 seconds

## 🎁 Perfect For

- Valentine's Day proposals
- Anniversary surprises
- Long-distance relationships
- Special romantic gestures
- Just because you love them! 💕

---

Made with 💖 for someone special!

**Remember to personalize it before sharing!** ✨
