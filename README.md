## Personal site for GitHub Pages

This repository contains the source for **Elizaveta Pestova’s** personal website and robotics portfolio, served via GitHub Pages.

### Structure

- `index.html` – main landing page with summary, contacts and technical stack.
- `projects.html` – robotics and autonomy case studies (sim-to-real, teleoperation, simulation infrastructure, navigation).
- `cv.html` – CV-style page with work experience, education, skills and publications.
- `blog.html` – professional notes and future blog posts about robotics and control.
- `assets/css/style.css` – shared styling for all pages.

### Local preview

You can open any of the HTML files directly in a browser, or use a simple HTTP server for local testing, for example:


```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

### Deploying to GitHub Pages

1. Push this repository to GitHub as `<username>.github.io`.
2. In the repository settings, enable GitHub Pages (if necessary).
3. The site will be available at `https://<username>.github.io`.

# LizaP9.github.io