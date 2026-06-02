# Kosher Culinary Camp Website

One-week kosher culinary day camp at Chabad of Southern Delaware.  
**August 3-7, 2026 · 9:00 AM - 3:00 PM**  
Hosted by Rabbi Sholom, Chabad of Southern Delaware.

## Structure

```
/
├── index.html          Main camp homepage
├── register.html       Registration page (Cognito Forms placeholder)
├── photos.html         Photo albums page
├── content/
│   ├── site.json       All editable text content (CMS-managed)
│   └── gallery.json    Photo albums (CMS-managed)
├── uploads/            Images go here
└── admin/
    ├── index.html      Decap CMS admin panel (/admin)
    └── config.yml      CMS configuration
```

## Items Needing Client Input

See full list in PLACEHOLDERS.md or the inline HTML comments.

**Critical before launch:**
- [x] Venue address: 17032 Minos Conaway Rd, Lewes, DE 19958
- [ ] Cognito Forms embed code (register.html)
- [ ] Instagram / Facebook handles
- [x] Hero banner image (uploads/hero-banner.webp)

## CMS

Visit `/admin` to manage content via Decap CMS.  
Configure `admin/config.yml` with your GitHub repo details before use.

## Design

- Fonts: Fredoka One (headings) + Nunito (body) via Google Fonts
- Colors: Ocean blue (#1B6CA8), Golden yellow (#F4A01C), Sky blue (#E8F4FD)
- Warm Chabad community camp aesthetic
