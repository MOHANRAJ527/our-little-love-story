# Our Little Love Story ❤️

A responsive React + Vite birthday memory website. The project includes the uploaded photos, two MP4 memories, the uploaded MP3 background track, the 1816 keypad gate, photo lightbox, timeline, and the complete supplied Tanglish letter.

## Run locally

```bash
npm install
npm run dev
```

## Build for hosting

```bash
npm run build
```

Deploy the project folder to Vercel (New Project → import Git repository, or use Vercel CLI). Framework preset: Vite; build command: `npm run build`; output directory: `dist`.

All media is bundled under `public/media`, so it is available to every visitor after deployment. The password screen is a front-end surprise gate, not high-security authentication; visitors with technical access to the site files can inspect the password.
