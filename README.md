# AGI Accelerator (agi.lease)

Static site for the AGI Accelerator — the live-in AI founder residency in San
Francisco. Content blended from the Kylon build (agi-lease.kylon.app).
Operated by AGI Corp · AGI Future Foundation.

## Deploy
```bash
vercel          # preview deploy
vercel --prod   # production
```
Then add the custom domain (`agi.lease`) in the Vercel dashboard
(Settings → Domains). DNS is managed at Hostinger: apex A → `76.76.21.21`,
www → `cname.vercel-dns.com`.

## TODO
- [ ] Wire the apply + get-involved forms to a backend (Formspree / Vercel Function)
- [ ] Wire the $500 deposit checkout
- [ ] Publish the 10 founder guides and link them
- [ ] Replace `#` placeholders in footer social links with real profile URLs
