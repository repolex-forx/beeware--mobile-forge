# Repolex Knowledge Graph of beeware/mobile-forge

RDF knowledge graph data for [beeware/mobile-forge](https://github.com/beeware/mobile-forge), parsed by [repolex](https://repolex.ai).

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
rlex download beeware/mobile-forge
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7917b1591d13210eb3ae73ff3ace02fc0aac4779
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7917b1591d13210eb3ae73ff3ace02fc0aac4779
│           └── chunk-001.nq.gz
├── blob
│   ├── 01ad8ea24284ab70b938b9a0ff633d9e00dccd62.nq.gz
│   ├── 01f80b996cff157e9fe0c26251a74abaee5f1d7f.nq.gz
│   ├── 045edb13e486ad39785beac10582c60e8c9b373a.nq.gz
│   ├── 0e26b573a79e15568ce61720064132815c6a6b43.nq.gz
│   ├── 10844aea7a650e473ebfc61ff41ecb6555ac164f.nq.gz
│   ├── 1356712d1729fd6ac9a1bbaa27a9327cd54c31de.nq.gz
│   ├── 1f1d39c7d84bb243c9c9b547a3fddbf177708bfe.nq.gz
│   ├── 1f410b1af0c15941cd3fc67124a3a274f7453e23.nq.gz
│   ├── 2062904183a4ba5609c0fad54ccd6de88c82a8c6.nq.gz
│   ├── 2239aa86c66c8c59240e2fa610fa8094194f7e36.nq.gz
│   ├── 27f9f0c14cb7ccb657da7ef9e52d4ae82cbb35af.nq.gz
│   ├── 2d343e00e6b46fb430fc6ed9dac1b4e683830a26.nq.gz
│   ├── 2efdc4971d06e8938fd3eb63f8486c36a14e4ef2.nq.gz
│   ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
│   ├── 3ee20f4878ecfbd80b53e847d31cceea7a76746f.nq.gz
│   ├── 429276a4657a5014c55ba7466ceb98a3ae5c12e4.nq.gz
│   ├── 458c7c70e85ab3f8ae673ea633a58ad08d0abd61.nq.gz
│   ├── 488157531480895c74f94e272f908b66f95c074d.nq.gz
│   ├── 4943fe03680319bb8459072f7fef985384a355bd.nq.gz
│   ├── 4a09c81e23ca735b7d235c71f9ed7feca8081af3.nq.gz
│   ├── 4db2680d623eef75663266d50cd949f40eb5638d.nq.gz
│   ├── 5099944566cdbaa1b2ba9867803de0d288ed08f0.nq.gz
│   ├── 51a809456adbc8ddca5a43667de92a600e136754.nq.gz
│   ├── 58c7747cdf5bbfc06fef455d9c5e399c34fb025c.nq.gz
│   ├── 58cd6b5e61eff273e920942e28041f8ddcf1e1b5.nq.gz
│   ├── 58e5cc0bd8952d1d86224c55c61fc9d115bd824d.nq.gz
│   ├── 5a13871aac74ce3d55bafa2897a25a9e97aa20bc.nq.gz
│   ├── 607660b5f854703515b2a4083e795ec0e1858b65.nq.gz
│   ├── 66a4cc1003bb37dbdb9141cbadaa49d754e50112.nq.gz
│   ├── 68c94c948923e35248838a81948d9c809f5c26bc.nq.gz
│   ├── 6b2ba9af87493cd29281b2dd33f49ffce3e19bea.nq.gz
│   ├── 6d7b949aec56246ce7c5873f9ceea700e5f64d03.nq.gz
│   ├── 75bea4a0f6975fea62cb872f1bd76c0999466321.nq.gz
│   ├── 75c2446f876b5c63a440453aa4ad49c36928774d.nq.gz
│   ├── 784141bca0cb2ce99b1b3f78866b2045ecff6ff7.nq.gz
│   ├── 788cece4c33907bfacb35eab2f8e6951e6e442eb.nq.gz
│   ├── 7bf32a4fb7eb7705321b53c32e10b3f8cba16c5a.nq.gz
│   ├── 7fc42b9913ec9e588268de16be172da1c7887bf5.nq.gz
│   ├── 88c755ad32a73ed38c5087fb3c57be9bc36c11b7.nq.gz
│   ├── 9160bbdcac863ec9d65f1d92285eaadb0ea781ec.nq.gz
│   ├── 95b6e00fcbf281e1eca27deeba68abd0bdca32f9.nq.gz
│   ├── 95bbf42ec1ed03e3d9c0314b25ab089b79b214d2.nq.gz
│   ├── 9708408ac78e043b2b693952fd5cbbcc454de5fe.nq.gz
│   ├── 9750c441357be3547753fdf57cee7a9720359c9d.nq.gz
│   ├── 97916bd4f2dfa855568949fb9c33fc81968b8f22.nq.gz
│   ├── 9ece630b848cb1b464b08489a517c360f086e39e.nq.gz
│   ├── a4eab7d086e4ff009494113e3e49c89b78f4ec2b.nq.gz
│   ├── a82526bf148505cee9266c06f6304c799efab19b.nq.gz
│   ├── a8d832e437fa76989b355794e79b316b32a33852.nq.gz
│   ├── ad8c51addb7e984befb56f036f600a1f59a730ed.nq.gz
│   ├── b23be8592de8d763b701ade33350198ccf3f33b4.nq.gz
│   ├── b4eb4484c337f22ada2fd61693d79feb7e6f58e1.nq.gz
│   ├── b6d37c81bcab00db9b98b8c966b762692fa15510.nq.gz
│   ├── b834affdddcf5014398ca9c16aafe3ea7f2d0422.nq.gz
│   ├── ba133d66b7eb5a73105ef9a6df04815cfa519dbf.nq.gz
│   ├── baff03eae2aea21d06510bab3577a8d7e9180499.nq.gz
│   ├── bddd6234016944909d581192399670a6d10ebd82.nq.gz
│   ├── c3de4aff5e1b20eaa5e49aa8eacfe93594b560b5.nq.gz
│   ├── c4d88e8173e484996f9c1fe716bd0fb7e4c8a73b.nq.gz
│   ├── c5f06ab0168c8d560f8e848df9da803ffbd2a2b3.nq.gz
│   ├── c72eb4037081693f5a614f5fabf573c2f2aac697.nq.gz
│   ├── c75b1d51ef1cae7758a83317f1d434627f68a06f.nq.gz
│   ├── cacf2a64a1b7bbeb95377e023b107bc78fed45bf.nq.gz
│   ├── cb520e6b30a1e71e4db4671ce5374f4485fe6c54.nq.gz
│   ├── cb9dbb0fae02d9c4f17018c32bf29e6c5e7dee4d.nq.gz
│   ├── cdb6e25a4ce0d5e12b8fa67c4b5e2bfd1cf29caf.nq.gz
│   ├── ce620a66404f301ecc6947fd1198af7c31eed64c.nq.gz
│   ├── d1975b098e81b8fbf1919a138b0cec7c6539f18b.nq.gz
│   ├── d2a7c2fd808087c365feb1aa9e6f90b5ab4e0b19.nq.gz
│   ├── d3d2b347600eb88483c70a89fb7ce6ee905cf989.nq.gz
│   ├── d66acb3f7b87704ee78593d8a6da387fb94f29a0.nq.gz
│   ├── d678cae28eb09457b9993aa1ad62525c5fa05011.nq.gz
│   ├── d905cc30d219ab9913fb2b32c60103f65072e042.nq.gz
│   ├── d9c1ea08e412554f606c2598e387a0ea5627ff85.nq.gz
│   ├── dafd917cbc3221169eb4d3cebdae1cb3a5857d11.nq.gz
│   ├── e2b685d8bbb7a6bfc75e637090a21f4b0d40ce07.nq.gz
│   ├── e45540da943560293e81c149d9940836fd56983f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea5c608f8c1b03b084e915a370109fe8af912630.nq.gz
│   ├── ec4f1c03a0413ed05a5b64a2545da5d7ebefa738.nq.gz
│   ├── ecabf6b2be0d84861b2da87709734c0e21fa7cf1.nq.gz
│   ├── ecd74b17d9530e887ecb3025b3ce75190d453733.nq.gz
│   ├── edf05ca401f974674407bbb5effadde96bccf364.nq.gz
│   ├── ef7d24f21d9064c543b4861bb88b96f6ebc7141a.nq.gz
│   ├── f97da85abd9fc3a542c4bbf505e23ccd578fe170.nq.gz
│   ├── fa16920ed5b5eb6a49e3bca76396b25448a4b6ac.nq.gz
│   └── fcd8a9c98b14f1042d2da4965dbdddffcb67c31e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7917b1591d13210eb3ae73ff3ace02fc0aac4779.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 95 files
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

[beeware/mobile-forge](https://github.com/beeware/mobile-forge)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
