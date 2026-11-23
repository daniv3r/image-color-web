# Agent Guidelines (website)

Read [README.md](README.md) first: it covers structure, the App Store link, screenshot updates and local preview. Git rules are in the root [AGENTS.md](../AGENTS.md).

## Rules

- The site is Jekyll for GitHub Pages. Pages: `index.html`, `privacy.md`, `support.md`, `terms.md`.
- The App Store link comes from `app_store_url` in `_config.yml`.
- Privacy commits (`[Privacy]`) show the policy text being updated alongside analytics changes; check that history before editing policy text.
- Screenshots come from `marketing/app-store/raw-captures/en-US/`; regenerate with the `sips` command in the README.
