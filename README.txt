Backlink Monitoring Tool — Welcome Pages
========================================

Files to publish together in the root of an external HTTPS website:

  index.html   : icon hidden behind the Chrome puzzle menu (two illustrations)
  toolbar.html : icon already visible in Chrome toolbar (one illustration)
  style.css    : common responsive CSS
  icon.png     : extension icon
  step-pin.png : outlined puzzle (1), pin (2)
  step-open-3.png : open extension after pinning (3)
  step-open-1.png : open extension when already visible (red arrow, no number)

The page header contains the icon and “Backlink Monitoring Tool Installed”
on one row where space allows. Instruction text aligns with the illustrations.
The first image on index.html is cropped below its instructions on desktop,
so part of the next illustration is visible on the first screen. The browser
page beneath the Chrome extension menu is intentionally not important.

Example addresses after publishing on GitHub Pages:
  https://EXAMPLE.github.io/                (hidden icon)
  https://EXAMPLE.github.io/toolbar.html     (visible icon)

Selection between the two URLs is up to the extension's installer logic.
These HTML pages do not inspect browser state or communicate with extension.
No analytics, JavaScript, remote fonts, or external resource dependencies.

Direct toolbar version: no numbered badge, only the red arrow pointing to the icon.
