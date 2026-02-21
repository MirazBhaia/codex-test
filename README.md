# codex-test

## Local development

```bash
npm install
npm run dev -- --host 0.0.0.0 --port 5173
```

## Production build

```bash
npm run build
```

## GitHub Pages deployment

This repo includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml`.

To publish:
1. Push to `main`.
2. In GitHub, go to **Settings → Pages**.
3. Set **Source** to **GitHub Actions**.
4. After workflow completes, your live URL will be:
   `https://<your-github-username>.github.io/<repo-name>/`
