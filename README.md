# Repolex Knowledge Graph of dabeaz/curio

RDF knowledge graph data for [dabeaz/curio](https://github.com/dabeaz/curio), parsed by [repolex](https://repolex.ai).

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
lexq download dabeaz/curio
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 73da34cdbce6df9ec46ce31e093b6d6bc218d076
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 73da34cdbce6df9ec46ce31e093b6d6bc218d076.nq.gz
│   └── repolex
│       └── 73da34cdbce6df9ec46ce31e093b6d6bc218d076
│           └── chunk-001.nq.gz
├── blob
│   ├── 07dae33235dfcb19868c193f3edc6b114d7defe5.nq.gz
│   ├── 0acf71979b5b161eb019f5dbed2f98c2f0df6cc8.nq.gz
│   ├── 0b23df887ff4d1b4f643869c2c712a31642ba8c7.nq.gz
│   ├── 0d54427a659797e031c212ccfa47888e1fd2fd8c.nq.gz
│   ├── 0d5da0c81c0b77bc1c3c8120b991215b62320a71.nq.gz
│   ├── 0efde705388d25e6f3277e7306804caa57d5073e.nq.gz
│   ├── 103af2c2b16aebd4f7f7dbfc6c9a4aa0ee57001f.nq.gz
│   ├── 14826cfb21516e7a39955d6c400b39d602166dce.nq.gz
│   ├── 16bc825185488ac3c63ff379215a02aaef0ff953.nq.gz
│   ├── 1a2f7941efcf1f4c2664fb8e3fcfb184a2e73e1a.nq.gz
│   ├── 1db73757c2138f91e2b7c0ce4dd557414f977cd1.nq.gz
│   ├── 1dee663329b253845b0e53b0c3f80615036c9588.nq.gz
│   ├── 26d66979adaa11f40a84825b6a9cb88f311e75ce.nq.gz
│   ├── 27e35c5f118470e14d4b3ce213a4fbb388171817.nq.gz
│   ├── 29a91942ce2e675f72358903fc2e43d3158d7037.nq.gz
│   ├── 2a2712232c798212f7cb33a7747a70936d6e176e.nq.gz
│   ├── 2ac2e43c457bf654a398db13702d424ecc680465.nq.gz
│   ├── 2ae06aeff5c562d2f59e389842b38d90e3f15f11.nq.gz
│   ├── 2b9734bd948520fd48f09efcd69dc6559a42774e.nq.gz
│   ├── 2d66f54a9727e8bd708f86fa017b0e6056844db1.nq.gz
│   ├── 2f36b995a35bacd62280086c455ec99a909b1324.nq.gz
│   ├── 345b5edbe0a9eaad04abe9a430e3d406a9266e55.nq.gz
│   ├── 3877c3221310107ef142511dab7c92ec28f729a3.nq.gz
│   ├── 4080d0f39de88f63f39af96d3f2ad933404c5854.nq.gz
│   ├── 4416ce3bfe246318c3109ea14f2c76329d5a38e7.nq.gz
│   ├── 4431b0f3963500cc3f5261dc53aa0317c72e4c1a.nq.gz
│   ├── 4441e0984a257bcf13ac11f5129a30540aae7e16.nq.gz
│   ├── 44f08d5fbb5a9565fffd94f83832f4ec30958a1b.nq.gz
│   ├── 4a13b52852435fec562bd208e41c1706bb351a73.nq.gz
│   ├── 4f6c8f1e650200d3e21595b9291de520d2746fff.nq.gz
│   ├── 505508845ade64a2cdf9d54bdb40687cca16c0a9.nq.gz
│   ├── 5625a965393576ec4f79ade43ce9f65397ce1bba.nq.gz
│   ├── 5a27fabf7caf82f54048bc82cc28fc33cc8a0c2f.nq.gz
│   ├── 5d588aacb2b622203e28845b9c3d726d8927445f.nq.gz
│   ├── 5f60a0ef35fbd8b856dd33769cd02fb4fdf1d216.nq.gz
│   ├── 600d0be9f650ac2b0bb4b2682279e0d8a8ddef50.nq.gz
│   ├── 63ece412bd8f5433c8c426ff9eb522192e2ff0ee.nq.gz
│   ├── 6aaf69426156536b720310b199c9a7913a9c8926.nq.gz
│   ├── 6adf347b845e70ded4765d0106c90ff351000ad8.nq.gz
│   ├── 6ed2a38f3ebac5d04e3bd50a1a7f9ab7281ed42c.nq.gz
│   ├── 75b166445cbe94a283c4f091c014fc6af1a86882.nq.gz
│   ├── 814b284fb2a0c2567b325ead780ea1734cb761b3.nq.gz
│   ├── 827948966775851ef51c404c87e9366a0c937ee5.nq.gz
│   ├── 83f04707f4022002872c26e4f355da721870b3ed.nq.gz
│   ├── 872386fe1de675540cba545be369040eeda81a5b.nq.gz
│   ├── 8e7fa92ce60fe0f1c4c0d1132cd75c4581e050a1.nq.gz
│   ├── 8f157440d92793ccd943cfaf9396480bc020d7ac.nq.gz
│   ├── 934c0657bb285ec70ab0b68217aafc8ad0cc8527.nq.gz
│   ├── 998b1f479c99aa6940345fc26ff91570d9a4dd87.nq.gz
│   ├── 9bc7665000bd95164c6102b3419da66d3b520b68.nq.gz
│   ├── 9e3a719e4faaca0dbcedb3a74fdc3fe0379265b0.nq.gz
│   ├── a5d7c7b6099b33be50aff17c6f2fa79196d08549.nq.gz
│   ├── a71c988a586e915c3cb07be07b79dc87ff6fc025.nq.gz
│   ├── a92c69b81eb5bdb719a1559e8291e432da404a02.nq.gz
│   ├── aa987dd14b016b27e8a33852765c2201cedd4e68.nq.gz
│   ├── b1b3a77ff84da3f8758e8ad47cd78cc384b2022d.nq.gz
│   ├── b6b9879a4c3ce9967c355dfaebe2fa0ed68e5e51.nq.gz
│   ├── b86c5e5fc24bdeb5d5579de84dda022ac1763f3c.nq.gz
│   ├── bb94b35301acecc1f0188a93eec9eff711387e1d.nq.gz
│   ├── bee8a64b79a99590d5303307144172cfe824fbf7.nq.gz
│   ├── c376377544ad635b70198ad19d578044a3b7cc75.nq.gz
│   ├── c689721fad31be92cf206bd5c34f08f7131e6086.nq.gz
│   ├── c7bc8e89b9cfe91cf776c206277cc50e57ccad0b.nq.gz
│   ├── ca7fc394835009e5c9a0926fe5f8bdc66d725a4c.nq.gz
│   ├── ce2ffa2fcf7f421e258e46388e1113ef2913e66e.nq.gz
│   ├── cff2bc15fece4c2c5e23489ce956d207227caa62.nq.gz
│   ├── d53326ffe9d10d1a2d015154de90710b6cc57ec7.nq.gz
│   ├── d559aaf9c59c891a89174460cfef0d707fd0fb3b.nq.gz
│   ├── da183a8210765b56e52a723b06acb7fe40875ac2.nq.gz
│   ├── e48c3e84f9634bdb6700de0a9dd596aec6afb88c.nq.gz
│   ├── e5dc3d59ce3de9606e5ddd244c6ba0af81896e18.nq.gz
│   ├── e6adec9f8ccf304a0db9fc0a1915ccbb2f5bc80a.nq.gz
│   ├── e728c089b8a02703285d5af537d5944765ba7074.nq.gz
│   ├── e7a189a0665b93bf030f815e3c7f73a0fa88da53.nq.gz
│   ├── ea53f7fa6468b9617f26655568a87f98b2ed1f3b.nq.gz
│   ├── ec0efc3097aa895c80942650b583c3b2eb77cd70.nq.gz
│   ├── ecd0abcff119b7b9e7737b61386a0f501d7d18f4.nq.gz
│   ├── f6c7c43ae9d97b42eb679bd9ecd0070b244e0086.nq.gz
│   ├── f809147a2c2bde14f9a3419c777f3831d43a4a6f.nq.gz
│   ├── fd39f7473ae79b25d95010cf1d528c4fdeb0781a.nq.gz
│   └── fed4b3161ffa9d66e1df9a4f0fbdd9c4604eae07.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 73da34cdbce6df9ec46ce31e093b6d6bc218d076.nq.gz
├── filetree
│   └── 73da34cdbce6df9ec46ce31e093b6d6bc218d076.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 91 files
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

[dabeaz/curio](https://github.com/dabeaz/curio)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
