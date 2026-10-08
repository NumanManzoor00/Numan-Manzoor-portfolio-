# Noman Manzoor Portfolio

This is the latest portfolio source, including the left / center / right navbar update.
Built with plain HTML, CSS, and JavaScript. No npm install or build is required.

## Run on Windows
1. Extract the ZIP.
2. Open the Noman-Portfolio-Source folder in VS Code.
3. Use the Live Server extension and choose Open with Live Server on index.html.
   Alternatively, from this folder run: python -m http.server 5500
   Then open http://localhost:5500 in your browser.

## What to edit
- index.html: page structure, logo, section layout, page title and metadata.
- style.css: colors, spacing, button shapes, navbar, responsive layouts and animations.
- app.js: text in English (en), Chinese (zh), Arabic (ar), skills, experience, projects and platform/contact links.
- assets/portrait.webp: homepage photo.
- assets/favicon.png: browser tab image.

Important: app.js replaces translated page text when the page loads.
For a permanent text change, update the en / zh / ar objects in app.js,
not only the text in index.html.
Project titles, descriptions, skills and jobs are in the content object.
Project technology labels and links are in projectData and platforms.
Contact URLs are in links. The WhatsApp hero/footer links are also in index.html.

## Styling
style.css contains named comment sections from the design updates.
The rules near the bottom override earlier rules. For small custom changes,
add your CSS at the end of style.css, or edit the latest relevant section.
The last section controls navbar left / center / right alignment.

## Languages and theme
The site remembers language and theme using browser localStorage.
Select English when reviewing English text updates.
Arabic uses right-to-left page text with left / center / right navbar placement.

## Publishing
Upload index.html, style.css, app.js and assets together to a static website host.
Keep index.html at the hosting root. This download does not automatically update
or publish your existing Sites website. You can return the edited files here
and ask to apply them to that site.

Google Fonts are loaded online; local fallback fonts work when offline.
Project images are illustrative HTML/CSS previews, not project screenshots.

## Background video
assets/background.mp4 is your optimized, silent background video.
assets/background-poster.webp is the fallback image.
The background plays on a loop, has a pause button, and respects reduced-motion preferences.
Video styling is at the bottom of style.css; playback logic is at the bottom of app.js.
