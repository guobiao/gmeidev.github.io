# gmei.dev

[Homepage of Guobiao Mei](https://gmei.dev/)

Source repository for my personal website and family homepages, hosted on GitHub Pages and built with [Jekyll](https://jekyllrb.com/) (Gemfile-free) using a custom responsive light/dark card layout.

## Structure

- `index.md` — Main homepage (contact, summary, experience, education, publications, and hobbies)
- `n1ui/` — Amateur radio station page (FCC call sign N1UI) with a theme-adaptive inline SVG emblem
- `jingxu/`, `april/`, & `aiden/` — Family homepages (`jingxu.gmei.dev`, `april.gmei.dev`, `aiden.gmei.dev`) sharing the structured card layout
- `_layouts/` — Default HTML layout with light/dark theme toggle, structured card support (`structured`, `nav`, and `site_brand` front matter), BibTeX copy controls, and SEO metadata
- `_includes/` — Custom HTML head partial loading Google Tag Manager (`gtm.js`)
- `assets/` — Custom stylesheet (`css/style.scss`), favicon and vector/raster logos (`images/`), and academic paper PDFs and abstract/BibTeX pages (`papers/`)
- `_config.yml` & `CNAME` — Jekyll configuration (site metadata, `jekyll-seo-tag`, tracking tag ID) and custom domain (`gmei.dev`)
