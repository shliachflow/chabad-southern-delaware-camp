# Kosher Camp Southern Delaware — Camp Website

One-week kosher day camp for kids ages 3–12.  
**August 17–21, 2025 · 9:00 AM – 3:00 PM**  
Hosted by Rabbi Sholom Vogel, Chabad of Southern Delaware.

## Structure

```
/
├── index.html          Main camp homepage
├── register.html       Registration page (Tally embed — needs form URL)
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
- [ ] Venue address (location section)
- [ ] Registration form URL (Tally or other — register.html)
- [ ] Instagram / Facebook handles
- [ ] Hero banner image (uploads/hero-banner.jpg)

## CMS

Visit `/admin` to manage content via Decap CMS.  
Configure `admin/config.yml` with your GitHub repo details before use.

## Design

- Fonts: Fredoka One (headings) + Nunito (body) via Google Fonts
- Colors: Ocean blue (#1B6CA8), Golden yellow (#F4A01C), Sky blue (#E8F4FD)
- Shore/beach-town aesthetic with Jewish warmth
