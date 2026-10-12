# Repolex Knowledge Graph of Pylons/deformdemo

RDF knowledge graph data for [Pylons/deformdemo](https://github.com/Pylons/deformdemo), parsed by [repolex](https://repolex.ai).

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
rlex download Pylons/deformdemo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a54e82d97cbe07da4df207757765f462b0e0d67c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a54e82d97cbe07da4df207757765f462b0e0d67c
│           └── chunk-001.nq.gz
├── blob
│   ├── 0389ee33dea38b01ab7be9144b424cd60c46f3a3.nq.gz
│   ├── 06da517120a4126ce279b66e29fd4e6049e67cbf.nq.gz
│   ├── 1b263fd9e84a69152dd2f307c497436817716b28.nq.gz
│   ├── 1b28969ae92a8927167c03a61f2450dd69498eb2.nq.gz
│   ├── 1f58328826b026630400da62b32f718ccf5c9b8e.nq.gz
│   ├── 22e0d92bf0f86f10eefd267592a0386dca649922.nq.gz
│   ├── 2a7eca1b98aae29c15852943b64d44348d13bcc8.nq.gz
│   ├── 2afa2a0325a5a56d6c0983c4e53b8d0daeea702e.nq.gz
│   ├── 2c0537c386f4bb886c17bcc85cbc06ffb040ce5a.nq.gz
│   ├── 2ea82cb93f818ccd0622230f4fc16b55318b157a.nq.gz
│   ├── 2efffe2c8704c1672db9d6e52b2fd92acd09ec2e.nq.gz
│   ├── 2f1b177588f3ba86cc5f33155cd61605c909a3fa.nq.gz
│   ├── 375a6cc6eca202b937508aeb75f6a71fb3f0f301.nq.gz
│   ├── 3a96965ee8d3058bb19f4bc36f1d96d9c531926f.nq.gz
│   ├── 40f6b89fa771a0f20f4b2714cefbbbf84afac567.nq.gz
│   ├── 438404e4e04ed519959eca93e705ddabcb7f9100.nq.gz
│   ├── 47a46406ef942f6f0c7f1b9e7432c853eab4b27e.nq.gz
│   ├── 50080860d4347124369f20c3e83b1aa58d9485e0.nq.gz
│   ├── 5015772cdcef1e02ce2a01e566581ee13bbe159f.nq.gz
│   ├── 57e16816d2e482daa47c55f8c693d7db509f9bb3.nq.gz
│   ├── 58feb691dc5776c6001d23626d7b05caa1f422b3.nq.gz
│   ├── 5aff4f9bfe9eeb2b83d4bf5440812be0f5e2eba2.nq.gz
│   ├── 6b5a779028b299bc047b69d0b3ea153cdbacffbf.nq.gz
│   ├── 6f5f5ed1d84d6ee08f302c492f82d1714ff13979.nq.gz
│   ├── 745a7739445827ee1a7ccffa8d329132889c15d3.nq.gz
│   ├── 75ad13359a4c0c69f1bba9a5c05cb0516e17e1d1.nq.gz
│   ├── 7a09f6f54e0527b0957152e92b256a98dcd5cfb1.nq.gz
│   ├── 805d758f99b52f288a8ecdb26924ba2a8a131f2c.nq.gz
│   ├── 82bb4134ad84761af37f07c1fe901473a0cf8613.nq.gz
│   ├── 8a0b85b6cab2168bfce372128d4e310e1607432d.nq.gz
│   ├── 90006e00471c858b36149c94ca63b30633b19d85.nq.gz
│   ├── 982a7c111d5a1ca20a48f4c4ffc35d6b6a811970.nq.gz
│   ├── 9da5251eb08a5afcb475677b945aa635438d0811.nq.gz
│   ├── a440bc8b6c0271341e860114e3cd217e4e037a62.nq.gz
│   ├── a7a964faf708a55a28c2bc62b538aef749d6ee39.nq.gz
│   ├── a916c8bdfea0a5f8a9ad66b035810a888b96779a.nq.gz
│   ├── b096d37719809f720ed72cec63757a516bf4f9bb.nq.gz
│   ├── b3fd4a2d2072d0b57ba4873318ecb6e93585baa5.nq.gz
│   ├── bf8d94247667e270b3fe6ea443787dda1ba0df87.nq.gz
│   ├── bfead2ca040c32ab6b088cbe7534a804075720f9.nq.gz
│   ├── c09ef2e1f2fb5d9eb40437d86a9e73fcf213d1c7.nq.gz
│   ├── c0fcb97de215ad9cb143b8701f9f1577c6d8ea02.nq.gz
│   ├── c5188bed807fab20e78b007c755bdd515b0e921e.nq.gz
│   ├── cf0d8a0b9ff8a784a6712989fa0a73b70689c994.nq.gz
│   ├── cfeb05e9f51df12da8bbfcaecf67b17e88b41ab3.nq.gz
│   ├── d0c57d8d484b947e250469ec8d61a44c03bcf26e.nq.gz
│   ├── d9e7c7ef5d9c22db3d3eef1397d84c33e7bc2fc0.nq.gz
│   ├── dd1eed888c5fb0d42908bd3f744fb743925143be.nq.gz
│   ├── e065c97dbb1bcb43f2917b492e7b2ae3073aef7c.nq.gz
│   ├── e623ff83e99eb3d3065d0916af3e65ce456f8e4e.nq.gz
│   ├── e7a6ee3476dc16a2b46f318cbfc8031169788545.nq.gz
│   ├── f696eb78d34418741ec059a38114b73a72db08c6.nq.gz
│   └── fc0b2439e826acd104da153ef128538254a66275.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a54e82d97cbe07da4df207757765f462b0e0d67c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 61 files
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

[Pylons/deformdemo](https://github.com/Pylons/deformdemo)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
