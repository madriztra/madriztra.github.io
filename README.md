# Insta Agent — iOS PWA starter

Mobile-first PWA inspired by the workflows in `Jakeschincariol/instagram-agent-skill`.

## What works in this starter
- 13 workflow screens that create structured prompts for an AI assistant.
- Local brand voice and draft storage (browser localStorage).
- Copy-ready outputs; no Instagram password or scraping.
- Offline shell after first successful load.
- iPhone safe-area layout and Add to Home Screen support.

## Important limitations
This is an iOS-ready PWA MVP, not a full port of the original Python tools or Claude skills. The generators create prompts locally; to get AI-written results, copy the prompt into ChatGPT or connect a secure server-side AI API. Do not put an API key in `app.js` or any browser code. Drafts are stored on this device/browser only and are not synced. Viral research is a manual research worksheet, not an Instagram scraper. It does not auto-publish, comment, follow, or send DMs.

## Deploy (GitHub Pages)
1. Create a new public GitHub repository.
2. Upload all files in this folder to the repository root.
3. In repository Settings → Pages, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
4. Wait for GitHub Pages to provide the site URL.
5. Open that URL in Safari on iPhone → Share → Add to Home Screen.

HTTPS hosting is required for service workers/PWA installation. GitHub Pages provides HTTPS.
