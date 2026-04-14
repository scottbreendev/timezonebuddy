# Time Zone Buddy — Website

This folder (`website/`) sits at the repository root and contains the marketing website for **Time Zone Buddy**.

**Tech stack:** Plain HTML5 + Tailwind CSS (CDN) + Alpine.js + GSAP. No build step.

**Before making changes**, read `docs/website_AI_instructions.md` — it is the single source of truth for all website decisions, colors, components, and content.

## Structure

```
website/
├── .nojekyll               ← Required for GitHub Pages
├── index.html              ← Homepage
├── support.html            ← Support / FAQ
├── privacy-policy.html     ← Privacy policy
├── css/
│   └── styles.css          ← CSS custom properties + utilities
├── js/
│   └── app.js              ← Alpine.js + GSAP
└── images/
    ├── icon.png            ← App icon (1024×1024 PNG, rendered by render_icon/ — run `cd render_icon && swift run render_icon ../website/images/icon.png` to regenerate)
    ├── device-frame.png    ← iPhone frame overlay
    ├── ss-01.png … ss-05.png  ← App screenshots
    └── og-image.png        ← Social preview (create before go-live)
```

## Go Live

See the **Go Live Checklist** in `docs/website_AI_instructions.md` section 15.
