# Repolex Knowledge Graph of zenml-io/template-starter

RDF knowledge graph data for [zenml-io/template-starter](https://github.com/zenml-io/template-starter), parsed by [repolex](https://repolex.ai).

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
rlex download zenml-io/template-starter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3cdcd74d36695e5fec44fe82e6512b763aefe590
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3cdcd74d36695e5fec44fe82e6512b763aefe590
│           └── chunk-001.nq.gz
├── blob
│   ├── 05c2d77657efa19ffbfa41679f91547bbf484362.nq.gz
│   ├── 1118234cbf4851e62fc6ba3b82367ee79b590438.nq.gz
│   ├── 14c3050a0879beb04e5472aedb7ac8c6a6db4277.nq.gz
│   ├── 16ae3630df8f7464729f493cf3d5157313d1b295.nq.gz
│   ├── 17859ea12f54cbee0b269c6008c20ac31efe723d.nq.gz
│   ├── 1e0a8ac5dac0af2d2749d72b8d20e905d89b215d.nq.gz
│   ├── 1fceb056dfd79dc3b658b4fdbd75ebac6b2bbe05.nq.gz
│   ├── 20acdd3cdfd1b8c8ef6fe8437b8f6b6f66e822cf.nq.gz
│   ├── 236fdf118178bf2cdd91fdd8c9f18ffd293c8560.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 29490d6ce0e2ed932fe34e34004db20616be0b79.nq.gz
│   ├── 2bf2968c9c506dd51095c75c6cd555ff91dc287e.nq.gz
│   ├── 3449a2cb9c66165298297276ee17e34e58dc8413.nq.gz
│   ├── 358d5537c8c5b66e2f2e3696ce43b83156b417f0.nq.gz
│   ├── 3697641bee1afa5bf5627fcb4720e0440004f8ab.nq.gz
│   ├── 3ace80894fab147d045e6f17e86faa9b924d9b44.nq.gz
│   ├── 3de332b9d2a2301d4400a47e60efdd74fa880ffa.nq.gz
│   ├── 455f4d7aed45e1272b330a2054eab17dbff9fd12.nq.gz
│   ├── 4bc11e5e934b848d9119d5cc717cbaca33fa23b6.nq.gz
│   ├── 4c1c80e8b91699db5c46dbb265558f10eec5e0c8.nq.gz
│   ├── 609e97d2f6fccbc14a197e1ca68e3d67c974f398.nq.gz
│   ├── 6a7bcaf2d3f90de20378cc4fb84e84fddf3de6a4.nq.gz
│   ├── 7cd9597b7e70c0d3920b8122e1a5f508344d2371.nq.gz
│   ├── 81197e9574f15318a66d83f999593733d2958176.nq.gz
│   ├── 8ba29ae85a57aade34f80f7764a6d43ddfd74558.nq.gz
│   ├── 8f56defad50300bb3a9435ac66a19c581e6f207e.nq.gz
│   ├── 91ba876c5a7a24ef1164ee8e5501c81fd0045f10.nq.gz
│   ├── 9e2caa9ae48c98183323e507b215eafed5f94c27.nq.gz
│   ├── a16d30e209720630785ef6754553c7f2965f976f.nq.gz
│   ├── a2e6a7d0499ed87303cbbc6efed936d3e6c9b2a9.nq.gz
│   ├── a6bf7c902d6b67a1fb11c11bb5c1ba6f2b773d01.nq.gz
│   ├── aee0212329a61c80a66e24f13a0abd79a80f61f5.nq.gz
│   ├── be13c925bf35d890a198e8ae1db8ff22a9590bc5.nq.gz
│   ├── c893ab316411045386506e42af89677f2189bf0d.nq.gz
│   ├── cc653b61a703a2c1887717b362d052e24323764c.nq.gz
│   ├── ce1064545a4a6a4e5597fcfb1f1cbd3960e37f09.nq.gz
│   ├── d0304f68df955a67782b6a0150c01e3b9fc44dcb.nq.gz
│   ├── d12247e02c2cacfe7236e907644d9edf0f0d0513.nq.gz
│   ├── d24b9b006bd5151e6e7eb4a715c9e4802316909c.nq.gz
│   ├── d64947ffc8fd7d79b9d28892509b1f32c078d5e3.nq.gz
│   ├── d756f05d51aa35749a4c83c91fabd6cb79af228f.nq.gz
│   ├── da5a95ce53804ae75ab871e0fd71fdb1ef9a71a6.nq.gz
│   ├── db3019132ee75b75cf331422cd0ea4d5eb37be8d.nq.gz
│   ├── db3fa2ce67e9d354f6df66edf1198f87664e2e02.nq.gz
│   ├── dddbd1e9d3bb041d4048f76ebb140ea30e5ab488.nq.gz
│   ├── ea97bd4b12a690fd2c6913f7416615273b572593.nq.gz
│   └── fe6c6a0abd500a6c5812ef07cf87a48f7d14127c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3cdcd74d36695e5fec44fe82e6512b763aefe590.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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

[zenml-io/template-starter](https://github.com/zenml-io/template-starter)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
