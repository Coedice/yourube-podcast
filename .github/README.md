# Youtube Podcast

A tool for converting your YouTube channel into a podcast feed.

## How to Use

1. Clone this repo
2. Configure your podcast's settings in `_config.yml`
3. Set `SOURCE_URL` to your podcast's URL in `Makefile`
4. Execute `make update`
5. See the podcast feed in `_site/podcast.rss`

## Hosting

This tool is designed to be convenient to use with GitHub Pages.

To use it with GitHub Pages:

1. Fork this repo
2. Enable GitHub Pages in the repo's settings
3. Generate the podcast feed (through `make update`)
4. Commit and push the changes.
