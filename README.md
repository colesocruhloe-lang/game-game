# Pulse Drop
A ready-to-wrap mobile arcade game built with Vite + Capacitor.

## Build
1. Install Node.js 20+.
2. Run `npm install`.
3. Run `npm run build` for the web build.
4. Run `npx cap add android` and/or `npx cap add ios` once, then `npm run cap:sync`.
5. Open Android Studio / Xcode, set your signing account, app icons and store metadata, then archive/upload.

Package ID: `com.pulsedrop.game`

The game is intentionally asset-light: the visuals are rendered in code, so there are no external image assets to break or license.
