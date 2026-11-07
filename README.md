# Repolex Knowledge Graph of allenai/olmo-cookbook

RDF knowledge graph data for [allenai/olmo-cookbook](https://github.com/allenai/olmo-cookbook), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/olmo-cookbook
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c226eb6a07ccef068c26379d9c90304fbaeea841
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c226eb6a07ccef068c26379d9c90304fbaeea841
│           └── chunk-001.nq.gz
├── blob
│   ├── 02a28d4e4d86c9b1d8d0d651f6ab83b1347bd508.nq.gz
│   ├── 0c6f6b67fc73ee67f8e8d4bb0446ca15dd812db6.nq.gz
│   ├── 0df71f690919c3ca943a372c1eb77b768f621953.nq.gz
│   ├── 0e5dc8b3a1c64c15015444e4cde3caac7f2fbc39.nq.gz
│   ├── 117f82fef2b37342131914bfcffa5fa0f801f9aa.nq.gz
│   ├── 1356f844cfcf2ab4da51c7f8778326c8d509dd4c.nq.gz
│   ├── 161c77f6d8a87ad72d5da9a6820b1148229ee6f8.nq.gz
│   ├── 1bbf7f050912510175369bcb54437a3130d024a8.nq.gz
│   ├── 1dfb44b8b6e895bcaf9979bb247495ff8dab7a76.nq.gz
│   ├── 1eca7493dcafb486eb0de0b2c5e530acc81ef362.nq.gz
│   ├── 1f71434d8ada2cba2b93415a636d4d93a1fb5db9.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 28374eea90cdd8315833fa64129706ef9c4d0503.nq.gz
│   ├── 28ef29faf5a2f00b7024b76eed15367c1b203f75.nq.gz
│   ├── 2e02f94d23e775f233d054d996d5e3651c2c7ea4.nq.gz
│   ├── 2ed2c1128b0722ed050a61eadadfb8295aa4326e.nq.gz
│   ├── 34aee87765c951f5ca465ac47d3930d0471a9706.nq.gz
│   ├── 38a3608e2246d741aa025c5204b9404e861c02d5.nq.gz
│   ├── 3c2e43397e52ca0552e86d33c153419c8b2dbb48.nq.gz
│   ├── 3e03ad9c8291c3718bc2fcc3e4a31d2cc51ed3a2.nq.gz
│   ├── 3ea97c515223483c1bb2cb6f7e5c84c4b42e369e.nq.gz
│   ├── 41446bd9e730253f160884451eddbf3f6de201e4.nq.gz
│   ├── 42a3bd7179a62cbb5ea3951b792d4607be53a2f3.nq.gz
│   ├── 43e7f255e5dbf510f20de0215f919d0ddd27d56c.nq.gz
│   ├── 4a3f6eac37a38a84650aca6de42ed9f2b1a06c30.nq.gz
│   ├── 4c83db2d32aa4421f02481c0b597df00a1b0811c.nq.gz
│   ├── 4db2e6da171065dcbb2e03ec0d06b74b4199070a.nq.gz
│   ├── 4e38ef6d063b5e512ab8cad9ef0a150d06c1cc5a.nq.gz
│   ├── 4ea8426d1ca70c3ee4062196a25726f00c0ba3f5.nq.gz
│   ├── 52c64c2cbb6ed51fe0ad0a025b643e0e5126da05.nq.gz
│   ├── 53c57189b2e1f512778bb3cd463e396fd4e41734.nq.gz
│   ├── 5626c2f677b40e2302cf3d6c0c695a43cd82e08a.nq.gz
│   ├── 5709d2443de82ec3085c73af9b64545f385683c6.nq.gz
│   ├── 5751e28218b70e6e2e0e65dc6ad50e751fd0c7e8.nq.gz
│   ├── 57a92e0d937a6ccd2fe3d4d9299be3b5637e9cb4.nq.gz
│   ├── 598ab930bf19ab06b22ddddbb2a2383c37375e3d.nq.gz
│   ├── 5b16f748c7337a10158e74a16f69ef568403b15c.nq.gz
│   ├── 5cebb0f65c45a38a7970cfe29f3a8dd5da45888c.nq.gz
│   ├── 5d9f0e08ce86a7dc0dec225c404e7de8c80b47d5.nq.gz
│   ├── 5f1e679a957e4fd8aa8c099d49c71a42fa6bca5f.nq.gz
│   ├── 5f3d89164e9885c5fa94e35e83208bf6952663d8.nq.gz
│   ├── 5fed24f898d1fe2005aa911193b8ca78a59cd4ae.nq.gz
│   ├── 650bd1866e1cd967704f58e364d0e1f43cd46577.nq.gz
│   ├── 6abebe062ac63a306bdcd6acbd7c366c4d7bdd56.nq.gz
│   ├── 6bc2fa7cadaa8fbc89ed461339bf94c324df5e57.nq.gz
│   ├── 6d9b78f64f7a0c55f0de313f46e44f3e3ff77ab7.nq.gz
│   ├── 6f6e59bb9a87db4fd31adf2de606da7833da2e58.nq.gz
│   ├── 73148d4aceec392464f839c4f00c0776fc499c00.nq.gz
│   ├── 79ef199454a078112bd82dda9b74502dd9111633.nq.gz
│   ├── 8108f300871cbfd11d05d0f4f3b192581f4df5ee.nq.gz
│   ├── 83ae3bdf350698ff09fffa9fc89d8eb0804ebc16.nq.gz
│   ├── 869b724b2672acce8088941d754073705cce9b2c.nq.gz
│   ├── 8d9359d286860a76efd57c33b0a046be824d90c5.nq.gz
│   ├── 8deaa7e3b5b778f47fd6a7cbd76ad9c9e8ca778a.nq.gz
│   ├── 8efba3ecdfe28955fb3d3049406c48384ef18d27.nq.gz
│   ├── 92eb621fa677c5e5e49627b1b1b0d0169b3b9b99.nq.gz
│   ├── 9502b44f186a3211e060138ef0c8592e688fcdcb.nq.gz
│   ├── 96ba8a4d3cfc09026aae3496aa8679fcf520b490.nq.gz
│   ├── 9b84b8c29c089f0b42363f0fa26d34c097502a74.nq.gz
│   ├── 9c7665bf9cc4fa02e8e6016e23a63cf60c964c9f.nq.gz
│   ├── 9d24ff502945597f7df442093605d1a58ad5373c.nq.gz
│   ├── a573aeea3d5fb6b911eb3b20efeb7e2e21d50b90.nq.gz
│   ├── a5b4ac5abf6bd391c5e95341124c7d72f26c4ac0.nq.gz
│   ├── ab57c50ce4aa20ef826a4f741755b0c354bf5f3a.nq.gz
│   ├── aea7594ecd32789ac52910cdebc765c85d330bbf.nq.gz
│   ├── af4eb806b677c89ca8418f2952d0af9e04e4dc37.nq.gz
│   ├── b0ba5e6e2333161fdc9fab7513fb201fb839a225.nq.gz
│   ├── b5399d062135547d420da05c3aa996500abd547a.nq.gz
│   ├── c293b5c8f1f8cc20a2952ba1b58c9ef6115186c5.nq.gz
│   ├── c3b63a9555414c9e88e5388e25e8bf62f02baa2a.nq.gz
│   ├── c499f20ddfa890c454acda23c23b07cd7e5cfae8.nq.gz
│   ├── c64e99161e4e3742a9cde913cb66e28fed7e7d06.nq.gz
│   ├── c80d2dc81d775f41ce93f45f484bf7b24f6dcce0.nq.gz
│   ├── c8de6203af549f99a6a53674bd5b8695ca81ab72.nq.gz
│   ├── ca5349264507ea4e074b5fc74af530cf1e077bab.nq.gz
│   ├── cb505789df1f0958185c3c0f3b1b2e90a028a74e.nq.gz
│   ├── cb766c745309b0db53cc5a59dbb5a3b554a58684.nq.gz
│   ├── cc360cee487183f38e2ebd02865eaf3e666e7c1a.nq.gz
│   ├── cd385642af0b7abe9faa8d696ce384d8d6335f9d.nq.gz
│   ├── cf98f510d1e3d836831ca9bb745c46ba1e4c4000.nq.gz
│   ├── d71284073a67f9272180b3584d4cc412202ae3f7.nq.gz
│   ├── d8abdcddba23deb9f59e02e302dd7e64618ad318.nq.gz
│   ├── dc124d72a71e4aeee145bb92bbc370e972d6bc56.nq.gz
│   ├── e1a3166e5152fd9c0922868ab2c1a52ca5a422dc.nq.gz
│   ├── e682d2b83ea449dc47c16d6f9ee67bef5aac4e22.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb5fe85d0c1b0bf8937787635d19a304a3d72487.nq.gz
│   ├── ec44ca444af52d75b44836f9f944f1e58b99ce97.nq.gz
│   └── f7c59d60bb7c22b91a14edc1971e0234965ee144.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c226eb6a07ccef068c26379d9c90304fbaeea841.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 97 files
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

[allenai/olmo-cookbook](https://github.com/allenai/olmo-cookbook)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
