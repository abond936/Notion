# Notion Asset Library

This folder is the live external asset host for Notion object icons and covers.

## Current Host

- repository: `abond936/Notion`
- asset root in repo: `notion-assets/`
- proven working URL pattern in this workspace:
  - `https://raw.githubusercontent.com/abond936/Notion/main/notion-assets/<path>`

GitHub Pages can also be used later, but the current working Notion cover and icon workflow is based on the raw GitHub HTTPS URLs above.

## Purpose

Use this folder as the stable external host for:

- reusable Notion page icons
- reusable Notion page covers

This avoids short-lived Notion attachment URLs and makes the asset path predictable for agent-driven object creation.

## Folder Layout

- `icons/`: hosted icon assets
- `covers/`: hosted cover images
- `index.html`: quick browser check
- `asset-map.json`: working asset map for this workspace
- `asset-map.example.json`: shape example only

## Working Rule

- Notion remains the operating surface.
- This repository is the canonical external asset host.
- Generic object templates should rely on stable icon URLs from this folder.
- Fixed-cover templates should rely on stable cover URLs from this folder.
- Generic templates that intentionally have no cover should keep no cover.

## Current Asset Classes

- base gray icon set
- light icon variants
- current populated light icon variant:
  - `notion-icon-pack-light-f1f1ef`
- domain-colored icon variants:
  - personal purple
  - social red
  - experiential blue
  - commercial green
- fixed cover images for the current special strategy and journal templates

## Agent Rule

Before setting an icon or cover in Notion:

1. Resolve the intended object/template rule from Notion canon.
2. Resolve the asset path from `asset-map.json`.
3. Build the full raw GitHub URL.
4. Apply that URL directly in Notion.
