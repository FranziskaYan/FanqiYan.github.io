# Fanqi Yan — Personal Research Website

One-page, fully static About site. No JavaScript framework, build tool, tracking, analytics, or runtime dependencies are required.

## Preview

Open `index.html` in a browser. All files are in the site folder.

## Publish publicly for free on GitHub Pages

1. Sign in to GitHub and create a **public** repository named `FanqiYan.github.io` under the `FranziskaYan` account.
2. Upload the files from this folder to the repository root (not a nested folder).
3. Go to **Settings → Pages → Build and deployment**. Select **Deploy from a branch**, choose **main / (root)**, and save.
4. The public address will be `https://franziskayan.github.io/FanqiYan.github.io/` once GitHub Pages has deployed.
5. To improve discoverability, link the published URL from your LinkedIn, Google Scholar, OpenReview and university profiles. Add your site to [Google Search Console](https://search.google.com/search-console/about) and request indexing of its homepage. Google indexing is not immediate or guaranteed.

Alternatively, deploy the folder to Netlify, Cloudflare Pages, or another static-hosting provider.

## Search visibility

Included in `index.html`: descriptive page title, meta description, index/follow directives, Open Graph tags, semantic headings, and Person schema.org structured data with verified professional links. `robots.txt` explicitly allows crawling.

This package already includes the canonical URL and sitemap for `https://franziskayan.github.io/FanqiYan.github.io/`. If you publish to a different domain, update both the canonical URL and sitemap accordingly.

## Editing

- Text: update content inside `index.html`.
- Color palette: change CSS `:root` variables.
- Social links: edit links in the hero and contact section, plus the `sameAs` array in the structured data.
- To add your photo later, replace the abstract hero graphic with an image; this starter intentionally does not invent or use a portrait.

Content based on the user's supplied research summary and public academic profiles. Review the text and contact details before publication.

Note: This is a GitHub Pages **project site**, so its public URL includes the repository name.
