# ETHAN BATTLE ARENA

Complete static 3D browser game: eight city worlds, eight missions, four weapons, grenades, crouching, training, XP, upgrades, mobile controls and an offline PWA.

## Upload to GitHub
1. Extract this ZIP.
2. Create a GitHub repository and choose Add file > Upload files.
3. Upload the extracted contents. index.html and vercel.json must be at the repository root.
4. Commit the files.

## Deploy on Vercel
Import your GitHub repository. Framework preset: Other. Root directory: repository root. No build command is needed. Output directory: . (current directory). The included vercel.json configures static deployment.

Use HTTPS for installation, offline support and gyro permissions. Open the website normally; opening index.html directly from your computer does not support the modules/PWA reliably.

## Local preview
Run python -m http.server 8000 in the extracted folder, then open http://localhost:8000.

## Controls
WASD: move; mouse: aim; click or G/F/H/J: shoot; right mouse: aim zoom; Shift: sprint; Space: jump; R: reload; E: heal; C: crouch; Z: grenade; 1-4: weapons; V: camera; Escape: pause. Mobile uses the joystick, swipe aiming and action buttons.

## Installation and updates
Use Install Game or your browser's install menu. On iPhone/iPad use Safari > Share > Add to Home Screen. Wait for Offline ready before disconnecting. After edits, change the CACHE name in sw.js, commit and deploy; installed users can select Update Ready in the lobby.

## Your domain and SEO
Update the canonical URL, Open Graph URL and VideoGame URL in index.html, plus sitemap.xml and robots.txt, to your production domain. The supplied URLs point to the current preview publication. Public hosting is required for search-engine indexing. The ZIP has no account restriction of its own.

## Saves
Coins, XP, upgrades and settings are stored on the current browser/device. Progress does not sync between devices or domains. Training awards no coins or XP. This is single-player against bots; online multiplayer is not included.

## Credits and validation
Retain CREDITS.txt and THREE-LICENSE.txt. Gameplay simulation, collisions, rewards, upgrade purchases, training and offline-cache logic were checked. Real-device visual quality, frame rate and sensor testing remain pending.


## Latest repair: city lobby and offline download

Added forward-facing scout artwork beside the lobby setup. Fixed input reset after pausing, mobile aim toggles, paused simulation, outfit preview, training setup labels, and audio-unavailable startup. Offline files now retry interrupted downloads, show download progress, verify readiness, and offer a retry button. Relative manifest and worker paths also support repository subpaths. All eight cities and three difficulties, mission choices, combat, shop, reward guards and offline-cache behavior were checked in automated simulations. Physical phone installation, browser WebGL rendering/FPS, and device gyro remain real-device validation steps.

Replace all repository files with this release. If an existing installed app shows UPDATE READY, pause or finish your match and tap UPDATE READY. Keep your browser storage to retain earned coins. For public search indexing, use your public Vercel/GitHub Pages URL and update canonical, sitemap and Open Graph URLs.
