# [cruizba.dev](https://cruizba.dev)

My personal website, built with [Hugo](https://gohugo.io/). Theme used is
[Hugo blog awesome](https://github.com/hugo-sid/hugo-blog-awesome) with some modifications.

# Serve it locally

1. Install Hugo (extended): https://gohugo.io/installation/linux/
2. Run the following command:
```
hugo server
```

Link preview cards are generated at build time by fetching each URL's OpenGraph
metadata with `resources.GetRemote` (see `layouts/shortcodes/card.html`).
Responses are cached for 24h, so builds only hit the network when the cache is
cold or expired.
