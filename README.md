# isynced.com - Premium Domain Landing Page

A premium domain landing page for isynced.com, optimized for wearable tech, IoT, and API synchronization markets.

## Features

- Modern, responsive design
- Optimized for Cloudflare Pages deployment
- Performance optimized with caching headers
- SEO-friendly structure
- Interactive domain statistics
- Image modal gallery

## Deployment to Cloudflare Pages

### Prerequisites

- Node.js and npm installed
- Cloudflare account
- Wrangler CLI installed (`npm install -g wrangler`)

### Quick Deploy

1. Install dependencies:
```bash
npm install
```

2. Deploy to Cloudflare Pages:
```bash
npm run deploy
```

Or using wrangler directly:
```bash
npx wrangler pages deploy .
```

### Preview Locally

```bash
npm run preview
```

Or:
```bash
npx wrangler pages dev .
```

## File Structure

```
.
├── index.html              # Main HTML file
├── standalone-styles.css   # CSS styles
├── favicon.ico            # Site favicon
├── placeholder.svg        # Placeholder image
├── robots.txt             # SEO robots file
├── wrangler.toml          # Cloudflare Pages configuration
├── _headers               # Custom headers for caching and security
├── package.json           # Node.js dependencies and scripts
└── README.md              # This file
```

## Configuration

### wrangler.toml

Configured for Cloudflare Pages static site deployment with:
- Static file serving
- Performance optimizations
- Caching rules

### _headers

Custom headers for:
- Security headers (X-Frame-Options, X-Content-Type-Options, etc.)
- Cache control for static assets
- Performance optimization

## Performance Optimizations

- CSS preloading
- Deferred script loading
- Resource hints (preconnect)
- Long-term caching for static assets
- Security headers

## License

MIT

