PROJECT OCEANUS — Android PWA demo

FILES: index.html, manifest.webmanifest, sw.js, icon.svg, icon-192.png, icon-512.png

ANDROID PHONE ONLY SETUP:
1. Download the ZIP and extract it in Files on your Android phone.
2. To preview only, open index.html in Chrome (some phones require a file-manager HTML viewer). Local file previews are NOT installable PWAs.
3. To INSTALL as an app, publish all six files together on an HTTPS static host (e.g. GitHub Pages or Netlify Drop) using your phone's browser. Do not upload the ZIP as a single website file unless the host supports extracting it.
4. Open the published HTTPS link in Chrome on Android.
5. Chrome menu (three dots) > Install app or Add to Home screen. Chrome may show a shortcut rather than Install if hosting/configuration is incomplete.
6. Launch OCEANUS from your home screen. After loading once online, cached app assets can work offline.

GITHUB PAGES PHONE OPTION:
- Sign in at github.com in Chrome, create a PUBLIC repository named oceanus-app.
- Use Add file > Upload files to upload the six extracted files into repository root and commit.
- Open repository Settings > Pages > Deploy from a branch > main > /(root) > Save.
- Wait for deployment; open https://YOUR_USERNAME.github.io/oceanus-app/ in Chrome.
- Chrome menu > Install app (or Add to Home screen).

NOTE: The demo does not control real pumps, ESP32, or solar hardware. Sample readings are static. Real mains-powered pump integration requires properly rated contactor, overload protection, safe manual override, and a qualified electrician.
