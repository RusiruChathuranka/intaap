# Lumi — AI Companion MVP Demo

A responsive, interactive static demo for the AI companion platform MVP.

## Live demo

Once GitHub Pages is enabled, the site will be available at:

https://rusiruchathuranka.github.io/intaap/

## Included demo flows

- Responsive dark, premium interface with dashboard and companion portrait cards
- Companion creation wizard and one-active-companion rule
- Simulated chat with sample responses
- Bonding score and 50%, 70%, 80%, and 100% milestone progression
- Memories view and local demo memory management
- Media gallery and a simulated first-free-image flow
- Subscription preview and simulated Plus activation
- Settings, end-relationship flow, and reset-demo action
- Browser local storage for sample progress

## Important limitations

This is a **static frontend demo**, not a production AI service. Google sign-in, live AI chat, image/audio/video generation, real billing, and server-side entitlement checks are not connected. Demo data is stored in the browser and is not secure or synchronized across devices. No payment is collected.

Before production, connect a backend (for example, Supabase Auth and PostgreSQL), enforce entitlements server-side, and select AI/media/payment providers that explicitly permit the intended business model. Add suitable adult-eligibility verification, privacy controls, moderation, and data deletion.

## GitHub Pages setup

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **GitHub Actions** as the source.
3. The workflow in `.github/workflows/pages.yml` deploys the static site after a push to `main`.
4. Check **Actions** for the deployment status. The first deployment may take a few minutes.

## Local preview

Open `index.html` in a browser, or serve the folder with any static HTTP server.
