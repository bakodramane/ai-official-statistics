# AI for Official Statistics

**A bilingual, independent knowledge hub on AI for surveys, censuses, administrative data and official statistics, by Dramane Bako.**

- **Blog URL (after GitHub Pages activation):** https://bakodramane.github.io/ai-official-statistics/
- **English homepage:** https://bakodramane.github.io/ai-official-statistics/
- **French homepage:** https://bakodramane.github.io/ai-official-statistics/fr/accueil/
- **English articles:** /en/ · **French articles:** /fr/
- **RSS feed:** /feed.xml
- **Professional portfolio:** https://bakodramane.github.io/

This repository contains the complete historical bilingual AI blog from the professional website, including 125 post-source files and the Jekyll knowledge hub. The original post permalinks and translation metadata have been preserved. The content and site source were transferred with exact Git blob SHA matches.

## Enable GitHub Pages (one-time)

Go to this repository's **Settings → Pages → Build and deployment** and choose **Deploy from a branch**, with **Branch: main** and **Folder: /(root)**. Save. The public site can then be verified at the blog URL above.

The source is built with Jekyll and GitHub Pages, using `url: https://bakodramane.github.io` and `baseurl: /ai-official-statistics` in `_config.yml`.

## Development and validation

```bash
bundle install
bundle exec jekyll serve
bundle exec jekyll build
python3 scripts/check_site_links.py _site --baseurl /ai-official-statistics
```

GitHub Actions runs the build, project-baseurl link checker and EN/FR archive and RSS checks on updates to `main` and on pull requests.

## Editorial workflow

Post conventions (front matter, translation pairs, tags, sources, tone) are in [docs/content-guidelines.md](docs/content-guidelines.md).

The existing ChatGPT weekly bilingual AI update automation has been retargeted to this repository. It remains scheduled for Mondays at 09:00 Europe/Rome and prepares an English/French pair in a review branch without merging or publishing the posts directly. Preserve the `translation_key`, `lang`, French permalinks and source-quality controls.

## Portfolio migration dependency

The professional portfolio cutover is staged separately in [PR #34](https://github.com/bakodramane/bakodramane.github.io/pull/34). **Only merge PR #34 after this blog URL and RSS are live**, to avoid forwarding old public article URLs to an unpublished site.

The blog expresses personal views and does not represent FAO or any other institution.
