# Repolex Knowledge Graph of twisted/sine

RDF knowledge graph data for [twisted/sine](https://github.com/twisted/sine), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/sine
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a81b653641b559936bb35bb328eafe44d420b162
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a81b653641b559936bb35bb328eafe44d420b162
│           └── chunk-001.nq.gz
├── blob
│   ├── 00b25c8e5f1b8b4079afb8f3a8bb0ff7609c3931.nq.gz
│   ├── 02ef8db2e7d269dee6b8cd44902e487537342f1d.nq.gz
│   ├── 068ecfb7092547a46797d70a64ac8422e2339d17.nq.gz
│   ├── 08d72bd8c96db3653adc759108cca86c414ee4b9.nq.gz
│   ├── 09458b29a41ed263dfb3c6c93cf5624e9da89064.nq.gz
│   ├── 12998ac69ca1dfce490f0203c5830f57a2e2db84.nq.gz
│   ├── 1446deb69ad46c4fdaaa044c62bf12dbb8d10479.nq.gz
│   ├── 15e7dbedec3ce7c74e2545587bdaff01dcbec569.nq.gz
│   ├── 1a9c5d7a0d5d672be999968ce6770b2e33e7730d.nq.gz
│   ├── 1aed2c4762b954c5ee18e7baee51167f6baa046f.nq.gz
│   ├── 1c7000d4474d8b1bc029f68354bb8825382722c9.nq.gz
│   ├── 1ed992552a1fe7d7b40332ae6a73008e2beb6b9e.nq.gz
│   ├── 267dae5b2c70102e0b777b6f7786284bfd03c1ae.nq.gz
│   ├── 2ede0f9c0efa00f06d06ff73fbf2da4ab8e94c89.nq.gz
│   ├── 2fd6238c18fc54d551587aa3ea27a73ddad55ea1.nq.gz
│   ├── 3b74e73e89658b830e8f1b667825441d2d29036f.nq.gz
│   ├── 47e725108999cd1fd6aa7d42b7f2ee722a05f0e9.nq.gz
│   ├── 49d6e8e3842c370f79105d0959edca84854c6f7c.nq.gz
│   ├── 49ed4042deea0a3ea5cb8a3e58d5fea4a481a0d6.nq.gz
│   ├── 4e912be46513515a3bb6f9d4b78da2842f9c3825.nq.gz
│   ├── 577d0bc49bd91f7f51a54cdcb6b2b6a22913db03.nq.gz
│   ├── 5d7ab583e04394cef18da1f3ca9c36cbcdb37009.nq.gz
│   ├── 6200cac911ff854915bb836bcddd432a970f2bf2.nq.gz
│   ├── 71d2086f2deb9b7fb87984c120f7f7f6f8d61a38.nq.gz
│   ├── 76f8a4bfb311f11f2711a56ff9aab789d94ccd80.nq.gz
│   ├── 7dbfb9d0f53e4744e070acaccbaac18e90aad3a4.nq.gz
│   ├── 80e05f2b5130e7bc7dfd0d1a58445b7daab0a95e.nq.gz
│   ├── 81ae18f993c82639724de844520cb3744352e9ec.nq.gz
│   ├── 823bce9c4218a4dc492c88b91ce651045ed4a18d.nq.gz
│   ├── 8b13c873e9e3c2099eb29c282117535df05864c7.nq.gz
│   ├── 8e0dfcd48ecbe62624008b2d49bfe83deee3b9fa.nq.gz
│   ├── 9d85712e2dfa18f47bc7cc15514c7ab42a1bb82a.nq.gz
│   ├── a256f0a9ff14fc6592782377cad6c9195305ebe8.nq.gz
│   ├── a49017a3ed4f645fe57184e0e21a75db45639423.nq.gz
│   ├── a98874bb3db79afb61b91a1bf6d498065529000e.nq.gz
│   ├── af61682749318ceeba0658ce94f3edcb482d3cc6.nq.gz
│   ├── b5bcb24a3950ffec9754a678ceea4b792b47503c.nq.gz
│   ├── b7c07640038237389ed231c4b536a76c52de2a5c.nq.gz
│   ├── b80a7bc9d58be6f0f5cde85129cf7ea21e06e6da.nq.gz
│   ├── b8369da666d58d8366d210ae0524090a28f9ec89.nq.gz
│   ├── b944bb1cd51b26217700dba9f1a52d9c32c0ace0.nq.gz
│   ├── bb73ad752c4040aafa4b763f180e362d03427245.nq.gz
│   ├── bcffe0030d550b490236cdc90098543a8cdb1dae.nq.gz
│   ├── bd4052f1f7bc699b0c6ac5b35b1a8f7817394067.nq.gz
│   ├── c061bff8dbacc330fcba7a7b63dd69ab4ed5807c.nq.gz
│   ├── c234dc1fdab5f4604134da6a444bfd85ceb6ed0d.nq.gz
│   ├── c255d2fb031959b8d40b6162bcc311ee441657c0.nq.gz
│   ├── c50534e5818f93f12161cb4192d3d46aac4e6b5c.nq.gz
│   ├── c554099fbac2d664a0be849629e0ff5364a2a703.nq.gz
│   ├── cbac10f903ab47166812121830fa128efffccf41.nq.gz
│   ├── d1f29d4a9ce3d1fa8374450272007aeb515d6515.nq.gz
│   ├── d9560178bfcfdfbe9c83b6cc84a3da42102a4355.nq.gz
│   ├── d96db9ca40c3928b175288f8183d9f2d7b79984e.nq.gz
│   ├── dbea10779a8011b449c0dd341c744646b33908e5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eeea34a716f24fe82c73bd983bfe20b380a4637b.nq.gz
│   ├── f40b9aa228d0306154c2ba03255981de0b17058b.nq.gz
│   ├── f47e52a87a7d35f05c27968ef3ca434acbcf36f1.nq.gz
│   ├── f56e981ef4d17426e5a8300ff400567f50ac513f.nq.gz
│   ├── f618fe4041d9ea6b8febdab8ea9838d80105e00f.nq.gz
│   ├── f89a71be5bc88a0ae85847375c6c3461c33d0bb3.nq.gz
│   ├── fabd541569eaf76311b18af03d0e81365af60033.nq.gz
│   ├── fba114288a04691bbb924c8053203412dca214ed.nq.gz
│   ├── fe8118d6022047c4516267b75b203a6c1bcf0a4c.nq.gz
│   └── ff15a0de0cd5395a2a93b2846f87caacfef5ad7f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a81b653641b559936bb35bb328eafe44d420b162.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 72 files
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

[twisted/sine](https://github.com/twisted/sine)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
