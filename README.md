# Repolex Knowledge Graph of mdsteele/rust-cfb

RDF knowledge graph data for [mdsteele/rust-cfb](https://github.com/mdsteele/rust-cfb), parsed by [repolex](https://repolex.ai).

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
rlex download mdsteele/rust-cfb
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 45d0d07adc8e95f9c239ac7dcc42761b1347ed3e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 45d0d07adc8e95f9c239ac7dcc42761b1347ed3e.nq.gz
│   └── repolex
│       └── 45d0d07adc8e95f9c239ac7dcc42761b1347ed3e
│           └── chunk-001.nq.gz
├── blob
│   ├── 108b97ec0a78f8f1a6af98688389556fee5b0300.nq.gz
│   ├── 1b1e1bfad6f6d7d40a98682923b31f1e52afd2ee.nq.gz
│   ├── 1fef5c0cd1be413879f6871ebe2b73ee06f872f3.nq.gz
│   ├── 22362943e104cfd308d37c50f8c21c576de9e871.nq.gz
│   ├── 2263a563a8cfc4575cf00b8ad565f0827bd81c39.nq.gz
│   ├── 2828bbaa88158d27ae5259ff5b233d1776d31e01.nq.gz
│   ├── 2d976b550c63d0c95a5962e8fb8bebd78b435ae7.nq.gz
│   ├── 2f47eb5963e48e9c2f4d659eb7d71a0210e393d6.nq.gz
│   ├── 30ee462e73ee62592eb2c3ab5df1b5099b178924.nq.gz
│   ├── 36f1832cce1683f8970f49249188ca8c4eae4993.nq.gz
│   ├── 3f0b832bb3b1de42425bc9ecb41882dc9ebdd37f.nq.gz
│   ├── 459f1285d971f694b1c2986bddc8f279b67ee556.nq.gz
│   ├── 484d8b427e510b836ffe4b73dd2952b3af2257e3.nq.gz
│   ├── 4c241470970a5b153b8972222f599e6dc9a6adc6.nq.gz
│   ├── 509ba58e845b3975e680ca74d15781181225de17.nq.gz
│   ├── 55ad7e8817e5d5902306fdf4af1960f630bc34ef.nq.gz
│   ├── 5aa4ba0f29efc20327d46a631f2a9ad798b257e0.nq.gz
│   ├── 6e50d3b434b4a36a1442fb8eec58bce5b88cf16a.nq.gz
│   ├── 6f91c67c658cede3d2146f24ca5e7f93196e1380.nq.gz
│   ├── 74e7a6ea606b1503455189ba3d017b0c0a44e01b.nq.gz
│   ├── 78d0233182615e5ec11dc824e5ea4b22e905b359.nq.gz
│   ├── 7a3135cacf363aeeb5ae355d35fbf70c328ea50b.nq.gz
│   ├── 8042175f3873f9bc6d5e23d975259df64f74c8de.nq.gz
│   ├── 83a1eeb8433ede7c2f4b9c3b180fb3044282fa2b.nq.gz
│   ├── 83d96f8f4429b7e907004d5c28816f0e1a35327c.nq.gz
│   ├── 878b7e4abed177ff0132c9be9335301630a69e93.nq.gz
│   ├── 8c290ed7bdd059bacb0447ec799366b9adb9d302.nq.gz
│   ├── 9069927a595ad04bb28cd09238b14daaafb322a8.nq.gz
│   ├── 99152fb5f9bb60642aaf366ef39cb145ce63f86f.nq.gz
│   ├── 996afbb897b3c469f16a0d975fe498e18ef699a5.nq.gz
│   ├── a0925114d619b8cee7d72961b052ddcc42023a24.nq.gz
│   ├── a30fc4ec5451a656e1543c7716fe9efdbe80dac5.nq.gz
│   ├── ad00b0562e303411631ae7dc78c4efa7a9e73711.nq.gz
│   ├── ad89ee4e1c529a858f8ce1b72809f6e614df18d1.nq.gz
│   ├── ae0b75adbdf0017faa3c79315c7feb83075d6486.nq.gz
│   ├── ae6bf8d9fc384a69ea8a595b2b0854c180657b60.nq.gz
│   ├── ae6d85540e9ca86b3fb1fa11672efba3b02d44cf.nq.gz
│   ├── b615aeb0ddb9307657f06203d0a2000a5eab3720.nq.gz
│   ├── b69dd71b61edd5f94346c88ee72f715902f5abe7.nq.gz
│   ├── b7dc96879182eabdccb83288a57b606e265d0ee7.nq.gz
│   ├── c25a33955099c68fc5ae144512879137336ff540.nq.gz
│   ├── c5cbf58a7950479556f8a50797a0fbe7310cb66b.nq.gz
│   ├── c7cb6b2b4f91751fe72b89ef43fb7e4753be28f4.nq.gz
│   ├── cb8e29fb22308f65443dd0e960085c1de9dd8a6c.nq.gz
│   ├── d71ac72dc1ad62507dd43dde80dd946637c70e99.nq.gz
│   ├── e490bd98eeab416fdd41418762f63c72ecb5f3e6.nq.gz
│   ├── edae7dbcec11b57067ddc81e4c3bc8964ad0b44e.nq.gz
│   └── fcbab498caf754f0e21bf1b4116440982815c2ce.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 45d0d07adc8e95f9c239ac7dcc42761b1347ed3e.nq.gz
├── filetree
│   └── 45d0d07adc8e95f9c239ac7dcc42761b1347ed3e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 58 files
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

[mdsteele/rust-cfb](https://github.com/mdsteele/rust-cfb)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
