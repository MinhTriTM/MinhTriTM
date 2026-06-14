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

## Stats and charts

Everything below regenerates on a schedule from my real activity.

![overview](./metrics.svg)

<p>
  <img alt="commit calendar" src="./metrics.calendar.svg" />
  <img alt="code changes" src="./metrics.lines.svg" />
</p>

![languages](./metrics.languages.svg)

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

## All repositories

Every public repository I own, nothing left out. 335 in total.

### Command-line tools (244)

- [aclanthology-cli](https://github.com/tamnd/aclanthology-cli)
- [acmdl-cli](https://github.com/tamnd/acmdl-cli)
- [acmqueue-cli](https://github.com/tamnd/acmqueue-cli)
- [algorithmvisualizer-cli](https://github.com/tamnd/algorithmvisualizer-cli)
- [alignmentforum-cli](https://github.com/tamnd/alignmentforum-cli)
- [amz-cli](https://github.com/tamnd/amz-cli) - A delightful command line for Amazon.com: crawl every public surface into rich, structured data
- [any-cli](https://github.com/tamnd/any-cli) - Scaffold a new tamnd/*-cli repository, fully wired.
- [applepodcasts-cli](https://github.com/tamnd/applepodcasts-cli)
- [archive-cli](https://github.com/tamnd/archive-cli) - A fast, scriptable CLI for the Internet Archive and the Wayback Machine
- [archwiki-cli](https://github.com/tamnd/archwiki-cli)
- [arctic-cli](https://github.com/tamnd/arctic-cli) - A command line for the bulk Reddit archive: pull the monthly torrent dumps and the Arctic Shift API, convert to Parquet, query locally, and publish to Hugging Face.
- [arstechnica-cli](https://github.com/tamnd/arstechnica-cli)
- [arxiv-cli](https://github.com/tamnd/arxiv-cli)
- [atcoder-cli](https://github.com/tamnd/atcoder-cli)
- [baidu-cli](https://github.com/tamnd/baidu-cli)
- [barchart-cli](https://github.com/tamnd/barchart-cli)
- [bbc-cli](https://github.com/tamnd/bbc-cli)
- [betterexplained-cli](https://github.com/tamnd/betterexplained-cli)
- [bilibili-cli](https://github.com/tamnd/bilibili-cli) - A fast, friendly command line for bilibili.com. Resolve any video, user, comment, danmaku, dynamic, live room, bangumi, audio, article, or favorite into clean structured records, all from one binary.
- [biorxiv-cli](https://github.com/tamnd/biorxiv-cli)
- [bloomberg-cli](https://github.com/tamnd/bloomberg-cli)
- [bluesky-cli](https://github.com/tamnd/bluesky-cli)
- [britannica-cli](https://github.com/tamnd/britannica-cli)
- [bytebytego-cli](https://github.com/tamnd/bytebytego-cli)
- [cacm-cli](https://github.com/tamnd/cacm-cli)
- [cambridge-cli](https://github.com/tamnd/cambridge-cli)
- [ccrawl-cli](https://github.com/tamnd/ccrawl-cli) - A fast, friendly command line for Common Crawl
- [chemrxiv-cli](https://github.com/tamnd/chemrxiv-cli)
- [classcentral-cli](https://github.com/tamnd/classcentral-cli)
- [clinicaltrials-cli](https://github.com/tamnd/clinicaltrials-cli)
- [cmu15445-cli](https://github.com/tamnd/cmu15445-cli)
- [codecademy-cli](https://github.com/tamnd/codecademy-cli)
- [codechef-cli](https://github.com/tamnd/codechef-cli)
- [codeforces-cli](https://github.com/tamnd/codeforces-cli)
- [codinghorror-cli](https://github.com/tamnd/codinghorror-cli)
- [comick-cli](https://github.com/tamnd/comick-cli)
- [compilerexplorer-cli](https://github.com/tamnd/compilerexplorer-cli)
- [coursera-cli](https://github.com/tamnd/coursera-cli)
- [cpalgorithms-cli](https://github.com/tamnd/cpalgorithms-cli)
- [craftinginterpreters-cli](https://github.com/tamnd/craftinginterpreters-cli)
- [cran-cli](https://github.com/tamnd/cran-cli)
- [cratesio-cli](https://github.com/tamnd/cratesio-cli) - CLI for the crates.io Rust package registry
- [crossref-cli](https://github.com/tamnd/crossref-cli)
- [cryptostanford-cli](https://github.com/tamnd/cryptostanford-cli)
- [cs229-cli](https://github.com/tamnd/cs229-cli)
- [cs231n-cli](https://github.com/tamnd/cs231n-cli)
- [cs50-cli](https://github.com/tamnd/cs50-cli)
- [csdn-cli](https://github.com/tamnd/csdn-cli)
- [cses-cli](https://github.com/tamnd/cses-cli)
- [csfieldguide-cli](https://github.com/tamnd/csfieldguide-cli)
- [csrankings-cli](https://github.com/tamnd/csrankings-cli)
- [csstricks-cli](https://github.com/tamnd/csstricks-cli)
- [cstheoryse-cli](https://github.com/tamnd/cstheoryse-cli)
- [ctrip-cli](https://github.com/tamnd/ctrip-cli)
- [cvf-cli](https://github.com/tamnd/cvf-cli)
- [databaseinternals-cli](https://github.com/tamnd/databaseinternals-cli)
- [dbengines-cli](https://github.com/tamnd/dbengines-cli)
- [dblp-cli](https://github.com/tamnd/dblp-cli)
- [deeplearningbook-cli](https://github.com/tamnd/deeplearningbook-cli)
- [devdocs-cli](https://github.com/tamnd/devdocs-cli)
- [devto-cli](https://github.com/tamnd/devto-cli)
- [dictionary-cli](https://github.com/tamnd/dictionary-cli)
- [distill-cli](https://github.com/tamnd/distill-cli) - A command line for Distill.pub machine learning research
- [dlmf-cli](https://github.com/tamnd/dlmf-cli)
- [dmoj-cli](https://github.com/tamnd/dmoj-cli)
- [doaj-cli](https://github.com/tamnd/doaj-cli)
- [dockerhub-cli](https://github.com/tamnd/dockerhub-cli)
- [douban-cli](https://github.com/tamnd/douban-cli)
- [douyin-cli](https://github.com/tamnd/douyin-cli)
- [dzone-cli](https://github.com/tamnd/dzone-cli)
- [eleutherai-cli](https://github.com/tamnd/eleutherai-cli)
- [elife-cli](https://github.com/tamnd/elife-cli)
- [eloquentjs-cli](https://github.com/tamnd/eloquentjs-cli)
- [encmath-cli](https://github.com/tamnd/encmath-cli)
- [eppreprints-cli](https://github.com/tamnd/eppreprints-cli)
- [europepmc-cli](https://github.com/tamnd/europepmc-cli)
- [exercism-cli](https://github.com/tamnd/exercism-cli)
- [explainshell-cli](https://github.com/tamnd/explainshell-cli)
- [f1000-cli](https://github.com/tamnd/f1000-cli)
- [facebook-cli](https://github.com/tamnd/facebook-cli) - A delightful, scriptable command line for Facebook
- [fandom-cli](https://github.com/tamnd/fandom-cli)
- [fastai-cli](https://github.com/tamnd/fastai-cli)
- [feedbooks-cli](https://github.com/tamnd/feedbooks-cli)
- [figshare-cli](https://github.com/tamnd/figshare-cli)
- [freebsddocs-cli](https://github.com/tamnd/freebsddocs-cli)
- [freecodecamp-cli](https://github.com/tamnd/freecodecamp-cli) - A command line for freeCodeCamp news and tutorials
- [frontiers-cli](https://github.com/tamnd/frontiers-cli)
- [gapminder-cli](https://github.com/tamnd/gapminder-cli)
- [gitee-cli](https://github.com/tamnd/gitee-cli)
- [github-cli](https://github.com/tamnd/github-cli)
- [githubdocs-cli](https://github.com/tamnd/githubdocs-cli)
- [gobyexample-cli](https://github.com/tamnd/gobyexample-cli)
- [goodread-cli](https://github.com/tamnd/goodread-cli) - A fast, friendly command line for public Goodreads data. One binary that turns books, authors, series, lists, quotes, users, shelves, genres, reviews, and search into rich structured records.
- [google-cli](https://github.com/tamnd/google-cli)
- [gutenberg-cli](https://github.com/tamnd/gutenberg-cli)
- [hackerearth-cli](https://github.com/tamnd/hackerearth-cli)
- [hackernews-cli](https://github.com/tamnd/hackernews-cli) - A command line for Hacker News. A single pure-Go binary, no API key, output as table/JSON/JSONL/CSV/TSV/URL.
- [hackernoon-cli](https://github.com/tamnd/hackernoon-cli) - A command line for Hackernoon tech stories
- [hackerrank-cli](https://github.com/tamnd/hackerrank-cli)
- [highscalability-cli](https://github.com/tamnd/highscalability-cli) - A command line for the High Scalability blog
- [huggingface-cli](https://github.com/tamnd/huggingface-cli)
- [hupu-cli](https://github.com/tamnd/hupu-cli)
- [ifeng-cli](https://github.com/tamnd/ifeng-cli)
- [imdb-cli](https://github.com/tamnd/imdb-cli)
- [infoq-cli](https://github.com/tamnd/infoq-cli)
- [interpretableml-cli](https://github.com/tamnd/interpretableml-cli)
- [iqiyi-cli](https://github.com/tamnd/iqiyi-cli)
- [jayalammar-cli](https://github.com/tamnd/jayalammar-cli)
- [joelonsoftware-cli](https://github.com/tamnd/joelonsoftware-cli)
- [jsinfo-cli](https://github.com/tamnd/jsinfo-cli)
- [juejin-cli](https://github.com/tamnd/juejin-cli)
- [jutge-cli](https://github.com/tamnd/jutge-cli)
- [kaggle-cli](https://github.com/tamnd/kaggle-cli)
- [kattis-cli](https://github.com/tamnd/kattis-cli)
- [kernelorg-cli](https://github.com/tamnd/kernelorg-cli)
- [khanacademy-cli](https://github.com/tamnd/khanacademy-cli)
- [komal-cli](https://github.com/tamnd/komal-cli)
- [kr36-cli](https://github.com/tamnd/kr36-cli)
- [kvant-mccme-cli](https://github.com/tamnd/kvant-mccme-cli)
- [leanpub-cli](https://github.com/tamnd/leanpub-cli)
- [leetcode-cli](https://github.com/tamnd/leetcode-cli)
- [lesswrong-cli](https://github.com/tamnd/lesswrong-cli)
- [lilianweng-cli](https://github.com/tamnd/lilianweng-cli)
- [linkedin-cli](https://github.com/tamnd/linkedin-cli) - A command line for public LinkedIn data: profiles, companies, and jobs as structured records. Pure Go, no API key.
- [linuxdo-cli](https://github.com/tamnd/linuxdo-cli)
- [lobsters-cli](https://github.com/tamnd/lobsters-cli)
- [lwn-cli](https://github.com/tamnd/lwn-cli)
- [mangadex-cli](https://github.com/tamnd/mangadex-cli)
- [mangafire-cli](https://github.com/tamnd/mangafire-cli)
- [martinfowler-cli](https://github.com/tamnd/martinfowler-cli)
- [mathnet-cli](https://github.com/tamnd/mathnet-cli)
- [mathnet-ru-cli](https://github.com/tamnd/mathnet-ru-cli)
- [mathoverflow-cli](https://github.com/tamnd/mathoverflow-cli)
- [mathse-cli](https://github.com/tamnd/mathse-cli)
- [mathworld-cli](https://github.com/tamnd/mathworld-cli)
- [maven-cli](https://github.com/tamnd/maven-cli)
- [mdpi-cli](https://github.com/tamnd/mdpi-cli)
- [medium-cli](https://github.com/tamnd/medium-cli)
- [mitnews-cli](https://github.com/tamnd/mitnews-cli)
- [mlxtend-cli](https://github.com/tamnd/mlxtend-cli)
- [morningpaper-cli](https://github.com/tamnd/morningpaper-cli) - A command line for The Morning Paper CS paper reviews
- [nand2tetris-cli](https://github.com/tamnd/nand2tetris-cli)
- [nber-cli](https://github.com/tamnd/nber-cli)
- [neetcode-cli](https://github.com/tamnd/neetcode-cli)
- [netease163-cli](https://github.com/tamnd/netease163-cli)
- [neteasemusic-cli](https://github.com/tamnd/neteasemusic-cli)
- [neuralnetworksdl-cli](https://github.com/tamnd/neuralnetworksdl-cli)
- [neurips-cli](https://github.com/tamnd/neurips-cli)
- [nlab-cli](https://github.com/tamnd/nlab-cli)
- [npmjs-cli](https://github.com/tamnd/npmjs-cli)
- [ocwmit-cli](https://github.com/tamnd/ocwmit-cli)
- [oeis-cli](https://github.com/tamnd/oeis-cli)
- [opendatastructures-cli](https://github.com/tamnd/opendatastructures-cli)
- [openreview-cli](https://github.com/tamnd/openreview-cli)
- [openstax-cli](https://github.com/tamnd/openstax-cli)
- [oschina-cli](https://github.com/tamnd/oschina-cli)
- [osmwiki-cli](https://github.com/tamnd/osmwiki-cli)
- [ossucs-cli](https://github.com/tamnd/ossucs-cli)
- [ostep-cli](https://github.com/tamnd/ostep-cli)
- [oupopen-cli](https://github.com/tamnd/oupopen-cli)
- [owasp-cli](https://github.com/tamnd/owasp-cli)
- [owid-cli](https://github.com/tamnd/owid-cli)
- [paperreview-cli](https://github.com/tamnd/paperreview-cli)
- [paulgraham-cli](https://github.com/tamnd/paulgraham-cli)
- [paulsmath-cli](https://github.com/tamnd/paulsmath-cli)
- [peerj-cli](https://github.com/tamnd/peerj-cli)
- [philpapers-cli](https://github.com/tamnd/philpapers-cli)
- [physicsforums-cli](https://github.com/tamnd/physicsforums-cli)
- [pixiv-cli](https://github.com/tamnd/pixiv-cli)
- [pkggodev-cli](https://github.com/tamnd/pkggodev-cli)
- [plosone-cli](https://github.com/tamnd/plosone-cli)
- [pragmaticengineer-cli](https://github.com/tamnd/pragmaticengineer-cli)
- [producthunt-cli](https://github.com/tamnd/producthunt-cli)
- [proofwiki-cli](https://github.com/tamnd/proofwiki-cli)
- [pubmed-cli](https://github.com/tamnd/pubmed-cli)
- [pwc-cli](https://github.com/tamnd/pwc-cli)
- [pydocs-cli](https://github.com/tamnd/pydocs-cli)
- [pypi-cli](https://github.com/tamnd/pypi-cli)
- [pythondiscuss-cli](https://github.com/tamnd/pythondiscuss-cli)
- [qiita-cli](https://github.com/tamnd/qiita-cli)
- [qqmusic-cli](https://github.com/tamnd/qqmusic-cli)
- [quanta-cli](https://github.com/tamnd/quanta-cli)
- [reddit-cli](https://github.com/tamnd/reddit-cli) - A fast, friendly command line for public Reddit data. One pure-Go binary, no API key.
- [refactoringguru-cli](https://github.com/tamnd/refactoringguru-cli)
- [regex101-cli](https://github.com/tamnd/regex101-cli)
- [reuters-cli](https://github.com/tamnd/reuters-cli)
- [rosettacode-cli](https://github.com/tamnd/rosettacode-cli)
- [rustbook-cli](https://github.com/tamnd/rustbook-cli)
- [sageopen-cli](https://github.com/tamnd/sageopen-cli)
- [segmentfault-cli](https://github.com/tamnd/segmentfault-cli)
- [semanticscholar-cli](https://github.com/tamnd/semanticscholar-cli)
- [sicp-cli](https://github.com/tamnd/sicp-cli)
- [sinafinance-cli](https://github.com/tamnd/sinafinance-cli)
- [sinanews-cli](https://github.com/tamnd/sinanews-cli)
- [smashingmag-cli](https://github.com/tamnd/smashingmag-cli)
- [soundcloud-cli](https://github.com/tamnd/soundcloud-cli)
- [springer-cli](https://github.com/tamnd/springer-cli)
- [ss64-cli](https://github.com/tamnd/ss64-cli)
- [stackoverflow-cli](https://github.com/tamnd/stackoverflow-cli)
- [stdebooks-cli](https://github.com/tamnd/stdebooks-cli)
- [steam-cli](https://github.com/tamnd/steam-cli)
- [substack-cli](https://github.com/tamnd/substack-cli)
- [sysapproach-cli](https://github.com/tamnd/sysapproach-cli)
- [thegradient-cli](https://github.com/tamnd/thegradient-cli)
- [theodinproject-cli](https://github.com/tamnd/theodinproject-cli)
- [threads-cli](https://github.com/tamnd/threads-cli) - A command line for Threads: profiles, posts, replies, and search as clean structured data.
- [tieba-cli](https://github.com/tamnd/tieba-cli)
- [tiengtrungbotui-cli](https://github.com/tamnd/tiengtrungbotui-cli)
- [tiengtrungonline-cli](https://github.com/tamnd/tiengtrungonline-cli)
- [tiktok-cli](https://github.com/tamnd/tiktok-cli) - A command line for TikTok. Read public profiles, videos, comments, hashtags, sounds, and search as clean JSONL.
- [timus-cli](https://github.com/tamnd/timus-cli)
- [tiobe-cli](https://github.com/tamnd/tiobe-cli)
- [tldp-cli](https://github.com/tamnd/tldp-cli)
- [tldrpages-cli](https://github.com/tamnd/tldrpages-cli)
- [toutiao-cli](https://github.com/tamnd/toutiao-cli)
- [tumblr-cli](https://github.com/tamnd/tumblr-cli)
- [twitch-cli](https://github.com/tamnd/twitch-cli)
- [tycs-cli](https://github.com/tamnd/tycs-cli)
- [uci-cli](https://github.com/tamnd/uci-cli)
- [unsdg-cli](https://github.com/tamnd/unsdg-cli)
- [usaco-cli](https://github.com/tamnd/usaco-cli)
- [usenix-cli](https://github.com/tamnd/usenix-cli)
- [uva-cli](https://github.com/tamnd/uva-cli)
- [v2ex-cli](https://github.com/tamnd/v2ex-cli)
- [visualgo-cli](https://github.com/tamnd/visualgo-cli)
- [vldb-cli](https://github.com/tamnd/vldb-cli)
- [weibo-cli](https://github.com/tamnd/weibo-cli)
- [weread-cli](https://github.com/tamnd/weread-cli)
- [wikibooks-cli](https://github.com/tamnd/wikibooks-cli)
- [wikidata-cli](https://github.com/tamnd/wikidata-cli)
- [wikipedia-cli](https://github.com/tamnd/wikipedia-cli) - A fast, friendly command line for Wikipedia: read articles as text or Markdown, search, summarize, walk links and categories, query Wikidata, fetch pageviews, and stream and convert the public XML dumps.
- [wikisource-cli](https://github.com/tamnd/wikisource-cli)
- [wikiversity-cli](https://github.com/tamnd/wikiversity-cli)
- [wiktionary-cli](https://github.com/tamnd/wiktionary-cli)
- [wileyopen-cli](https://github.com/tamnd/wileyopen-cli)
- [wolframfns-cli](https://github.com/tamnd/wolframfns-cli)
- [worldbank-cli](https://github.com/tamnd/worldbank-cli)
- [x-cli](https://github.com/tamnd/x-cli) - A fast pure-Go command line for X (Twitter) over the free public surfaces. No paid API.
- [xiaohongshu-cli](https://github.com/tamnd/xiaohongshu-cli) - A command line for Xiaohongshu. One pure-Go binary, no API key.
- [xiaoyuzhou-cli](https://github.com/tamnd/xiaoyuzhou-cli)
- [yahoofinance-cli](https://github.com/tamnd/yahoofinance-cli)
- [ytb-cli](https://github.com/tamnd/ytb-cli) - A CLI for YouTube: videos, channels, search, comments, transcripts, and Music, with an optional local SQLite store.
- [ytmusic-cli](https://github.com/tamnd/ytmusic-cli)
- [zenodo-cli](https://github.com/tamnd/zenodo-cli)

### Indexes (12)

- [3blue1brown-index](https://github.com/tamnd/3blue1brown-index) - Browsable index of every 3Blue1Brown video. 179 videos, 24 playlists, 608M+ total views. Math, physics, and CS explained through stunning animations.
- [awesome-index](https://github.com/tamnd/awesome-index) - Auto-generated enriched index of sindresorhus/awesome - with stars, last update, commit counts, and more
- [cmu-database-group-videos-index](https://github.com/tamnd/cmu-database-group-videos-index) - Browsable index of every lecture and talk from the CMU Database Group YouTube channel. 585 videos, 35 playlists, 11 years of database systems education.
- [dbdb-index](https://github.com/tamnd/dbdb-index) - Every database management system on dbdb.io, indexed. 1071 systems with stats, charts, and full metadata. Built with Go.
- [go-scp-index](https://github.com/tamnd/go-scp-index) - Human-readable index of the OWASP Go Secure Coding Practices Guide with chapter descriptions and Go code examples
- [godev-index](https://github.com/tamnd/godev-index) - A curated guide to everything on go.dev, organized for learners and practitioners
- [hn-daily-index](https://github.com/tamnd/hn-daily-index) - Daily archive of the top 10 Hacker News stories, organized by date
- [kernel-index](https://github.com/tamnd/kernel-index) - A browsable, hand-curated index of every documentation page in the Linux kernel. 1,393 pages across 56 sections. From getting your first patch merged to writing device drivers, it's all here.
- [khanacademy-index](https://github.com/tamnd/khanacademy-index) - Browsable index of Khan Academy YouTube videos. 4400+ videos across math, science, computing, and more. Organized by date with full metadata.
- [mastg-index](https://github.com/tamnd/mastg-index) - Human-readable index of all OWASP MASTG tests, techniques, and tools, organized by MASVS control groups
- [mdn-index](https://github.com/tamnd/mdn-index) - A complete index of all 14,000+ articles on MDN Web Docs, organized by technology
- [wstg-index](https://github.com/tamnd/wstg-index) - Human-readable index of all OWASP Web Security Testing Guide (WSTG) tests, auto-generated from the official checklist.json

### Vietnamese translations (14)

- [bgc-vi](https://github.com/tamnd/bgc-vi) - Hướng dẫn Lập trình C của Beej - Vietnamese translation of Beej's Guide to C
- [bgclr-vi](https://github.com/tamnd/bgclr-vi) - Tham chiếu Thư viện C của Beej - Vietnamese translation of Beej's Guide to C Library Reference
- [bggit-vi](https://github.com/tamnd/bggit-vi) - Bản dịch tiếng Việt của Beej's Guide to Git
- [bgipc-vi](https://github.com/tamnd/bgipc-vi) - Bản dịch tiếng Việt của Beej's Guide to Interprocess Communication
- [bglcs-vi](https://github.com/tamnd/bglcs-vi) - Bản dịch tiếng Việt của Beej's Guide to Learning Computer Science
- [bgnet-vi](https://github.com/tamnd/bgnet-vi) - Vietnamese translation of Beej's Guide to Network Programming
- [bgnet0-vi](https://github.com/tamnd/bgnet0-vi) - Bản dịch tiếng Việt của Beej's Guide to Network Concepts
- [brain-vi](https://github.com/tamnd/brain-vi) - brain (Tiếng Việt) - auto-translated from tamnd/brain
- [draft-docs-vi](https://github.com/tamnd/draft-docs-vi)
- [kernel-docs-vi](https://github.com/tamnd/kernel-docs-vi) - Vietnamese translation of Linux kernel documentation (mirror of torvalds/linux Documentation/ with vi_VN translations)
- [mdn-translated-content-vi](https://github.com/tamnd/mdn-translated-content-vi) - Vietnamese translation of MDN Web Docs
- [pe-vi](https://github.com/tamnd/pe-vi) - Bản dịch tiếng Việt của Project Euler -- 994 bài toán toán học và lập trình
- [python-docs-vi](https://github.com/tamnd/python-docs-vi) - Vietnamese translation of the Python documentation, auto-synced from Transifex (PEP 545)
- [ziglang-vi](https://github.com/tamnd/ziglang-vi) - Vietnamese translation of ziglang.org (upstream: codeberg.org/ziglang/ziglang.org)

### Everything else (65)

- [ant](https://github.com/tamnd/ant) - Every public record is a URI, and ant dereferences it: a URI front door over the tamnd site CLIs.
- [beej-vi-docker](https://github.com/tamnd/beej-vi-docker) - Shared container image for building Beej's Guides (texlive + pandoc + Libertinus fonts). Pulled by tamnd/bgnet-vi and tamnd/bgc-vi.
- [blog](https://github.com/tamnd/blog) - Notes on programming, open source, and whatever I'm reading
- [brain](https://github.com/tamnd/brain) - My extended brain, what you learn is what you note.
- [brain-ja](https://github.com/tamnd/brain-ja) - brain (日本語) - auto-translated from tamnd/brain
- [brain-zh-cn](https://github.com/tamnd/brain-zh-cn) - brain (中文) - auto-translated from tamnd/brain
- [bunpy](https://github.com/tamnd/bunpy) - Bun for Python: one binary - runtime, package manager, bundler, test runner. Pure-Go. No CPython on the box.
- [cs50-i18n](https://github.com/tamnd/cs50-i18n) - Open multilingual translations of CS50 Harvard course materials
- [dbrest](https://github.com/tamnd/dbrest) - High-performance, PostgREST-compatible REST API over any database, in Go
- [distillpub](https://github.com/tamnd/distillpub) - Distill translation tracking
- [distillpub--post--augmented-rnns](https://github.com/tamnd/distillpub--post--augmented-rnns) - Attention and Augmented Recurrent Neural Networks
- [distillpub--post--building-blocks](https://github.com/tamnd/distillpub--post--building-blocks) - The Building Blocks of Interpretability Vietnamese translation
- [distillpub--post--ctc](https://github.com/tamnd/distillpub--post--ctc) - Sequence Modelling with CTC Vietnamese translation
- [distillpub--post--deconv-checkerboard](https://github.com/tamnd/distillpub--post--deconv-checkerboard) - Deconvolution and Checkerboard Artifacts
- [distillpub--post--feature-visualization](https://github.com/tamnd/distillpub--post--feature-visualization) - Feature Visualization Vietnamese translation
- [distillpub--post--feature-wise-transformations](https://github.com/tamnd/distillpub--post--feature-wise-transformations) - Feature-Wise Transformations Vietnamese translation
- [distillpub--post--handwriting](https://github.com/tamnd/distillpub--post--handwriting) - Four Experiments in Handwriting with a Neural Network
- [distillpub--post--misread-tsne](https://github.com/tamnd/distillpub--post--misread-tsne) - How to Use t-SNE Effectively
- [distillpub--post--momentum](https://github.com/tamnd/distillpub--post--momentum) - Why Momentum Really Works Vietnamese translation
- [distillpub--post--research-debt](https://github.com/tamnd/distillpub--post--research-debt) - Research Debt Vietnamese translation
- [docs](https://github.com/tamnd/docs)
- [dual](https://github.com/tamnd/dual) - Go implementation of dual numbers.
- [fastmlx](https://github.com/tamnd/fastmlx) - Go reimplementation of jundot/omlx: continuous-batching MLX LLM inference server for Apple Silicon
- [gauth](https://github.com/tamnd/gauth) - Clean authentication for Go
- [githome](https://github.com/tamnd/githome) - A self-hosted, GitHub-compatible software forge written in Go. REST v3, GraphQL v4, and the gh CLI, byte for byte.
- [githome-bench](https://github.com/tamnd/githome-bench) - Real-world benchmark and SLO gates for the Githome forge
- [github-compat](https://github.com/tamnd/github-compat) - Conformance test suite: prove any GitHub-compatible API host works with every client library, CLI, and integration
- [gitview](https://github.com/tamnd/gitview) - Browse any git repo with a GitHub style web UI
- [go-internals](https://github.com/tamnd/go-internals)
- [gocopy](https://github.com/tamnd/gocopy) - Pure-Go compiler from Python 3.14 source to a CPython-compatible .pyc. No cgo, no embedded CPython at runtime.
- [goipy](https://github.com/tamnd/goipy) - Pure-Go CPython 3.14 bytecode interpreter. Runs .pyc files without cgo or embedded CPython.
- [gomlx](https://github.com/tamnd/gomlx) - An OpenAI/Anthropic-compatible LLM inference server for Apple Silicon, built on MLX
- [gopapy](https://github.com/tamnd/gopapy) - Pure-Go parser for Python 3.14 - full PEG grammar, ast.dump compatible output, built on participle.
- [gopy](https://github.com/tamnd/gopy) - A Go reimplementation of the CPython interpreter core, targeting 100% behavioural compatibility with CPython 3.14.
- [gopygo](https://github.com/tamnd/gopygo) - Transpile CPython 3.14 .pyc files to standalone Go programs.
- [gopython](https://github.com/tamnd/gopython) - Idiomatic Go port of CPython 3.14's Python/ compiler, runtime, and VM layer.
- [gsearch](https://github.com/tamnd/gsearch) - Scrape the rich content of a Google Search results page from the command line. No API key.
- [gsearch-worker](https://github.com/tamnd/gsearch-worker) - Google Search rich-content scraper on a Cloudflare Worker: Hono API + Google-lookalike UI, backed by Browser Rendering.
- [hn-fdw](https://github.com/tamnd/hn-fdw) - Query the full Hacker News archive from Postgres via duckdb_fdw, with zero copies. Stream row groups straight from the Hugging Face Parquet dataset on demand.
- [homebrew-bunpy](https://github.com/tamnd/homebrew-bunpy) - Homebrew tap for bunpy
- [httpclient](https://github.com/tamnd/httpclient) - Simplified HTTP Client for Go
- [hugo-brainy](https://github.com/tamnd/hugo-brainy)
- [kernel-worker](https://github.com/tamnd/kernel-worker) - Vietnamese Linux kernel documentation Cloudflare Worker for kernel.go-mizu.dev
- [kumo](https://github.com/tamnd/kumo) - Crawl a whole host into structured data
- [leetcode](https://github.com/tamnd/leetcode)
- [liteio](https://github.com/tamnd/liteio) - High-performance, S3-compatible object store in Go. An Apache-2.0 MinIO alternative.
- [mdn-worker](https://github.com/tamnd/mdn-worker) - Vietnamese MDN Web Docs mirror. Built with rari + Fred, deployed on Cloudflare Workers
- [openindex](https://github.com/tamnd/openindex) - A web-scale search engine in Go with an open, public, auditable index. Grounded, cited AI answers on a corpus crawled cleanly and published as immutable artifacts.
- [postgrest-compat](https://github.com/tamnd/postgrest-compat) - Compatibility test suite for PostgREST client libraries against PostgREST and dbrest
- [Python-100-Days-English](https://github.com/tamnd/Python-100-Days-English)
- [python-docs-template](https://github.com/tamnd/python-docs-template) - Starter template for PEP 545 Python docs translations (any language)
- [python-docs-vi-machine-translation](https://github.com/tamnd/python-docs-vi-machine-translation) - [Machine Translation] Vietnamese translation of Python 3.14 docs - do not use directly, human review required
- [python-one](https://github.com/tamnd/python-one) - Historical Python source tarballs (1.0.1 through 2.0c1) mirrored from legacy.python.org, extracted and committed at their original release dates.
- [s3-compat](https://github.com/tamnd/s3-compat) - S3 compatibility test suite for MinIO, SeaweedFS, Garage, RustFS, and liteio
- [setup-zig](https://github.com/tamnd/setup-zig) - tamnd fork of mlugg/setup-zig with action.yml on node24 + daily upstream mirror
- [sicp-docker](https://github.com/tamnd/sicp-docker) - Docker image for SICP build toolchain (XeLaTeX, texi2any, inkscape, Inconsolata LGC)
- [spambot](https://github.com/tamnd/spambot) - A spambot written in Go
- [spintax](https://github.com/tamnd/spintax) - A Go package to parse spintax, a text format used for automated article generation.
- [tago](https://github.com/tamnd/tago) - Incremental static site generator for Go - SQLite cache, D3 graph/tree/calendar, html/template themes
- [tago-doks](https://github.com/tamnd/tago-doks) - A clean documentation theme for tago, styled after Doks (getdoks.org).
- [tamnd](https://github.com/tamnd/tamnd)
- [vi.react.dev](https://github.com/tamnd/vi.react.dev) - Vietnamese translation of react.dev
- [vigo](https://github.com/tamnd/vigo) - 100% faithful, modernized Borland Turbo Vision IDE - reimagined as a self-hosted Go IDE written in Go.
- [zag](https://github.com/tamnd/zag) - A Zig interpreter for CPython 3.14 bytecode. One static binary, no libpython.
- [zig](https://github.com/tamnd/zig) - Daily GitHub mirror of codeberg.org/ziglang/zig

## Where to find me

- Notes and writing: [tamnd.github.io/blog](https://tamnd.github.io/blog/)
- Most CLIs have their own docs at `name.tamnd.com`, for example [ytb-cli.tamnd.com](https://ytb-cli.tamnd.com)
