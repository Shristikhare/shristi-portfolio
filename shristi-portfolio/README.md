# Shristi Khare — Portfolio

React + Vite + Tailwind CSS portfolio site.

## Run locally

```bash
npm install
npm run dev
```

## Build for production

```bash
npm run build
```

Output goes to `dist/`.

## Deploy to Vercel

1. Push this folder to a GitHub repo.
2. Go to https://vercel.com/new, import the repo.
3. Framework preset: **Vite**. Build command: `npm run build`. Output dir: `dist`.
4. Deploy.

## Deploy to Netlify

1. Push this folder to a GitHub repo.
2. Go to https://app.netlify.com/start, import the repo.
3. Build command: `npm run build`. Publish directory: `dist`.
4. Deploy.

## Notes

- The resume PDF is embedded directly in `src/App.jsx` as a base64 data URI (`RESUME_PDF_DATA_URI`), so the "Download Resume" and resume cards open it in a new tab with no external hosting needed. Replace it with your latest resume by re-encoding a PDF to base64 and swapping the string.
- Update `PROFILE.linkedin` and `PROFILE.github` in `src/App.jsx` if those links change.
