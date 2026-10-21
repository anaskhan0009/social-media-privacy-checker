# Social Media Privacy Checker — Per-Platform Settings Audits for Facebook, Instagram, TikTok, WhatsApp & X

The privacy settings exist on every platform — they're just buried under five different menu systems, written to be skipped. This free checker walks you through the settings that matter on **Facebook, Instagram, TikTok, WhatsApp and X (Twitter)**, platform by platform, with the exact path to each switch and an honest explanation of what it stops. Every platform gets its own **privacy score (0–100)**, ticks save automatically, and a **free local account** lets you save dated audits to prove your posture is improving instead of quietly decaying.

**Live Demo:** https://anaskhan0009.github.io/social-media-privacy-checker/

## Features

- **5 platform walkthroughs, 6 high-impact settings each** — post audience, friends-list visibility, tag review, discoverability by phone/email, DM restrictions, disappearing messages, app locks, location in posts
- **Critical (★) items flagged** — the settings whose absence causes real-world damage: 2FA everywhere, WhatsApp's two-step PIN (anti SIM-swap), private accounts for minors
- **Per-platform + combined scores** — a live dashboard of your whole social footprint, not five disconnected checklists
- **Saved audits with full CRUD** — snapshot any platform's settings + score + your note; load an audit back to review or update it; delete anytime
- **Free local account system** — sign up / log in (passwords stored only as salted SHA-256 hashes in your browser), guest mode with auto-saved ticks, JSON export/import

## How to Use

1. Open the [live demo](https://anaskhan0009.github.io/social-media-privacy-checker/) (or `index.html` locally) next to the app you're auditing.
2. Work one platform at a time: follow each step in the app, set the switch, tick it here.
3. Log in and save an audit per platform.
4. Re-run quarterly — platforms move menus and add new data-hungry features constantly; your saved audits make regressions visible.

## Why Bother? Defaults Are a Business Model

Platforms earn from engagement and data, so defaults are tuned for sharing: public posts, findable-by-phone accounts, open DMs. Those defaults hand scammers your family graph, your daily patterns and a stage to impersonate you from. Thirty deliberate minutes per platform is one of the highest-value security chores there is — this checker turns it into a scored, trackable habit.

## Ethical Use

This is a **defensive self-help tool** for your own accounts. It reads nothing from your accounts and connects to nothing — you report your own settings.

## Tech

Single self-contained `index.html` — HTML, CSS, vanilla JavaScript, WebCrypto (SHA-256 password hashing), localStorage persistence.

---

Built by **Dinal Studios** — free cyber security tools and web apps.
GitHub: https://github.com/anaskhan0009

*Keywords: social media privacy settings, facebook privacy check, instagram private account, tiktok privacy settings, whatsapp two step verification, twitter privacy, online privacy audit*
