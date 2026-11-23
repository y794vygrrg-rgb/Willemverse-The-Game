# Friends Quest

A five-level top-down browser adventure with six selectable placeholder characters. All characters are unlocked and differ only cosmetically.

## Play locally
Open `index.html` in a modern browser.

## Publish on GitHub Pages
1. Create a new public GitHub repository (for example `friends-quest`).
2. Upload `index.html` to the repository root and commit it.
3. Open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
4. Wait for GitHub Pages to provide your public game URL.

## Customize
Edit the `HEROES` array in `index.html` to change names, descriptions, and outfit colors. The `drawHero` function draws placeholder characters. Replace it later with custom character sprites. Edit `LEVELS` to change level names, palettes, obstacles, and relic counts.

## Controls
WASD, arrow keys, or touch direction buttons. Collect all relics, then walk to the golden exit. In the boss level, collect relics first, then move into the boss three times to break its seals before exiting.

No build step, server, or external dependencies required.
