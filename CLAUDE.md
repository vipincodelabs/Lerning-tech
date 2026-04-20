# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A static learning portal for personal curriculum on JavaScript, TypeScript, ES6, Docker, Linux, and Git/GitHub. No build tools, no dependencies, no backend — pure HTML/CSS files opened directly in a browser.

## Running the Site

Open `index.html` directly in a browser, or serve with any static file server:

```bash
# Python (built-in)
python -m http.server 8080

# Node (if available)
npx http-server .
```

## Architecture

```
index.html                  # Hub page — links to all learning modules
javascript-mastry.html      # Fully built JS curriculum (2000+ lines)
typescript.html             # Beginner + Intermediate TS curriculum (~2000 lines)
es6.html                    # Fully built ES6 curriculum (~1200 lines)
react-hooks.html            # Placeholder (empty)
docker.html                 # Placeholder (empty)
linux.html                  # Placeholder (empty)
git-hub.html                # Placeholder (empty)

_promts/                    # Mentor prompt templates (Markdown)
  javascript.md             # 13-phase JS learning roadmap
  typescript.md             # 3-level TS roadmap (Beginner → Advanced)
  es6.md                    # 11-topic ES6 roadmap
  docker.md                 # 3-level Docker roadmap
  linux.md                  # 3-level Linux roadmap
  git-hub.md                # Git/GitHub roadmap
  js-best-part-for-react.md # JS concepts most relevant for React
  react-hooks.md            # React hooks learning roadmap
```

## Design System

All pages share a consistent dark-theme design defined inline in each HTML file:

- **Colors:** Purple accent `#7c6af7`, teal `#5eead4`, orange `#fb923c`, dark background `#0f0f23`
- **Fonts:** Segoe UI for body; Cascadia Code / Fira Code / JetBrains Mono for code blocks
- **Layout:** Two-column (sidebar nav + main content) on content pages; responsive CSS Grid on `index.html`

CSS is embedded directly in `<style>` tags — there is no external stylesheet or CSS preprocessor.

## Content Pages Pattern

Each content page (e.g., `javascript-mastry.html`) follows this structure:
- Sidebar with topic navigation and progress tracking
- Main content area with learning phases/sections
- Inline code blocks with dark-theme syntax-style coloring
- No JavaScript — all interaction via CSS `:hover` / `:target`

## Mentor Prompts (`_promts/`)

These Markdown files define AI mentor personas to feed into Claude or other AI tutors. They specify teaching methodology, response format, and topic sequencing. They are not rendered by the site — they are standalone prompt documents.
