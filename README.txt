Quick Sets - installable offline workout web app

Files: index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, apple-touch-icon.png
Everything is static and has no dependencies.

Host: upload all files together to any static host (Netlify, Vercel, Cloudflare Pages,
GitHub Pages, your own server). It must be served over HTTPS for install and offline mode.
Test locally: run `python3 -m http.server` in this folder and open http://localhost:8000

Install: iPhone Safari > Share > Add to Home Screen. Android Chrome > menu > Install app.

Updating: after editing any file, change the version in sw.js (const V = 'quick-sets-v4').
