# Notion Asset Library for GitHub Pages

This folder is a Pages-ready asset library for Notion icons and covers.

## Purpose

Use GitHub Pages as the stable HTTPS host for:

- reusable Notion page icons
- reusable Notion page covers

This avoids short-lived or UI-only asset paths and gives the agent a predictable URL pattern.

## Recommended Repository

Create a dedicated repository such as:

- `notion-assets`
- `notion-asset-library`

Recommended visibility:

- public, if the images are not sensitive

GitHub Pages then serves files like:

- `https://<owner>.github.io/<repo>/icons/<file>.svg`
- `https://<owner>.github.io/<repo>/covers/<file>.png`

## Folder Layout

- `icons/`: page icon assets
- `covers/`: cover images
- `index.html`: simple browser check
- `asset-map.example.json`: optional mapping structure for Notion-side cataloging

## Initial Workflow

1. Create the GitHub repository.
2. Copy this folder's contents into the repository root.
3. Enable GitHub Pages from the default branch root.
4. Upload or commit new cover files into `covers/`.
5. Use the resulting HTTPS URLs as Notion page covers.

## Notes

- Icons can continue to be set either from uploaded assets or from the existing local icon workflow.
- Covers should use normal hosted image files such as PNG or JPG.
- The agent should treat this repository as the canonical external asset host, while Notion remains the operating surface.
