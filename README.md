# Repolex Knowledge Graph of executablebooks/sphinx-panels

RDF knowledge graph data for [executablebooks/sphinx-panels](https://github.com/executablebooks/sphinx-panels), parsed by [repolex](https://repolex.ai).

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
rlex download executablebooks/sphinx-panels
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 44bab2341d97707365396efc0b23a1edac26da7c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 44bab2341d97707365396efc0b23a1edac26da7c
│           └── chunk-001.nq.gz
├── blob
│   ├── 08aaed205a6ad5a5bd4e0b7b26c0c78c8facc103.nq.gz
│   ├── 1172b9004ab7bcc1b6209185f4b3e9042a915ad2.nq.gz
│   ├── 19ebd7ed8aa483fb7cc962ce07139538de10d6f3.nq.gz
│   ├── 1b057df2f20dfd4bce4e1eb04026384cefcfb300.nq.gz
│   ├── 1b6555cf7c35790e997e2bb0aa07393a8b0f5def.nq.gz
│   ├── 1b68cc99390609c294198a4904d8ca268fe7bd89.nq.gz
│   ├── 232701f4110b6a6d6d157d1948e5c7186f425da9.nq.gz
│   ├── 2629460aaef5118cb1468cec7d8f900d95355fac.nq.gz
│   ├── 2a08e1cec4aa469911e5692d0c23f0635b63ad41.nq.gz
│   ├── 2b1e0db3e5acb53e417d65ffd1f34124215f217a.nq.gz
│   ├── 2e357cd414a362ff3c8b84402fa65fdab97a40e4.nq.gz
│   ├── 2fe55aa721f1304567b5b82a785424701d6af95b.nq.gz
│   ├── 350df47ac3c761baf9f5e9c654307eb61da927c8.nq.gz
│   ├── 3525377d5e24de4cf9e69381ecd9e75d5cd8a733.nq.gz
│   ├── 499e2ed3291bb084528d4ba8fe8775f324c3e6cf.nq.gz
│   ├── 4bc95b96ec58e873965af6650c0a1b5036a23af1.nq.gz
│   ├── 544c6d9f38abeec86ff61cdd1f11faba74a59184.nq.gz
│   ├── 57a68aea570b0d255150947f652b9e89d3dea418.nq.gz
│   ├── 5937569aa7255872b5594d032843355f1bd3f96b.nq.gz
│   ├── 5d30bd85ccb91e319ae16f22164bbf2071768bea.nq.gz
│   ├── 5fd0792af301780755fd3b68021f6e60519b74cd.nq.gz
│   ├── 61b945a7c2e9d12bc01d9c804454e0aed4df1939.nq.gz
│   ├── 6b9c046303a382f6b2ead2bd89b722888391a585.nq.gz
│   ├── 71e04aa3a5e38b47355795b06fe99565b5305305.nq.gz
│   ├── 7b4accb344a7c5bc9011a33b491440566105035e.nq.gz
│   ├── 84c26c26f36ad232cbd4a5026e2bf61312b41b6c.nq.gz
│   ├── 84e5d969d23713d839892e39658b21ef59d3ed22.nq.gz
│   ├── 8539bafbd088eb9c841c9fb7ee0ce657274f29a9.nq.gz
│   ├── 8695f426bc86e5324344bb1893e3399943820c28.nq.gz
│   ├── 8e5b3bd432e9ea96492638b9ae46c17c2d58a465.nq.gz
│   ├── 96956528242ce1cf14e7d885bcf8856e311399ac.nq.gz
│   ├── 970578a0eabbd358d9a6fe8b9da82daa94c43070.nq.gz
│   ├── 98624cd420d9c9e4d1d9a4e6b5eaee6ed1ff3e84.nq.gz
│   ├── 9c8d89d018b9b0350ee13ed75e775804d88f6033.nq.gz
│   ├── 9efc2c287d608885aff101e752062b56f2bea6a8.nq.gz
│   ├── a655c26b7b26ce7b1186ceee1cd65a9a97802548.nq.gz
│   ├── a7c650b14ab4777ab89ce45999b5c113dd05ed38.nq.gz
│   ├── ac2a5469fb580dddeca419ca32ed3677bd39b47e.nq.gz
│   ├── b3f2d1a4c6b680c01110201845ab91d626b60f82.nq.gz
│   ├── b7977ed7d352921a450522ea99b3febf6f613e33.nq.gz
│   ├── b98433032e7bf308eb4300be8c8e2ed8f3e1d66c.nq.gz
│   ├── bf1f575497eadf02c4e85717bede7769fba2c1ce.nq.gz
│   ├── c5f9edef1a55f512c4d9ff904f55c88e0eb69584.nq.gz
│   ├── d335657bf2a4d259b51e82cea64341c03759ccad.nq.gz
│   ├── d9e2855525e1172f4e52f27591c04f7a8ad30f70.nq.gz
│   ├── dd57a8c15b8b8bee62efd53b26bbfc2b7fb6b357.nq.gz
│   ├── dda9865ad01e8f6ecebfc69f0889c81050a594f0.nq.gz
│   ├── e165dbbc7b18871f4d240fa4f3655693678bbf59.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea9efe1db7b49946d7ec7d60e282236dd5188709.nq.gz
│   ├── ede386b625c2beaf8c449ae0578e2327011d1adf.nq.gz
│   ├── f44161d9a4112119226fe1ad84aff9b8bd989096.nq.gz
│   ├── fb028fd785266cd372629224acc53413bbfbc140.nq.gz
│   ├── fc14abc85d6dafc8460171ecb4c8f2addef1ce9c.nq.gz
│   ├── fc838aef5e457c508ad3c41ac93e851ab2d14c5a.nq.gz
│   └── fee388005a8f43fc6fcafe0e7e3ecda6949a8a93.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 44bab2341d97707365396efc0b23a1edac26da7c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 64 files
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

[executablebooks/sphinx-panels](https://github.com/executablebooks/sphinx-panels)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
