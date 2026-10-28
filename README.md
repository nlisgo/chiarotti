# chiarotti.co.uk

One-page brochure site for Rachel Chiarotti, Private Client Solicitor. It is static HTML with no build step, hosted on GitHub Pages.

## Deploy

1. Push this folder to a GitHub repository.
2. In the repository, open **Settings → Pages**. Set the source to *Deploy from a branch*, using `main` and `/ (root)`.
The site is currently previewed at https://nlisgo.github.io/chiarotti/.

3. To switch to the custom domain, add a `CNAME` file containing `chiarotti.co.uk`, or set it under Settings → Pages. Then, at your DNS provider:
   - Add `A` records for `@` pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153` and `185.199.111.153`.
   - Add a `CNAME` record for `www` pointing to `nlisgo.github.io`.
4. When DNS has propagated, turn on **Enforce HTTPS** in Settings → Pages.

## Images

- `assets/rachel-portrait.jpg`: hero portrait, cropped to 4:5 from the original photo.
- `assets/rachel-meeting.jpg`: Rachel with a client (about section), cropped from the digital flyer. Swap in the original photo for a higher-resolution version.
