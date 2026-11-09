# Repolex Knowledge Graph of airbnb/javascript

RDF knowledge graph data for [airbnb/javascript](https://github.com/airbnb/javascript), parsed by [repolex](https://repolex.ai).

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
rlex download airbnb/javascript
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8ed19247bef145e3cc41b24a02dd1fe6d9b5e681
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8ed19247bef145e3cc41b24a02dd1fe6d9b5e681
│           └── chunk-001.nq.gz
├── blob
│   ├── 01e519867165d9bc4eb0f94b202ee32cc1eedaf4.nq.gz
│   ├── 06f4f8907524aa788436b5daf19bdb7f5a04e3ff.nq.gz
│   ├── 09c247451afea2864f95c1836a7b1b8cb9ffe01f.nq.gz
│   ├── 0ab4f937f71af20e5b88184a303efe7f27267c45.nq.gz
│   ├── 1b3ce07defc7d764cfc000a47da1edcaf2636c94.nq.gz
│   ├── 2e6ab68a1b32e4e579e7f91a42a22c42b1cd19a4.nq.gz
│   ├── 4380bf5567f46e5d25d46465331624e9e34a26bd.nq.gz
│   ├── 43c97e719a5a824700932f72e6e7e6748ce45d01.nq.gz
│   ├── 51522a3f4eaea1c2aa21affe1594ce792a291daf.nq.gz
│   ├── 58065120a46c35321af0048a5661f7e3565eebb0.nq.gz
│   ├── 5808be61865839a503479f44997f87eed4793bfa.nq.gz
│   ├── 5e59cbebf47b9e32410c8e21b62b397ec5f4e387.nq.gz
│   ├── 6432e10ddaba4284c1eed67578d44268d7034f73.nq.gz
│   ├── 67cfd5e8a35cc6bcb58fd69e6846f94f38eef082.nq.gz
│   ├── 68ba86b9251175824ab6241ef36a4038ad3cd25c.nq.gz
│   ├── 69d80c025220d0b6480d4a5984ca6f4f916b637d.nq.gz
│   ├── 6b0d3bfec77ac5495471ee4e3ac0fcaf5f9ad9e4.nq.gz
│   ├── 72f4ab8078faa9501961d3ea6995e9ecfa083a16.nq.gz
│   ├── 7606a50a46b30ef30a5367135811e38d938a4283.nq.gz
│   ├── 79052b256a1b798a60b80e15dd29ff9ea199b580.nq.gz
│   ├── 7c4cf691c393b803882afe6d2e27e61288da7889.nq.gz
│   ├── 7ce44c98211049f9bd2a82184b524bad7dcd670d.nq.gz
│   ├── 7d61989e6ab3ab6b232cb91979dcca536bdb3265.nq.gz
│   ├── 8176480fe1a1f0da34cf2d25a7ac274b1bc0fe34.nq.gz
│   ├── 825456b8a48dd1220af79c72aa60f44ba7af3a59.nq.gz
│   ├── 8f3f054d293f97dcd8061d76fdc136db1000780f.nq.gz
│   ├── 9c23197fabfb4b927b2e784456664ee3072043be.nq.gz
│   ├── 9e203a54733db55062449d10c6aa7d923a946121.nq.gz
│   ├── a3dda4e5101bf4b59ebd47add5f8080a3079710b.nq.gz
│   ├── a7a08a349e0d58fc4a8b94e87157b82708ff694d.nq.gz
│   ├── a7f70284e35c9a14dcf72fb5faa1ca6409e3622b.nq.gz
│   ├── ab2c306fd9dac19cfd7900959e8ec37ef7f14e43.nq.gz
│   ├── ac10dfe52800d1a858923e927c39d69abfc7d45f.nq.gz
│   ├── ad38834d88049def98184cbc15c9168247e1ad20.nq.gz
│   ├── af1b557d11a1eb964e2dce055cafd67f6da1a554.nq.gz
│   ├── b178d7f909e8e052c673346d55a6dc4dcf97794d.nq.gz
│   ├── b9453924dc9aa3fdfd3fa50a9093771bab85bf05.nq.gz
│   ├── bb1ea3911806644fb4a5240be3892b9dbfeeaee0.nq.gz
│   ├── bd91faf2ea5a751f9f9c3b72e5e44477a2846465.nq.gz
│   ├── be17c9a571a54f8859495ae4d4cc1d527a103be7.nq.gz
│   ├── c4d29e0b3919ec28b646e020302d890c8f9c25b4.nq.gz
│   ├── cba44bb384cf56f20d6083a86eab1061f70e214d.nq.gz
│   ├── cea4567406f0bd183205299720d8cc455f2e2218.nq.gz
│   ├── db6f34c77cfe6647412538be87f14093fa3d5fdc.nq.gz
│   ├── e0aceaae1c40e15c849e38d65a370b8a0086b4c7.nq.gz
│   ├── e18088143add65be0c365049edb6ee7ee3a5d614.nq.gz
│   ├── e5c9089c7525adf0994706628acd068ea215adf3.nq.gz
│   ├── e88f71224a58ba33319bcd15ea5947d7699ecb3a.nq.gz
│   ├── eb3631b9e33b01b7df8e7e45af6a3e16ad3034e8.nq.gz
│   ├── f405009e869d0f57b0a159095039f5bdf5063a43.nq.gz
│   ├── f61602d161a5753a7d039ee90c465101c1df5222.nq.gz
│   └── fff3ba2d33ebdfdf5ae0ffa6ff6411dadc5b28e2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8ed19247bef145e3cc41b24a02dd1fe6d9b5e681.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 60 files
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

[airbnb/javascript](https://github.com/airbnb/javascript)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
