Millennium is a small early-2000s-style Zola theme for a personal site, blog and photos. No JavaScript. Needs Zola 0.23.6 or newer.

The theme lives at the repository root (`templates/`, `static/`, `theme.toml`), so it can be used as a theme directly:

    git submodule add https://github.com/durnwalder/millennium themes/millennium

then set `theme = "millennium"` in your site's config.

This repository is also its own demo site: `content/` and `zola.toml` build with the root templates, no `theme` line needed. Run `zola serve` to preview or `zola build` to build.

Sites using the theme must set `extra.blog_section` and `extra.gallery_section`; `theme.toml` supplies them as defaults.
