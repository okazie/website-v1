# wendi.lol

My portfolio site. One file: `index.html`.

## Editing
- Replace anything in [square brackets] with your own words.
- Photos: put image files next to `index.html`, then swap a placeholder like
  `<div class="img">Robot photo here</div>` for `<div class="img"><img src="robot.jpg" alt="My robot"></div>`.
- New project: copy a whole `<article class="card"> ... </article>` block.
- Colours: change `--accent` at the top of the file.

## Publishing (Cloudflare Pages)
In the Cloudflare dashboard: Workers & Pages → Create → Pages → Connect to Git → pick this repo.
Build command: none. Output directory: `/`. Then Custom domains → add `wendi.lol`.
Every push to `main` updates the live site.
