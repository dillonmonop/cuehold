# App Beta Site

Static beta landing page for the upcoming iPhone app currently using an internal codename.

This repo will host the public beta website, waitlist page, privacy page, and support page for External TestFlight preparation.

## Current status

- Public name: pending
- Domain: pending
- Hosting: GitHub Pages
- Stage: Internal TestFlight / External Beta preparation
- App platform: iPhone
- Website scope: landing page, beta waitlist, privacy, support

## Site structure

text / ├── index.html       # Landing page ├── beta.html        # Waitlist / beta interest page ├── privacy.html     # Privacy policy ├── support.html     # Support/contact page ├── styles.css       # Shared styling └── assets/          # Images, screenshots, icons 

## Pages needed

- / — landing page
- /beta — beta waitlist
- /privacy — privacy policy
- /support — support and contact

## Product positioning

This app helps users capture messy thoughts, screenshots, voice notes, pasted text, and shared content, then triage them into clearer next actions.

It does not replace Apple Reminders or Apple Calendar.

The app helps users decide what matters, then safely exports commitments into Apple native apps only when the user chooses.

## Non-negotiables

- Do not imply Apple affiliation.
- Do not call the app a Siri replacement.
- Do not describe it as a medical ADHD treatment.
- Do not claim full automation.
- Do not promise silent scheduling.
- Do not publish under the internal codename once external testing begins.
- Do not add paid/subscription messaging yet.
- Keep the website focused on Capture → Triage → What Next.

## External beta readiness checklist

text [ ] Public name selected [ ] Domain purchased [ ] GitHub Pages enabled [ ] Custom domain connected [ ] Landing page drafted [ ] Beta waitlist embedded [ ] Privacy page drafted [ ] Support page drafted [ ] Contact email created [ ] AI/privacy disclosure reviewed [ ] TestFlight beta copy drafted [ ] App Store Connect support URL ready [ ] App Store Connect privacy URL ready 

## Planned stack

text Hosting: GitHub Pages Domain: pending Waitlist form: Tally Email/waitlist updates: Loops or MailerLite Support email: pending 

## Development notes

This is a static website.

No build system is required unless deliberately added later.

Recommended first files:

text index.html beta.html privacy.html support.html styles.css 

## Local preview

Open index.html directly in a browser.

Optional local server:

bash python3 -m http.server 8000 

Then open:

text http://localhost:8000 

## GitHub Pages setup

1. Push this repo to GitHub.
2. Go to repo settings.
3. Open Pages.
4. Set source to the main branch.
5. Select root folder.
6. Save.
7. Add custom domain later after the public name is selected.

## Future custom domain target

text www.[name].app [name].app 

Recommended URLs:

text https://www.[name].app https://www.[name].app/beta https://www.[name].app/privacy https://www.[name].app/support 

## Current priority

Build the external-readiness shell without overbuilding.

Name first.  
Landing page second.  
Privacy/support third.  
External TestFlight only after safety pack is ready.
