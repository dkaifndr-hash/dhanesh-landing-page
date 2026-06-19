# Landing Page — Dhanesh Kumar

Conversion-focused landing page for AI consulting, cohort program, and done-for-you agents.

## Local Preview

```bash
cd /home/dkaifndr/workspace/landing-page
python3 -m http.server 8000
# Open http://localhost:8000
```

## Deployment

### GitHub
```bash
git init
git add .
git commit -m "Add landing page"
git branch -M main
git remote add origin https://github.com/dkaifndr-hash/your-repo-name.git
git push -u origin main
```

### Vercel
1. Go to https://vercel.com/new
2. Import the GitHub repo
3. Framework: "Other" (static)
4. Deploy

## CTA Placeholder

The final CTA button contains `[ CTA_LINK: Replace with your Calendly / meeting scheduler URL ]`. Replace this with your actual booking link before deploying.

## Missing Assets to Add

- [ ] Calendly / meeting scheduler URL for CTA
- [ ] Client testimonials (add as you complete engagements)
- [ ] Case studies with real numbers
- [ ] Your headshot (optional, for "About" section)
- [ ] LinkedIn profile link in nav/footer

## QA Checklist

- [x] Hero clarity — specific headline, not vague
- [x] CTA clarity — one primary action (book a call)
- [x] CTA placeholder — marked clearly for replacement
- [x] Mobile responsive — tested at 480px, 768px
- [x] Brand-specific copy — no generic SaaS language
- [x] No fake proof — honest placeholder note
- [x] Visual hierarchy — clear section flow
- [x] No broken anchors — all links valid
- [x] SEO meta tags — title, description, OG tags
- [x] Vercel ready — static HTML/CSS, no build step needed

## Version 2 Improvements

1. Add a "Results" section with specific case studies as you complete client work
2. Add an email capture lead magnet (e.g., "Free AI Readiness Scorecard")
3. Add a short video intro above the fold for higher conversion
4. Add social proof logos as you get permission from clients
5. Add a sticky CTA bar that appears on scroll for mobile visitors
