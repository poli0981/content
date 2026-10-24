---
title: "Bên thứ ba / Third-Party Notices"
order: 4
---

## English

This site is built with open-source software. Each component below remains under its own license; full license texts ship with each package and in the repository's `THIRD-PARTY-NOTICES.md`.

## Tiếng Việt

Trang web này được xây dựng bằng phần mềm mã nguồn mở. Mỗi thành phần dưới đây giữ nguyên giấy phép gốc của nó; toàn văn giấy phép đi kèm từng package và trong file `THIRD-PARTY-NOTICES.md` của repo.

## Components

| Component                                                     | License          |
| ------------------------------------------------------------- | ---------------- |
| Astro + @astrojs/\*                                           | MIT              |
| Svelte                                                        | MIT              |
| Tailwind CSS                                                  | MIT              |
| Pagefind                                                      | MIT              |
| Zod                                                           | MIT              |
| jose (admin sign-in check)                                    | MIT              |
| marked, yaml (admin editor)                                   | MIT / ISC        |
| sharp                                                         | Apache-2.0       |
| Satori + @resvg/resvg-js (build-time OG images)               | MPL-2.0          |
| TypeScript (build-time type checking)                         | Apache-2.0       |
| Wrangler                                                      | MIT / Apache-2.0 |
| Bricolage Grotesque, Be Vietnam Pro, Literata, JetBrains Mono | SIL OFL 1.1      |

**Infrastructure services** (not packages, listed for transparency):

- **Cloudflare** — hosting (Workers, KV, R2 storage, Images), CDN, Web Analytics, Turnstile, Access (the admin sign-in) and Workers Logs.
- **GitHub** — source code, content, and bug reports (filed in a private repository).
- **Discord** — notifications when a bug report arrives.
- **YouTube / Steam / GitHub public data** — read by a scheduled job for the home-page widgets; their pictures are copied and served from this site.
