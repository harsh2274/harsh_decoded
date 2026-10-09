# Harsh's website

A static resume and portfolio website, ready to publish with GitHub Pages. It uses plain HTML, CSS, and JavaScript, so there is no build step.

## Make it yours

- Resume content is in `index.html`; update it as your experience changes.
- The original resume PDF stays local and is excluded from Git and the Pages deployment.
- Adjust colors, typography, and layout in `styles.css`.
- The hero photograph is loaded from Unsplash; change its URL in the `.hero-art` rule to use a different image.

## Publish with GitHub Pages

1. Create a GitHub repository for this site. For a user site, name it `your-username.github.io`.
2. Push these files to the repository's `main` branch.
3. In the repository, open **Settings → Pages** and set the source to **GitHub Actions**.
4. The workflow in `.github/workflows/pages.yml` deploys the site on each push to `main`. The published URL appears in the workflow run and in **Settings → Pages**.

For a project repository with a different name, the site URL is `https://your-username.github.io/repository-name/`.