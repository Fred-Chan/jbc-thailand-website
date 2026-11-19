# JBC Thailand Open

Official website for the **Junior Botball Challenge Asia — Thailand Open**, an international
youth robotics competition held in Bangkok, Thailand.

- **Live**: https://jbc-thailand.itccc.app
- **Next edition**: Sunday 9 May 2027 · Bangkok
- **Stack**: static HTML + CSS (single page, no build step)
- **Deploy**: Vercel (auto-deploys from `main`)

## Structure

```
index.html      # the whole site (markup + styles + scripts)
images/         # optimized event photos (served locally, no external CDN)
```

## Local preview

```bash
python3 -m http.server 8765
# open http://127.0.0.1:8765
```
