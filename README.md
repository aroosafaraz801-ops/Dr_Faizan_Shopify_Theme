# Dr. Faizan Shabbir Rana — Clinical Urology & Kidney Care Shopify 2.0 Theme

A bespoke, production-grade **Shopify 2.0 Medical Theme** developed for **Dr. Faizan Shabbir Rana** (MBBS, MS Urology - King Edward Medical University, Head of Urology Department, DHQ Hospital Bhakkar).

---

## 🏥 Clinical Scope & Visual Aesthetic
- **Color Palette**: Deep Royal Medical Navy (`#050b18` / `#09132b`), Metallic Gold (`#d4af37`), Medical Cyan (`#06b6d4`), and Sehat Card Emerald (`#059669`).
- **Typography**: Dual-language typography pairing:
  - Latin Display & Body: `Space Grotesk` + `Plus Jakarta Sans`
  - Urdu Calligraphy: `Noto Nastaliq Urdu` (100% authentic rendering of Urdu medical terms)
- **10 Core Specialized Surgeries Included**:
  1. **PCNL**: گردہ کی پتھری کا بذریعہ کیمرہ آپریشن (Percutaneous Nephrolithotomy)
  2. **URS**: گردہ کی نالی کی پتھری کا آپریشن (Ureteroscopy)
  3. **Litholapaxy**: مثانہ کی پتھری کا آپریشن
  4. **TURP**: مثانہ کے غدود کا آپریشن (Transurethral Resection of Prostate)
  5. **TURBT**: مثانہ کی رسولی کا آپریشن (Transurethral Resection of Bladder Tumor)
  6. **DVIU**: پیشاب کی نالی سکڑنے کا آپریشن (Direct Vision Internal Urethrotomy)
  7. **Nephrectomy / Pyeloplasty**: ناکارہ گردے کا نکالنا، گردے کی پیدائشی رکاوٹ کا آپریشن
  8. **Lithotripsy**: بے ضرر شعاعوں سے پتھری کا علاج
  9. **Erectile Dysfunction**: مردانہ کمزوری اور امراض مخصوصہ کا علاج
  10. **Male Infertility**: مردانہ بانجھ پن اور ویریکوسیل کا علاج
- **Hospital Consultation Timings & Centers**:
  - **Layyah**: Qadir Ali Hospital, Katchery Road (Every Friday: 1:00 PM – 5:00 PM)
  - **Fateh Pur**: Aasia Iqbal Hospital, Multan Road (Every Friday: 10:00 AM – 1:00 PM)
  - **Bhakkar**: National Hospital & DHQ Hospital Bhakkar
- **Sehat Card Integration**: Prominent Pakistani National Sehat Sahulat Card panel indicators.
- **Direct WhatsApp Dispatch**: Instant pre-filled booking tickets to `0312-7064602`.

---

## 📁 Theme Directory Structure

```
shopify-theme-dr-faizan/
├── layout/
│   └── theme.liquid                  # Master HTML wrapper with meta tags & asset loaders
├── templates/
│   ├── index.json                    # Online Store 2.0 homepage section sequence
│   ├── page.liquid                   # Static page template
│   └── 404.liquid                    # Custom 404 error template
├── sections/
│   ├── header.liquid                 # Sticky navigation, emergency top bar, WhatsApp CTA
│   ├── hero-doctor.liquid            # Doctor credentials banner with gold badge & portrait card
│   ├── sehat-card-banner.liquid      # National Sehat Card announcement ribbon
│   ├── services-grid.liquid          # 10 clinical procedure cards with interactive booking triggers
│   ├── pcnl-specialty.liquid         # Kidney stone camera surgery deep-dive & graphic
│   ├── prostate-cancer-care.liquid   # Prostate awareness, PSA diagnostics & urgency banner
│   ├── clinic-locations.liquid       # Hospital schedule cards (Layyah, Fateh Pur, Bhakkar)
│   ├── appointment-booking.liquid    # Interactive scheduler with WhatsApp direct routing
│   └── footer.liquid                 # Doctor credentials, schedules & emergency helplines
├── snippets/
│   ├── icon-whatsapp.liquid          # SVG WhatsApp icon
│   ├── icon-phone.liquid             # SVG Phone icon
│   ├── icon-location.liquid          # SVG Location pin icon
│   ├── icon-clock.liquid             # SVG Clock icon
│   ├── icon-shield.liquid            # SVG Sehat card shield badge
│   ├── icon-kidney.liquid            # SVG Urology & kidney medical vector
│   └── meta-tags.liquid              # SEO, Open Graph & social meta data
├── assets/
│   ├── theme.css                     # Complete CSS design system & responsive rules
│   ├── theme.js                      # Language switcher, menu & WhatsApp appointment handler
│   ├── dr-faizan-portrait.jpg        # Authentic doctor portrait photo
│   ├── banner-services-grid.jpg      # Authentic procedure services poster
│   ├── banner-pcnl-procedure.jpg     # Authentic PCNL camera surgery banner
│   └── banner-prostate-cancer.jpg    # Authentic prostate cancer diagnosis poster
├── config/
│   ├── settings_schema.json          # Theme customizer settings schema
│   └── settings_data.json            # Theme preset values
├── locales/
│   ├── en.default.json               # English translations
│   └── ur.json                       # Urdu (اردو) translations
├── preview.html                      # Standalone pixel-perfect browser preview
└── index.html                        # Direct preview entry point
```

---

## 🚀 How to Upload to GitHub

Open terminal in this directory and run:

```bash
git init
git add .
git commit -m "Initial commit: Dr Faizan Shabbir Rana Shopify 2.0 Theme"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

---

## 🛒 How to Install in Shopify

### Option 1: ZIP Upload via Shopify Admin
1. Compress the contents of `shopify-theme-dr-faizan` into a `.zip` file (make sure `layout/`, `templates/`, `sections/`, `snippets/`, `assets/`, `config/`, and `locales/` are at the root of the ZIP).
2. Go to **Shopify Admin** &rarr; **Online Store** &rarr; **Themes**.
3. Under **Theme library**, click **Add theme** &rarr; **Upload zip file**.
4. Click **Publish** to make it live!

### Option 2: Shopify CLI
```bash
shopify theme push --store your-store.myshopify.com
```

---

## 🖥️ Live Browser Preview
Double-click `preview.html` or `index.html` in file explorer to open the site directly in Google Chrome, Microsoft Edge, or any modern browser without needing a local web server.
