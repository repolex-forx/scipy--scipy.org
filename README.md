# Repolex Knowledge Graph of scipy/scipy.org

RDF knowledge graph data for [scipy/scipy.org](https://github.com/scipy/scipy.org), parsed by [repolex](https://repolex.ai).

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
rlex download scipy/scipy.org
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2f177bcdb7b5c9b163aa4951db52b0512baeed8f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2f177bcdb7b5c9b163aa4951db52b0512baeed8f
│           └── chunk-001.nq.gz
├── blob
│   ├── 025ec35c4f89f6a90a88456d5e2c079e5762cb3f.nq.gz
│   ├── 04a305ed1e80d3f92e9e22b870422e0081349b08.nq.gz
│   ├── 0993caf700d6ddd2742f4a77f0ce58753aabae88.nq.gz
│   ├── 0cef45e9f8424433e9127b1d25ad806e4e9fa335.nq.gz
│   ├── 0e7503bcf9fa281503e5cf87c081420f7428c312.nq.gz
│   ├── 0e9ff58ffb4d2fdf5acae2849ee2e6601f213734.nq.gz
│   ├── 1118782434af7cbc915c8014dd0189fd534a2067.nq.gz
│   ├── 124ef481bed31d8243a2e3bea9c8e46906917921.nq.gz
│   ├── 17918a1a52d175f80519505cc5df94f074c71f0f.nq.gz
│   ├── 1b54986a888388a819aaaa881a1c703388f8e4e7.nq.gz
│   ├── 1bee151bea4dc5275086c05ac12abd70edf29e59.nq.gz
│   ├── 21f381c532eab3b340ce0a63cca5b6a8f6b14d96.nq.gz
│   ├── 26f317f303e7d1c370118aa59edea7fa59a7c28a.nq.gz
│   ├── 28459f376f38fc702047796663ea1328ecadc739.nq.gz
│   ├── 2bf834b60acb88ff2b251436c2d78eed0c110e9b.nq.gz
│   ├── 2feca309049705839a2e21e40f734571c04d9e7b.nq.gz
│   ├── 3072d8312ad57736b4ad3f6ccdada4f5fbbe56bd.nq.gz
│   ├── 3176333310f7bafbab0d8013f31fe90ab335f9fe.nq.gz
│   ├── 33974f88773f14d484a9f80d6df2d65b58d66ba2.nq.gz
│   ├── 34d078ab08e995724691ba9f7da5a62bb496f231.nq.gz
│   ├── 3925fe5773e76bb19173a6391a0eb0018177947c.nq.gz
│   ├── 3ac7ef3878c3e7b32646250ffd43a4973316d3cc.nq.gz
│   ├── 3b5ca194bfd47e19006e609790212fbe7887a4b6.nq.gz
│   ├── 3ccf2cb2d9187e15c9807b47dbe0e24d5d354e8d.nq.gz
│   ├── 40f0c5dc3d4d136081fb25c02ccefc1a1c81062f.nq.gz
│   ├── 4107cd4e09a6721fe58b55438320814fde51fcb9.nq.gz
│   ├── 439d8e8a651be9f2761b6f79a244d71090f32743.nq.gz
│   ├── 43ddc182c98b515c1924149ee538e66f7aa003de.nq.gz
│   ├── 43ec3f01778d5ba7fc0ab66166b56947f8a9141a.nq.gz
│   ├── 472bf4fdfbd5506beb2b344a671d2d39000cfb69.nq.gz
│   ├── 475eba53af07f0579f8a1e1fcdccbe573459760c.nq.gz
│   ├── 53b0cb844307a94ab2d0dd96ddec8b136574f00a.nq.gz
│   ├── 54a7f4465e00d2bcce1e1fbf5350a5d6439ebf32.nq.gz
│   ├── 55fe20b8878a52cb960d69682acf57a3bf5b8bad.nq.gz
│   ├── 59a765cc5552c26a2d46f1ea5befadedfea620f2.nq.gz
│   ├── 5cfdcac56c5bc4ed9a7e4d289bd2710bd4fea04d.nq.gz
│   ├── 63ec40f31c3681b785e8fe845f4478fe93eefe62.nq.gz
│   ├── 65c1a80ef01df52f1d8d824f6a6d5a5b707c5362.nq.gz
│   ├── 65e09a4e7caa9aeb057272ee8b706e7afc81b7f8.nq.gz
│   ├── 660f57a18d38c8d5869178cba95cb33484e813b4.nq.gz
│   ├── 674e5930c3dddd4a603920fafc4857bb56381d25.nq.gz
│   ├── 679eddacbb934a5bd689bb775f727d4b7ab1c8fd.nq.gz
│   ├── 6d781a3ed760578af4c7f509be134f71a321d32d.nq.gz
│   ├── 6d85a6d75561a2a1ee867490e13d7569e8cb7785.nq.gz
│   ├── 78df03c91e30c764df2182871475cb5793c261f8.nq.gz
│   ├── 7b6c1fb3bf4eb7f13223aedd2d313998d1932098.nq.gz
│   ├── 7bb955bd1c9e7617e44197993288997c9a82466a.nq.gz
│   ├── 841f16d1b359ca0770ce6a2b3821fd865d855abc.nq.gz
│   ├── 84628e904128195e9189f738ba242686f6397337.nq.gz
│   ├── 86633b240c536b371c1429a4c0b7f0b9c0fc5fff.nq.gz
│   ├── 870daf7994b2e126da33369a8cd331ded5faa6eb.nq.gz
│   ├── 8945dadf12626d501c497f91d60dffb994c705c2.nq.gz
│   ├── 8c1f534382a1d2f14c037fb16ad1be36a8c51e1c.nq.gz
│   ├── 8d57adbfad8de0a05fa739253a6754d458c58e1a.nq.gz
│   ├── 97c847d9fb82423ef5e59e83638181160be492ce.nq.gz
│   ├── 9930d6fcb8f7fcd6d1920ab037dac60482529b83.nq.gz
│   ├── 997504b465e8f8c409ebee298542e7e0b8e84d94.nq.gz
│   ├── 9fc53ab71018a204c050aada0d39a3d2647f388a.nq.gz
│   ├── a05a606b013428c263a179730cbd6e55633d9606.nq.gz
│   ├── a9cff3794409855a29d598b2c3a872477f91697d.nq.gz
│   ├── acf03e9a058724d581963b9f71695b94e2bcadbf.nq.gz
│   ├── b117035afd95f219bcb1e9b8e913952e6f5b6c5a.nq.gz
│   ├── b9c55bc8bb2fb622e5cd87849e151b918eb75ba5.nq.gz
│   ├── b9dc581546f45c35a195a9e5ee421d0d37d37021.nq.gz
│   ├── bb2ca095ac83d34b815c6f0543bede0472599c2f.nq.gz
│   ├── bd1119bf7f151fefbdc59a94b56efe49c09d1614.nq.gz
│   ├── c15c45f54c59020eb82541c6a9730056df691525.nq.gz
│   ├── c71f97d6feee5fb34afc6ca356aea6c65920ded2.nq.gz
│   ├── c8926f254f278258ec3b516e80e181fd4b55d751.nq.gz
│   ├── cb10015f3588c216f69e8a3095e0d01ec004db3a.nq.gz
│   ├── cb2a5f752658c64ac48827c9e92ee650ddb74ef0.nq.gz
│   ├── cb4a9743298460fca68727cd665ef7c60d998b4c.nq.gz
│   ├── cfaabe3b4f480255f1182796d03863f40e1b4fed.nq.gz
│   ├── cfb4d57b7813fc52a9c94e38f5d853d0dedfa6d8.nq.gz
│   ├── cfed564c58f2286edd5523104d427dfa00931ebf.nq.gz
│   ├── d08af909be6a4e82a8ac984749664b1bfe33f133.nq.gz
│   ├── d3d25b34b158b3bd98129f648c62c4cf96d34c98.nq.gz
│   ├── d60d53aa08e20636737399a71467624128cd95e7.nq.gz
│   ├── d68f6787ffb93958242add7dbc9dd742df7ed3d3.nq.gz
│   ├── de7fb686ccce5120cf5a6e814de7452f316d43bb.nq.gz
│   ├── ded59ffe71951809f9dd1df99ed2a06ecaf6de3e.nq.gz
│   ├── e664af965af6a30aad0cf9f7bb5599a28c4b5b45.nq.gz
│   ├── e9b12c3ecb47d2a2a7bc2b20b43ed3d695f803ae.nq.gz
│   ├── ea8625df54f1656c44f6cceb3bde030527bff932.nq.gz
│   ├── f1418e9fee9d29b2c47da2703b66727b016f98a1.nq.gz
│   ├── f38ada4e8cf9848e55ed41b2dc427d9ac0893aaf.nq.gz
│   ├── f5669a0c8d172977b9f8a0f9169b1bbe619b5f6e.nq.gz
│   ├── f5a2a28d757c5e1d1ccba46597500111748ba1fb.nq.gz
│   ├── f9173cc732e39ba74476c0da2890f5382d848c03.nq.gz
│   ├── f928a53c496a38b47875a9f2a5933522b0c54cb0.nq.gz
│   ├── fa4b3ed8cabb702a7df5f7ab2c4bd7875537a4f6.nq.gz
│   ├── fc01a2940428a0d879c7cac332b5cad64fdd8b36.nq.gz
│   └── ff30947a09fccc918e15a9186f6e70506e1173b1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2f177bcdb7b5c9b163aa4951db52b0512baeed8f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 101 files
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

[scipy/scipy.org](https://github.com/scipy/scipy.org)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
