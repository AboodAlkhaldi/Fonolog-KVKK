# Fonolog Legal Site

Static HTML site for Google Play compliance.

## Pages
- `/` — Landing page (index.html)
- `/privacy` — Gizlilik Politikası & KVKK
- `/terms` — Kullanım Koşulları
- `/data-safety` — Veri Güvenliği & Hesap Silme
- `/account-deletion` — Hesap Silme Talep Formu

## Deploy to Vercel (5 minutes)

### Option A — Vercel CLI
```bash
npm i -g vercel
cd fonolog-site
vercel --prod
```
Choose your preferred project name (e.g. `fonolog`) → site goes live at `fonolog.vercel.app`

### Option B — Vercel Dashboard (no CLI)
1. Go to https://vercel.com/new
2. Click "Import Git Repository" or drag & drop this folder
3. No build settings needed — it's pure static HTML
4. Deploy → copy the URL

## URLs to paste into Google Play Console
- Privacy Policy URL:  https://fonolog.vercel.app/privacy
- Data Safety URL:     https://fonolog.vercel.app/data-safety
- Terms of Service:    https://fonolog.vercel.app/terms

## Files
```
fonolog-site/
├── index.html             ← landing page
├── privacy.html           ← privacy policy + KVKK
├── terms.html             ← terms of service
├── data-safety.html       ← data safety + account deletion
├── account-deletion.html  ← account deletion request form
├── shared.css             ← shared styles
├── vercel.json            ← Vercel config (clean URLs)
└── README.md
```
