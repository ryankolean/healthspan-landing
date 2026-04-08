# Healthspan Landing Page

Marketing and community landing page for the [Healthspan](https://github.com/ryankolean/healthspan-app) open-source health intelligence platform.

**Live:** [https://ryankolean.github.io/healthspan-landing/](https://ryankolean.github.io/healthspan-landing/)

## What This Is

Single-page static landing site covering:
- Product overview and value proposition
- Feature highlights and dashboard preview
- Development roadmap
- Open source contributor CTA
- Email waitlist capture

## Deploy

Static `index.html` — no build step. Deployed via GitHub Pages from main branch using GitHub Actions.

## Waitlist Integration

The email form logs to console. To connect a real backend, replace the submit handler in the `<script>` block with a POST to your provider (ConvertKit, Buttondown, Supabase Edge Function, etc.).

## Tech

- Vanilla HTML/CSS/JS — zero dependencies
- Google Fonts: Instrument Serif + Satoshi
- Responsive down to 320px
- Scroll-triggered animations via IntersectionObserver
- Custom SVG icons (no emoji)
- CSS noise grain texture

---

Summit Software Solutions LLC
