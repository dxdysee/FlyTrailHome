# FlyTrail GitHub Pages website

The static website is in this directory. The workflow at `.github/workflows/pages.yml` deploys it from the `main` branch using GitHub Actions.

## Turn on GitHub Pages

1. Push this repository to GitHub.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **GitHub Actions** as the source.
4. Push a change to `site/` or run **Deploy FlyTrail website** from the **Actions** tab.
5. GitHub will show the published website URL in the workflow deployment.

The pages are `index.html`, `support.html`, and `privacy.html`. The support and privacy pages use `excorbe@gmail.com`.

## Before launch

- Replace the App Store search links in `index.html` with the direct App Store listing URL when the listing is available.
- Capture real screenshots from the release candidate in the iPhone and iPad sizes required by App Store Connect. The current images are branded artwork, not captures of the app UI. Put the chosen screenshots in `assets/` and update the gallery in `index.html` to use them.
- Confirm the privacy policy against the final app build and publisher details before entering its public URL in App Store Connect and the app.
