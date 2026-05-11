# Deivids Bandars Portfolio

Static portfolio site intended for `deivids.ghocoyops.com`.

## Local Preview

Open `index.html` directly in a browser.

Optional local server:

```bash
npx serve .
```

## Deploy

Fastest options:

1. Push this folder to a GitHub repository, for example `deivids-portfolio`.
2. Import the repository in Vercel, Netlify, or Cloudflare Pages.
3. Use static settings:
   - Build command: none
   - Output directory: `.`
4. Add custom domain: `deivids.ghocoyops.com`.

## DNS

For Vercel, add the exact DNS records Vercel gives you for `deivids.ghocoyops.com`.
Usually that means adding a `CNAME` record for `deivids` pointing to Vercel's target.
