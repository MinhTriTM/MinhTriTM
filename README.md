# Hi, I'm Tam

Developer in Ho Chi Minh City. I take messy public data and turn it into something you can hold in one hand: a single Go binary, a browsable index, a clean line of JSON. I write the notes down as I go, and I translate the books and docs I learned from into Vietnamese so they reach more people.

![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Zig](https://img.shields.io/badge/-Zig-F7A41D?style=flat-square&logo=zig&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/-Postgres-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Cloudflare](https://img.shields.io/badge/-Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

## What I build

### Site CLIs

One small Go binary per website. Point it at public data, get back structured JSON or JSONL, no API key required. They all sit on a shared framework so each repo only carries its own data domain.

- [ytb-cli](https://github.com/tamnd/ytb-cli) reads YouTube: videos, channels, search, comments, transcripts
- [x-cli](https://github.com/tamnd/x-cli) reads X over the free public surface
- [amz-cli](https://github.com/tamnd/amz-cli), [archive-cli](https://github.com/tamnd/archive-cli), and roughly 240 more in the same family
- [any-cli](https://github.com/tamnd/any-cli) scaffolds a new one, fully wired, in a few seconds
- [ant](https://github.com/tamnd/ant) is the front door: every public record is a URI, and ant dereferences it
- [kumo](https://github.com/tamnd/kumo) crawls a whole host into structured files

### Browsable indexes

Hand-curated, searchable maps of large doc sets and video archives, so the good stuff is easy to find.

- [mdn-index](https://github.com/tamnd/mdn-index), [kernel-index](https://github.com/tamnd/kernel-index), [godev-index](https://github.com/tamnd/godev-index), [dbdb-index](https://github.com/tamnd/dbdb-index)
- [3blue1brown-index](https://github.com/tamnd/3blue1brown-index), [khanacademy-index](https://github.com/tamnd/khanacademy-index)
- OWASP guides: [wstg-index](https://github.com/tamnd/wstg-index), [mastg-index](https://github.com/tamnd/mastg-index), [go-scp-index](https://github.com/tamnd/go-scp-index)

### Languages and runtimes, in Go

- [goipy](https://github.com/tamnd/goipy) is a pure-Go CPython 3.14 bytecode interpreter that runs .pyc files without cgo
- [gopy](https://github.com/tamnd/gopy) reimplements the CPython core in Go, aiming for matching behavior
- [vigo](https://github.com/tamnd/vigo) rebuilds Borland Turbo Vision as a modern Go TUI

### Backend and infrastructure

- [dbrest](https://github.com/tamnd/dbrest) is a PostgREST-compatible REST API over any database
- [liteio](https://github.com/tamnd/liteio) is an S3-compatible object store under Apache-2.0
- [githome](https://github.com/tamnd/githome) is a self-hosted, GitHub-compatible forge
- [openindex](https://github.com/tamnd/openindex) is a web-scale search engine with an open, auditable index

### Vietnamese translations

Beej's guides (network programming, C, the C library reference), Project Euler, the Python docs, MDN, the Linux kernel docs, and the Distill.pub articles.

## A bit of activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tamnd/tamnd/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tamnd/tamnd/output/github-snake.svg">
  <img alt="contribution snake" src="https://raw.githubusercontent.com/tamnd/tamnd/output/github-snake.svg">
</picture>

<p>
  <img height="170" alt="stats" src="https://github-readme-stats.vercel.app/api?username=tamnd&show_icons=true&hide_border=true&include_all_commits=true&theme=tokyonight" />
  <img height="170" alt="top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tamnd&layout=compact&langs_count=8&hide_border=true&theme=tokyonight" />
</p>

![activity graph](https://github-readme-activity-graph.vercel.app/graph?username=tamnd&theme=tokyo-night&hide_border=true&area=true)

## Where to find me

- Notes and writing: [tamnd.github.io/blog](https://tamnd.github.io/blog/)
- Most CLIs have their own docs at `name.tamnd.com`, for example [ytb-cli.tamnd.com](https://ytb-cli.tamnd.com)
