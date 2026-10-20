# Repolex Knowledge Graph of pylint-dev/pylint-qt

RDF knowledge graph data for [pylint-dev/pylint-qt](https://github.com/pylint-dev/pylint-qt), parsed by [repolex](https://repolex.ai).

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
rlex download pylint-dev/pylint-qt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 93e40dcf81190c4cbdbaeba1b41c06c97cbadfc9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 93e40dcf81190c4cbdbaeba1b41c06c97cbadfc9
│           └── chunk-001.nq.gz
├── blob
│   ├── 05bee367b2af32d87157c32811f39d519d8b5b44.nq.gz
│   ├── 0823cd55c60e71876dfa5f648364f0d88271cd55.nq.gz
│   ├── 15e3e3dbc9713bd468f8631e3aa684f28a970015.nq.gz
│   ├── 1a4dbeb973ce1993271eb18c8d616dfaa2b22c7e.nq.gz
│   ├── 1b04e06be3392191e446297ce62698f54976b136.nq.gz
│   ├── 2940be363588e358df074c7a1c5841a96e62b396.nq.gz
│   ├── 347720d8a2ec24ab4244161ea17d0b204e8ebc45.nq.gz
│   ├── 3f68f108bc3d64d4bac45a57b4018efb63f4937a.nq.gz
│   ├── 49d0fe86cb5adf5cefbb861a0b94201d00cc792d.nq.gz
│   ├── 4a79d834d8eb52aa3461571900b186f943b977eb.nq.gz
│   ├── 4d2910a1bc94aaf8b7299dab19f03faebfde519b.nq.gz
│   ├── 4f3612c6c94d6660fd91bfb4e83989d7996317c9.nq.gz
│   ├── 50b224043bed215b3c541d589e48a5520006d85a.nq.gz
│   ├── 52e4745c085ef673ae99c27cb86416bf0ad197e5.nq.gz
│   ├── 5881f87c218e00026a8342b63c520944b9740b69.nq.gz
│   ├── 6313b56c57848efce05faa7aa7e901ccfc2886ea.nq.gz
│   ├── 72599ddbd8089fd4d6740fbbbdcbeca65ad79038.nq.gz
│   ├── 72d724f4b5b8a6d7eca53854a85f6cf380ff473f.nq.gz
│   ├── 7729f469cab54b45ed7e9e64595643772fa55cfb.nq.gz
│   ├── 7c4c6b44b6fffaec80c752fca9b224e3bff6d1f7.nq.gz
│   ├── 7cd380e972ff016496dc466ae44090929878f294.nq.gz
│   ├── 82bc881faf96a408e56b57ebf384cf2f999e44f9.nq.gz
│   ├── 8cd906fb148902923d48b7dfb1b722d073ee21eb.nq.gz
│   ├── 8e3020ab330d753f28dec479cd004d2f4b60e418.nq.gz
│   ├── 980b3e3e70554d91c99f5be4f1062c96f5088c31.nq.gz
│   ├── 9ccf58c10dc40de0b44278aff3df16836812f38c.nq.gz
│   ├── 9d9d9e412dd68d98d870ff1a96b5af67db37e88b.nq.gz
│   ├── 9f73efdaea628387f192e507780bfcde5553deac.nq.gz
│   ├── a142eb2276c209d967792eea7acf233f325330b5.nq.gz
│   ├── a408f2d8bba0a82596c49766e7d117f5d619ee67.nq.gz
│   ├── a42e3a9c9d870aa605240c4f713480fb87c79c32.nq.gz
│   ├── a8a43cb3eee4557c5c54bfa64cb518167a4104d0.nq.gz
│   ├── aeaaf8fbc0dc5cb01d65e28d67ffd346a2609d6b.nq.gz
│   ├── b1b282402c21ea9ef4f8c889249089601c129297.nq.gz
│   ├── b588f584f318a4c33359e04c7e52f964a3b2016f.nq.gz
│   ├── b82e3a10814cae87bd091468a8cce426d76a5349.nq.gz
│   ├── bbaa1ae342805b9f6cd3f4dabca5a47874395402.nq.gz
│   ├── bc206560f602cf26f85210096ef4329f8e0a9a10.nq.gz
│   ├── bdce3be53334e3dc641bd23babcca1274f277803.nq.gz
│   ├── bfe5a6e03182758f9224be22d11d7bc6591bc91c.nq.gz
│   ├── c12e06e15d47d8b08b0f86af011729e043931d0c.nq.gz
│   ├── c22887d179b2d1d617eb0d744f9a9fe778d28ecd.nq.gz
│   ├── c3cea564491f486445f975360edf5d3e5cf0ea5b.nq.gz
│   ├── c5a60652c0c5d1cb3112b6687582eff811b91198.nq.gz
│   ├── c900320d8e440878c30932d6cbbeffe4a992844a.nq.gz
│   ├── cdeac82c761bb062106017950840328810056d82.nq.gz
│   ├── cfbac83900a7c120ae41c0d5c31b5d4e46833544.nq.gz
│   ├── d90660a19cb2d6e90b9646956d7c1dbd46389c04.nq.gz
│   ├── d9b9620cf104025f901f5eef8bc0071161891f32.nq.gz
│   ├── e1e9859ee52ff958188ce113cfb6094aa2fd35ab.nq.gz
│   ├── e365e30e959dcdd7dabe58e44b8a41de2362320f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ef6698b6623a898e45cec1a2f4b9634893bb5a71.nq.gz
│   └── f188551d8fe06734e0ba96057e1c67b2a2641178.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 93e40dcf81190c4cbdbaeba1b41c06c97cbadfc9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 62 files
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

[pylint-dev/pylint-qt](https://github.com/pylint-dev/pylint-qt)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
