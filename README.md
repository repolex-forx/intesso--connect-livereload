# Repolex Knowledge Graph of intesso/connect-livereload

RDF knowledge graph data for [intesso/connect-livereload](https://github.com/intesso/connect-livereload), parsed by [repolex](https://repolex.ai).

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
lexq download intesso/connect-livereload
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 13a8cca3192dc077f01e5681cd393681f9e6b060
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 13a8cca3192dc077f01e5681cd393681f9e6b060.nq.gz
│   └── repolex
│       └── 13a8cca3192dc077f01e5681cd393681f9e6b060
│           └── chunk-001.nq.gz
├── blob
│   ├── 05ade97ffa297e849a3633aff9cec66e5eea939c.nq.gz
│   ├── 0a90f884c63bc2aac0e881acbab301d5a14580f6.nq.gz
│   ├── 0ccd1faf14db601cd060d0eefd4decbbc8f85446.nq.gz
│   ├── 0e1715d462c8d33c8b95d532d5581582ac6df654.nq.gz
│   ├── 125b8d1ac054cad7e457bf022ecf8d71c7845678.nq.gz
│   ├── 1931efa00c9c13424586f96065bcd3ab2a0491af.nq.gz
│   ├── 1cf4c00a097c719e0ee48d577e953ec31e5c0994.nq.gz
│   ├── 23eab8b8d218435f5d5d9e2f4ce4777505518c65.nq.gz
│   ├── 382a1ea21a1289d3eb5398214441d8c88cade5bd.nq.gz
│   ├── 393af10e88cde3856906feea967feeee5ef41356.nq.gz
│   ├── 3dc1064ffd6027dc2d0b57a4fdeb71cecb2f0d84.nq.gz
│   ├── 44696c5e8d7c4b6535f4eb36610058a5797174c4.nq.gz
│   ├── 4dd9fa9b20942743a9c86e959705ab00a30877f9.nq.gz
│   ├── 5072542865f46fbf5cbadf3a4bdca3b8ddd0d0c9.nq.gz
│   ├── 5a51f243caa31a3d25f12b30e9cf9f2f83ac4860.nq.gz
│   ├── 66a5483630a2a3914bbafd8784ef1aa829785877.nq.gz
│   ├── 6763174c5b04d5f4545cacb2ace494fb69b96288.nq.gz
│   ├── 70659d8b08bb335276804806bc2934921d3d38da.nq.gz
│   ├── 70e8fef9c730f643ca5e75ea7c657189730cbd1a.nq.gz
│   ├── 782766f4d1f8c8b3ff9e4adb206b03d66052eee6.nq.gz
│   ├── 81fa4ceba306ce2e9fbe52e5c3fbfd7743f1bfeb.nq.gz
│   ├── 8580ba20eaf2677f7c1221d08c9c16900af50079.nq.gz
│   ├── 85ee0c3b5d90d6c3aa32eb3c5cd2e0b0da2fe9d9.nq.gz
│   ├── 9c107df344f93a5d34950ad0dfdc08bebe96a415.nq.gz
│   ├── a85728e715cfb1fdd319351ca31da7064336fd16.nq.gz
│   ├── ad0534ab753c19a9b2f4ba7786e468f6aaead45c.nq.gz
│   ├── aeda9a75026f4b70764e76a249795c5f7fc74868.nq.gz
│   ├── b02c0106d704336b856dc3cf4f1797ca0f1eb05f.nq.gz
│   ├── c67b72256dd2cc66dd36ef3a380d808b20d758b7.nq.gz
│   ├── cc9f0b1ddcffe6fc0a6f0fe2f3794ced38fcf3fa.nq.gz
│   ├── cdb9c2c650ddf2960a3069e0ab48bb9ada621f5c.nq.gz
│   ├── dffa9cb77a0c7b0d80b1705d851c4118ea2f9635.nq.gz
│   ├── e6a32fe99304819efce5db32eb3f4cacfe531713.nq.gz
│   ├── e793da9bedafd11c3be498f85074b169e2ba4ef1.nq.gz
│   ├── e9a46087b736214414835d35bd014051d399d627.nq.gz
│   ├── f2a1bc0c6f545e20e631a96e8e92f9822e75d046.nq.gz
│   ├── f4d32d0e9815216247a488d9fd252253083824e9.nq.gz
│   └── fb47018ea037a594577f955db44a7ac3594ccc53.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 13a8cca3192dc077f01e5681cd393681f9e6b060.nq.gz
├── filetree
│   └── 13a8cca3192dc077f01e5681cd393681f9e6b060.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 48 files
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

[intesso/connect-livereload](https://github.com/intesso/connect-livereload)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
