# web-dev

This repository contains multiple web projects. The legacy FIFA project remains in [`fifa/`](fifa/).

## CorpLingua

CorpLingua is a deployable, local-first micro-learning web app for workplace communication practice. It implements daily themes, sentence practice, inline definitions, playback, browser speech-recognition feedback where supported, evaluations, and progress tracking.

### Run locally

```bash
npm install
npm run start
```

### Deploy

Pushing to `main` triggers the GitHub Pages workflow in `.github/workflows/deploy-pages.yml`. The app is built with `npm run build` and the generated `dist/` directory is published.

Learner progress is stored in each user's browser with `localStorage`; no server, credentials, or database are required.
