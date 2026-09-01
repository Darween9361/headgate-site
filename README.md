# Headgate Animal Health — website

Single-file static site (`index.html`). Hosted on GitHub Pages from the `main` branch; custom domain `headgateanimalhealth.com` (set by the `CNAME` file).

## Deploy
Push to `main` — GitHub Pages rebuilds in ~30 seconds.

## DNS (Squarespace Domains → DNS settings)
Delete Squarespace's default records for `@` and `www`, then add:

| Type  | Host | Value                       |
|-------|------|-----------------------------|
| A     | @    | 185.199.108.153             |
| A     | @    | 185.199.109.153             |
| A     | @    | 185.199.110.153             |
| A     | @    | 185.199.111.153             |
| CNAME | www  | darween9361.github.io       |

Then in GitHub → repo Settings → Pages: wait for "DNS check successful" and tick **Enforce HTTPS**.
