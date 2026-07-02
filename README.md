# Qairo AI — Website

Single-page brand/credibility site for Qairo AI.

## Contents

```
WEBSITE CODE/
├── index.html            # The full single-page site
├── css/style.css         # All styling (dark + copper palette, responsive)
├── js/main.js            # Scroll reveals, nav, mobile menu, FAQ accordion
└── assets/
    ├── qairo-logo-full.png   # Full lockup (Qairo + AI Consulting), original
    ├── qairo-wordmark.png    # "Qairo" wordmark, original (black background)
    ├── qairo-mark.png        # Q mark, original (black background)
    ├── qairo-wordmark-t.png  # Wordmark, transparent bg (used in nav + footer)
    ├── qairo-mark-t.png      # Q mark, transparent bg (used in hero + CTA)
    └── favicon.png           # 64px favicon from the transparent Q mark
```

The `-t` versions were extracted from the originals (copper artwork lifted off
the black background) so the logos sit cleanly on any dark surface without a
visible box.

## Notes

- No build step, no dependencies — plain HTML/CSS/JS. Open `index.html` in a
  browser or serve the folder with any static host (Netlify, Vercel, GitHub
  Pages, Cloudflare Pages).
- Fonts load from Google Fonts: **Jost** (headings) and **Inter** (body).
- Contact email used throughout: `bradleym@qairoai.com`.
- Anchor sections: `#about`, `#how`, `#services`, `#faq`, `#contact`.
