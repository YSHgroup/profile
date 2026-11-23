# David Chan — AI/ML Engineer Portfolio

A responsive, single-page portfolio for presenting David Chan's background, AI/ML interests, selected projects, and online profiles. It is built with plain HTML and CSS and requires no build step or runtime dependencies.

## Links

- **Live portfolio:** [yshgroup.github.io/profile](https://yshgroup.github.io/profile)
- **GitHub:** [YSHgroup](https://github.com/YSHgroup)
- **Hugging Face:** [ysh-david](https://huggingface.co/ysh-david)
- **Reddit:** [David-dev100](https://www.reddit.com/user/David-dev100)
- **Bluesky:** [david-dev100.bsky.social](https://bsky.app/profile/david-dev100.bsky.social)
- **Mastodon:** [@david_chan](https://mastodon.social/@david_chan)
- **Canonical portfolio:** [yshintro.netlify.app](https://yshintro.netlify.app/)

## Features

- Sections for the introduction, about, skills and interests, selected work, profiles, and contact
- Responsive layout with accessible navigation and a skip-to-content link
- SEO metadata, Open Graph and Twitter cards, and Schema.org structured data
- Sitemap, robots directives, favicon, and social-sharing image
- Static files with no framework, build step, or runtime dependencies

## Project structure

```text
.
├── index.html              # Page content, metadata, and structured data
├── assets/
│   ├── css/
│   │   └── styles.css      # Layout, responsive rules, and visual styles
│   ├── icons/
│   │   └── favicon.svg
│   └── images/
│       └── og-image.png    # Social-sharing preview image
├── robots.txt
├── sitemap.xml
├── _redirects               # Canonical-host 301 redirects for Netlify
└── _headers                # Netlify-specific response headers (not used by GitHub Pages)
```

## Preview locally

No installation or build command is required. Open `index.html` in a browser, or serve the project root using a local static-file server. For example, with the **Live Server** extension in VS Code, open `index.html` and choose **Open with Live Server**.

The page loads Google Fonts and social icons from external services, so those resources require an internet connection.

## Deploy

The source is published on [GitHub Pages](https://yshgroup.github.io/profile). The canonical production domain is [https://yshintro.netlify.app/](https://yshintro.netlify.app/); keep canonical, Open Graph, structured data, sitemap, and redirects aligned with that domain.

To publish changes, push them to the repository's configured GitHub Pages source. In the repository settings, open **Pages** and select the appropriate branch and folder (usually the repository root). Since this is a plain HTML/CSS site, no build command is needed. GitHub Pages does not process the Netlify-specific `_headers` file.

## Updating content

- Edit page content, profile links, and SEO metadata in `index.html`.
- Edit layout and styling in `assets/css/styles.css`.
- Replace the favicon or social preview image in `assets/icons/` or `assets/images/`, updating references in `index.html` and `sitemap.xml` if filenames or URLs change.
- Keep the canonical URL, structured data, sitemap, and social metadata aligned with the production domain.
