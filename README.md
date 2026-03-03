# QUBIT Waitlist

**Deployment:** Cloudflare Pages
**Repo:** https://github.com/ashleysbrain/qubit-waitlist
**Live URL:** TBD (after Cloudflare Pages setup)

## Setup

1. In Cloudflare dashboard, go to **Workers & Pages**
2. Click **Create application** → **Pages** → **Connect to Git**
3. Select this repo: `ashleysbrain/qubit-waitlist`
4. Configure:
   - Project name: `qubit-waitlist`
   - Production branch: `main`
   - Build settings: None (static HTML)
5. Deploy

## Structure

- `index.html` — Waitlist landing page
- Uses Formspree for email collection (no backend needed)

---

**Part of:** Divinity Science / Qubit Health
**Separate from:** Goddess Divinity (completely separate infrastructure)
