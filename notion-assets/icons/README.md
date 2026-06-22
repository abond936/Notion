This folder hosts the live reusable icon library for the Notion workspace.

Folder names under the domain-colored packs are stable ids carried forward from the first generated set. Treat the file contents and `color-metadata.tsv` as the source of truth for the actual color, not the legacy hex embedded in the folder name.

## Current Structure

- root gray set:
  - neutral object/database icons
- `notion-icon-pack-light-f1f1ef/`
  - light icons for dark mode
- `notion-icon-pack-personal-purple-a78bfa/`
  - personal-domain icons
- `notion-icon-pack-social-red-f87171/`
  - social-domain icons
- `notion-icon-pack-experiential-blue-60a5fa/`
  - experiential-domain icons
- `notion-icon-pack-commercial-green-4ade80/`
  - commercial-domain icons

## File Rule

Within each set, the semantic filenames stay constant:

- `triangle-alternate_gray.svg`
- `circle-alternate_gray.svg`
- `view_gray.svg`
- `bullseye_gray.svg`
- `chess-knight_gray.svg`
- `checkmark-square_gray.svg`
- `document_gray.svg`
- `thought_gray.svg`
- `book_gray.svg`
- `chat_gray.svg`
- `apple_gray.svg`
- `fork-and-knife_gray.svg`
- `chart-line_gray.svg`
- `repeat_gray.svg`

Only the hosted folder changes by color family.

## Current Object Rule

- goals use the `bullseye_gray.svg` file from the domain-selected icon set
- strategies use the `chess-knight_gray.svg` file from the domain-selected icon set
- neutral database or scratch references can use the root gray set or a light set
