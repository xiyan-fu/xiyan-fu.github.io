# Xiyan Fu — Personal Academic Website

A static academic homepage inspired by [Wei Tao's site](https://itaowe.com/), built with plain HTML/CSS/JS (no build step).

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
# Python
python -m http.server 8080

# Node (if npx available)
npx serve .
```

Then visit `http://localhost:8080`.

## Deploy (GitHub Pages)

1. Create a GitHub repository and push this folder.
2. In **Settings → Pages**, set source to **main** branch, folder **/ (root)**.
3. Your site will be at `https://<username>.github.io/<repo>/`.

## Customize

| Item | File / location |
|------|-----------------|
| Photo | Replace `profile__photo` `src` in `index.html` (or add `assets/images/photo.jpg`) |
| Email, links | Sidebar `contact-list` in `index.html` |
| Bio & publications | `index.html` main sections |
| Colors & fonts | `assets/css/main.css` |

## Data sources

- [Google Scholar](https://scholar.google.com/citations?user=q1glETQAAAAJ&hl=en)
- [ACL Anthology](https://aclanthology.org/people/xiyan-fu/)
