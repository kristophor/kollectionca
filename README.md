# Kollection

A small, dependency-free company landing page for GitHub Pages. Plain HTML and CSS; no build step, JavaScript, external fonts, analytics, or paid services.

## Edit

Open `index.html` directly in a browser. Update company copy and contact details in `index.html`, styling in `styles.css`, and the icon in `favicon.svg`.

The initial phone and postal address come from the existing public contact page at https://kollection.ca/contact-us/. Company email and confirmation of current contact details are pending.

## Publish

Target repository: `kollectionca/kollectionca.github.io`.

In the repository's **Settings → Pages**, select **Deploy from a branch**, then **main** and **/ (root)**. The site will be available at https://kollectionca.github.io/.

For the later switch to `kollection.ca`, configure the custom domain in GitHub Pages and update the domain's web DNS records using GitHub's documentation: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site. Preserve email-related MX and TXT records. There is deliberately no CNAME file until the domain is ready to move.

The former WordPress projects and app pages are not part of this replacement.
