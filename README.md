# CorpLingua

A deployable, local-first micro-learning web app for workplace communication practice. It implements the PRD's daily themes, sentence practice, inline definitions, playback, speech-recognition feedback where supported, evaluations, and progress tracking.

## Run locally

```bash
npm install
npm run start
```

## Deploy

This is a static Vite app. Run `npm run build` and deploy the generated `dist/` directory to Netlify, Vercel, Cloudflare Pages, GitHub Pages, or any static host. Configure the host build command as `npm run build` and the publish directory as `dist`.

Progress is stored in each user's browser with `localStorage`; no server, credentials, or database are required for deployment.
