# theinfodump-site

The studio site for **The InfoDump LLC** — software made by people who won't shut up about it.

Live at: https://theinfodump.com

## Stack

- Plain HTML + CSS, no build step
- Hosted on GitHub Pages
- DNS via Cloudflare → GitHub Pages A records
- Custom domain configured via `CNAME` file

## Local development

Just open `index.html` in a browser. There's no build step.

```bash
# from this directory
open index.html
# or serve over localhost
python3 -m http.server 8000
```

## Deploy

Push to `main`. GitHub Pages will rebuild automatically.

## Projects

- **Linear Timer+** — interval timer with Pomodoro, scheduling, and presets. Live on iOS, Chrome, and (soon) Android. → [lineartimer.com](https://lineartimer.com)
- More to come.

## Contact

contact@theinfodump.com
