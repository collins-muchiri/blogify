# Blogify — Modern Blogging Platform

![category](https://img.shields.io/badge/category-web-platform-EC4899?style=flat-square) ![language](https://img.shields.io/badge/language-HTML-2563EB?style=flat-square) ![license](https://img.shields.io/badge/license-MIT-16A34A?style=flat-square) ![maintenance](https://img.shields.io/badge/maintenance-active-16A34A?style=flat-square) ![repo](https://img.shields.io/badge/repo-blogify-111827?style=flat-square)

---

*A modern blogging platform with clean design, built with plain HTML, CSS and JavaScript.*

## Overview

Blogify is a lightweight blogging front-end built without frameworks: static
HTML for structure, CSS for the presentation system, and JavaScript for the
interactive layer. The point of the no-build approach is durability — the site
is a set of files that any static host can serve as-is, with nothing to
compile, nothing to version-lock, and nothing to break between machines. It
deploys to Vercel out of the box (a `vercel.json` is included) and is live at
the link below.

## Features

- **Framework-free** — plain HTML/CSS/JS that renders from any static file server.
- **Clean design system** — a consistent typography and layout system defined entirely in CSS.
- **Vercel-ready** — ships with `vercel.json` and deploys unchanged; live at [blogify-three-taupe.vercel.app](https://blogify-three-taupe.vercel.app).
- **Security policy** — a `SECURITY.md` is included for responsible disclosure.

## Technology stack

| Component | Technology | Why |
| --- | --- | --- |
| Structure | HTML | Universal, dependency-free markup. |
| Presentation | CSS | The whole design system in one place. |
| Behavior | JavaScript | Interactivity without a build step. |

## Getting started

```bash
git clone https://github.com/collins-muchiri/blogify.git
cd blogify
python3 -m http.server 8080   # or open Index.html directly, or serve with any static server
```

Then open <http://localhost:8080>.

## Usage

Open the site, browse the post list, and read a post — the layout adapts down
to phone widths. To publish changes, edit the HTML/CSS/JS and redeploy; on
Vercel a push to the connected branch is enough.

## Status and roadmap

Working today: the static front-end and its Vercel deployment. Next: turning
the static pages into a small content pipeline. Explicitly out of scope: a
server-side backend — Blogify is intentionally static.

## Contribution and license

Issues and pull requests are welcome — please open an issue first for
substantive changes. This project is released under the MIT License.
