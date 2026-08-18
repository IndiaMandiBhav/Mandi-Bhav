# 🌾 Ankit All India Live Mandi Bhav — GitHub Only

This version calls the Government of India's data.gov.in mandi resource directly from the browser.

Resource:
`9ef84268-d588-465a-a308-a864a43d0070`

## GitHub Pages deployment

1. Upload this project to a GitHub repository.
2. Go to **Settings → Pages**.
3. Select **GitHub Actions** as the source.
4. Push to the `main` branch.
5. The included workflow publishes `index.html`.

## API

The API key is already inserted in `index.html` because this version is designed for GitHub-only hosting.

### Security warning

The API key is PUBLIC in this version. Anyone can open the browser's page source/developer tools and see it.

If the key has usage limits or should remain private, use the Cloudflare Worker version instead.

## Features

- Real data.gov.in Min / Modal / Max prices
- State → District → Market → Commodity filters
- Date selection
- Hindi / English
- Trending design
- Previous-day modal-price comparison
- Up/down arrows
- No random/fake prices
- Mobile responsive
