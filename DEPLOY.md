# Deploying the PostAxiom site

## Current structure
- `index.html` — homepage
- `platform.html` — platform architecture
- `science.html` — methods and scientific stack
- `research.html` — research DNA and founder agenda
- `roadmap.html` — staged commercial roadmap
- `styles.css` — shared site styles
- `.nojekyll` — GitHub Pages compatibility

## To publish with GitHub Pages
1. Make the repository public if needed for your preferred Pages setup.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder.
5. Save.

## To attach the custom domain later
1. Acquire and control the final domain, for example `postaxiom.ai`.
2. In **Settings → Pages**, set the custom domain.
3. Add the matching DNS records at the registrar.
4. After the domain is active, create a `CNAME` file in the repository root with the final domain.
