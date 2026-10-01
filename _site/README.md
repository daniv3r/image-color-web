# image-color-web

Marketing, support, privacy policy, and terms of use site for **PicNum: Paint by Number**, built with Jekyll for GitHub Pages.

The App Store badge and the nav **Download** button link to `app_store_url` in `_config.yml`. If it is left empty, the badge is replaced by a non-interactive "Coming soon" message and the Download button is hidden.

## Structure

| Path | What it is |
| --- | --- |
| `index.html` | Landing page content (hero, how it works, features, closer). Uses the `home` layout. |
| `privacy.md`, `terms.md`, `support.md` | Legal and support pages. Plain Markdown; they use the `default` layout. |
| `_layouts/home.html`, `_layouts/default.html` | Page shells for the landing page and for the Markdown pages. |
| `_includes/` | Shared `head`, `nav`, `footer`, and the App Store `badge`. |
| `assets/site.css` | All styles (design tokens, nav, footer, device frames, landing sections, legal typography). |
| `assets/mosaic.svg` | Faceted "regions and numbers" hero backdrop. Generated once from a seeded script; no JS at runtime. |
| `assets/screens/` | Web-sized copies of the App Store captures used inside the CSS device frames. |

The look follows the promo sheet in `marketing/app-store/promo-sheet/`.

## Updating screenshots

`assets/screens/*.jpg` come from the raw simulator captures in `marketing/app-store/raw-captures/en-US/` (iPhone resized to 900 px wide, iPad to 1300 px wide, JPEG quality 85):

```
sips -s format jpeg -s formatOptions 85 --resampleWidth 900 <capture>.png --out assets/screens/<name>.jpg
```

## Local preview

There is no Gemfile in this repo; GitHub Pages builds the site. To preview locally, install Jekyll (with the `minima` theme from `_config.yml`) and run:

```
jekyll serve
```

Then open http://localhost:4000.
