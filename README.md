<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/3d9ee4d0-79b3-4793-b33b-67a54fcaa807

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`

## Build for production

1. Install dependencies:
   `npm install`
2. Create the production bundle:
   `npm run build`
3. Preview the production build locally:
   `npm run preview`

## Put it on the internet

The fastest path is to publish this Vite app with Vercel or Netlify.

1. Push this folder to GitHub.
2. Import the repository in Vercel or Netlify.
3. Use `npm run build` as the build command.
4. Use `dist` as the publish/output folder.

## GitHub Pages

This repository is already configured for GitHub Pages.

1. Push the code to the `main` branch on GitHub.
2. In the repository settings, enable GitHub Pages from the `GitHub Actions` source.
3. Every push to `main` will build the site and publish it automatically.
4. If you rename the repository, update the `base` value in [vite.config.ts](vite.config.ts).

If you want, I can also prepare this repo specifically for GitHub Pages or Vercel.
