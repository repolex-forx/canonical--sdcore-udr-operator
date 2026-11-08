# Repolex Knowledge Graph of canonical/sdcore-udr-operator

RDF knowledge graph data for [canonical/sdcore-udr-operator](https://github.com/canonical/sdcore-udr-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/sdcore-udr-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2405e4e92f2593864bb74abc55c0275b740c5c16
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2405e4e92f2593864bb74abc55c0275b740c5c16
│           └── chunk-001.nq.gz
├── blob
│   ├── 00e65b07cf99bd3cc21a3d546176e8402d5f495d.nq.gz
│   ├── 07e10a08514124ce2ce63de2bd3fccecb89797e1.nq.gz
│   ├── 0b680d508757e960bfc1e7190cc29509514d1562.nq.gz
│   ├── 13af703428e23ce7d56cf7a1bc7061b64a8f6a18.nq.gz
│   ├── 171fbe92f44f86d0062386008e7da8e1daaf0d53.nq.gz
│   ├── 1f542378c988eefeb223a862bb4652c6ae428d7a.nq.gz
│   ├── 2055a28de90818ffa33b0a2ff4e1fdbd93eb1473.nq.gz
│   ├── 226fa3f76fb3fdb98e46be1e89af25d7c96901ee.nq.gz
│   ├── 25cb11278c0ddde8afb5b476bf01d2ca28d229fe.nq.gz
│   ├── 2fd62eb5ad044b218c2456c0b706ae2f2cbcd7cd.nq.gz
│   ├── 3bcd8a9f726c1e7ff32172d0ed5d95ab6436a34c.nq.gz
│   ├── 46fdfb6ff31d8f845aa61ec8d9c441011982757c.nq.gz
│   ├── 4d394c33b8ea132a10ef09db97c9509d10e14fd1.nq.gz
│   ├── 5411236d6b63bc4bd54f36ff39cc6f7912a44507.nq.gz
│   ├── 5776eddda2cdd051f85e5895ab2b506c6bc843d3.nq.gz
│   ├── 5e0d9cab5e5361ead031b0a40da939afa2a211c5.nq.gz
│   ├── 5e9f32d92b83e47a15fdda4109b1741b41c6d4d2.nq.gz
│   ├── 600d02af803be67f129cf6f7429b03737855678b.nq.gz
│   ├── 6063f72f417271a6cba967b4e767ccd955d209b3.nq.gz
│   ├── 727826f9f36924787876729fe3f0de7e0562edd7.nq.gz
│   ├── 79908aa7c8e0e0cad2c5b6dcf51c3f4e846f44db.nq.gz
│   ├── 7a0c0fccef5df67c3dc9120f1abcc2be7e060e41.nq.gz
│   ├── 7bbbdf45bed96dd74d8c9566653b60262bd9277d.nq.gz
│   ├── 8588e735404dde06002ec57f110f846f04ed0c61.nq.gz
│   ├── 8d771e187ba4b2ced1b643c804548e5c014bab70.nq.gz
│   ├── 9ca56a8830a92c94a3be6a6aeb3dfe77d9cd869b.nq.gz
│   ├── a81c4625c094f11963e67c498ab3809ecb84c1f2.nq.gz
│   ├── bbe77cb69558e274639017d0079c3ebd6bc948a5.nq.gz
│   ├── bc4b5a46de8057cbc11051996964b8cca6173a9a.nq.gz
│   ├── bd418d4c38a2ac7224a9d96b73029764359b499a.nq.gz
│   ├── c7b58c2cd0b5e0e6055191e0e9f379bfa1bd2609.nq.gz
│   ├── c814dc788d8211632908e0aae543a6114bb68c4e.nq.gz
│   ├── c8560827eb1e26161ac506847f05f95cc8148dc8.nq.gz
│   ├── c97c821634b862f9bcfde151bbb8f3fc55b4ed0b.nq.gz
│   ├── cd61964a464b79b8b4e350db0410eacc6c5c5d80.nq.gz
│   ├── cee5f07887945768f745ce8697a95facba10a068.nq.gz
│   ├── d01d3ec218c3341b0efcc04120cea0290c5f3ca3.nq.gz
│   ├── d20ba2d630ed7e6f444051dd3ca031389491820f.nq.gz
│   ├── d242377efcdfd5427de179302d2ac6fa073dfd52.nq.gz
│   ├── d54e174965cd46628cb383227260a3687f776d53.nq.gz
│   ├── ebcba510b69ed86777aa78e0e023185cf7fd5004.nq.gz
│   ├── ed67d9f62e5efc1621f0c0e8ae8ee293fdde7856.nq.gz
│   ├── f0571dc2b05049fc3780efcdffbafae38febe7a8.nq.gz
│   └── f2eee1494fa1897b5ea3aace2e8780b651fea001.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2405e4e92f2593864bb74abc55c0275b740c5c16.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
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

[canonical/sdcore-udr-operator](https://github.com/canonical/sdcore-udr-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
