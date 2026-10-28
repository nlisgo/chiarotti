# chiarotti.co.uk

One-page brochure site for Rachel Chiarotti, Private Client Solicitor. It is static HTML with no build step, hosted on GitHub Pages.

## Deploy

1. Push this folder to a GitHub repository.
2. In the repository, open **Settings → Pages**. Set the source to *Deploy from a branch*, using `main` and `/ (root)`.
3. The `CNAME` file already sets the custom domain to `chiarotti.co.uk`. At your DNS provider:
   - Add `A` records for `@` pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153` and `185.199.111.153`.
   - Add a `CNAME` record for `www` pointing to `<your-github-username>.github.io`.
4. When DNS has propagated, turn on **Enforce HTTPS** in Settings → Pages.

## Images

The photos in `assets/` were cropped from a phone photo of the printed flyer. Replace them with the original image files, keeping the same filenames:

- `assets/rachel-portrait.jpg`: portrait (hero)
- `assets/rachel-meeting.jpg`: Rachel with a client (about section)
