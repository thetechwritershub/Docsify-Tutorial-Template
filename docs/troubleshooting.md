# Troubleshooting Common Issues

## 1. Content Not Loading
   
Docsify only serves files from the `/docs` folder. Ensure all assets (images, CSS) and Markdown files are placed inside docs.

## 2. Sidebar/Navbar Not Displaying

Check that `_sidebar.md` or `_navbar.md` exists in the docs folder. Also, confirm that `loadSidebar: true `or `loadNavbar: true` is set in `index.html`.

## 3. Broken Links in Sidebar/Navbar

Make sure all `.md` files referenced in `_sidebar.md`or `_navbar.md` exist in the docs folder.

## 4. Cover Page Missing

Verify that `_coverpage.md` is in `/docs` and that `coverpage: true `is enabled in `index.html.`

## 5. Essential Files & GitHub Pages

- Essential files must start with an underscore (_sidebar.md, _navbar.md, _coverpage.md) and must be in `/docs`.
   
- Add a `.nojekyll` file to docs to prevent GitHub Pages from ignoring underscored files.