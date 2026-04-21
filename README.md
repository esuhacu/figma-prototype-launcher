# PWA Launcher (iOS-style + Android install)

This folder is a small installable launcher page that opens your Figma prototype.

## Prototype URL
https://www.figma.com/proto/3aONvjRxAcJCrYXPq56lBJ/Migration-Onboarding-Journey?node-id=481-20761&p=f&viewport=-1681%2C-4197%2C0.1&t=eaUgXONch721VECk-1&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=481%3A20761&page-id=1%3A5&show-proto-sidebar=0&hide-ui=1

## Deploy on GitHub Pages
1. Copy all files in this folder to the **root** of your GitHub repo.
2. Repo Settings → Pages → Source: `main` + `/root`
3. Wait ~1 minute.

## iOS install ("PWA-style")
- Open the launcher in **Safari**
- Share → **Add to Home Screen**
- Launch from the Home Screen icon for fullscreen mode.

## Android
- Open the launcher in Chrome
- Use the in-page **Install** button (or Chrome menu → Install app)

### Note about Android + Figma
Android standalone mode applies only within this site's scope. Because the prototype is on `figma.com`, Chrome may show URL bars after navigation.
For true fullscreen on Android, use the native WebView wrapper included in this bundle.
