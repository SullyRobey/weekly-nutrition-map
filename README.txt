Weekly Nutrition Map - phone app package

Files: index.html (the app), manifest.webmanifest, sw.js, icon-192.png, icon-512.png, apple-touch-icon.png.
Keep them together in one folder.

Option 1 - Host it free, then install on your phone (works offline after the first visit)
  1. Upload the whole folder to any free static host, for example Netlify Drop, Cloudflare Pages or GitHub Pages.
  2. Open the https address it gives you on your phone.
  3. iPhone: Safari > Share > Add to Home Screen.
     Android: Chrome menu > Install app (or Add to Home screen).

Option 2 - Run it from your own computer on home wifi
  1. Unzip, open a terminal in the folder and run: python3 -m http.server 8000
  2. Find your computer's local IP address (for example 192.168.1.20).
  3. On your phone, on the same wifi, open http://192.168.1.20:8000
  4. Add to Home Screen as above. This gives you the icon and full-screen look, but it only works while your computer is serving it,
     because phones only allow offline mode on https addresses.

Option 3 - Just open the file
  Opening index.html directly works in a computer browser. Phones often block or preview local files badly, so use Option 1 or 2 there.
