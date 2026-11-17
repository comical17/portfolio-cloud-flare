# COMICAL STUDIO — 2D & 3D Animation Portfolio

An interactive, responsive animation portfolio website featuring:
- **Dedicated 2D Animation Page (`2d.html`)** displaying all 13 hand-drawn 2D reels, walk cycles, combat studies, and storyboard animatics with category filtering.
- **Dedicated 3D Modeling Page (`3d.html`)** displaying the interactive Three.js 3D Comical maquette, 4 turntable reels, and 18 high-resolution character model sheets.
- **Homepage (`index.html`)** with interactive mascot, Hero Dynamic Pose Switcher (Hero, Shrug, Panic, T-Pose), and the complete 4-step 2D/3D Animation Process Pipeline.
- **Service & Collaboration Pricing Cards** with direct project brief form and clipboard email copy.

---

## Project Structure

```
comical-portfolio/
├── index.html                     # Main entry homepage for Cloudflare Pages / GitHub Pages
├── 2d.html                        # Dedicated 2D Animation Portfolio page
├── 3d.html                        # Dedicated 3D Modeling & Animation page
├── comical-portfolio.html         # Original HTML backup (preserved untouched)
├── index.html.txt                 # Original text backup (preserved untouched)
├── _headers                       # Cloudflare Pages HTTP range & video cache headers
├── .gitignore                     # Git ignore rules for clean deployment
│
├── 2d videos/                     # 13 Hand-drawn 2D animation MP4 reels
│   ├── COM11.mp4
│   ├── Female crocs2d.mp4
│   ├── mani Football.mp4
│   ├── Mani Office.mp4
│   ├── mani space.mp4
│   ├── Most famous Thug.mp4
│   ├── stick man_1.mp4
│   ├── 1re draw tribe.mp4
│   ├── dogesh22.mp4
│   ├── jorden1.mp4
│   ├── test 2.mp4
│   ├── zackd aniamtion.mp4
│   └── Empire Mine_SB.mp4
│
└── 3D RENDER/                     # 4 3D animation/turntable MP4 reels + 18 renders
    ├── MOUSE.mp4
    ├── oleo.mp4
    ├── OLEO2.mp4
    ├── VARIO.mp4
    └── RE4NDER/                   # High-res character model sheets & clay sculpts (JPEG)
```

---

## How to Test Locally

You can open `index.html`, `2d.html`, or `3d.html` directly in any web browser:
1. Double-click `index.html` in your file explorer.
2. Click **2D Art** in the top navigation to navigate to `2d.html`.
3. Click **3D Models** in the top navigation to navigate to `3d.html`.
4. Click the **COMICAL** logo to return to the homepage anytime.

---

## How to Deploy to GitHub & Cloudflare Pages

### Step 1: Initialize Git Repository
```bash
cd c:\Users\comical\Documents\comical-portfolio
git init
git add .
git commit -m "Comical Studio portfolio with dedicated 2D and 3D pages"
```

### Step 2: Push to GitHub
```bash
git remote add origin https://github.com/YOUR_USERNAME/comical-portfolio.git
git branch -M main
git push -u origin main
```

### Step 3: Deploy on Cloudflare Pages
1. Log in to [Cloudflare Dashboard](https://dash.cloudflare.com/) > **Compute (Workers) > Pages**.
2. Click **Connect to Git** and choose `comical-portfolio`.
3. Leave Build Command empty, Output Directory as `/` (root), and click **Save and Deploy**.
