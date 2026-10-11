# Repolex Knowledge Graph of python-trio/unasync

RDF knowledge graph data for [python-trio/unasync](https://github.com/python-trio/unasync), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download python-trio/unasync
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3a0a3bee2a8898766884adca297f1ad131da884b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3a0a3bee2a8898766884adca297f1ad131da884b
│           └── chunk-001.nq.gz
├── blob
│   ├── 055a113c27896d329c44ca282001c4dd61eabed9.nq.gz
│   ├── 0cfa1ee18a5710681cee0f6209bf9db40cfc2174.nq.gz
│   ├── 13d66eb62894adf14f2e82ea8fea626eaf5c34f1.nq.gz
│   ├── 16e3ec4fda659fe00268d44712385794435a39fa.nq.gz
│   ├── 2516c649b01e18803f4a2641651dd17bd96370bb.nq.gz
│   ├── 268e7c7d903b5d50410a5bf4f8843fb2e1039148.nq.gz
│   ├── 291bfeaa3b207e4173c50080f22cfb473363ee5a.nq.gz
│   ├── 2c7cf2364e3cb61d937c1d0ecbc20aa22d1e1cf3.nq.gz
│   ├── 2ef9215358376780582c77922fce15b009e6faaf.nq.gz
│   ├── 30e8d3747886eb833aaefe6007cdde132d051462.nq.gz
│   ├── 333d748311fc42c09260a7f1e93a1f1dd0def1bd.nq.gz
│   ├── 37ba775c328f52e30e2b766bd5f5686eb7328be3.nq.gz
│   ├── 4441194242d614f85b51a9188209ea00e0b25c1d.nq.gz
│   ├── 4b9bab0e8393619c260d5c17ccd8699cd511df3b.nq.gz
│   ├── 4f0cd41538a3451c2e1ed5ed70dd324718f3f2db.nq.gz
│   ├── 51f3442917839f8e0f0cccb52b3c10968ad0779e.nq.gz
│   ├── 5221b71cbad01fa27e58bef3589fcfc2fd8cbec8.nq.gz
│   ├── 53783441323b1640c0cbf6f69eed7b6869f6daf9.nq.gz
│   ├── 53cc93862914394f566865a9da32462f8f3465a6.nq.gz
│   ├── 5741cac9c96c17284e0656412443991e271871c1.nq.gz
│   ├── 5b626257f59526c7f5bb684c083f3fb1650f59d1.nq.gz
│   ├── 5e913bdbb92049a0ee445baf238b64f2bcf6e251.nq.gz
│   ├── 67898ba6f5cffa770a3110d8c996c8203cbbdc26.nq.gz
│   ├── 6a159b1420e13913c7c8ff4cf3bafd0d1e0555df.nq.gz
│   ├── 7215610c75a5997f0f7a533494949e39b822a379.nq.gz
│   ├── 78ca077de9fea94276f3ad494e163de0c910d84e.nq.gz
│   ├── 7bf791bdd3873fb5ca35687ef10639d9cf39c86e.nq.gz
│   ├── 82b8e54e71d3449dc0baf847f90fc558c8d42f47.nq.gz
│   ├── a4c23926de5665f51043db6f18cf28537635a688.nq.gz
│   ├── a5f4e075cdfaf0e86c02341ba4309358d2d1ecab.nq.gz
│   ├── ab5a3c8a25826fb2920c1ee39fc030345fc5f713.nq.gz
│   ├── ab9b7d5f045969681f8e958203e2b15b3efb6fbe.nq.gz
│   ├── b8bb97185926d7daed314609753173945ed4ff1a.nq.gz
│   ├── ba39583545348ff3b2d4cbf5f72db4104fb19029.nq.gz
│   ├── c05482e65846a1087bf14886267c2400fcb78cb6.nq.gz
│   ├── d20e3067d10091a10baf899ccc802303b57b989f.nq.gz
│   ├── d421bb309c48a91382f00c512ebd19049de23f74.nq.gz
│   ├── d5d6a9dbabc732981681d19f3727759953787f7b.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d784b3d054ef72ed371118a2505f2e0d83490245.nq.gz
│   ├── d7f339e51c25eeb9380e24a1ac6f7dd59af01dcb.nq.gz
│   ├── dff3253441fefee1e055c0e7a290566fc5b7b9b1.nq.gz
│   ├── e58f2c8df87d93d29ab6a010638c15a0b15a34ca.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f3f084e82a4c044f9ad09b1a294ac705d8178dc0.nq.gz
│   └── f96f4d3dfd00c35635e5fddd078ebd85c25ebd0a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3a0a3bee2a8898766884adca297f1ad131da884b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 54 files
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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[python-trio/unasync](https://github.com/python-trio/unasync)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
