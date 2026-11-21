# TremorCare AI — Personal PWA MVP

A mobile-first, bilingual (Egyptian Arabic / English) personal wellbeing and symptom-tracking web app.

## Included in this MVP
- Dark mode by default and light-mode toggle.
- Arabic / English language switch.
- Personal symptom tracking (0–10), side, activity context, notes and history.
- Mood/stress check-ins and a basic CBT reflection prompt.
- Medication notes (records only; no dosing recommendations).
- Links to PubMed, ClinicalTrials.gov and Europe PMC search.
- Export and delete local data.
- PWA manifest, icons and service worker for Add to Home Screen / offline shell.

## Run locally
Serve this folder from a local static HTTP server. Do not open `index.html` as a `file://` URL because service workers require HTTPS or localhost.

## Deploy as a free static site
Connect this folder/repository to a static hosting provider (for example Render Static Site):
- Build command: leave empty (or `echo static` if required)
- Publish directory: `.`

## Add to iPhone
1. Open the deployed HTTPS URL in Safari.
2. Tap Share.
3. Choose Add to Home Screen.

## Important limitations
This is a personal tracking and educational MVP, not a medical device, diagnosis, treatment recommendation, or substitute for a neurologist / movement-disorders specialist or mental-health professional. The assistant screen is currently a transparent placeholder with research-search shortcuts; it is not connected to a live AI model or a live evidence retrieval backend. Video-based tremor measurement is not implemented. Do not change medication based on this app.

Data is stored in browser localStorage on the current device. It is not encrypted medical storage and does not sync between devices. Avoid storing highly sensitive information on a shared device.
