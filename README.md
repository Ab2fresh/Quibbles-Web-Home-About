# Quibbles — Web Homepage & About Page

A recreation of the Quibbles platform homepage and About page, built with
plain HTML and CSS.

## 🔗 Live Repository
https://github.com/Ab2fresh/Quibbles-Web-Home-About

## 📄 About the Project
This project replicates the Quibbles homepage (post feed, sidebar,
communities, recommended posts) and the About Quibbles page, using a
single `index.html` file with embedded CSS and a small JavaScript
function to switch between the Home and About views.

## 🗂️ Project Structure
quibbles-project/
├── index.html        # Homepage + About page (HTML, CSS, JS all in one file)
└── images/
└── logo.jpeg      # Quibbles logo and username avatar
## 🛠️ How It Was Built
1. Studied the layout of the homepage and About page — top bar, sidebar
   navigation, communities list, resources list, post feed, and the
   recommended posts panel.
2. Structured the page using CSS Grid for the sidebar / feed / right-column
   layout.
3. Combined the Home and About sections into one `index.html` file, with a
   `showPage()` JavaScript function that toggles which section is visible
   when a sidebar link is clicked.
4. Added the real Quibbles logo image into an `images/` folder and linked
   it into the top bar.
5. Renamed the working file to `index.html` so it can later be served
   automatically by GitHub Pages.

## 🚀 How the Code Was Pushed to GitHub
```bash
git init
git add .
git commit -m "Initial commit: Quibbles homepage and about page"
git remote add origin https://github.com/Ab2fresh/Quibbles-Web-Home-About.git
git branch -M main
git push -u origin main
```

## 📌 Status
- [x] Homepage and About page built
- [x] Logo  and avatar image added
* [x] Code pushed to GitHub
* [ ] Deployed live 
* [ ] CI/CD with GitHub Actions  
- [x] Code pushed to GitHub
- [ ] Deployed live (in progress)
- [ ] CI/CD with GitHub Actions (in progress)
