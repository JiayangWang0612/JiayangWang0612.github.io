# Updating your GitHub repository

This ZIP is a cleaned source snapshot of `JiayangWang0612.github.io`. It keeps the original Academic Pages theme and adds your academic content. It does not include Git history or a generated `_site/` folder.

## What changed

- Updated the biography and sidebar, including Ph.D. candidate status.
- Added the JSM oral presentation (August 2025) and MBL workshop (May 2026).
- Added the 2026 arXiv preprint with its authors, citation, abstract-page link, and PDF link.
- Added Research, Publications, Experience, and Teaching navigation.
- Replaced sample teaching entries with your Fall 2023 and Spring 2024 STAT 324 experience.
- Removed fictional publications, talks, teaching records, the dummy CV, sample blog posts, demo pages, sample downloads, and unused demo assets.
- Fixed teaching dates, removed missing icon references, and enabled an automatically generated sitemap.
- Preserved your photographs, cartoon illustration, research figure, contact information, site-verification file, and theme attribution.

## Replace the source in your existing repository

Use your existing `JiayangWang0612.github.io` repository. Do not create a nested `JiayangWang0612.github.io/` folder inside it.

1. Keep a backup of your current repository before replacing its files.
2. Unzip the archive. Copy the **contents** of its `JiayangWang0612.github.io` folder into the root of your existing repository, replacing matching files. Include `.gitignore` and the folders whose names begin with `_`.
3. Delete the old template paths listed below. They are intentionally absent from this ZIP. Keep the existing repository's `.git` folder: it contains your Git history and connection to GitHub.
4. Review the changes in GitHub Desktop or your usual Git client, then commit and push to the branch that currently publishes your website. If you use GitHub's browser upload, upload the extracted files and separately delete the old template paths; uploading a ZIP by itself will not update the site.
5. Check the Pages build/deployment result on GitHub and open the updated site. A successful GitHub Pages build is the final deployment check.

Do not delete any additional personal files you added to GitHub after creating the original ZIP. Merge those changes separately.

GitHub's [publishing-source documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) explains where to check the branch and folder used by Pages.

## Validation

The configuration and content metadata were parsed, navigation and local asset references were checked, changed Liquid templates passed a syntax check, and the complete theme SCSS compiled successfully. The source archive was checked for sample content and archive clutter.

A full Jekyll build and browser preview were not run because Ruby and Bundler were unavailable in the editing environment. Run the preview commands in `README.md` or check the GitHub Pages build after committing the update.

## Old template paths to delete

The following paths were present in the supplied ZIP and are absent from this cleaned version. Directories can be deleted in one operation when they contain only these sample files.

- `.github/ISSUE_TEMPLATE/bug_report.md`
- `.github/ISSUE_TEMPLATE/feature_request.md`
- `CONTRIBUTING.md`
- `_data/authors.yml`
- `_data/comments/layout-comments/comment-1470944006665.yml`
- `_data/comments/layout-comments/comment-1470944162041.yml`
- `_data/comments/markup-syntax-highlighting/comment-1470969665387.yml`
- `_data/comments/welcome-to-jekyll/comment-1470942205700.yml`
- `_data/comments/welcome-to-jekyll/comment-1470942247755.yml`
- `_data/comments/welcome-to-jekyll/comment-1470942265819.yml`
- `_data/comments/welcome-to-jekyll/comment-1470942493518.yml`
- `_drafts/post-draft.md`
- `_pages/archive-layout-with-content.md`
- `_pages/category-archive.html`
- `_pages/collection-archive.html`
- `_pages/cv.md`
- `_pages/markdown.md`
- `_pages/non-menu-page.md`
- `_pages/page-archive.html`
- `_pages/tag-archive.html`
- `_pages/talkmap.html`
- `_pages/talks.html`
- `_pages/terms.md`
- `_pages/year-archive.html`
- `_portfolio/portfolio-2.html`
- `_posts/2012-08-14-blog-post-1.md`
- `_posts/2013-08-14-blog-post-2.md`
- `_posts/2014-08-14-blog-post-3.md`
- `_posts/2015-08-14-blog-post-4.md`
- `_posts/2199-01-01-future-post.md`
- `_publications/2009-10-01-paper-title-number-1.md`
- `_publications/2010-10-01-paper-title-number-2.md`
- `_publications/2015-10-01-paper-title-number-3.md`
- `_publications/2024-02-17-paper-title-number-4.md`
- `_talks/2012-03-01-talk-1.md`
- `_talks/2013-03-01-tutorial-1.md`
- `_talks/2014-02-01-talk-2.md`
- `_talks/2014-03-01-talk-3.md`
- `_teaching/2014-spring-teaching-1.md`
- `_teaching/2015-spring-teaching-2.md`
- `files/paper1.pdf`
- `files/paper2.pdf`
- `files/paper3.pdf`
- `files/slides1.pdf`
- `files/slides2.pdf`
- `files/slides3.pdf`
- `images/3953273590_704e3899d5_m.jpg`
- `images/500x300.png`
- `images/bio-photo-2.jpg`
- `images/bio-photo.jpg`
- `images/browserconfig.xml`
- `images/editing-talk.png`
- `images/foo-bar-identity-th.jpg`
- `images/foo-bar-identity.jpg`
- `images/image-alignment-1200x4002.jpg`
- `images/image-alignment-150x150.jpg`
- `images/image-alignment-300x200.jpg`
- `images/image-alignment-580x300.jpg`
- `images/manifest.json`
- `images/mstile-144x144.png`
- `images/mstile-150x150.png`
- `images/mstile-310x150.png`
- `images/mstile-310x310.png`
- `images/mstile-70x70.png`
- `images/paragraph-indent.png`
- `images/paragraph-no-indent.png`
- `images/safari-pinned-tab.svg`
- `markdown_generator/PubsFromBib.ipynb`
- `markdown_generator/publications.ipynb`
- `markdown_generator/publications.py`
- `markdown_generator/publications.tsv`
- `markdown_generator/pubsFromBib.py`
- `markdown_generator/readme.md`
- `markdown_generator/talks.ipynb`
- `markdown_generator/talks.py`
- `markdown_generator/talks.tsv`
- `sitemap.xml`
- `talkmap.ipynb`
- `talkmap.py`
- `talkmap/leaflet_dist/MarkerCluster.Default.css`
- `talkmap/leaflet_dist/MarkerCluster.css`
- `talkmap/leaflet_dist/leaflet.markercluster-src.js`
- `talkmap/leaflet_dist/leaflet.markercluster.js`
- `talkmap/leaflet_dist/screen.css`
- `talkmap/map.html`
- `talkmap/org-locations.js`
