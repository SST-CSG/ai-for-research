# AI for research

Guides for researchers at the School of Science & Technology, City St George's, University of London, on using Claude in research.

Published at https://sst-csg.github.io/ai-for-research/

## What is here

| Path | Page |
| --- | --- |
| `index.html` | Front page that lists the guides |
| `setup/index.html` | Setting up Claude for your research |
| `proposals/index.html` | Writing proposals with Claude |
| `coding/index.html` | Coding with Claude |
| `fonts/` | The font files, `fonts.css` and the font licences |
| `.nojekyll` | Tells GitHub Pages to serve the files exactly as they are |

Each page is one HTML file that carries its own styles, its script and the logos. Only the fonts are shared. The pages set no cookies, use no analytics and load nothing from other sites.

## Publishing

The site is served by GitHub Pages from the `main` branch. This is set under **Settings > Pages > Deploy from a branch**, with branch `main` and folder `/ (root)`. Every commit to `main` is live within a few minutes. There is no build step.

## Editing a page

1. Open the file on github.com and click the pencil icon.
2. Use the editor's search (Ctrl+F or Cmd+F) to find a phrase from the page, and change the text between the tags.
3. Click **Commit changes**.

The very long lines that start with `data:image` are the logos. Leave them as they are. They make the file large, so the editor can be slow to open.

The pages reuse a few building blocks. To add one, copy an existing block and change its text:

- `figure class="chat"`: a chat window with a prompt and an example reply.
- `details class="fold"`: reference material that opens when clicked.
- `ol class="route"`: the numbered route under the banner. Each step links to a section by its `id`.

## Adding a guide

Copy one of the guide folders, rename it, edit its `index.html`, and add a list item for it in the front page `index.html`.

## Keeping the guides accurate

- Each guide states the date its facts were checked, under the title and in its Sources section. When you check a guide again, update both dates.
- Product details and funder policies on AI change quickly. The funder policies in the proposals guide deserve a fresh check before each funding round.
- The replies inside the chat windows are examples written for the guides, with invented call details, results and data. Each one carries an "Example" tag. They are not transcripts.
- Two points in the coding guide were written from the documentation and have not been tested on Hyperion: connecting the desktop app through the jump host, and running the Claude Code extension for VS Code over Remote - SSH.

## Licences

Fira Sans and IBM Plex are distributed under the SIL Open Font License 1.1. The licence texts are in `fonts/`. The logos belong to City St George's, University of London, and are used with the University's permission.
