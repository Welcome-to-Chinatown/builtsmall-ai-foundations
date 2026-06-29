# BuiltSmall AI Foundations

The post-webinar landing page and slide deck for BuiltSmall's free monthly AI Foundations webinar, hosted by Welcome to Chinatown.

**Live URLs (GitHub Pages):**
- Landing page: `welcome-to-chinatown.github.io/builtsmall-ai-foundations/`
- Deck: `welcome-to-chinatown.github.io/builtsmall-ai-foundations/deck.html`

## Files

- `index.html` — mobile-friendly recap landing page (shareable post-webinar)
- `deck.html` — the 25-slide self-contained presentation deck
- `lockup_lite.png`, `wtc_lite.png` — BuiltSmall and Welcome to Chinatown brand marks
- `jason.jpg`, `henry.jpg` — case study portraits (used with permission)
- `jason_modifiers.png`, `jason_flavors.png`, `jason_heatmap.png` — Soft Swerve dashboard views
- `henry_project.jpg`, `henry_invoicing.jpg`, `henry_status.jpg` — Ideas of Order tool views (client PII redacted)
- `qr_office_hours.png`, `qr_newsletter.png`, `qr_survey.png` — brand-colored QR codes used live

## Editing the landing page

The recap page has two TODO placeholders that need real URLs after each webinar:
- **Zoom recording link** — search `data-recording` in `index.html`
- **Handout link** — search `data-handout` in `index.html`

Both buttons currently show a "Link coming" tag and a disabled CTA. Once you have the URLs, replace `href="#"` with the real URL and remove the `class="cta disabled"` (drop `disabled`) plus the `<span class="placeholder-tag">Link coming</span>` line.

## Webinar details

- Cadence: last Wednesday of each month, 12 to 1pm ET
- Format: one hour, three live demos, no building
- Audience: small business owners across New York
- Powered by Welcome to Chinatown, New York State's AI Specialist Entrepreneur Assistance Center
