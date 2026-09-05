# Repolex Knowledge Graph of dtolnay/anyhow

RDF knowledge graph data for [dtolnay/anyhow](https://github.com/dtolnay/anyhow), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download dtolnay/anyhow
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5c657b32522023a9f7ef883fb08582fd8e656b1a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 5c657b32522023a9f7ef883fb08582fd8e656b1a.nq.gz
│   └── repolex
│       └── 5c657b32522023a9f7ef883fb08582fd8e656b1a
│           └── chunk-001.nq.gz
├── blob
│   ├── 018267d315fa7c51ad6d8c26f6e97b5db23f7761.nq.gz
│   ├── 0689506965430f17d2f9ffe0c34a225e34c93d9f.nq.gz
│   ├── 080b3b9e00e3c987cc34bd3edefda3844b95fea6.nq.gz
│   ├── 0b5f69fb03c57f8becbf037bb7d7c22c6451bdce.nq.gz
│   ├── 125fe36ad7a12ed9e5375f5f1519209c8011f791.nq.gz
│   ├── 139b743bbf9bdf9a7fe6b4ec3fa90a57f8fa0306.nq.gz
│   ├── 1558de56a25236181d4b8d12e7f7614d147cdc6f.nq.gz
│   ├── 1b5ec8b78e237b5c3b3d812a7c0a6589d0f7161d.nq.gz
│   ├── 2053fc9e571449d60a984db464e10c6fd651e743.nq.gz
│   ├── 20fe888c30ab44fa877a58de0304f4b5e2a5a5cf.nq.gz
│   ├── 23a6a065ec960a031726c8c26222b0405d4f5851.nq.gz
│   ├── 2976cd86204a54e08088d7ca76a91ff15c55c790.nq.gz
│   ├── 2a4c66508a0a651806b5e77ae97e97267c123145.nq.gz
│   ├── 31aa79387f27e730e33d871925e152e35e428031.nq.gz
│   ├── 3343e7499a5ef861532de1e88f9ada69d1d63088.nq.gz
│   ├── 4521b51c8ca216e795cbe0292bd9ae684ff813c8.nq.gz
│   ├── 4d6b3ab322937a45b8180ae705503816151688ff.nq.gz
│   ├── 52e6ab6fdb315e935c80f8bed8fbfb121c3f0493.nq.gz
│   ├── 55a29641136719dda63cb8f6570871418e306ece.nq.gz
│   ├── 59578af91a666d8ce2dcc58fcb490ba42311eafa.nq.gz
│   ├── 5a4e0eccd5a33a5717c1e878152e7de8bb06dd17.nq.gz
│   ├── 6da171d1b8906687e3cbb3fbaae8faf864b66d3d.nq.gz
│   ├── 74f1fa1c9509ea11a0fef8149c64a6e58c08dac2.nq.gz
│   ├── 750707701cdae985156601cc906195021ba6a6e5.nq.gz
│   ├── 78225bb6603f14ecde59db68a0f4dd19048a5b58.nq.gz
│   ├── 795757d4b77561836d5a522a71bed973873a0722.nq.gz
│   ├── 7da4bf55a1042f31b0752a125e3f9368462e65dc.nq.gz
│   ├── 803809b238f0d2109be19bd53142ee0582b69732.nq.gz
│   ├── 8206f22c41dd712ef4ef63dd155e12ab625818ef.nq.gz
│   ├── 938c1c24ee3215b438cee98727f5cab27029eba0.nq.gz
│   ├── 9a108cba0a9936715a95690b944a36febbf9305f.nq.gz
│   ├── 9b584df412c208d8452d6e77ad8ab3bc0192e294.nq.gz
│   ├── a70d6ecc980bd17cb48888ef1b678aa8f24978b6.nq.gz
│   ├── a9f40c33d42970fe7187d04199f1c9bff408a667.nq.gz
│   ├── b2a3f3146a448ad79ca2588fe0ed65c385e6b144.nq.gz
│   ├── b4470d551ab49783f0adcbbe4596497b26591755.nq.gz
│   ├── b870ca713d4adf9625bc06b4d9b4ba1761d0bc77.nq.gz
│   ├── b978631acdc43039dbb1e969684c2b141538003d.nq.gz
│   ├── bad3ddda4fcd1dc5f80b7843f404288fac0f04d3.nq.gz
│   ├── bf0229a2b238b3be78b35b4d7793c7e474056219.nq.gz
│   ├── c7df4e17c2f3dd8f6a68b5e56811fdde9f68af56.nq.gz
│   ├── c8b901ab41d8f549680e1b458ed74d0ab199df06.nq.gz
│   ├── c92ec92d461f36a36add0ca7dc06d9e109f9b45c.nq.gz
│   ├── d2e89afc1b36e2c053381a3ed8420490d0954eef.nq.gz
│   ├── d9ae520a9c74ad4eb207db27439d4765b3d7f34b.nq.gz
│   ├── dc95160609a6ebb8ba5e7c61cadacd92210846fa.nq.gz
│   ├── e4d2ca8fa51a7118bff269dc66b03f8fdf744e04.nq.gz
│   ├── e56bc6696280ef303d352e08f9912830ade4b90f.nq.gz
│   ├── e9e21997b1aca0707f8749ea13c09aec66c899d2.nq.gz
│   ├── ea4e58f55ee43cd023b63c11749e9da7197c0140.nq.gz
│   ├── f4fbc94d5f9ce54b954fc0d3229872c9dd440c84.nq.gz
│   ├── fb1fb132d50c8eacdf9aaf61250c0ce6aa91a413.nq.gz
│   └── fc165a5be90c76446700891ce55a70cade729981.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 5c657b32522023a9f7ef883fb08582fd8e656b1a.nq.gz
├── filetree
│   └── 5c657b32522023a9f7ef883fb08582fd8e656b1a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 63 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |

## Source repository

[dtolnay/anyhow](https://github.com/dtolnay/anyhow)

---
*Parsed on 2026-09-05 by [repolex](https://repolex.ai)*
