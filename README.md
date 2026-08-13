<!-- markdownlint-disable MD013 -->

# Apostol Apostolov Personal Site

A responsive, single-page personal-site placeholder built with plain HTML and CSS for direct static hosting.

![HTML](https://img.shields.io/badge/HTML5-static-E34F26)
![CSS](https://img.shields.io/badge/CSS3-responsive-1572B6)
![Build](https://img.shields.io/badge/build-none-4C1)

This repository contains a lightweight portfolio shell with sections for an introduction, experience, projects, and contact details. It deliberately has no framework, package manager, or build pipeline. The current biography, work history, projects, availability statement, and email address are placeholders and must be replaced before the site is published as a real personal profile.

<!-- Product proof needed: capture the finished homepage at desktop and mobile widths after real profile content replaces the placeholders. -->

## Current Status

- **The page shell is complete.** The responsive navigation, hero, timeline, project cards, contact section, and footer are implemented in plain HTML and CSS.
- **The visible content is placeholder material.** Biography, experience, projects, links, availability, and contact details still need real portfolio information.
- **There is no release or package version.** This is a static site source repository, so status is more useful here than a versioned What's New block.

## Features

- **A focused landing page.** The hero introduces the owner and provides direct links to the work and contact sections.
- **Clear portfolio sections.** About, experience, projects, and contact content each have a distinct place in the page hierarchy.
- **Responsive layouts.** Grids, navigation, typography, cards, and the timeline collapse into a single-column mobile presentation below 700 pixels.
- **Semantic page structure.** Landmarks, labelled navigation, section headings, descriptive links, and visible focus states support keyboard and assistive-technology use.
- **No build tooling.** The browser loads `index.html` and `styles.css` directly, with Google Fonts requested at runtime.

## Quick Start

Open `index.html` directly in a browser, or serve the folder with any static file server. For example:

```bash
npx serve .
```

Then open the local address printed by the server.

## Publish with Cloudflare Pages

Create a Pages project from this repository with these settings:

| Setting | Value |
| --- | --- |
| Production branch | `main` |
| Framework preset | None |
| Build command | Leave empty |
| Build output directory | `/` |

No environment variables are required. Any static host that serves the repository root can use the same files.

## Replace Before Publishing

Review every placeholder in `index.html`, especially:

- the hero introduction and availability note;
- both experience entries and their dates;
- all three project cards and links;
- the biography and positioning copy;
- `hello@example.com` in the contact link;
- the page description, copyright year, and footer wording.

The current project links point back to the contact section rather than to real case studies. The site also loads DM Mono and Manrope from Google Fonts, so use local font files or a system stack if the deployment must avoid third-party requests.

## Structure

```text
index.html   Page content and semantic structure
styles.css  Color tokens, typography, layout, interactions, and responsive rules
README.md   Setup and publication notes
```

## License

This repository does not currently include a license file. Do not assume permission to reuse or redistribute the design until a license is added.
