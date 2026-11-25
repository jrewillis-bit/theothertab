# The Other Tab

A personal Jekyll blog. Enable Settings > Pages > Deploy from a branch > main > / (root).

## Publish
Create `_posts/YYYY-MM-DD-title.md` using the example in `_drafts/example.md`. Use one category (Technology, Digital Living, Minimalism, Personal Finance, Sustainability, Film & Media, Gaming, Teaching, Photography or Life), a description and optional tags. Commit to main. Drafts are not published. Edit `_config.yml` when moving to a custom domain. No advertising or external fonts. Cloudflare Web Analytics is enabled through the public beacon token.

## Cover images
Optional post front matter: `cover: /assets/images/example.jpg` and `cover_alt: Description of the image`. Upload the image to that path. Posts without images use a simple category header.

## SEO
The sitemap regenerates with every build. Submit https://theothertab.uk/sitemap.xml in Google Search Console and Bing Webmaster Tools. Google domain verification requires the TXT record supplied by Google in Porkbun. Alternatively use URL-prefix HTML meta verification by setting `google_site_verification` in `_config.yml`; use `bing_site_verification` for Bing's meta code. Only use genuine codes. Each article's title, description and cover automatically generate canonical, Open Graph, Twitter and BlogPosting metadata. Optional `author` and `last_modified_at` can be provided in front matter. The fallback social image is `assets/social-card.png`.

## Personal pages and featured posts
Edit `now.md`, `uses.md` and `bookmarks.md` to maintain the personal pages. Mark a post `featured: true` to pin it to the homepage; if several posts are marked, the newest wins. Images within articles automatically open in a keyboard-accessible lightbox unless already linked or marked `data-no-lightbox`.

## Version 1.0
Add gallery entries to `_data/photos.yml` (src, alt, caption, album, settings). Add notes to `_notes/` with layout: default, title and date. Series posts use `series` and numeric `series_part`; use `last_modified_at` for revised posts. Set `cloudflare_analytics_token` to the public beacon token supplied by Cloudflare Web Analytics; leave blank to disable analytics. PWA provides an offline fallback, not full offline article caching. Scheduled future posts require a rebuild after their publication date.

## Still Worth It? long-term reviews
The series hub lives at `/still-worth-it/`. Add a new post with `series: "Still Worth It?"` and the next unused positive integer `series_part`. Part 0 is reserved for the introductory article and uses `series_intro: true`. The hub and article series navigation populate automatically. Use `_drafts/still-worth-it-review.md` for the review structure; fill in actual ownership details and mark unknowns rather than inventing figures. Use the series artwork at `/assets/images/still-worth-it.svg` when no suitable original photograph is available. The homepage carousel continues to use its existing curated selections.
