# AI Agent Instructions for Dacca

## Project overview
- This repository is a simple static hotel website for Dacca Palace De Luxe.
- Content is authored directly in HTML files with inline CSS and image references.
- There is no build tool, package manager, or backend service in this workspace.

## Key files
- `dacca-palace.html` — the main hotel landing page with a clean layout.
- `dacca-palace-de-luxe.html` — an alternate or updated hotel landing page with richer styling.
- `images/` — contains image assets referenced by the pages.

## What agents should know
- Edit the HTML pages directly for content, layout, and style changes.
- Keep CSS changes within the existing `<style>` blocks unless adding a new page.
- Maintain relative image paths like `images/...` and avoid external asset injection unless the user asks.
- Preserve the page structure and navigation links when adding sections.

## Common tasks
- Update hotel copy, room descriptions, offers, contact details, and local destination text.
- Add or replace images in `images/` and update `src` attributes accordingly.
- Keep markup valid HTML5 and avoid introducing JavaScript or unsupported frameworks.

## When to ask for clarification
- If the user wants to add a new page or section beyond the current two HTML files.
- If the user asks for functionality that requires a build step, backend, or scripting.
- If image assets need to be generated, optimized, or renamed.
