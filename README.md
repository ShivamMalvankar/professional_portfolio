# Shivam Malvankar — Portfolio Website

A dark, futuristic portfolio website built with pure HTML, CSS, and JavaScript.  
No frameworks. No build step. Just upload and go live. 🚀

---

## 🖥️ Live Demo

> After setup: `https://ShivamMalvankar.github.io/portfolio/`

---

## 🚀 Deploy to GitHub Pages (Step-by-Step)

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and log in
2. Click the **+** icon → **New repository**
3. Name it: `portfolio` (or anything you like)
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload the file
**Option A — Upload via browser (easiest):**
1. In your new repo, click **Add file → Upload files**
2. Drag and drop `index.html` into the upload area
3. Scroll down, click **Commit changes**

**Option B — Via Git (if you have Git installed):**
```bash
git clone https://github.com/ShivamMalvankar/portfolio.git
cd portfolio
# Copy index.html into this folder, then:
git add index.html
git commit -m "Add portfolio website"
git push origin main
```

### Step 3 — Enable GitHub Pages
1. In your repository, click **Settings** (top menu)
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select `main` branch → `/ (root)`
4. Click **Save**
5. Wait ~1 minute, then visit:
   ```
   https://ShivamMalvankar.github.io/portfolio/
   ```

---

## 📁 File Structure

```
portfolio/
└── index.html      ← The entire website (single file)
└── README.md       ← This file
```

---

## ✏️ Customization

| What to change | Where in index.html |
|---|---|
| Project GitHub links | Search `href="https://github.com/ShivamMalvankar"` |
| Phone number | Search `+91 98193 81110` |
| Email | Search `shivammalvankar07@gmail.com` |
| Add new projects | Copy a `.project-card` div block |
| Add new skills | Copy a `.skill-chip` div |
| Typing phrases | Find the `phrases` array in `<script>` |

---

## 🛠️ Built With

- Pure HTML5, CSS3, JavaScript
- Google Fonts (Syne + Space Mono)
- Canvas API for animated particle background
- IntersectionObserver for scroll animations
- Zero dependencies — works offline too

---

Made with ❤️ by Shivam Malvankar — Mumbai, India
