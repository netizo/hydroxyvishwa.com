# Hydroxy Vishwa — Coming Soon

Static landing page for [hydroxyvishwa.com](https://hydroxyvishwa.com).

## Deployment

Hosted via GitHub Pages. Any push to `main` auto-deploys.

### Custom Domain Setup

1. In repo Settings → Pages → set source to `main` branch, root `/`
2. Add custom domain: `hydroxyvishwa.com`
3. At your domain registrar, add these DNS records:

| Type  | Name | Value                          |
|-------|------|--------------------------------|
| CNAME | www  | `<your-username>.github.io`    |
| A     | @    | `185.199.108.153`              |
| A     | @    | `185.199.109.153`              |
| A     | @    | `185.199.110.153`              |
| A     | @    | `185.199.111.153`              |

4. Check "Enforce HTTPS" once DNS propagates
