# LJT-Homepage

Personal academic website for Junteng Liu, forked from [Academic Pages](https://github.com/academicpages/academicpages.github.io).

The site contains two pages:

- **About**: personal details, research interests, education, research experience, honors, all six publications, and contact information.
- **Publications**: the same six publications, with full author lists, venues, and years.

## Content

- `_pages/about.md`: About page.
- `_pages/publications.html`: Publications page.
- `_data/publications.yml`: structured publication records for the Publications page.
- `_data/navigation.yml`: site navigation.
- `_config.yml`: site identity and contact links.

Publication records use years only. No separate publication-detail pages, blog, portfolio, teaching, talks, or CV pages are published. Original template examples outside the two selected pages are excluded from the build.

## GitHub Pages activation

GitHub Pages is not yet enabled for this fork. The available GitHub integration can update files and run workflows, but it does not expose the repository's Pages activation setting.

To publish, open **Settings → Pages → Build and deployment**, select **GitHub Actions** as the source, and run the **Deploy Academic Pages template site to Pages** workflow. The configured project-site URL is `https://spallaselvylt93422.github.io/LJT-Homepage/`.

The separate **Jekyll build** workflow validates the site without requiring Pages activation. It checks both pages, all publication titles and author lists, and the two-page sitemap.

## Local preview

Install the Ruby dependencies with `bundle install`, then run `bundle exec jekyll serve --baseurl /LJT-Homepage`.

The original theme license and attribution are retained.
