Advanced Viewer

A single-file, no-dependency image viewer with smooth momentum panning, momentum zoom, and a lightweight touch-up tool all in one .html file you can open straight in a browser.

Features
Buttery pan & zoom — inertia-based movement and zoom, both fully tunable (smoothness + amount)
Brush & rectangle tools — paint over parts of the image in any color, with an eyedropper (native screen picker where supported, click-to-sample fallback elsewhere)
Undo — button or Ctrl/Cmd + Z
Replace image — swap in a new image without leaving the viewer
Remembers everything — your image (including edits) and all settings persist across reloads via IndexedDB
Light/dark aware — follows your system color scheme
Usage
Open viewer.html in a browser, or drop an image onto the page
Drag to move, scroll to zoom
Double-click to open settings (tools, brush color/size, zoom & movement tuning, replace image)
Right-click + drag to reposition while settings are open
F — fullscreen · 0 — fit to screen · L — load new image · Esc — close settings
Tech

Vanilla HTML/CSS/JS, <canvas> for image editing, IndexedDB for persistence. No build step, no dependencies.
