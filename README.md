# John Saleeb: Personal Website

Source for **[saleebj.github.io](https://saleebj.github.io)**, built with Jekyll and hosted free on GitHub Pages.

## How it works

- This repository is named `saleebj.github.io`, which matches the GitHub username, so GitHub Pages serves it at the root address above.
- Every change merged into `main` is rebuilt and published automatically, usually within 1 to 2 minutes.
- Hosting is free because the repository is public. There is no custom domain and nothing to renew.

## Where things live

| What | File |
| --- | --- |
| Name, email, LinkedIn, Google Scholar, CV link, menu | `_config.yml` |
| Home page | `index.md` |
| About (education timeline, Ubben Fellowship) | `about.md` |
| Research | `research.md` (old `/projects/` link redirects here) |
| Personal Projects (podcasts, hobbies) | `personal.md` |
| Publications | `publications.md` (source of truth: [Google Scholar](https://scholar.google.com/citations?user=4CvPldMAAAAJ&hl=en)) |
| Colors, fonts, layout | `assets/css/main.scss` |
| Photos and link preview image | `assets/images/` |

Design: Libre Caslon Text headings, Plus Jakarta Sans body, deep navy `#2f4a6d` primary accent.

## Editing

The quickest way to make a small change is to open the file on GitHub, click the pencil icon, edit, and commit to `main`.

To preview locally:

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.
