# Claude Code instructions — MUHSIN

You are working on MUHSIN, a personal creative portfolio for a photographer and AI creator.

## Product direction
- Premium, minimal, cinematic dark visual identity with a restrained lime accent.
- Arabic is the default language and must use RTL layout; English toggle must remain functional and switch to LTR.
- The owner publishes work; visitors browse only. Do not add public user accounts or public posting.
- Portfolio categories: photography, video/films, AI art, and Lightroom/photo editing.
- Support portrait and landscape media layouts, accessible controls, responsive mobile design, and keyboard-friendly dialogs.

## Technical constraints
- Hosting target: GitHub Pages. Do not configure or deploy to Vercel.
- Keep the project simple and static unless a secure backend is explicitly designed and approved.
- Never place API keys, passwords, or private credentials in client-side code or Git history.
- Real owner-only uploads and persistent media storage are not implemented yet. Before implementing them, propose a secure authenticated storage/backend architecture and explain any required service setup.
- Optimize images responsibly; do not claim that uploaded files are 4K or lossless unless the actual source and delivery pipeline support it.

## Current entry point
- `index.html`: current responsive portfolio homepage.
- `README.md`: local preview and GitHub Pages publishing instructions.
