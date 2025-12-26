# 120homework

This repository contains the **Laurel** landing page template located in the `laurel/` directory. Static assets are already built in `laurel/dist/`, so the site can be deployed directly without a build step.

## GitHub Pages deployment

A GitHub Actions workflow (`.github/workflows/deploy-pages.yml`) publishes the landing page to GitHub Pages.

1. Ensure the repository's **Pages** settings use **GitHub Actions** as the source (this may be set automatically after the first successful run).
2. Push changes to the `main` branch or use the **Run workflow** button to trigger a deployment.
3. The workflow uploads everything in `laurel/` and deploys it to the `github-pages` environment.

After the workflow finishes, the landing page will be available at the URL shown in the deployment summary.
