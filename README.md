# Molio Landing Page

Static landing page for [Molio](https://t.me/MolioBot) — an AI-powered personal finance Telegram bot.

## Stack

- Pure HTML
- Tailwind CSS via CDN (no build step)
- Inter font from Google Fonts

That's it. One file, zero dependencies, opens in any browser.

## Local preview

Just open `index.html` in your browser — no server needed.

For a local server (optional, helps with iframe/CORS testing):

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to https://vercel.com/new
3. Import the repo — Vercel auto-detects it as a static site
4. Deploy

## Custom domain

After deploy:

1. Vercel dashboard → project → **Settings → Domains**
2. Add your domain (e.g. `molio.uz`)
3. Vercel shows you the DNS records to add at your registrar
4. Add them and wait 5–60 minutes for propagation

## Update content

Edit `index.html`. Push to GitHub. Vercel redeploys automatically.

## License

Private project — all rights reserved.
