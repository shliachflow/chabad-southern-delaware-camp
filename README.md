# Kosher Culinary Camp Website

One-week kosher culinary day camp at Chabad of Southern Delaware.  
**August 3-7, 2026 · 9:00 AM - 3:00 PM**  
Hosted by Chabad of Southern Delaware.

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
    ├── index.html      Optional Decap admin panel (/admin)
    └── config.yml      Optional Decap configuration
```

## Items Needing Client Input

See full list in PLACEHOLDERS.md or the inline HTML comments.

**Critical before launch:**
- [x] Public location: Chabad of Southern Delaware, Lewes, DE
- [ ] Cognito Forms embed code (register.html)
- [ ] Instagram / Facebook handles
- [x] Hero banner image (uploads/hero-banner.webp)

## CMS

Use Pages CMS with this GitHub repository to manage the main content and images. The optional `/admin` Decap setup is configured for GitHub, not Netlify.

## Design

- Fonts: Fredoka One (headings) + Nunito (body) via Google Fonts
- Colors: bright aqua/teal, sunny yellow, sky blue, and playful accent colors
- Warm Chabad community camp aesthetic
