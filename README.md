# ANIMORA AI — Android starter app

A responsive HTML/CSS/JavaScript frontend starter for an all-in-one AI creative studio.

## Included and working
- Responsive dark dashboard and navigation
- AI Chat interface demo (clearly marked; not connected to a model)
- Image/video prompt preparation and local project list
- Local image upload preview for Image-to-Video
- Local video import and browser playback controls
- Device/browser text-to-speech for voiceover preview

## Not connected yet
Real AI chat, image generation, text-to-video, image-to-video, voice generation, advanced editing, effects, transitions, and exporting require suitable services and a secure backend. The frontend intentionally does not pretend these requests have been generated.

## Test on Android
1. Extract `ANIMORA-AI.zip`.
2. Open `index.html` in a mobile browser if your file manager offers that option, or publish the three files with GitHub Pages.
3. For easiest online preview, create a GitHub repository, upload `index.html`, `style.css`, and `script.js` to the repository root, then enable GitHub Pages in Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
4. Open the Pages URL on your Android phone.

## Important security note
Never put private API keys in `script.js` or any browser-visible file. Add a backend (for example, a serverless function) that stores secrets securely, validates requests, and calls the AI provider. Then connect the frontend to your backend endpoint.

## Android APK
This project is currently a mobile-friendly website, not an APK. After testing, it can be packaged as an Android app using a trusted WebView/Capacitor workflow. APK signing and publishing are separate steps.
