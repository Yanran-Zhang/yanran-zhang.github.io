# Yanran Zhang — Academic Website

Source for the personal academic website of **Yanran Zhang** (Ph.D. student, Department of Automation,
Tsinghua University). Built with [Jekyll](https://jekyllrb.com/) and deployed through
[GitHub Pages](https://pages.github.com/).

🌐 Live site: `https://yanran-zhang.github.io/`

## Template credit

This site is built on the **[academic-homepage](https://github.com/luost26/academic-homepage)** template
by [luost26](https://github.com/luost26). Many thanks for the excellent starting point.

## Structure

| Path | Purpose |
|------|---------|
| `_data/profile.yml` | Bio, contact info, education, and honors |
| `_data/authors.yml` | Author name rendering rules (bold / link) for publications |
| `_data/navigation.yml` | Top navbar entries |
| `_publications/` | One Markdown file per paper (front matter + abstract) |
| `_news/` | Time-ordered news items shown on the home page |
| `assets/images/covers/` | Paper teaser / cover figures |
| `assets/images/etc/wechat.png` | WeChat QR code |

Each publication entry links directly to the canonical code repository on GitHub.

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

Then open the URL printed in the terminal.

## Notes

- The base URL is set to `""` in `_config.yml`, which is correct for a `<username>.github.io` Pages site.
- A personal portrait can be added at `assets/images/photos/portrait.jpg` and enabled in `_data/profile.yml`.
