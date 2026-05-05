# Pomodoro

Tiny static Pomodoro app. No build step, dependencies, server, or external assets.

## Cloudflare Pages

Dashboard deploy:

- Framework preset: `None`
- Build command: leave blank
- Build output directory: `.`

Wrangler deploy:

```sh
wrangler pages deploy .
```

The app stores timer state, task text, and seven days of stats in browser `localStorage`.
