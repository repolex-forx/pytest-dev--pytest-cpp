# Repolex Knowledge Graph of pytest-dev/pytest-cpp

RDF knowledge graph data for [pytest-dev/pytest-cpp](https://github.com/pytest-dev/pytest-cpp), parsed by [repolex](https://repolex.ai).

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
rlex download pytest-dev/pytest-cpp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a1b526e69c821051d571a55f67d0b6972b8652a2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a1b526e69c821051d571a55f67d0b6972b8652a2
│           └── chunk-001.nq.gz
├── blob
│   ├── 0054a7e079a263dc46fef44be3641230eb23147f.nq.gz
│   ├── 01c8030c39e657f6d8b0dd22785055b84ece11c9.nq.gz
│   ├── 05aaca3f1a3c2fdf08a6ae5f3d779ac5042553a5.nq.gz
│   ├── 05fd4f894e2694fbb21aaeb24cc76cd3bc494264.nq.gz
│   ├── 06c2cf329ceae9121d04262cfaaefb022d30f653.nq.gz
│   ├── 08534cb6c4e0eb06c5160483a72724d8e760ac00.nq.gz
│   ├── 0a21dd2157707fb32c459248b0c5341609ec0614.nq.gz
│   ├── 0c2ef2e035d1d87e35b7c841245397c06ba55d86.nq.gz
│   ├── 0c4ed92e738ba61ed6b5f28fd3b0cb4ca2c264b8.nq.gz
│   ├── 0d10276c2d4932fe2a4aa6104320f6aa916d3a36.nq.gz
│   ├── 0e759010d9e8f29c0c73abf499d6e59c994982f3.nq.gz
│   ├── 0f9868959d215760f4567fe6165e077739947432.nq.gz
│   ├── 10488b0ea4509a6591f06b05ac5ae14433b652ee.nq.gz
│   ├── 129efe071e95f850b699e3e5f6d13f4909fced08.nq.gz
│   ├── 18990129027e05a75162e6e34a2033096a315cb0.nq.gz
│   ├── 1d4275979ff61101bf1ae9c3205f41f40830c336.nq.gz
│   ├── 20d77f54f41c9bb8800b2c1e92f8d05fbb3c7571.nq.gz
│   ├── 248a89bab472de43c90c52090ce271193fd9a1d4.nq.gz
│   ├── 2712ab4b98fd703af65551edb6e526ac28b2c08a.nq.gz
│   ├── 272d705a91004680dc8b33f7be4058fd716e0163.nq.gz
│   ├── 2b3dd7fbc61f33b2da33ae73e946de877061f762.nq.gz
│   ├── 2cca362120d43473936e3d7696ac9bcee33e1ec8.nq.gz
│   ├── 2f3e35bbd02f92335fb91d70b10a988c91a57e32.nq.gz
│   ├── 30e73d24caaf1f0aeebe71a858c8b0e10ac22f8f.nq.gz
│   ├── 31b25787e844d7fc573ab3fdd813a82845701cab.nq.gz
│   ├── 32b30e758cb7be360f0df496682206c20fdf4352.nq.gz
│   ├── 35f2ff790571deab19bb201b735dbc71d507fe9b.nq.gz
│   ├── 36cdac2279aeea702e0d3520c77258e9273726a5.nq.gz
│   ├── 3a10352baae5ba71acb607e671d9bf15d16e79ad.nq.gz
│   ├── 3b76feae1454806490ffe28305d65617437f962a.nq.gz
│   ├── 3cd47673965a2bd4efaa40eb0c9d6bf4b921ba4c.nq.gz
│   ├── 41e31c1767dee55cc5d5c0bea2df267c5d81176d.nq.gz
│   ├── 49928b827b23319c20aa4e6fed323bceaf325dc8.nq.gz
│   ├── 4b1afe341bc76636659f205aa5c4962147a54844.nq.gz
│   ├── 4c61f52b04ec9139b2cbd2589f26ac7984e2a55c.nq.gz
│   ├── 4f539683e6d65c96c67c993b067efc139737a0f2.nq.gz
│   ├── 526cf778564a8e80cb3661b438c196908322b018.nq.gz
│   ├── 583287ce96ebc282ed3123ea853c16f0e3b7c312.nq.gz
│   ├── 5ff19132ee5c120af9d674eb6d2a8883a9e9805b.nq.gz
│   ├── 659e0f0bb5df62905bb35f9ab038f2c38d3c0e66.nq.gz
│   ├── 65d8dfb834845d059216349a5631b3b6c38d0195.nq.gz
│   ├── 66850068ccda1cba197f24b7ad03c2f36680c480.nq.gz
│   ├── 67d1cfa33251eef062b81253e457b265f0274a83.nq.gz
│   ├── 694fe1e4d81b3fd62da919d1502bb23771460947.nq.gz
│   ├── 712238330c3f56ef284859da5525688f6840d994.nq.gz
│   ├── 742bd203847c95d15c8f409f3ef02b0601a81116.nq.gz
│   ├── 769e613bc5b012b77b677c3a404ebbea6a82427d.nq.gz
│   ├── 781b738952ee0d3af21c4c0f850f5191e1e04f76.nq.gz
│   ├── 7b3d34547316ac9b534b7af336014a577f1f7bf1.nq.gz
│   ├── 877f14b61383ddc691056b99dcac9cf185fa45d5.nq.gz
│   ├── 88c337f8009f9cdadb3b50e30f4b591eb13f8f2a.nq.gz
│   ├── 8b4eb9ecc7204fbf7c6a3598104093fbb8afcb5e.nq.gz
│   ├── 8cb94bffd9416e3bb86b3718e778135b966c5031.nq.gz
│   ├── 9264d9fa963de1230dfa3415d5867cfa871bf358.nq.gz
│   ├── 932334c9187145552ad3ea82981549a771c1b03b.nq.gz
│   ├── 94d3ac3e43f9590e4834d9f0724c226d20e6806a.nq.gz
│   ├── 97db45e2c482572d549dd5e73d3ee281b7a8d1f7.nq.gz
│   ├── 9a091f9f948da18309c51072f43daeaae521a28c.nq.gz
│   ├── 9d5aeeedd41c856f7fd1f9dd52c0209ba458e6f1.nq.gz
│   ├── 9f53e0b3e01db1425ddd6683ccf349a1650e61d7.nq.gz
│   ├── a5f152b31dd89affabd4793d081b8a0db7dadb4b.nq.gz
│   ├── a89aac15836839af983c690e3afa03301354b3e7.nq.gz
│   ├── ab0a53d23baf48084a78feafff8c4049bf57105e.nq.gz
│   ├── b0ee6093b4a250cf11936ccc8208a612291b8140.nq.gz
│   ├── b19416d53c95f084efe51bf8ef23cc693f3c5d40.nq.gz
│   ├── b251404945740333b7e8d53ce91dbf86c45ebb54.nq.gz
│   ├── b97352c3fd5a648c88880e95bfb7d4157ae80bdc.nq.gz
│   ├── ba392cfbd2668b6abeb09b19475c59a07e078916.nq.gz
│   ├── ba411348691886c16f47ffffc71c7e960a014311.nq.gz
│   ├── bbde843ad0b9aa4f1881235d8057bae9c9a4867d.nq.gz
│   ├── be006de9a1ae3b9628e796c74277cd6d61e0a34a.nq.gz
│   ├── c45f1f260e25af5eb67bb7d8bc757612cf4c4470.nq.gz
│   ├── c79698f53413b4db29f030087fad41777505d7dd.nq.gz
│   ├── c9b85602e1976ece147411d798905cb1b4bfa5b7.nq.gz
│   ├── cb08b61a59a9e16b3657861f1c9609001d2096b2.nq.gz
│   ├── cc2bdc7813d060b6d5822bea843371c0bf98d5bd.nq.gz
│   ├── cc8e9c855f8b980a38a3d48a1e72d579445be649.nq.gz
│   ├── d2a29352ba0f34ac7d64c07b914cb93a6cadaf3e.nq.gz
│   ├── d5144c0d00f5c7600693ea025802c0d7d5250d2e.nq.gz
│   ├── d8e8723965a1dc01ea7f656619b71fb5069849da.nq.gz
│   ├── da317eed5a0d258605c89e0d88fc43c17c1eb290.nq.gz
│   ├── da77df59894d6364602604ddcfb0143f421d5c6b.nq.gz
│   ├── dda8857ca052661617dd212574ca296b413a9dbe.nq.gz
│   ├── e0efc29e4a2a977e1a50a45bb375243c968547d7.nq.gz
│   ├── e502d08d73e7d70bede86cbd711754cd09de841c.nq.gz
│   ├── e66f75937f09a3317ab1f7925a3d7a173bcb2011.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9706eebaab6f63e07c443f5d9ef3f4d677c2f7f.nq.gz
│   ├── ea1d6ab2ce57cc30ec387de65de307f957ee1839.nq.gz
│   ├── f2effb6d23b3b7a8c077a65c9e41e2c03d9023ef.nq.gz
│   ├── f5f578b3758fdd22d974a8dbc0165cce0fe9288c.nq.gz
│   ├── f92b4e4269c042de4714a02a5604ce7bd725b102.nq.gz
│   ├── f958dbf471af01201bf869b4b065883648664ff4.nq.gz
│   └── fdd06fb2a92bb6dbb58d1de5372559e8c93c7a54.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a1b526e69c821051d571a55f67d0b6972b8652a2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 102 files
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

[pytest-dev/pytest-cpp](https://github.com/pytest-dev/pytest-cpp)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
