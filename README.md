# Awesome Apps

A Jekyll site with a landing page of small browser-based ward tools, hosted on Netlify.

## Apps

| App | Folder |
| --- | --- |
| Ward manager time log | `ward_logger/` |

## Add an app

1. Put the app in its own folder as `<id>/index.html`. A standalone HTML file without front matter is copied as-is.
2. Add an entry to `_data/apps.yml` with the same `id`. It appears on the landing page and in the **All apps** menu.

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

## Deploy on Netlify

Connect this repository in Netlify (**Add new site → Import an existing project**). `netlify.toml` sets the build command (`bundle exec jekyll build`) and publish folder (`_site`), so no extra settings are needed.
