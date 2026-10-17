# BadAss Cloud Phone

Static marketing site for BadAss Cloud Phone monthly cloud-phone plans.

**Live:** https://badasscloudphone.com/

## Contents

- `index.html` — complete landing page.
- `assets/` — shared and site-specific CSS and browser JavaScript.
- `deploy/badasscloudphone.conf` — production Nginx virtual host with HTTPS.

No build step or external runtime is required; deploy these files directly to a static web root.

## Production

Served by Nginx on Hetzner `144.76.78.158` from `/srv/badass-websites/dist/badasscloudphone.com`. HTTPS uses a Let's Encrypt certificate managed by Certbot.
