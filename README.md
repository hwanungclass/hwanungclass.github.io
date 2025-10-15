
# Quarto Course Website Starter

This is a minimal Quarto website for hosting lecture videos and notes.

## Quick Start

1) Install Quarto: https://quarto.org/docs/get-started/
2) Preview locally:
```bash
quarto preview
```
3) Render the site (optional):
```bash
quarto render
```
4) Publish to GitHub Pages:
```bash
quarto publish gh-pages
```
(You will be prompted to log in to GitHub and select a repo on first publish.)

## Adding a Lecture

- Create a new file under `lectures/lecture02.qmd`.
- Add the page to the menu in `_quarto.yml` under `website.navbar.left[Lectures].menu`.
- Commit and push; publishing will update the live site.
