# Rishitha C — Into My Universe

A 3D academic portfolio with an animated guide, black-hole portal, guided chapters, keyboard/touch walking controls, and optional browser speech narration.

## GitHub Pages
1. Create or open `Rishithachappidi.github.io` on GitHub.
2. Upload all extracted files to the repository root, including the `vendor` folder. Do not upload only the ZIP.
3. Settings → Pages → Deploy from a branch → main → /(root) → Save.
4. Your published address will be https://Rishithachappidi.github.io after GitHub finishes deploying.

## Local preview
Run `python -m http.server 8000` in this directory and open http://localhost:8000. ES modules require a local server; double-clicking index.html will not load the 3D scene.

## Tour order
1. Resume — education, experience, certifications, and the original resume PDF.
2. Skills — all skill categories together.
3. Projects — all selected projects in one scrollable panel.
4. Connect — LinkedIn and GitHub.

## Controls
- Click Walk into my world for an automatic tour.
- Click Continue journey at each chapter.
- Use W / Up and S / Down to walk; A / D to move sideways. On touch screens, hold Walk.
- Use numbered chapter buttons to jump directly to a chapter.
- Enable narration if you want spoken descriptions. Voice availability depends on your browser.
- All details opens a readable text version.

## Edit content
Update `content.js`. Academic content reflects information previously supplied by Rishitha; GitHub details were not independently verified during this build. No grades or awards are asserted. The SupplyGrid_ link preserves the trailing underscore.

## Requirements and attribution
Requires a browser supporting WebGL and JavaScript modules. Three.js is bundled locally; its MIT license is in vendor/THREE-LICENSE.txt. The scene, guide and portal are procedural. No API keys, accounts, paid services, or external image assets are required to run this site.
