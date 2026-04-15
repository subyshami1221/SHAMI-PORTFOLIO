# Shamithasri G — Graphic Designer Portfolio

A light & elegant portfolio website for Shamithasri G.

---

## STEP-BY-STEP SETUP GUIDE

### STEP 1 — Folder Structure
Create this exact folder structure on your computer:

```
shamitha-portfolio/
│
├── index.html
├── style.css
├── script.js
├── README.md
│
└── assets/
    ├── logo-orderla.jpg
    ├── logo-econiram.jpg
    ├── logo-ulagu.jpg
    ├── logo-makeup.jpg
    ├── poster-summer.jpg
    ├── poster-fatman.jpg
    ├── poster-fatman2.jpg
    ├── mag-flimfare.jpg
    ├── mag-mockup.jpg
    ├── mag-crime.jpg
    ├── mag-children.jpg
    └── shamithasri-resume.pdf
```

---

### STEP 2 — Prepare the Images

Export / save each image from the PDFs and name them EXACTLY as listed:

| File Name | What it is |
|---|---|
| logo-orderla.jpg | Orderla circular delivery logo |
| logo-econiram.jpg | ecoNiram colourful flame logo |
| logo-ulagu.jpg | Ulagu Tamil infinity logo |
| logo-makeup.jpg | Makeup Zone by Rithu R logo |
| poster-summer.jpg | Summer Party flyer |
| poster-fatman.jpg | Fatman Club registration form |
| poster-fatman2.jpg | Fatman Club benefits sheet |
| mag-flimfare.jpg | Flimfare magazine full layout |
| mag-mockup.jpg | Magazine mockup spread |
| mag-crime.jpg | Crime article editorial layout |
| mag-children.jpg | Children's magazine spread |
| shamithasri-resume.pdf | Her resume PDF for download |

**How to extract images from PDF:**
1. Open the PDF in Adobe Acrobat / any PDF viewer
2. Take a screenshot OR use "Export as Image"
3. Save as .jpg with the exact names above
4. Place all images inside the `assets/` folder

---

### STEP 3 — Open in VS Code

1. Open VS Code
2. File → Open Folder → Select `shamitha-portfolio`
3. Install the **Live Server** extension (if not already installed)
4. Right-click `index.html` → **Open with Live Server**
5. The portfolio opens in your browser at `http://127.0.0.1:5500`

---

### STEP 4 — Test Everything

Check:
- [ ] All 4 logo images load correctly
- [ ] All 3 poster images load correctly  
- [ ] All 4 magazine images load correctly
- [ ] Clicking any image opens the lightbox popup
- [ ] Resume PDF download button works
- [ ] Mobile menu works (resize browser to test)
- [ ] All nav links scroll to correct sections

---

### STEP 5 — Push to GitHub Pages

1. Create a **new GitHub account** for Shamithasri
2. Create a new repository named: `SHAMITHA_PORTFOLIO`
3. In VS Code terminal, run:

```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/USERNAME/SHAMITHA_PORTFOLIO.git
git push -u origin main
```

4. In GitHub → Repository → **Settings** → **Pages**
5. Source: Deploy from branch → `main` → `/ (root)`
6. Save — site will be live at:
   `https://USERNAME.github.io/SHAMITHA_PORTFOLIO/`

---

### CUSTOMISATION TIPS

**To change her name or info:**
- Open `index.html`
- Search (Ctrl+F) for the text you want to change
- Edit and save

**To add more projects:**
- Copy a `logo-card` / `poster-card` / `magazine-card` block in `index.html`
- Change the image src, title, and description
- Add the new image to `assets/`

**To change colors:**
- Open `style.css`
- Edit the CSS variables at the top (`:root { }`)
- `--accent: #8b5e3c` is the main brown — change to any color you like

---

## Files Summary

| File | Purpose |
|---|---|
| `index.html` | All page content and structure |
| `style.css` | All styling and layout |
| `script.js` | Navbar, lightbox, animations |
| `assets/` | All images and resume PDF |