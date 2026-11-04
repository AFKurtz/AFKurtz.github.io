# Andrew Kurtz — Personal Website

This is the source for [afkurtz.github.io](https://afkurtz.github.io/), a static portfolio documenting my background in engineering and physics, my completed work, and current and future projects.

## Structure

```text
.
├── index.html                 Home
├── about_me.html              Background and interests
├── projects.html              Project categories
├── finished_projects.html     Completed work
├── ongoing_projects.html      Work in progress
├── future_projects.html       Plans and ideas
└── assets/
    ├── css/site.css           All website styles
    ├── images/                Page photos and favicons
    ├── files/                 Downloadable résumé
    └── parallax/              Retained for a future effect
```

## How it works

The site uses regular HTML and a single handwritten CSS file. There is no build process, JavaScript framework, package manager, or generated CSS. All page links and images use relative URLs, so the site can be opened locally or hosted from the repository root on GitHub Pages.

The original visual layout and colors have been recreated in `assets/css/site.css`. The photos, content, and overall page organization are preserved. The homepage icons are embedded SVGs.


## Updating the design

- Change colors, typography, spacing, and responsive breakpoints in `assets/css/site.css`.
- Edit content directly in the corresponding HTML page.
- Replace pictures in `assets/images/` and update their paths in the HTML or CSS.
- `assets/parallax/` is intentionally retained for future animation work; it is not loaded by the current pages.
