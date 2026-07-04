# Diddle General Labor — Website

Single-file website for Diddle General Labor (junk removal, hauling, and general labor in Rector, AR).

Everything is in `index.html` — no build step, no dependencies, no server code. Open it in a browser to preview.

## Hosting

Any static host works. The two easiest free options:

- **GitHub Pages**: push this repo to GitHub, then in the repo go to Settings → Pages → set Source to the main branch. The site goes live at `https://<username>.github.io/DiddleGeneralLabor/`.
- **Netlify / Cloudflare Pages**: drag-and-drop the folder or connect the repo. Both serve `index.html` automatically.

To use a custom domain (e.g. `diddlegenerallabor.com`), buy the domain and point it at the host — every host above has a guide for this in its settings.

## Adding real photos

1. Create a folder named `photos/` next to `index.html` and put the images in it.
2. In `index.html`, replace a placeholder block like:

   ```html
   <figure class="ph"><span class="label">Photo placeholder</span><small>Garage cleanout — before</small></figure>
   ```

   with:

   ```html
   <figure><img src="photos/garage-before.jpg" alt="Garage cleanout — before"></figure>
   ```

## Before going live — replace placeholder content

- **Testimonials** on the Home page ("What neighbors say") are sample text. Replace with real customer quotes or delete the section.
- **Working hours** and payment details on the Contact page and in the FAQ are guesses — confirm them.
- The **service-area town list** is an educated guess; adjust as needed.
