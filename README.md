# Trading Fibb Website 🚀

A complete multi-page website for **Trading Fibb** — Smart Money Concept Trader.

## Pages
- **Home** — Hero, About, Features, Courses preview, Testimonials, YouTube section, Contact
- **Courses** — Full paid courses catalog with enroll modals
- **Free Resources** — Cheat sheets, templates, glossary, YouTube playlist

## Features
- ✅ Dark green trading theme matching your brand
- ✅ Animated ticker with Nifty/BankNifty prices
- ✅ Course enroll modals with lead capture form
- ✅ Custom cursor with glow effect
- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ WhatsApp floating button
- ✅ SMC glossary on Resources page
- ✅ Smooth page transitions & scroll animations
- ✅ Risk disclaimer (SEBI compliant)

## Files
```
trading-fibb/
├── index.html      ← Main website (all pages inside)
├── vercel.json     ← Vercel deployment config
├── logo.png        ← Your logo
├── Banner.png      ← YouTube banner
├── website_theme.png ← Hero background
└── README.md
```

## Deploy to Vercel via GitHub

### Step 1 — Create GitHub Repo
1. Go to https://github.com/new
2. Create a new repository (e.g. `trading-fibb-website`)
3. Upload all files from this folder to the repo

### Step 2 — Deploy on Vercel
1. Go to https://vercel.com and sign in with GitHub
2. Click **"Add New Project"**
3. Import your `trading-fibb-website` repo
4. Framework Preset: **Other** (static site)
5. Click **Deploy** → Done! ✅

### Step 3 — Custom Domain (Optional)
1. In Vercel project settings → Domains
2. Add your custom domain (e.g. `tradingfibb.com`)
3. Update DNS records as shown by Vercel

## Customization
- Replace `91XXXXXXXXXX` in WhatsApp links with your actual number
- Update subscriber/video counts as they grow
- Replace Telegram `#` links with your actual Telegram channel
- Update Twitter/Instagram links

## Contact Form (To make functional)
Currently shows an alert. To make it actually send emails:
- Use [Formspree](https://formspree.io) — replace the onclick with a form POST to your Formspree endpoint
- Or use [EmailJS](https://emailjs.com) for client-side email sending
