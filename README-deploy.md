# Starling Website — Deploy Handoff

## Project Path
`/Users/hitler/Downloads/star`

## What’s Included
- `index.html`
- `about.html`
- `services.html`
- `portfolio.html`
- `contact.html`
- `privacy.html`
- `terms.html`
- `styles.css`
- `script.js`
- `assets/logo/favicon.png`

## Quick Local Preview
```bash
cd /Users/hitler/Downloads/star
python3 -m http.server 8765
# open http://127.0.0.1:8765
```

---

## Option A: Netlify (Fastest)
1. Zip the folder (or drag folder directly to Netlify Drop).
2. Go to https://app.netlify.com/drop
3. Drag `star-delivery.zip` (or `star/` folder) into the drop zone.
4. Netlify gives a live URL instantly.
5. Add custom domain in **Site settings → Domain management**.

## Option B: Vercel
1. Create a new project in Vercel.
2. Import/upload this folder.
3. Framework preset: **Other** (static site).
4. Deploy.
5. Add custom domain in project settings.

## Option C: cPanel / Shared Hosting
1. Upload all files in `star/` to `public_html/`.
2. Ensure `index.html` is at root.
3. Confirm `assets/logo/favicon.png` path remains intact.
4. Enable HTTPS in hosting panel.

---

## Pre-Launch Checklist
- [ ] Replace placeholder social links with real links
- [ ] Replace placeholder phone/email if needed
- [ ] Replace stock images with licensed client images
- [ ] Connect contact form to backend (Formspree/Webhook/CRM)
- [ ] Verify mobile spacing on real devices
- [ ] Add analytics (GA4 / Meta Pixel if required)

---

## SEO Notes (Already Included + Suggested)
Current pages include titles and basic structure. For stronger SEO, add:
- unique meta descriptions per page
- Open Graph tags (`og:title`, `og:description`, `og:image`)
- Twitter card tags
- sitemap.xml + robots.txt

---

## Form Integration Suggestion
Current contact form is front-end only. Quick integration options:
- Formspree
- Netlify Forms
- Custom webhook (Zapier/Make/n8n)

---

## Delivery Archive
Archive file:
`/Users/hitler/Downloads/star-delivery.zip`
