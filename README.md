# عبدالله ♡ منى — Wedding Invitation

A cinematic Arabic wedding invitation built with React, Vite, and Tailwind CSS. The original couple portrait is included in `src/assets/`.

## Run locally

```bash
npm install
npm run dev
```

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository's `main` branch.
3. In GitHub, open **Settings → Pages** and set the source to **GitHub Actions**.
4. Push to `main`. The included workflow at `.github/workflows/deploy.yml` will build and publish the invitation automatically.

The workflow automatically uses the repository name as the GitHub Pages base path, so it also works when the repository is not named after a custom domain.

## Important

- Keep the image file at `src/assets/WhatsApp_Image_2026-09-16_at_20.10.43_1790233677149.jpeg`.
- The Google Maps button already points to the exact venue link supplied for the invitation.
- The countdown target is ٦ أكتوبر ٢٠٢٦ at ٦ مساءً.