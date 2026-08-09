# poli0981/content

Content for **[poli0981.dev](https://poli0981.dev)** — blog posts, stories, project pages,
Q&A entries, gallery album metadata, and the legal texts.

This repository is consumed as a **git submodule** mounted at `src/content/` in
[`poli0981/poli0981-dev`](https://github.com/poli0981/poli0981-dev). The site's Astro
content collections read directly from these paths, so the directory names here are load-bearing:

| Directory   | Collection | Notes |
| ----------- | ---------- | ----- |
| `blog/`     | `blog`     | `.md` / `.mdx`, one file per locale (`lang: vi \| en`, paired by `translationKey`) |
| `stories/`  | `stories`  | `<series>/<chapter>.md` — the folder name is the series route segment |
| `projects/` | `projects` | standalone schema (`name`, `tagline`, `stack`, `repo`, `year`…) |
| `faq/`      | `faq`      | `q`, `lang`, `group` (`channel` / `dev` / `personal`), `order` |
| `gallery/`  | `gallery`  | album **metadata only** — the images live in the site repo under `src/assets/gallery/<album>/` |
| `legal/`    | `legal`    | bilingual within one file (`## English` then `## Tiếng Việt`); both locale routes render the same document |

## Editing

Frontmatter is validated by Zod at build time in the site repo
(`src/content.config.ts`) — a missing or misspelled field **fails the build** rather than
rendering something broken. Notable rules:

- `description` max 200 chars, `title` max 120
- `lang` must be `vi` or `en`; pair translations with a shared `translationKey`
- `draft: true` hides an entry from production builds but keeps it visible in `npm run dev`
- gallery albums need a `captions.json` in the site repo with **both** `vi` and `en` for
  every image, or the build fails

`blog/lan-dau-viet-truyen.mdx` imports `@/components/Callout.astro`. That alias resolves
into the *site* repo, which works because the submodule is mounted inside its `src/`.
MDX files can only use components that exist there.

## Publishing a change

Commit here, then bump the submodule pointer in the site repo — the site builds from the
commit that repo has pinned, so a commit here alone does not deploy anything.

## License

Code in the site repo is GPL-3.0-only. **The content in this repository is not.**
See [`CONTENT-LICENSE.md`](CONTENT-LICENSE.md): © Kokone (SkullMute), all rights reserved,
and explicitly not licensed for machine-learning training.
