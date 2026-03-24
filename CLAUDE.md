# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Minimal Electron desktop app that displays a profile card UI. No framework — plain HTML/CSS/JS.

## Commands

- **Run the app:** `npm start` (runs `electron .`)
- **Install dependencies:** `npm install`

There are no test, lint, or build commands configured.

## Architecture

- `main.js` — Electron main process. Creates a `BrowserWindow` and loads `index.html`.
- `index.html` — Single-page UI with a profile card layout. Links `style.css`.
- `style.css` — All styling. Card is fixed 1280x720 with a circular avatar and a state panel.
- `package.json` — Only dependency is `electron` (devDependency).
