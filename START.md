# 🚀 Quick Start Guide

## Test Your Portfolio Locally with Node.js

Follow these simple steps to run your portfolio on your local machine:

### Step 1: Open Terminal/Command Prompt
Make sure you're in the portfolio directory:
```bash
cd C:\Users\avinash\Documents\my_one_repo
```

### Step 2: Start the Server

**Option A: Using npm (Recommended)**
```bash
npm start
```

**Option B: Using npx directly**
```bash
npx serve -l 8000
```

**Option C: Using http-server**
```bash
npx http-server -p 8000
```

### Step 3: Open Your Browser
Once the server starts, open your browser and go to:
```
http://localhost:8000
```

### What You'll See
- **3D Interactive Landing Page** with all your projects displayed as floating cards
- **Emoji Icons** representing each project type
- **Category Filters** at the top right (All, Animations, Simulations, etc.)
- **Hover Effects** - Move your mouse over cards to see them animate
- **Click Cards** to navigate to individual projects

### Controls
- **🖱️ Drag** - Rotate the camera view
- **🖱️ Scroll** - Zoom in/out
- **👆 Click** - Click any card to visit that project

### Troubleshooting

**If the server doesn't start:**
1. Make sure Node.js is installed: `node --version`
2. If not installed, download from: https://nodejs.org/

**If you see a blank page:**
1. Check browser console (F12) for errors
2. Make sure you're accessing `http://localhost:8000` (not `file://`)

**If projects don't load:**
1. Check that `/data/projects.json` exists
2. Look in browser console for network errors

### Next Steps

Once you confirm everything works locally:

1. **Push to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Portfolio with 26 projects"
   git branch -M main
   git remote add origin YOUR_GITHUB_URL
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repo → Settings → Pages
   - Source: Deploy from branch `main`
   - Folder: `/ (root)`
   - Save and wait 2-3 minutes

3. **Update README.md**
   - Replace `YOUR_USERNAME` with your GitHub username
   - Replace `YOUR_REPO_NAME` with your repository name

## Features Implemented ✅

- ✅ 26 projects organized in `/projects/` directory
- ✅ All project paths updated for GitHub Pages
- ✅ 3D interactive landing page with Three.js
- ✅ SVG/Emoji icons (no need for thumbnail images!)
- ✅ Category filtering (5 categories)
- ✅ Featured project badges
- ✅ Responsive design (mobile-friendly)
- ✅ Smooth animations and transitions
- ✅ Ready for GitHub Pages deployment

## Project Categories

1. **Three.js Animations** (8 projects) - Red theme
2. **Three.js Simulations** (4 projects) - Cyan theme
3. **Three.js Models** (6 projects) - Green theme
4. **Three.js Shaders** (1 project) - Pink theme
5. **Web Apps** (7 projects) - Purple theme

---

**Happy coding! 🎨✨**
