# Repolex Knowledge Graph of ansible-collections/redhat.ai

RDF knowledge graph data for [ansible-collections/redhat.ai](https://github.com/ansible-collections/redhat.ai), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/redhat.ai
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5a132d00106ad8bee72bc58ec4708ac6f6a753c3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5a132d00106ad8bee72bc58ec4708ac6f6a753c3
│           └── chunk-001.nq.gz
├── blob
│   ├── 0164155b81025416095f31a4732098ec238e6476.nq.gz
│   ├── 12871f410f15697dabaab05729ccf571582acd6c.nq.gz
│   ├── 19e9fdba0f9de83c8df5070bcf254404e8765aa1.nq.gz
│   ├── 1b7e7a3199725abcbe736bbfb0f3a16845ec3ef7.nq.gz
│   ├── 1f3b6fd2e21f29dd103f1708c7ce83ddbab753d9.nq.gz
│   ├── 222c3c163f246303a602dd108af3a136ff3036f7.nq.gz
│   ├── 276e3f3bae0ee4346d0ebf8b05afb275a5370750.nq.gz
│   ├── 2aa8b9e52334e573408cb6f9f7eed0eceba97b89.nq.gz
│   ├── 2d75cfc37cb0b840630fe225e644e7c8f7e67914.nq.gz
│   ├── 33941df9561bbcc67f14e53db460d061b49be49f.nq.gz
│   ├── 38d8ce5fd6d618dc30d0fae2e450fd42a3536b03.nq.gz
│   ├── 3ae48062333b0aed5431aa430de0127cd72ea44f.nq.gz
│   ├── 42024f25858a15ee029c42ad78bb08347499eedd.nq.gz
│   ├── 42aff2dc9b9b2347ff134608a116c2a94b7814c6.nq.gz
│   ├── 47e92259ffeb9d62faad3c8570366e15010202cc.nq.gz
│   ├── 48c6e5e0f049fa9860dc65cbd1e5bdb2d5e08471.nq.gz
│   ├── 547920f05c8bc6baae8a76b5637ad59914f77f27.nq.gz
│   ├── 56b3045a5e707fd89a7f04599a1ac295a650e8bf.nq.gz
│   ├── 59bf1c048877e1311950eae4c6b4683ce36cc336.nq.gz
│   ├── 5c4b109783f2bd9e151a4d61ef4b2711caff5a85.nq.gz
│   ├── 6704877e84886399d257495248392e6ab2bbfd04.nq.gz
│   ├── 74ff5a979a73edde510f097ce736508fae118c06.nq.gz
│   ├── 7d9ca6ec02f6aa448e1308eaa8958eab24c20c19.nq.gz
│   ├── 7ee85b639534d6cbdc146f3808753a24103bcc21.nq.gz
│   ├── 80db78b932bc8e545947d59d781f3398cccf36ca.nq.gz
│   ├── 8348b41bede8c0e296d74d57a38592dc76586b86.nq.gz
│   ├── 88fa3fdf75dd1b5b5f581ce2cc3d88515937258e.nq.gz
│   ├── 89a4b0a671568503131bb148fc987bc8ee73bbfa.nq.gz
│   ├── 8ba8460b5b5163adf6cdd66439f4ea2432e2b146.nq.gz
│   ├── 8c8ecb15a83c2b16883131cc3c1e776d8e1fb487.nq.gz
│   ├── 8d3f1426f6c0edaec93f27226d3e2fdc3da43445.nq.gz
│   ├── 8dd516182c7a44cab8f44c39a1efbbd9a87615d1.nq.gz
│   ├── 9781be246fb4134a855243e73afd8b28185c86be.nq.gz
│   ├── 994430351870d6b2fff640c3ee8e79dbd2cb5135.nq.gz
│   ├── 99bcaf7f540655cd94f4e7232efe9f7caa4fd0f6.nq.gz
│   ├── 9a9d96333b572a750f14020b81b86f7fd3fbddfe.nq.gz
│   ├── 9c64618d2ca723b7b3ab239ef4716b286f50396e.nq.gz
│   ├── a3432b01d3b27fe8a4acdec5bf4a03e7cc5234a6.nq.gz
│   ├── a555ca8dada41c865b149ff75e90b0190e376239.nq.gz
│   ├── a6c451a00f2688a729b1732e9d2d7ee3f8972475.nq.gz
│   ├── a79cf4572849d99045eb2766f6f76e7407dc51c2.nq.gz
│   ├── a8ae07e446118493d774c322e11620e934aa8019.nq.gz
│   ├── aac9dc78166b3bcad3572b7ea88b87e6e2d9d722.nq.gz
│   ├── ac36fbd6ef7bcf8420f5e3d573d177d94eec564b.nq.gz
│   ├── b13f5e74872624ad36c5ddde1f85d47777547269.nq.gz
│   ├── b1c82d44c30b6a2ad04be13bc3231f7f32431ea3.nq.gz
│   ├── b2e7285b520bff9e66d8949a49495a8eaf511141.nq.gz
│   ├── bce600d36235a157c640f3c1ddb21547a4b6f82a.nq.gz
│   ├── bd717af2e6c6f1c71f4a7f6eb7feaa2b61c62bcf.nq.gz
│   ├── c077c872694404235bd6bb4d6db713b3e1d29b07.nq.gz
│   ├── c12ca146fc1421e304ba0ce2f00423292a7ae730.nq.gz
│   ├── c17e4acd41c4fa89e657a4e74cfdc1f997626871.nq.gz
│   ├── c3726e8bfeeea82230cb1d7040b064fd99c5ed92.nq.gz
│   ├── c7299e838fb1a54f1ed435c49e79abebce9905bc.nq.gz
│   ├── c971e4b556d2300a124de2995e738d1e84c45432.nq.gz
│   ├── c97c44432785f00ec4f17d03566425940a836792.nq.gz
│   ├── cc13776c82684bb4691f05154c99bbf66cb4a5e5.nq.gz
│   ├── cf2a7124aeda581f296405c64cb4d687a889a598.nq.gz
│   ├── cf7a4a6cdeb1669ceebe1c49afdf8f0de72340d6.nq.gz
│   ├── d01316967eaa122d274a514adc29edb0bde65912.nq.gz
│   ├── d2bd8508d084ba9705740ad23b64be9a3daa9f45.nq.gz
│   ├── d811f38e96f1fb84cc0bcca987429830293b7a79.nq.gz
│   ├── d92f81c9567853892dba8a2c034137cbb18dda71.nq.gz
│   ├── dc0490dc2fa01412dd297e94658bdad9513dfea5.nq.gz
│   ├── e432a90abb7b81a926771f68fd6cebbedc0a225e.nq.gz
│   ├── e64045c21f4d982e85613329cb01ddcea0c5f418.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea0d0ad2bb90d759a66d78606f4fff465292791f.nq.gz
│   ├── ecd6385d8445c57446e41e48d23cf89ecfe1c677.nq.gz
│   ├── ed4c32b6402d27dcee9fbcaa6b75eb96936bd86e.nq.gz
│   ├── f03debc086d8be9f592dd1c0a88c407a9eaf68e3.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f7deab5f2775cad59179f0c276a3adc93bac1376.nq.gz
│   ├── f9ebcc89ec9518451791aff875fe5a8d608bc0f1.nq.gz
│   └── fb9d246108eb62f5aa7e91532dea51a5d6d65a5d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5a132d00106ad8bee72bc58ec4708ac6f6a753c3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 83 files
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

[ansible-collections/redhat.ai](https://github.com/ansible-collections/redhat.ai)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
