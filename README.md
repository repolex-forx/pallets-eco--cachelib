# Repolex Knowledge Graph of pallets-eco/cachelib

RDF knowledge graph data for [pallets-eco/cachelib](https://github.com/pallets-eco/cachelib), parsed by [repolex](https://repolex.ai).

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
rlex download pallets-eco/cachelib
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 34140b8e5485fac142dca95eba9341aaea3a9070
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 34140b8e5485fac142dca95eba9341aaea3a9070
│           └── chunk-001.nq.gz
├── blob
│   ├── 035158ad70358b8c4d75a9e6939b81a4a104b708.nq.gz
│   ├── 04aec7c8cb5f4ddba90c59d8aaf215063c9ce7d4.nq.gz
│   ├── 0903f04c9eed89f89205bcafb2a46ac47d7fec26.nq.gz
│   ├── 0b2d7548315d78c493c10bf8e2b56d8f8447f6ab.nq.gz
│   ├── 0cc99d17a9e9176a3e9a70698acab4914acfc814.nq.gz
│   ├── 12c32a838fa5216e340dfba2c50e234e332bc9a3.nq.gz
│   ├── 17ed3c76bc599b78b2601e488d7c357eddac0261.nq.gz
│   ├── 19aa906397b8bd3357a17c744b7d58b91a9f2d98.nq.gz
│   ├── 2a445f9c62843f5205e3e4a920fd49c1808a399e.nq.gz
│   ├── 2bbf55abe0dc831ebc2f2c95b35bf14c0817f988.nq.gz
│   ├── 2bf597b6555ede8baeefed6ea024eacdf490eedb.nq.gz
│   ├── 2ed2ef9ba37a023492378c0af5f7ae656b0708bd.nq.gz
│   ├── 2ff985a67af35fdfd1076354b771c425867cdab4.nq.gz
│   ├── 307d2d900f4b2492040b0db0862246cf8eb79236.nq.gz
│   ├── 3085d3771705ad9d2e0261d15f3a0ed45c0327ce.nq.gz
│   ├── 3212b697f9241b05a7613c1118517ef009d119fc.nq.gz
│   ├── 3d2c8182f72cca0de161330393428afb11ed4bef.nq.gz
│   ├── 3f53f9c2bd77e595c4cf49ae454c2f542ae38402.nq.gz
│   ├── 3fc2e55a0fee16e6a64ace7cb699d38c9f9115c0.nq.gz
│   ├── 441d574b03af081541a880c723af6039af124ee5.nq.gz
│   ├── 488600cda6baa10ae777ddec349636e4877f4189.nq.gz
│   ├── 50ffaacb5a837ccd3def110fa2a30d7fd5554d12.nq.gz
│   ├── 51c3612ca3863864ee1416921430ce55573c6b6d.nq.gz
│   ├── 5296b963423cf84231a7ee8273e86b05411d1b25.nq.gz
│   ├── 563b5dd9a98e70ac6acf6d2fae8f2e0ca3380ffd.nq.gz
│   ├── 5a1ec418ce6d6918867c6c88dbfff508ca41dc4d.nq.gz
│   ├── 5c7230b564aaedad51120e7cc10aa0e77180e33a.nq.gz
│   ├── 63cef557a87d3cbe3d1def4382205329df4f465f.nq.gz
│   ├── 6a41ddae72bfd27c245c810b7a3cd6645e1957cb.nq.gz
│   ├── 6f5f5627eb3f3f9b9ac437f66acf43b0d360485e.nq.gz
│   ├── 7394ad3759e411f9c39ea827386d6db6b2bc99c7.nq.gz
│   ├── 74e5ced0dd618bb340466553f92e9117bb6ac0c4.nq.gz
│   ├── 7564ab8e3036734843289cfb34d1cb8e9b748fff.nq.gz
│   ├── 78ea487eca2bd839b13108845bdba28a68df6c55.nq.gz
│   ├── 841a8eebb95258e37103d99b9e41090a22596cb0.nq.gz
│   ├── 8441e5a64f3bdd680c9d67e8b44c9f176d2a351b.nq.gz
│   ├── 847bf262801f716cdcf470ccba25b2d5caf7cbad.nq.gz
│   ├── 85efdb29468a3a77911856449417bdde9333a02f.nq.gz
│   ├── 8b9bc2c9fe6a96cd4cc7b0111e13e9562017cc4d.nq.gz
│   ├── 8f60923c1b2c1035dd34821fe712d6beb9059d5f.nq.gz
│   ├── 945eadc654a311149951c33614e98cb09650735d.nq.gz
│   ├── 955deaf27bc821a6367e818f36c016892fed3d33.nq.gz
│   ├── 962ee49cb19aafc2abe0dc7d5b37b57c4a757b1e.nq.gz
│   ├── 96556dd15ea9e7f51a9946613a30d1febf2b4f23.nq.gz
│   ├── 99177117d30402bed01923a379018e4a6c01b151.nq.gz
│   ├── a0a68205f6faab6512b039c85fb64b17bc01266e.nq.gz
│   ├── a6c66e43ee2cda9df9bc4f2b7cbf69bfdb24c31a.nq.gz
│   ├── ab12acb488fac7873060c73abe3ca790d6ee6c54.nq.gz
│   ├── ab8c7fdbf9ed8b11ac99771b5091864ebf942f8a.nq.gz
│   ├── b0cd48b1eb3f8015be47de9a4e73591752dcf457.nq.gz
│   ├── bc7e6f47f8b25b24b61608b09751bf65c75248f4.nq.gz
│   ├── c100fa8ff36825355113c14147fe196db1bcd02c.nq.gz
│   ├── c401319c96681ce97aa0bb782fd41cfe0ab51408.nq.gz
│   ├── ca4b3aeef4ac0d1c25b64984db54e095af636572.nq.gz
│   ├── cdd6f85ebc7bb970e10ffb7f3e1785919b530a4d.nq.gz
│   ├── d0e0fe824b9ed38b6ae59cd35ace4101f77b75a9.nq.gz
│   ├── d1a933b9457e636a06a30199fc7a5f4de843dffd.nq.gz
│   ├── d1a95f94b32cd692895b5bc8cacdc835c6b18ec5.nq.gz
│   ├── dc4a103d72fc0f35ddfd3ea8512ad79964cc3377.nq.gz
│   ├── dc58c7d9d40ff8d40f5b8c723407a200dfe7c006.nq.gz
│   ├── e1aabb5cf346ed1555cf2f48a953489e19787226.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8bc9750f98c8190c9e065574f2e53b7a5fda3b0.nq.gz
│   ├── e99db210353734bc73318912818bc58d6acfbf63.nq.gz
│   ├── eac4292781911ddaf829077e07cb80de923706d5.nq.gz
│   ├── ede381a23ee12e3a6e1e8887d529d12b8d5c620c.nq.gz
│   └── f08dab9e427ac713726b5a4036887a970fb955f9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 34140b8e5485fac142dca95eba9341aaea3a9070.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 75 files
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

[pallets-eco/cachelib](https://github.com/pallets-eco/cachelib)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
