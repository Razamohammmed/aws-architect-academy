# AWS Architect Academy for iPhone

This is a small Progressive Web App (PWA) learning prototype with:
- 15 AWS learning tracks
- Topic checklists
- Multiple-choice knowledge checks
- Practical lab preparation checklists
- Architecture design prompts
- Local-device progress persistence in the browser
- A basic offline cache when hosted over HTTPS

## Important
This ZIP is a web app project, not an iOS `.ipa` installer. iPhones do not install arbitrary app ZIP files directly. To add it to the iPhone Home Screen, it must be hosted at an HTTPS address.

## Easiest setup
1. Extract this ZIP.
2. Upload the contents of this folder to a static HTTPS hosting provider you trust (for example, a GitHub Pages repository or another static web host).
3. Open the resulting HTTPS website in Safari on your iPhone.
4. Tap Share -> Add to Home Screen -> Add.
5. Open the new Home Screen icon.

Keep `index.html`, `manifest.json`, `service-worker.js`, and the `icons` folder together in the published directory.

## Local preview
Open `index.html` on a computer to preview the core learning UI. PWA installation and service-worker/offline support require an HTTPS host or localhost.

## Safety
The app does not connect to your AWS account and does not deploy resources. Follow AWS's current pricing, service availability, and security documentation before doing labs. Never put AWS access keys into this app.
