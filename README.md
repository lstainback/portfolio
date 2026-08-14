# Lauren Stainback — Instructional Design Portfolio

Personal portfolio website built with HTML and the Organic design system.

## Live site

After deploying: `https://lstainback.github.io/[your-repo-name]`

---

## GitHub Pages setup (step by step)

1. **Create a new repo** at github.com/new  
   - Name it something like `portfolio`  
   - Set it to **Public**  
   - Click **Create repository**

2. **Upload your files**  
   - On the repo page, click **Add file → Upload files**  
   - Drag in everything from this project folder (all `.dc.html` files, the `_ds/` folder, the `uploads/` folder, and this README)  
   - Click **Commit changes**

3. **Enable GitHub Pages**  
   - Go to **Settings → Pages** (left sidebar)  
   - Under **Source**, choose `Deploy from a branch`  
   - Set branch to `main`, folder to `/ (root)`  
   - Click **Save**

4. **Wait ~2 minutes**, then visit `https://lstainback.github.io/portfolio`

> The main page is `index.dc.html` — rename it to `index.html` before uploading so GitHub Pages loads it automatically as the home page.

---

## File structure

```
index.dc.html                  → Home page (rename to index.html for GitHub Pages)
projects.dc.html               → Projects listing
project-articulate.dc.html     → Articulate 360 project page
project-claude-skills.dc.html  → Claude Skills project page
project-canvas.dc.html         → Canvas LMS project page
project-playlab.dc.html        → Play Lab Bot project page
uploads/                       → Your photos and assets
_ds/                           → Organic design system (do not edit)
```

---

## Updating content

All pages are plain HTML — open any file in a text editor and edit the text directly. No build step or coding experience needed for copy edits.

### Add your Claude skill link
In `project-claude-skills.dc.html`, find:
```html
<a href="#" class="btn btn-primary ...">Open the Claude Skill →</a>
```
Replace `#` with your Claude skill URL.

### Add project screenshots
Replace the placeholder box on any project page with:
```html
<img src="your-screenshot.png" style="width:100%; border-radius:16px;" alt="Description">
```
Upload the image to your repo alongside the HTML files.

### Add your Play Lab URL
In `project-playlab.dc.html`, find `href="#"` on the "Open Play Lab" button and replace with your URL.
