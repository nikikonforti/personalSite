# nikikonforti.com

Personal website built with [Astro](https://astro.build) + [Tailwind CSS](https://tailwindcss.com).

## Setup

```bash
npm install
npm run dev      # localhost:4321
npm run build    # output to dist/
npm run preview  # preview the build locally
```

## Deployment (Vercel — recommended)

1. Push this folder to your GitHub repo (`nikikonforti/personalSite`)
2. Go to [vercel.com](https://vercel.com) → Import Project → connect GitHub
3. Select the repo — Vercel auto-detects Astro, no config needed
4. Add your custom domain: `nikikonforti.com` in Vercel's Domains settings
5. Update GoDaddy DNS to point to Vercel (Vercel gives you the records)

From then on: push to `main` → site auto-deploys.

## Adding content

### Art gallery
Put image files in `/public/art/` and add entries to the `pieces` array in `src/pages/art.astro`.

### Projects
Edit the `projects` array in `src/pages/work.astro`.

### Resume
Update `experience`, `education`, and `skills` arrays in `src/pages/resume.astro`.

## Easter eggs

- **Konami code** (↑↑↓↓←→←→BA) — hidden overlay appears
- **Click your photo** on the home page — confetti burst
- **Sparkle cursor trail** — active on desktop (hidden on mobile/touch)
- The tiny `↑↑↓↓←→←→ba` hint in the footer for the curious
