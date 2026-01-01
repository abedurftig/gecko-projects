# Gecko Projects Website

Static website for Gecko Projects, Hamburg, Germany.

## Structure

```
gecko-projects/
├── index.html          # Main page
├── 404.html            # Error page
├── robots.txt          # Search engine directives
├── sitemap.xml         # Site structure for SEO
├── favicon.svg         # Browser tab icon
├── css/
│   └── styles.css      # All styles
├── js/
│   └── main.js         # Mobile navigation
└── images/             # Image assets
```

## Development

Open `index.html` in a browser or use a local server:

```bash
python3 -m http.server 8000
```

## Deployment

Configure GitHub Pages or Cloudflare Pages to serve from the main branch.
