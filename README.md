# Clean Portfolio Website

This is a simplified static portfolio site.

## What was removed
- database code
- API server code
- monorepo/workspace setup
- Replit-only configuration
- extra backend dependencies

## Run locally
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

## Easiest hosting
### Netlify
1. Run `npm install`
2. Run `npm run build`
3. Upload the generated `dist` folder to Netlify Drop

### GitHub Pages
1. Push this folder to a GitHub repository
2. Add the workflow already included in `.github/workflows/deploy.yml`
3. In GitHub: Settings > Pages > Source = GitHub Actions

