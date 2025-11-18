# Jayam Pipes — Static Website

This repository contains a ready-to-deploy static website for **Jayam Pipes** (Established 2010, Vadaperumbakkam, Chennai). The theme is industrial grey/black and built for an elegant, premium corporate look.

## Files
- `index.html` — main site
- `assets/styles.css` — styles used by index
- `CNAME` — contains `jayampipes.in` (if deploying to GitHub Pages with custom domain)
- `README.md` — this file

## How to deploy (GitHub Pages)
1. Create a GitHub account if you don't have one.
2. Create a new repository named `your-username.github.io` (or any repo — see step 6 for project pages).
3. Upload the files preserving the folder structure (`assets/styles.css` in `assets/`).
4. If the repo is named `your-username.github.io` the site will be available at `https://your-username.github.io/`.
5. To use a custom domain (`jayampipes.in`): add the `CNAME` file (already present) and in your GitHub repo > Settings > Pages set custom domain to `jayampipes.in`. GitHub will provision HTTPS.

### DNS settings on GoDaddy for GitHub Pages (use these for apex domain)
- In your GoDaddy DNS for `jayampipes.in` create **A** records pointing to these GitHub Pages IPs:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- Add a **CNAME** record for `www` pointing to `<your-username>.github.io`. This ensures `www.jayampipes.in` redirects to the GitHub Pages site.
- Wait for DNS propagation (can be a few minutes to a few hours).

## Alternative: Netlify (drag & drop)
1. Zip the site folder or keep the folder local.
2. Create a free Netlify account.
3. Drag & drop the site folder to create a new site.
4. In Netlify Domain settings, add `jayampipes.in` as a custom domain. Netlify will give DNS instructions (you may need to add A or CNAME records at GoDaddy); Netlify also issues a free TLS certificate.

## Forms / Contact
- The included contact form uses a `mailto:` fallback. For reliable submissions use a free Form service: Formspree, Getform, or Netlify Forms (if hosted on Netlify). I can set up Netlify Forms or Formspree if you want.

## Images & Assets
- Replace placeholder SVGs with product photos (optimised). Place them in an `assets/images/` folder and update `index.html`.

## Next steps I can do for you (pick any):
- Integrate Formspree (free) so contact form submissions go to email without mailto.
- Provide exact terminal commands to push this to GitHub and connect `jayampipes.in` in GoDaddy.
- Create a 1-page PDF brochure using the same content and visuals.
