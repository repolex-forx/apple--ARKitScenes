# Repolex Knowledge Graph of apple/ARKitScenes

RDF knowledge graph data for [apple/ARKitScenes](https://github.com/apple/ARKitScenes), parsed by [repolex](https://repolex.ai).

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
rlex download apple/ARKitScenes
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 474aaa83d7b1c9080619d8485de2d7c885c01fc5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 474aaa83d7b1c9080619d8485de2d7c885c01fc5
│           └── chunk-001.nq.gz
├── blob
│   ├── 03c989ac8ba1450e7168f88e2ab3155335bf4135.nq.gz
│   ├── 06a470be8f97e56fdae547fd6d60bebaa6147d15.nq.gz
│   ├── 087bbcd200af4925a48a1405e36544eff8346bdf.nq.gz
│   ├── 16f87ecded726586b7546175967dd47413c37459.nq.gz
│   ├── 1c1009c7f4539f769fdda4406f2063e1b158d129.nq.gz
│   ├── 1d65bc18f95dd1b2f337a572aca3475e93190e12.nq.gz
│   ├── 29efff504f86b6852f5b58b30f05e2726c08c6f1.nq.gz
│   ├── 2a374d963448085d43de0b749403225efc16a523.nq.gz
│   ├── 2c7526114f789b2fe27dd6eb5e06eff2d8433563.nq.gz
│   ├── 2d1929a513eeffdd175f57a81d27f48d4f1cfd0a.nq.gz
│   ├── 3401a39b52bf2716e0ef82b61feb21a274d8e257.nq.gz
│   ├── 340d276dabe5d9c9a361d8f697dcc03ea76ec10e.nq.gz
│   ├── 36e73325c50c4f13c24a333a5754592f4ec3d954.nq.gz
│   ├── 39842f31b6dc28fac0d9118f246d493dda1c3a71.nq.gz
│   ├── 3c32ab32192e31739bfc5320be86c256891ab489.nq.gz
│   ├── 3d8d5d1939b3982a6ca0d51fb1ed09254036678e.nq.gz
│   ├── 4025b28fb176ad852aa1dc70368857d4e391522a.nq.gz
│   ├── 42d81484e8d129982f6d0afae0f26a131695defe.nq.gz
│   ├── 45be0c5719e31da245284fe649e1114858b0ae3d.nq.gz
│   ├── 478947064d918b0a8a4d83c6bb86ca394625c589.nq.gz
│   ├── 47f2b3c4718c65b47b2361b09beb91e57bc1ae24.nq.gz
│   ├── 4a0832f427047888b41e4338032959ab42927666.nq.gz
│   ├── 4c21f777843eb9422bf666cfdb0a24f6c93d3aea.nq.gz
│   ├── 50319b3d443e32b945c8fcd0a71831fad7b05844.nq.gz
│   ├── 51bb66cce1572bd470a4534998e911a9f240209f.nq.gz
│   ├── 51dd1929e7861014cda38854990cd9b261f5bfce.nq.gz
│   ├── 5366acdf2a54df9ea63cf5cec4915548ad161f8f.nq.gz
│   ├── 616cdcd93badfb1eb87c02e9ffc25760854a7592.nq.gz
│   ├── 61e9f92ffb2ae1dd0c9bcffc0740ceeac2a10c5a.nq.gz
│   ├── 66166d50b89ba6e603989b2c844beb47e1c60bce.nq.gz
│   ├── 6b57bbde06f67ac8ff3cc2bc6894c8b5782c34c2.nq.gz
│   ├── 71079496f778a4c3bfc27e0d05f24ebf460e5ef9.nq.gz
│   ├── 73406f8db19fb7c2dea6e96b48e7d95140b25814.nq.gz
│   ├── 7bba109f31efa4ae541b2008e9e9621abf4669b0.nq.gz
│   ├── 7ceeec5712add7f3fc5b026fb79e03471cafd09e.nq.gz
│   ├── 82b51946662c5d2d40f0b19e8cab57475cba17c3.nq.gz
│   ├── 8b6b1a0f320a7394160e74f9b13a111e9a8de749.nq.gz
│   ├── 95f607fb436414889f125bfa3ecee7242cacaa0c.nq.gz
│   ├── 9f266a9b06444c309db233b0cacda5e809df3b41.nq.gz
│   ├── a4e3661513897c66ce3c8d0cdb96ab624930f9c5.nq.gz
│   ├── aa2b994c85fb0eee09bcca8c1724908e71838a40.nq.gz
│   ├── ac565d42b1ca8301af5c615ab203363f41ff39db.nq.gz
│   ├── b060ec4526d0bcc72d9226eab059678f75f478c1.nq.gz
│   ├── b3c2708e3a95107dc3b1303bfa2de13fdab980a8.nq.gz
│   ├── be59641e5fa86473993087fd70c508c3f9ee37de.nq.gz
│   ├── c4dc40beab38624cfe6f7c3ef532a5f6671b69fb.nq.gz
│   ├── cfaa552c594c8dd255b126caf1df08bf62d9a1b3.nq.gz
│   ├── d426defe7ffae94b3b0cf3497725b0ce8c310144.nq.gz
│   ├── d780d1b4b42c529cd590b4a85daa9731e5b8c90d.nq.gz
│   ├── df9979ffc6091e0f6dd22eba469a1cdcdc2bdbe3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea5c93131ca1b505cc8e5634bee36a851618bd55.nq.gz
│   ├── eb1c0b0da905adaf942519ef1581e56e5dbc9253.nq.gz
│   ├── f1726d08664d32a4d750b5e619d662f4a7a017ab.nq.gz
│   ├── f2ae24623440bd1ad17261b9f312a1a73083547c.nq.gz
│   ├── f662209bb17ee4a2f94546471a5a4b23d83237b1.nq.gz
│   └── fbb6f7a8fdb2b9b605a5d42ea535f5deaeee8ad2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 474aaa83d7b1c9080619d8485de2d7c885c01fc5.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 63 files
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

[apple/ARKitScenes](https://github.com/apple/ARKitScenes)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
