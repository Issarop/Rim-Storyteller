RIM STORYTELLER PWA PACKAGE

FILES
- index.html: the app
- manifest.webmanifest: installation metadata
- sw.js: offline caching
- icon-192.png and icon-512.png: app icons

IMPORTANT
An installable PWA must be served from HTTPS (or localhost for testing). Opening index.html directly from Downloads will run the app, but service-worker installation and true app installation generally require hosting.

EASY HOSTING OPTIONS
1. GitHub Pages
   - Create a repository.
   - Upload all five files from this package to the repository root.
   - Enable Pages in repository Settings > Pages.
   - Open the resulting HTTPS address on the phone.

2. Netlify Drop or another static host
   - Upload the entire unzipped folder.
   - Open the resulting HTTPS address.

INSTALL AFTER HOSTING
Android Chrome:
- Open the hosted HTTPS address.
- Open the three-dot menu.
- Choose Install app or Add to Home screen.

Windows Edge:
- Open the hosted HTTPS address.
- Choose Settings and more > Apps > Install this site as an app.

OFFLINE USE
After the first successful hosted load and PWA installation, the app shell is cached for offline access. Colonist data and portraits remain stored locally in that browser/app profile. Export roster and event logs as backups.
