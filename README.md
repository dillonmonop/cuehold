# Cuehold Website

Static GitHub Pages site for Cuehold, the public-facing iPhone app name.

## Current status

- Public name: Cuehold
- Hosting: GitHub Pages
- Stage: v0.4 internal TestFlight active; external beta access coming soon
- TestFlight/App Store Connect state is not inferred from this repo
- Public App Store launch: not live
- Paid/subscription launch: not in scope
- App platform: iPhone
- Website scope: landing page, beta access, privacy, support

## Site structure

```text
/
├── index.html
├── beta.html
├── privacy.html
├── support.html
├── assets/
│   ├── favicon.svg
│   ├── social-preview.svg
│   └── screenshots/
└── styles.css
```

## Pages

- `/` — landing page
- `/beta.html` — beta status and access request
- `/privacy.html` — privacy notes
- `/support.html` — support and beta feedback

## Product positioning

Cuehold helps users capture messy thoughts, screenshots, voice notes, pasted text, and shared content, then triage them into clearer next actions.

It does not replace Apple Reminders or Apple Calendar.

Cuehold helps users decide what matters. Apple Reminders reminds. Apple Calendar maps time.

## Non-negotiables

- Do not imply Apple affiliation.
- Do not call the app a Siri replacement.
- Do not describe it as medical ADHD treatment.
- Do not claim full automation.
- Do not promise silent scheduling.
- Do not expose internal codename language on public pages.
- Do not add paid/subscription messaging yet.
- Keep the website focused on Capture → Triage → What Next.

## Development notes

This is a static website. No build system, framework, tracking, payment, or signup backend is required.

## Screenshots

Committed screenshot assets:

- `assets/screenshots/today-signal-build12.png`
- `assets/screenshots/library-build12.png`
- `assets/screenshots/build-plan-build12.png`
- `assets/screenshots/capture-flow.png`
- `assets/screenshots/today-signal-strip.png`
- `assets/screenshots/triage-saved-item.png`
- `assets/screenshots/today-signal.jpeg`

Do not publish personal data, real reminders, real calendar events, account details, private captures, emails, phone numbers, addresses, or internal TestFlight details.

Preview locally:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

GitHub Pages URL:

```text
https://dillonmonop.github.io/cuehold/
```

## Current priority

Keep the public site accurate, simple, mobile-friendly, and ready for external beta preparation without implying public availability.
