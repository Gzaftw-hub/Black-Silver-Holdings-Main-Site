# Black Silver Holdings Main Site

Static site for Black Silver Holdings, hosted on Cloudflare Pages project `blacksilverholdings-demo` (https://blacksilverholdings-demo.pages.dev).

```bash
python3 -m http.server 4174 --directory public
npx wrangler pages deploy public --project-name blacksilverholdings-demo --branch main
```

## TODO

- Social links: Instagram, LinkedIn and X icons are placeholders (`href="#"`, class `soon`, dimmed) in `public/*.html` (hero on `index.html` and footer on every page). Only YouTube is linked. Replace with real URLs, remove the `soon` class, add `target="_blank" rel="noopener"`, and add the URLs to `sameAs` in the JSON-LD in `public/index.html`.
- Real domain: replace demo URLs in `index.html`, `llms.txt`, `robots.txt`, `sitemap.xml`, attach to the Pages project, then add to Google Search Console (mfcchat9@gmail.com) and submit the sitemap.
