# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML teaching site for a Scratch programming course at 銘傳國中 (Ming Chuan Junior High School), aimed at 8th-grade students. All content is in Traditional Chinese (zh-TW). There is no build system — every file is a self-contained HTML page with all CSS embedded inline in `<style>` tags.

## Structure

- **`index.html`** — Main course portal, organized into two tabs (8th grade Semester 1 and 2)
- **`C01.html` – `C13.html`** — Sequential Scratch lessons for Semester 1 (geometry drawing → loops → conditionals → variables → functions → lists)
- **`algorithm01.html`**, **`algorithm02.html`**, **`linear_search.html`** — Algorithm lessons (linear search, binary search) for Semester 2
- **`zoo.html`**, **`zoo2.html`** — Psychological test game lessons using functions and lists
- **`basic.html`**, **`variable.html`**, **`framework.html`**, **`funcIllustration.html`** — Supplementary/concept pages
- **`course/act1.html`**, **`course/act2.html`** — Interactive whiteboard activity materials (with image assets in `course/`)
- **`image/`** — Shared images referenced across multiple pages (screenshots, diagrams, `.sb3` example files)
- **`midterm.html`**, **`review.html`**, **`introduction.html`**, **`videomap.html`** — Exam prep, review, and navigation pages

## Conventions

Each teaching page follows a consistent pattern:
- `lang="zh-TW"`, `charset="UTF-8"`, `font-family: 'Microsoft JhengHei'`
- A full-bleed gradient background with a centered white `.container` (max-width ~1000–1200px)
- A colored `.header` block at the top with the lesson title
- All CSS is self-contained within `<style>` — there are no external stylesheets or JS frameworks
- Step-by-step instruction sections use screenshot images from `image/` with Chinese-language alt text

When adding or editing a lesson page, match the visual style (gradient header, card layout, section blocks) of the existing pages in the same semester grouping. New pages for Semester 2 algorithm/web topics use cooler blue/teal gradients; Semester 1 Scratch lesson pages use warmer orange/purple gradients.
