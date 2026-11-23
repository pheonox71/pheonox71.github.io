# Chance Brenchley

Personal site for Chance Brenchley, a software engineer. One static page for recruiters hiring in Salt Lake City, remote, and Tokyo. GitHub Pages serves it at [pheonox71.github.io](https://pheonox71.github.io) from the `main` branch of this repository.

## Edit the site

There is no build step and no framework. Change the words in `index.html` and the layout in `styles.css`, then commit to `main`.

Preview locally:

```bash
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080). Light and dark colors follow the operating system (`prefers-color-scheme`). To change the accent or the page background, edit the variables at the top of `styles.css` and the matching block inside `@media (prefers-color-scheme: dark)`.

The copy is the approved headline, About, and resume bullets. Keep edits to that wording. Dates on the resume are still placeholders, so the page leaves dates off.

Where things live in `index.html`:

- Hero: name, headline, GitHub, and LinkedIn. An HTML comment marks where to add an email address and a resume PDF.
- What I bring, Featured projects, Experience, Skills, and Education are the sections below it.
- Footer repeats the GitHub and LinkedIn links.

## Project links

- **AsyncAcademy** links to the public repo [pheonox71/AsyncAcademy](https://github.com/pheonox71/AsyncAcademy). There is no demo link. The repo notes that the old hosted demo is not up.
- **RSPG Application** has no code link. There is no public RSPG repository under pheonox71. Add a Code link on that card if you publish one.
- **Basketball Maze Game** links to the [live demo](https://pheonox71.github.io/CS4280-FinalProject/) and [source](https://github.com/pheonox71/CS4280-FinalProject).

FishNearYou, CSJobSearchAlerts, and MailGuard are intentionally not on the page.

## Publish

This repository is a GitHub Pages user site. Pages is set to publish the root of `main`. Merge into `main` and the live site updates from that branch. A `.nojekyll` file keeps Pages from running the files through Jekyll.
