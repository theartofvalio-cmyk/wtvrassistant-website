# War Thunder VR Assistant Website

A static, responsive marketing/download website for War Thunder VR Assistant.

## Files

- `index.html` — site content and links
- `styles.css` — full visual design
- `script.js` — mobile navigation and full-size screenshot viewer
- `assets/website-logo.png` — supplied artwork used for the brand and favicon
- `assets/screenshots/` — real screenshots captured from the running Windows app

No Node.js, package manager, database or build step is required.

## Test locally

Double-click `index.html`, or run a local static server if you prefer.

Python example:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Recommended: GitHub Pages

### Separate website repository
1. Create a new public GitHub repository, for example `wtvrassistant-site`.
2. Upload all website files with `index.html` at the repository root.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`.
6. Save.
7. GitHub will show the generated `github.io` address after deployment.

### Use the existing app repository instead
You can also place the website inside a `/docs` folder in your existing repository and choose that folder as the Pages publishing source. A separate site repository is cleaner if the app repository already has a large Visual Studio project.

## Cloudflare Pages alternative

Cloudflare Pages can host this static website too.

1. Create/sign in to a Cloudflare account.
2. Create a Pages project.
3. Connect the website GitHub repository, or use Direct Upload.
4. There is no framework/build command required for this site.
5. Set the output/root directory to the folder containing `index.html`.
6. Deploy.

A custom domain can be added later.

## Artwork and screenshots

The page uses `assets/website-logo.png`, copied from the supplied `WebsiteLogo.png`. The screenshot tour uses real captures of Home, Profiles, VTrim, Axis Curves, Aircraft Profiles, KeyBind, Neck Assistant, Devices & Output, App Options and the Gear switch editor from the local Windows build. Replace screenshots when the published app UI changes. Keep screenshot filenames and `index.html` references aligned.

## Current external links

The site currently points to:
- GitHub repository
- GitHub latest release page
- Discord invite
- YouTube channel

Review these links before publishing if any have changed.

## Legal note

The footer and FAQ explicitly state that the project is community-made and not affiliated with or endorsed by Gaijin Entertainment. Keep that distinction prominent.
