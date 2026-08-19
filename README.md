# arjavpoudel.github.io

Personal site and blog for Arjav Poudel, built with [Jekyll](https://jekyllrb.com/) on the [academicpages](https://github.com/academicpages/academicpages.github.io) theme (a fork of [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)).

Live at [arjavpoudel.github.io](https://arjavpoudel.github.io).

## Running locally

Requires Ruby, Bundler, and Node.

```bash
gem install bundler
bundle install
bundle exec jekyll serve -l -H localhost
```

The site will be served at `http://localhost:4000` and rebuild automatically on changes.

## Using Docker

```bash
docker build -t jekyll-site .
docker run -p 4000:4000 --rm -v $(pwd):/usr/src/app jekyll-site
```

## Structure

- `_posts/` — blog posts
- `_pages/` — standalone pages (about, CV, etc.)
- `_sass/`, `assets/css/` — styling
- `images/`, `files/` — static assets
