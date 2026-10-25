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

Publication records use years only. No separate publication-detail pages, blog, portfolio, teaching, talks, or CV pages are published.

## Local preview

Install the Ruby dependencies with `bundle install`, then run `bundle exec jekyll serve --baseurl /LJT-Homepage`.

The original theme license and attribution are retained.
