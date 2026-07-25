# Gshock Aerial website

Static, mobile-responsive website prepared for GitHub Pages and the custom domain `www.gshockaerial.com`.

## Included SEO and accessibility work

- Unique page titles and meta descriptions
- Canonical URLs, Open Graph and Twitter Card metadata
- LocalBusiness, WebSite, WebPage, Service and FAQ JSON-LD
- One descriptive H1 per page and logical heading hierarchy
- Six dedicated service landing pages with internal links and quote CTAs
- Descriptive image alt text, explicit image dimensions, lazy-loading and compressed WebP assets
- `sitemap.xml`, `robots.txt`, `CNAME` and `.nojekyll`
- Keyboard-visible focus states, skip link, form labels, reduced-motion support and responsive navigation

## Publish with GitHub Pages

1. Create a GitHub repository and upload all files and folders in this package to the repository root.
2. In **Settings → Pages**, deploy from the `main` branch and `/ (root)`.
3. In **Settings → Pages → Custom domain**, enter `www.gshockaerial.com`. The included `CNAME` file uses that domain.
4. Point the `www` DNS record to your GitHub Pages hostname. Follow GitHub's current DNS guidance for the apex domain if you also want `gshockaerial.com` to redirect.
5. Enable **Enforce HTTPS** after DNS is active.
6. Submit `https://www.gshockaerial.com/sitemap.xml` in Google Search Console.

## Before launch

- Test the quote form once. FormSubmit may require an email confirmation on first use.
- Replace or add portfolio images as desired while preserving meaningful alt text and optimized WebP sizes.
- Run Google PageSpeed Insights and the Rich Results Test after the live deployment, because production hosting metrics cannot be measured accurately from local files.
