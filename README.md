# Op-Sym PWA Wrapper

This package is a free static Progressive Web App wrapper for the existing Op-Sym Apps Script web app.

Apps Script production URL:
https://script.google.com/macros/s/AKfycbygTbX2omi_63Ricm2bDmbBzcwNuBXtKxJI2NpHIqvLCf051BiU06BTPkM-ufdbyQAXbA/exec

Files:
- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png
- apple-touch-icon.png
- favicon-96.png
- .nojekyll

Purpose:
- Provide the Op-Sym name and Orbit + Check icon automatically to supported phones.
- Make Android/Chromium browsers offer a real install prompt when eligible.
- Make iPhone/iPad Safari use the Op-Sym name/icon when the user chooses Add to Home Screen.
- Keep the actual Op-Sym system on Apps Script.

Important:
Mobile operating systems do not allow websites to silently install themselves. The user must confirm installation/add-to-home-screen once.

GitHub Pages works over HTTPS, which is required for PWA service workers.
