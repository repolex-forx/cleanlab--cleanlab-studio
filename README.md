# Repolex Knowledge Graph of cleanlab/cleanlab-studio

RDF knowledge graph data for [cleanlab/cleanlab-studio](https://github.com/cleanlab/cleanlab-studio), parsed by [repolex](https://repolex.ai).

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
rlex download cleanlab/cleanlab-studio
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e5299e2f50208edae0c02106a50b2dbef902980f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e5299e2f50208edae0c02106a50b2dbef902980f
│           └── chunk-001.nq.gz
├── blob
│   ├── 003c7314478a1c44fae0c9beeca6138929b3e10b.nq.gz
│   ├── 00c51499086ebc3f6ee0e03caeed68b9f8d00827.nq.gz
│   ├── 011559af3402655e051cea36a62a5dadfc0c6775.nq.gz
│   ├── 09384cd8895febd7bff1e9acbd95fa305ff376c5.nq.gz
│   ├── 0a0e47b0b01b597936c8c2a8a09cafeda899168b.nq.gz
│   ├── 0b6c1b70dfb3078231a0feb7c18171ee504b5cde.nq.gz
│   ├── 0b776427f002678198ba7d29d72801dab10968f9.nq.gz
│   ├── 117c9cb4815433258c2f428c6606438c53fdfba5.nq.gz
│   ├── 119cf70ac833570bb422b2d28ff9fddac19b5442.nq.gz
│   ├── 173f5a91c4c6f255eef05be56ec616e2015aa4b3.nq.gz
│   ├── 17f27e2470352bc8d270fc4e16432b625384cb99.nq.gz
│   ├── 18a15920b393e3e29529e71ec52a7a93de6a14f2.nq.gz
│   ├── 1bfbbd99ed377808bc81f8d7cca64d1bcb9b3583.nq.gz
│   ├── 1c8aa7c999224a4c3c7d83855925eb8c8a802851.nq.gz
│   ├── 2590500b598368f26cb1db86eb5d344599ab7734.nq.gz
│   ├── 2b9560527b3b9d43ceea841c9416858aad4c4fc3.nq.gz
│   ├── 2bbadf85007c0fecb261686ea8fd5b55f7144dd0.nq.gz
│   ├── 2d0120dd54b1a73d5a8df0d0b091557263e15ce5.nq.gz
│   ├── 2dd25b4976399af07474534b63fa774b357625bc.nq.gz
│   ├── 31a5bbdafa91a12220dae8fa9afa3eb50819eb20.nq.gz
│   ├── 37e5751733ddc15c6380b53563a06013beb73cd2.nq.gz
│   ├── 3dd33d760d3f9ac350d4faffcca2dfbfb9a83f39.nq.gz
│   ├── 3f41558a9a85864b6915c73321af95e49dfeb6f4.nq.gz
│   ├── 4297d1150ea9b8deb679f59086dfb07e194c3e55.nq.gz
│   ├── 42a5cf5f79b93e87f8352063591a0cd38b39e891.nq.gz
│   ├── 431aad930fb324045d2405ce13df30fdb9cf6489.nq.gz
│   ├── 45e649565b4050edb3a924f78f33eef9e34f667c.nq.gz
│   ├── 4c7c31176f50c88efedd3cca8268120adf888240.nq.gz
│   ├── 54f70a0c7e03878d40e7555974de5238ed28bd62.nq.gz
│   ├── 55aa9ff585b4c5fc76f4b84c2bd341f77aa93928.nq.gz
│   ├── 56fe5af359b60f568ce071a417b23279c77ac9d5.nq.gz
│   ├── 58621bf71dda6a4a43ec2da7bc8facb0a5c5221c.nq.gz
│   ├── 5a70314de2608de364b5958bcf9b3137a426717d.nq.gz
│   ├── 5af5331e2c3e23ec199a3862b3204bbf98e4bee4.nq.gz
│   ├── 5db42cf67075ea10d7ab0140a76d907b27e4f9cb.nq.gz
│   ├── 5faa1e8f1ddf488199c11dac3d6eb1f910011fb3.nq.gz
│   ├── 637ba15970ad9c30e5837d96e9ff5402b1c5f926.nq.gz
│   ├── 65bb464daf4ff7711a25a52903774b5fcb973b9f.nq.gz
│   ├── 6a86924e257f47f9cf89950e8744cc4356542fbc.nq.gz
│   ├── 7700597e74f22c8e18154eaebdb113f1826e39bd.nq.gz
│   ├── 8006aa56939953950c0974d28cbb1907fdd68206.nq.gz
│   ├── 8241739e562763a694c5c29f9edac0c6d72ec2d4.nq.gz
│   ├── 829e70baac890bf285a083237d7500c404d42892.nq.gz
│   ├── 8fe375c13817a47edd74c202b56670eb5340f97b.nq.gz
│   ├── 970e2c761b0a4c90d9070cba351c7eb4f937f8a6.nq.gz
│   ├── 97a0d700c2acb5cea6e363b5bc9acb0b2dbc936b.nq.gz
│   ├── 97cdd9ccc146b6cfa1bbc8f067062205b575628b.nq.gz
│   ├── 9b90417d82b9f08c448fb9c9633515430168c321.nq.gz
│   ├── 9bdb377eecef993f56c2546c665a6b4f7a8392b4.nq.gz
│   ├── 9dc484b4a2b325c9dd5b36fce10c708d96af5720.nq.gz
│   ├── a05b6325914c7db7bcfd0025c79f6aff853cc4f8.nq.gz
│   ├── a2174e6912aad937f47a3e590abb31ba0312633f.nq.gz
│   ├── a354d9cb50ccee95c906f2be3d8bd9c314142813.nq.gz
│   ├── a95971d692b574e5b15bc9f23f6bf4d0f917deb8.nq.gz
│   ├── ab9240fe2fa80035ae46dcf8f4f833eb60e7e902.nq.gz
│   ├── acfbfaf82bcd9c69bd1c33c99c7c6e01aec20490.nq.gz
│   ├── afdd5c99f18ffcfadfd77cca890ccaeb6741667f.nq.gz
│   ├── b5e77ac2e79bde17e8f86bc7a71490b2850ad929.nq.gz
│   ├── bd417fac7bf108bdb0d3a1fa288c6c4d7794ece5.nq.gz
│   ├── c2e925a94e4bb3449c1f08e2b8d1b19f594f3a4a.nq.gz
│   ├── c6a2a9eef46a67e670d342387a090626a1679002.nq.gz
│   ├── c6e754d98bfdb246c52d11444e98b1616c12e83b.nq.gz
│   ├── c9256b0f2446715c6319893d8e3d6562689209f8.nq.gz
│   ├── c9dfd4883243ac6de5fc4f074b3be163fce6a29a.nq.gz
│   ├── cb67f4ef0f130615192abe18bddbb945bad6c8b7.nq.gz
│   ├── cef56b94b9d28e2748a0bae21c26b860b7e41b7f.nq.gz
│   ├── d187f4036f273fc64806f3f8f7dad7986151716b.nq.gz
│   ├── d2f2ef9bfd1ee3ce1e6a61585659694532db3e5d.nq.gz
│   ├── d9c866dc219edd461ba9e9b4d9dc7713dd630513.nq.gz
│   ├── da01854b28d32bee9392885d99abfdbe00a009b5.nq.gz
│   ├── db28e4b237c6b68a7e40d1b376e37770a0a1dc99.nq.gz
│   ├── dbca7c8d385c9160b67fb3866321895700625530.nq.gz
│   ├── deb87d2e6dd2fe4943e4cade19d0e507fa8c31ae.nq.gz
│   ├── e3f5aa30037d6d9e2f7ead1f72e55f86e073b5ed.nq.gz
│   ├── e5b9a159f736f27eaa20ab3bb28207844da27379.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec3a43c8ca2eb6d2e0739313ebf851defacf03f6.nq.gz
│   ├── f69996550145da0c6e3cfb155ca2ba26b38b0afd.nq.gz
│   └── fe23b8f12b618feedca08e1d991440394c0e7aeb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e5299e2f50208edae0c02106a50b2dbef902980f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 87 files
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

[cleanlab/cleanlab-studio](https://github.com/cleanlab/cleanlab-studio)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
