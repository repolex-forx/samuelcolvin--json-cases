# Repolex Knowledge Graph of samuelcolvin/json-cases

RDF knowledge graph data for [samuelcolvin/json-cases](https://github.com/samuelcolvin/json-cases), parsed by [repolex](https://repolex.ai).

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
rlex download samuelcolvin/json-cases
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 12caaa624f399d603db09dd634ae866425f737f0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 12caaa624f399d603db09dd634ae866425f737f0
│           └── chunk-001.nq.gz
├── blob
│   ├── 0364f5cee0b88beb16aca7313426e33b244aa182.nq.gz
│   ├── 0d1b99d039ec5f922287219dea10966b43b052d6.nq.gz
│   ├── 0d345818a0e96951b98eb6e3dea957103b4c4987.nq.gz
│   ├── 1406512174be1301c9abd21870a49255dc82611a.nq.gz
│   ├── 16a681078a2c1d3e5a6f004be9e1804ba0d9f0d6.nq.gz
│   ├── 2a008fa32ecb8f4e255c2937369b8d4aec717348.nq.gz
│   ├── 2ffc54c2c2e58721ba6ed3b712da21aafd98f69c.nq.gz
│   ├── 3944d8fb2ee4cfe85054464e40e2527a819e0240.nq.gz
│   ├── 3abb15d43159210be9fe55df1b8061f10b609925.nq.gz
│   ├── 48e0805c5ad611639ecff132cfe7a610ab392a49.nq.gz
│   ├── 4ead1661c4acc908d19ba4fd639356fd37087026.nq.gz
│   ├── 5054e5c80418bc9130756aaba8367782aac57f5c.nq.gz
│   ├── 516aa1bc660979737fe06b9e8dff2ae44693f567.nq.gz
│   ├── 5187d4a49cc799de6301a5a55fd6e2a797b400f5.nq.gz
│   ├── 532fb4522265956e9b4d7451c082988b3c3f56fc.nq.gz
│   ├── 5471826d28d357677a1ff0895ae484ee6da8077f.nq.gz
│   ├── 54a8056181d4f8df43f8df1f00b95121bc81590c.nq.gz
│   ├── 55fa8df05e88d9ab55c0fdc08ddb6ace8a4a5a87.nq.gz
│   ├── 58434afa8c477f9e7066f39581170ca693930cfd.nq.gz
│   ├── 60edafec2a7c8f6f15f67b346c8714ef23ea8b6f.nq.gz
│   ├── 6766881e427ff28f95e5962092715c6afce3bb15.nq.gz
│   ├── 6d904feec264067cc80b9f0bdf52e80f03c5f437.nq.gz
│   ├── 70880ad653eae083d0d27a6f82a5b0c7dcd57af6.nq.gz
│   ├── 7152447443de951eae8e7453074f78d4ae61c195.nq.gz
│   ├── 7a85e852fdd92a65fdec77698360eb989741c94d.nq.gz
│   ├── 7aa6dacb63ac048b9695a246368b3c2959a85041.nq.gz
│   ├── 7bc90a7fa8ab5c80ce8907595046bddcfe8b20ef.nq.gz
│   ├── 8150fbd86f758055330467d076b32e452af05882.nq.gz
│   ├── 8597a62d0e33841a01fdbdcbaa4d7e00b738287b.nq.gz
│   ├── 8f607a425d0d22f0b47a473ab4be8f381b4d3481.nq.gz
│   ├── 9079dd76ba3187f70255611b61bca9bffd2617c0.nq.gz
│   ├── 9380cd316e337fcf5e3b8bd2e3a72999a4491237.nq.gz
│   ├── 95063146e728a4131bee79d9b69a22b935ca0e58.nq.gz
│   ├── 9c22bb95a7f2d18a93c4e54b36f58e8c24ee6f44.nq.gz
│   ├── a461aadaae285649ffcaee8f98b7ae55c60f37bb.nq.gz
│   ├── a60c6892ddd9fd414614d0b2eb7e93c401cb18be.nq.gz
│   ├── a655a0a7347434e9bf3dce24bb234126c23fd6ac.nq.gz
│   ├── a6d025270a0f812ed9fd0a6fcb04ae594881c194.nq.gz
│   ├── a965550a1df9666f1e66799ffc2c281490bb1e18.nq.gz
│   ├── afa99a91d987bd6374c4bb1601c1a6c3d277609a.nq.gz
│   ├── b3b830da26100e6a79814b2a03b324b8117c1321.nq.gz
│   ├── b4eb56b48c05cd16996d4cdb34ef026262d777c7.nq.gz
│   ├── b7ed9d6246676b03d136e208efe3b1748731f387.nq.gz
│   ├── bbfb4a59aafe3ffc95e5b57f69b0f7622404b2f7.nq.gz
│   ├── c18b01b8d166feb2e4df83b1e14b4f9e2bb32e4a.nq.gz
│   ├── c3e5ff575dfa25e1307dcbdf03ce3b7bca5e9379.nq.gz
│   ├── c4b3621d5d59f56b7b43d84386e5501f72f4ce9c.nq.gz
│   ├── c637ca6ef34794892e8b4eb355b4104ad9d0ae65.nq.gz
│   ├── c7cce60c1a18d91f2764b85c462aaab876d27b95.nq.gz
│   ├── cc5f5c8230a20466801a5fc9408eeb559a945f3a.nq.gz
│   ├── d30ac52dc1727d9b88cc1ce816a70ca66dc5df31.nq.gz
│   ├── dd0f4594b036a4575eb303a2ca7aa7180d0d1cd9.nq.gz
│   ├── dd38749c7e050423caf48a7212326651ee8b0012.nq.gz
│   ├── dd5cd412512ec75cce55b22a77d68830cd6cc6a5.nq.gz
│   ├── ddfc48f7ceb9d2906a7e67f6a52736ab30c33230.nq.gz
│   ├── e50d8395f60b3ba611d1e08c2678ea8e660ca83d.nq.gz
│   ├── e5ed5d5f7c606208ef82f7e7a3086de85a683cab.nq.gz
│   ├── e5ef62906914874c758a20091c29cf9a03208444.nq.gz
│   ├── ecac55485cb9fb8a149373f8b901940800c573aa.nq.gz
│   ├── f0c2ba91354a0962dae5e8c4f316fac73a4d49b1.nq.gz
│   ├── f20399e55e3eb8650f9fc0a817a7ddd696997374.nq.gz
│   └── f300b76982abfbbc3e08c0158ac12d64001ea177.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 12caaa624f399d603db09dd634ae866425f737f0.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 68 files
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

[samuelcolvin/json-cases](https://github.com/samuelcolvin/json-cases)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
