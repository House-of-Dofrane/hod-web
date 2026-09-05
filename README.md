# hod-web

Public site for House of Dofrane at **houseofdofrane.com**.

Currently a single static placeholder (`index.html`). The full site rebuild lands in this
same repo and Vercel project, replacing the placeholder in place.

Run: open `index.html` in a browser. Deploy: push to `main`; Vercel auto-deploys.

DNS: Cloudflare (zone `houseofdofrane.com`), registrar GoDaddy. Apex A → Vercel, `www` CNAME → Vercel.
