# Repolex Knowledge Graph of tkem/cachetools

RDF knowledge graph data for [tkem/cachetools](https://github.com/tkem/cachetools), parsed by [repolex](https://repolex.ai).

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
lexq download tkem/cachetools
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5dce86fc5c9c565c6e9c912e2be5d6abb9586a1d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 5dce86fc5c9c565c6e9c912e2be5d6abb9586a1d.nq.gz
│   └── repolex
│       └── 5dce86fc5c9c565c6e9c912e2be5d6abb9586a1d
│           └── chunk-001.nq.gz
├── blob
│   ├── 0515793321b94bcfc5b40a2cadaadf11990ab216.nq.gz
│   ├── 0637d78f4b83f19c9494ba578fafe5eedb527ae1.nq.gz
│   ├── 1a01fba8fad70860a368b819f26a1eeaa5f7d803.nq.gz
│   ├── 1fbb94a08e7a231e64b88a6e80039238c3dedc72.nq.gz
│   ├── 1fd363a8922b1c02634cd3c594c1b8e4e9701d06.nq.gz
│   ├── 20c7a7d7d45e625f8b06712da62e96936469bd80.nq.gz
│   ├── 2990f99eabf1e875b74cb9a78c66264d5c0aa786.nq.gz
│   ├── 2b1634acf03df44365baa3a4774811410c7c5449.nq.gz
│   ├── 31c5680d62f0d4697e0d351de08285e34276fbe7.nq.gz
│   ├── 3955f720127945561e621263d1653bb32db35290.nq.gz
│   ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
│   ├── 5b09d5ae6494348775c1e23d18a64c2b63b74b2c.nq.gz
│   ├── 64b61dac32b08a34039ebfb45750a73132408a47.nq.gz
│   ├── 6bdf0cfe8a0150aa0b485966f407d97d36afe103.nq.gz
│   ├── 6c7dff4afe2c0e1d04f9e0d02e9bbca6523665a7.nq.gz
│   ├── 712ea5f679ae3e37e5dac087b1480bd6461dba32.nq.gz
│   ├── 7c3c2b62241b9df5728ec513441044863c9f1201.nq.gz
│   ├── 82bdc5f10d841d70569691fc39d010ccb0212107.nq.gz
│   ├── 8a9c463a47cfe43be06d98b8576368ef78769d6a.nq.gz
│   ├── 8ac6b8c4984dcd382e54c7923325af6d226ca3df.nq.gz
│   ├── 9297877668b00f4c264383a835186cd3c341d408.nq.gz
│   ├── a45a6790827864e6e695a2ef564380ef95b19386.nq.gz
│   ├── a62ab055c94b9de27aeddec59815d59a6dc63278.nq.gz
│   ├── ab917d3707cdfee82ac89cf758592c2b0dcdfac4.nq.gz
│   ├── afcb196d719dc292073d3c097604b908e139d94e.nq.gz
│   ├── b50482ed40010b3119c6d90fdd3a6a2b5f885dce.nq.gz
│   ├── bf4419f1bfef94d0348ce18f35fa6e7e6e3dfaeb.nq.gz
│   ├── c3c6aa63da7c2f35c97ffbc4367ebd8ce6dfe6c7.nq.gz
│   ├── c4b0a4f0130a3cc9e47a6ae80c22b6c62f9ff382.nq.gz
│   ├── d689ec7a704b00b26626b40a4e193e69d0e83879.nq.gz
│   ├── d9ac52270e6fe5fddc7d33981dad51ce984f37e7.nq.gz
│   ├── dd65a5dd5fbdcb2055d6f17840c2b6054086b796.nq.gz
│   ├── e309f69932bbe1be69f0aaefd94535fbb957e4cf.nq.gz
│   ├── e9a09e53929e7f83686f6ab372e018d9f919dd9c.nq.gz
│   ├── ea0dec62b3bf01442035cc23f6596d72f4659d5a.nq.gz
│   ├── f5ed8e169e0f0b8a3d90ef07366d2820322e2bbb.nq.gz
│   ├── f980a19c78c25959f922b8cc93854d91a89e686f.nq.gz
│   └── fbd16e32b09c59a7d9e32db5412c25decb3cffa6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5dce86fc5c9c565c6e9c912e2be5d6abb9586a1d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 47 files
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

[tkem/cachetools](https://github.com/tkem/cachetools)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
