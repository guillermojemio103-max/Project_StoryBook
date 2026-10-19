K-DRAMA STORYBOOK LIBRARY — SEPARATE HTML PAGES

HOW TO OPEN
1. Extract this ZIP.
2. Open the kdrama_storybook folder in VS Code.
3. Run index.html with Live Server.
4. Click "Read story" on any card to open its full story page.

PUBLISH ON GITHUB PAGES
1. Upload the contents of this project, including index.html, script.js, style.css, and the images folder.
2. Keep filenames exactly as shown; GitHub Pages uses case-sensitive paths.
3. In the repository, open Settings > Pages and publish from the branch and folder containing index.html.
4. Open the Pages URL and click "Read story." Stories open from index.html, so the links do not depend on separate story HTML files being uploaded.

If GitHub's web uploader limits the number of files in one upload, upload the project in multiple batches without changing the folder structure. GitHub Desktop can also upload the whole project folder.

FOLDER STRUCTURE
- index.html: main story library
- stories/story-1.html through stories/story-30.html: standalone copies for local use
- style.css: shared design, responsive layout, and dark theme
- script.js: story library, search, genre filter, favorites
- images/covers/: 30 cover illustrations
- images/scenes/: 30 story scene illustrations

Cover photos k1.jpg through k21.jpg and k23.jpg through k30.jpg are matched to their story titles. The extra k22.jpg is a duplicate Signal poster and is intentionally not used. My Demon uses its matching SVG cover. Story scene illustrations use the numbered SVG files.

The library's story links open full story pages rendered by script.js. The images folder is needed for the matching story covers and scenes.
