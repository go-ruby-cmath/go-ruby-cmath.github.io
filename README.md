<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-cmath/brand/main/social/go-ruby-cmath.png" alt="go-ruby-cmath/go-ruby-cmath.github.io" width="720"></p>

# go-ruby-cmath.github.io

The organization's institutional landing page, served at
<https://go-ruby-cmath.github.io> and built with [Hugo](https://gohugo.io). It
is a single page (custom `layouts/index.html`, capability cards driven by
`[[params.phases]]` in `hugo.toml`).

Documentation lives in a separate repository,
[go-ruby-cmath/docs](https://github.com/go-ruby-cmath/docs), served at
<https://go-ruby-cmath.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
