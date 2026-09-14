# Bao Long Nguyen — Engineering Portfolio

This is a simple static portfolio website built with HTML, CSS, and JavaScript.

## 1. Open it locally
Double-click `index.html`.

If your browser blocks anything, open the folder in VS Code and use the Live Server extension.

## 2. What to edit first
Open `index.html` in VS Code and search for:
- `Bao Long Nguyen`
- `1nguyenbaolong@gmail.com`
- `LinkedIn placeholder`
- Experience and project text

## 3. Add your real LinkedIn
Find the Contact section in `index.html` and add a link like:

```html
<a class="btn secondary" href="https://www.linkedin.com/in/YOUR-NAME" target="_blank">LinkedIn</a>
```

## 4. Add project photos later
Create a folder named `images` and put your photos there.
Then add this inside a project card:

```html
<img src="images/project-photo.jpg" alt="Description of the project" />
```

## 5. Publish free with GitHub Pages
1. Open repository Settings → Pages.
2. Under Build and deployment, choose `Deploy from a branch`.
3. Select branch `main` and folder `/root`.
4. Save. GitHub will give you a public URL.

## 6. Custom domain (optional)
Later you can buy a domain such as `baolongnguyen.com` and connect it to GitHub Pages.

## File structure
- `index.html` — all portfolio content
- `styles.css` — design, colors, layout, mobile responsiveness
- `script.js` — mobile menu and simple animations
- `resume.pdf` — your downloadable résumé
