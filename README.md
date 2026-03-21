# Run this site locally


This repository is a Jekyll site. To run it locally you'll need Ruby and Bundler (gem install bundler), and then:

```bash
# from repository root
bundle install
bundle exec jekyll serve --livereload
```

If your shell or environment has `bundle` available, `bundle jekyll serve` also works (it delegates to the locally installed bundle).

Notes:
- If you use Ruby 3+, `webrick` is included in the Gemfile so `jekyll serve` will run.
- If you want to match GitHub Pages' environment, consider swapping the Gemfile to use the `github-pages` gem instead.

Plugins in this repository's `Gemfile`:

- `jekyll-feed` — generates an RSS/Atom feed for your posts.
- `jekyll-seo-tag` — adds SEO meta tags to pages.

If you prefer the exact GitHub Pages environment, I can replace the Gemfile with one that uses `github-pages` (it pins many plugins). Otherwise the current Gemfile matches the Jekyll setup you shared.
