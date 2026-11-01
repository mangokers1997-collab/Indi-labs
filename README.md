# Indi Labs — Frontend Starter

A mobile-first, bilingual (Indonesian default / English toggle) frontend prototype for an AI-powered faceless content studio.

## Run locally
Open `index.html` in a browser. No build step is required.

## Publish with GitHub Pages (Android-friendly)
1. Create a public GitHub repository.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for the Pages URL shown in Settings → Pages.

## Included demo areas
- Dashboard and daily 5-video quota guard
- Multi-channel hub (demo rows; add channel interaction)
- Niche and keyword research sample (illustrative, not live market data)
- Script and storyboard outline template
- Browser speech preview (uses device/browser voices if available)
- Six-stage production pipeline (simulated)
- Multi-platform publish queue (simulated; no actual uploads)

## Important limitations
This is a frontend prototype only. It does **not** connect to GPT, managed video generation, managed TTS APIs, YouTube, Instagram, Facebook, or TikTok. RPM values and research output are illustrative, not real-time research or revenue guarantees. The 5-video limit is a client-side demo guard and must be enforced again on a secure backend before production use.

## Next engineering steps
1. Add a backend and database for users, channels, jobs, quota enforcement, and schedules.
2. Store API keys only on the backend (never in browser JavaScript).
3. Integrate the selected LLM, video generation, and TTS providers.
4. Add OAuth account connections and platform-specific publishing APIs.
5. Add moderation, rights checks, provenance, and human review before publishing.
