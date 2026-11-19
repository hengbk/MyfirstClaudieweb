# BK Photo-genic

One-page portfolio site for a wedding and portrait photographer. Plain HTML and CSS, no build step.

## Structure

- `index.html`: the whole site
- `images/`: portfolio photos
- `vercel.json`: Vercel settings (static deploy, image caching)

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 3000
```

## Deploy to Vercel

1. Go to [vercel.com/new](https://vercel.com/new) and import this GitHub repo.
2. Leave Framework Preset as **Other**, and leave the build command and output directory empty.
3. Click **Deploy**. Every push to `main` redeploys automatically.

Or from the command line: `npx vercel --prod`.

## Before going live

- Replace `hello@yourname.com` (link and text) in the contact section.
- Replace `[City]` in the about section.
- Swap the five "Your photo here" tiles for real images in `images/`.
