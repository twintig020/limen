# Limen — Warm Intros for Super-Connectors

A minimal, utility-first landing page for Limen communities.

## Quick Start

Open `index.html` in your browser to preview locally.

## Structure

```
website/
├── index.html          # Main landing page
├── paul/
│   └── index.html      # Community page
├── css/
│   └── style.css       # Design system
├── images/
│   ├── logo.png        # Limen logo
│   └── paul.png        # Community image
└── README.md
```

## Design

- **Typography**: DM Sans (headings), Inter (body)
- **Colors**: #FFB86A (primary), #171717 (headings), #717171 (body)
- **Approach**: Clean, bold, utility-first (based on Brave design principles)

## Deploy to GitHub Pages

1. Create a new public repository on GitHub named `limen`
2. Push this code to `main` branch
3. In GitHub repo settings, enable GitHub Pages from `main` branch
4. Site will be available at `username.github.io/limen`

## Connect Custom Domain

1. In GitHub repo settings, add custom domain `limen.to` under "Custom domain"
2. In Namecheap DNS settings, add:
   - CNAME record: `www` → `username.github.io`
   - A records pointing to GitHub Pages IPs
3. Update domain redirect settings

## License

All rights reserved.
