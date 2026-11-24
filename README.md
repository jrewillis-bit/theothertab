# The Other Tab

A personal Jekyll blog. Enable Settings > Pages > Deploy from a branch > main > / (root).

## Publish
Create `_posts/YYYY-MM-DD-title.md` using the example in `_drafts/example.md`. Use one category (Technology, Minimalism, Gaming, Teaching, Photography or Life), a description and optional tags. Commit to main. Drafts are not published. Edit `_config.yml` when moving to a custom domain. No analytics, cookies or external fonts.

## Cover images
Optional post front matter: `cover: /assets/images/example.jpg` and `cover_alt: Description of the image`. Upload the image to that path. Posts without images use a simple category header.

## SEO
The sitemap regenerates with every build. Submit https://theothertab.uk/sitemap.xml in Google Search Console and Bing Webmaster Tools. Google domain verification requires the TXT record supplied by Google in Porkbun. Alternatively use URL-prefix HTML meta verification by setting `google_site_verification` in `_config.yml`; use `bing_site_verification` for Bing's meta code. Only use genuine codes. Each article's title, description and cover automatically generate canonical, Open Graph, Twitter and BlogPosting metadata. Optional `author` and `last_modified_at` can be provided in front matter. The fallback social image is `assets/social-card.png`.
