# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview
Personal portfolio website for Josue Gonzalez Zaldivar, a game developer. Static HTML/CSS/JS site deployed via GitHub Pages.

## Project structure
- `index.html` — Main portfolio page (current, English)
- `contact.html` — Contact info and social links
- `more-projects.html` — Extended project gallery
- `maximum-football.html` — Detailed page for the Maximum Football project
- `index.css` — Single shared stylesheet for all current pages
- `index.js` — jQuery-based JS, only used by legacy pages

## Legacy pages (outdated, not linked from current nav)
- `index-EN.html`, `mastrabajo.html` — Older English/Spanish pages, reference jQuery + Animate.css + Font Awesome CDNs, and use `index.js`
- `index-old.html`, `index-old.css` — Even older version

## How to preview
Open any `.html` file directly in a browser. No build step, no dev server, no package manager required.

## Design notes
- Dark theme (`#1a1a1a` backgrounds, `#e0e0e0` text) with a purple body background (`hsl(263 100 50)`)
- Responsive via media queries in `index.css` at 768px and 480px breakpoints
- Navigation is duplicated across all pages — when adding a new page, update the `<nav>` block in every HTML file
- `index.js` uses jQuery (`$`) and is only relevant to the legacy pages; current pages don't load it
- CV/resume: `files/CV_4.pdf`
