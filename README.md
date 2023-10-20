# [cruizba.dev](https://cruizba.dev)

My personal website, built with [Hugo](https://gohugo.io/). Theme used is
[Hugo blog awesome](https://github.com/hugo-sid/hugo-blog-awesome) with some modifications.

# Serve it locally

1. Install Hugo: https://gohugo.io/installation/linux/
2. Run ogjson, a service which serves an API which returns JSON with OpenGraph metadata to generate links with card previews ([More info](https://akimon658.github.io/en/p/2022/hugo-url-cards/)):
```
docker run -d --rm -p 8080:8080 akimon658/ogjson:1.0.0
```

3. Run the following command:
```
hugo server --noHttpCache
```
