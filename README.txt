DHANAM - how to put it online (5 minutes)

FILES IN THIS FOLDER
  index.html      the app
  manifest.json   app name + icon (for Add to Home screen)
  sw.js           offline support
  icon-192.png    app icon
  icon-512.png    app icon (big)

STEP 1 - make a new GitHub repository
  github.com -> + (top right) -> New repository
  Repository name: DHANAM
  Public  ->  Create repository

STEP 2 - upload these 5 files
  In the new repo: Add file -> Upload files
  Drag ALL 5 files (index.html, manifest.json, sw.js, icon-192.png, icon-512.png)
  -> Commit changes

STEP 3 - turn on GitHub Pages
  Repo -> Settings -> Pages
  Source: Deploy from a branch
  Branch: main  /  (root)  ->  Save
  Wait ~1 minute.

STEP 4 - open it
  https://karattiparakkalshafeeq-ui.github.io/DHANAM/

STEP 5 - install on your phone (this makes it a real app)
  Open the link in Chrome -> menu (3 dots) -> "Add to Home screen" / "Install app"
  Now Dhanam has its own icon on your home screen, opens full screen,
  and works offline. Completely separate from VipaNanam.

NOTE: your data stays on the device (localStorage). Use
Settings -> Export backup now and then to keep a copy.
