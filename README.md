# Moonjunk Workshop website

Public introduction for **Moonjunk Workshop / 달빛 고물상**, hosted at
[moonjunk.kugora.ng](https://moonjunk.kugora.ng/).

## Maintain the complete website

- `index.html`, `en/`, `ja/`, and `zh-Hant/` contain the four language editions.
- `style.css` styles both the game introduction and the information pages.
- `assets/` contains the site icon and original development gameplay captures.
  Each language uses its corresponding screenshots. The hero is a decorative
  CSS illustration, labelled separately from actual gameplay.
- Privacy, support and account deletion pages contain the current pre-release
  notices. Preserve their content when changing the visual design.
- Keep `CNAME`, `.nojekyll`, and `app-ads.txt` when publishing.

GitHub Pages publishes this repository's `main` branch from the root. Publish
the complete site, including the stylesheet and images. Do not replace it with
a text-only subset when moving hosting or updating notices.

There is no JavaScript, external font, analytics script, contact form or build
step. For local preview, run `python3 -m http.server 4176 --bind 127.0.0.1` in
this directory. Review desktop and narrow mobile layouts, all four languages,
legal links and full-size image links before publishing. After deployment,
verify the live HTTPS pages and image assets against the committed files.

Only reviewed public website content belongs in this repository. Game source,
test records, credentials and personal data belong outside it. Publishing this
website does not publish the game or enable accounts, purchases or advertising.
