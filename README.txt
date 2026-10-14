EBOLT STATIC SITE

Files: index.html, about.html, main.js, styles.css, assets/live-circle.mp4

Run locally: open index.html in your browser. No build step is required.

GitHub push (run these commands in the VS Code terminal from this folder):
  git init
  git add .
  git commit -m "Add Ebolt static website"
  git branch -M main
  git remote add origin https://github.com/241fa18462-Tarun/Ebolt-website.git
  git push -u origin main

If origin already exists, use: git remote set-url origin https://github.com/241fa18462-Tarun/Ebolt-website.git


The live-circle video is stored in assets/live-circle.mp4 and loops while the page is open.
Keep the assets folder alongside index.html. Open index.html in your browser.

Update notes: Saved Note now includes a permanent + New note tile that opens a blank editor. The AI Chat Bot sidebar icon uses the supplied robot image URL. Save as new creates a separate saved note.

Profile and background update:
- Use the new User Info item in the left navigation to view/edit date of birth, calculated age, gender, country calling code, country, and state/province.
- Name and email are filled from the currently signed-in account and are read-only.
- Profile fields are saved in this browser's localStorage, separately for each signed-in email. Clearing browser storage removes local profile data.
- The supplied assets/live-circle.mp4 is used as a subtle full-screen animated background with pointer/touch/device-orientation parallax. Video playback depends on browser autoplay settings; it is muted and loops.
