# On This Day History

> Daily Historical Events Archive

## Deployment

- **Production URL**: https://on-this-day-428.pages.dev/
- **GitHub Repo**: https://github.com/wangdan197902-art/on-this-day
- **Cloudflare Project**: on-this-day

## Local Development

```bash
# Install Hugo (macOS)
brew install hugo

# Run dev server
hugo server -D

# Build for production
hugo --minify --baseURL "https://on-this-day-428.pages.dev/"
```

## Auto Deploy

Push to `main` branch → GitHub Actions auto-deploys to Cloudflare Pages.

## Project Structure

```
├── content/           # Markdown content
├── layouts/           # Hugo templates
├── static/            # Static assets (images, CSS)
├── data/              # JSON data files
├── hugo.toml          # Hugo config
├── wrangler.toml      # Cloudflare Pages config
└── .github/workflows/ # CI/CD
```
