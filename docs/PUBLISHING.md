# GitHub Pages publication and maintenance

## Initial publication

1. Create a new public repository owned by `yaysonvalencia`, named exactly `yaysonvalencia.github.io`. Do not rename or replace `yaysonvalencia`, which controls the existing profile README.
2. Put this site’s files at the repository root on `main`, including `index.html`, `assets`, `case-studies`, and `.nojekyll`. Do not upload the parent directory as an extra nesting level.
3. Open repository Settings → Pages. Under Build and deployment, select Deploy from a branch, branch `main`, folder `/(root)`, then Save.
4. Wait for the Pages build/deployment to succeed. Verify the live home page, every case-study URL, a missing-page URL, contact links, and image loading. Inspect the Actions run if deployment fails.
5. Confirm the published URL is https://yaysonvalencia.github.io. Enable Enforce HTTPS when available.

No custom domain, paid plan, build service, or access token embedded in the site is required. A branch-based static site is sufficient; a custom Actions workflow is unnecessary for this version.

Official references:
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Updating

Commit edits to `main`; GitHub Pages republishes the branch. Check the deployment and the changed pages. Use a branch and pull request for substantial redesigns. Keep an existing working version in Git history; revert the relevant commit if needed.

## Before adding another case study

Document the business question, project context, exact contribution, method, delivered artifact, evidence, business relevance, and limitations. Add realized outcomes only when the underlying evidence supports the measurement and attribution. Never add confidential employer or client material without authorization.

## Owner-controlled refinements

A current resume, approved professional headshot, and additional public operating examples can be added later. No placeholder downloads, invented email address, or client logos are included.
