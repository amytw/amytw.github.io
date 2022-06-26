# amytw.github.io

Github-based website

### Dev

* Run hugo server locally: `hugo server -D` (`-D` for showing draft pages)

### Debug log

1. Auto deploy website
   - [This tutorial](https://www.zoeydc.com/zh/posts/2021-05-23-hugo-website_github-pages_custom-domain/) is helpful
   - Make sure to have `hugo version` and `extended` flag correctly configured in `config.yaml`.
2. `hugo server` serves empty site
   - It means the theme is not correctly loaded. Try `git submodule update --init --recursive` to force loading the themes/stack.