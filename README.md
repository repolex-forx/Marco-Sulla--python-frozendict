# Repolex Knowledge Graph of Marco-Sulla/python-frozendict

RDF knowledge graph data for [Marco-Sulla/python-frozendict](https://github.com/Marco-Sulla/python-frozendict), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download Marco-Sulla/python-frozendict
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d4ee7590e2b507fd68124cd8a593778ce3c1158b
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d4ee7590e2b507fd68124cd8a593778ce3c1158b.nq.gz
│   └── repolex
│       └── d4ee7590e2b507fd68124cd8a593778ce3c1158b
│           └── chunk-001.nq.gz
├── blob
│   ├── 0a041280bd00a9d068f503b8ee7ce35214bd24a1.nq.gz
│   ├── 0dc6e75ff74488f8614dae526f5c71c3fa824837.nq.gz
│   ├── 0f0217ea311becd1d1135dc27f5e86cd5e3d8e0e.nq.gz
│   ├── 127450f365252969fd503b0cf33f968b95828d82.nq.gz
│   ├── 1309c34ba0b3920561ae795c3ad841d50934e734.nq.gz
│   ├── 1488c8e3a58e537dc968fc8ffe0aa72c7b8aa3ff.nq.gz
│   ├── 18699c41736b4c52fd0416c031c06d260555b6fc.nq.gz
│   ├── 1bdf18737bb8d3bc8b71c413622fe75aed35ef2a.nq.gz
│   ├── 23902f55bbb8a8e65d1332f8fdb8d853265e8b50.nq.gz
│   ├── 24973c07b1d48843b6939c89a328f4332e718d77.nq.gz
│   ├── 2856fedbc5bfbcf95f225647eb047a8ffcb7a397.nq.gz
│   ├── 287a8013022bb135ee792cf7af0e8d07d43fa155.nq.gz
│   ├── 298d8fa7e2ad5822afb25391aa0862f719dfd649.nq.gz
│   ├── 2fbe29eb95e8a9e51956d1a269700c5c2ecaddcb.nq.gz
│   ├── 367ba001608a6b78ad4ed85510401e4620005beb.nq.gz
│   ├── 3db2807c4805d7731adc0c779ddcda785bfc93a4.nq.gz
│   ├── 3f00002a8991ae39d3feec42867a3de4e665cbcb.nq.gz
│   ├── 3f615d052931940963de7cc24181b64d569f9649.nq.gz
│   ├── 4a845a8db6cbdc4b7747b6d799172f8009eb2b73.nq.gz
│   ├── 4fde99089665f9be3fbe31b3d894f9c0533594f0.nq.gz
│   ├── 512ff6f37600b47ee7bc593178971285421f2277.nq.gz
│   ├── 52bd17fc68625ac0841e2fef163e1020f7097ebe.nq.gz
│   ├── 53d278fbf38882cc6092a8315ca6cf06ebda6f6b.nq.gz
│   ├── 6800120fc4e2012f174133a2e39dd8cf0535ce7c.nq.gz
│   ├── 6887c4edf822fc581ad1c90c2c8710077f9c55b0.nq.gz
│   ├── 6bd321a0bf4cf3de8af59e3722d0e124a6cde66f.nq.gz
│   ├── 6e19f7fa5b1cf16a96762b66ff6c0caf71b442d3.nq.gz
│   ├── 6eb81c255d63af378ced27922f7bc0cc33582dee.nq.gz
│   ├── 71d6b0274420b83760b6ea684e57922251381cd6.nq.gz
│   ├── 7216253987fb537c7e624eeac3d0bac08388cd44.nq.gz
│   ├── 72503bc876f78e1b2eea31fd28bb70cfef3797aa.nq.gz
│   ├── 7946e67975f0182050fab66f11ca65dcfb8974f0.nq.gz
│   ├── 7947086f5cd030a14845af235b11e7399b592f00.nq.gz
│   ├── 7a26a0327a19869cacdd676b22de8abb49fb2ac4.nq.gz
│   ├── 80a4a2f8f62a90607aebf50f06eef7d8c70e4ae2.nq.gz
│   ├── 812371ecd713ce7a412f4c77b12e518d9f59571f.nq.gz
│   ├── 81f31ecf1787d014600330302254a475af48158d.nq.gz
│   ├── 8673e4a6dea6790c9b1b07348a2478ca5ce0f04d.nq.gz
│   ├── 8deb855333fbba0200f82cd51a9e8bbfa871d339.nq.gz
│   ├── 944f844f100d96cfc493085569ee9b8d3f3bd2aa.nq.gz
│   ├── 9b2c1923cf504d497aab3c7b36d21c3b09dc314e.nq.gz
│   ├── 9c1058b86cbedbd5aa43c689eb18cb413f993ee6.nq.gz
│   ├── 9e090423622ca341664a0fe84267ffc76b601e98.nq.gz
│   ├── b1a90eb0434c6c825c7e18d4d3e73ca74c1915e2.nq.gz
│   ├── b55e49c4c9f78966380a68486f275aeb1b6e33a4.nq.gz
│   ├── b788be536f11515391649efa927599bd8b8f7c3f.nq.gz
│   ├── badda799ba7288b2a5e6393b597b19ddf320add3.nq.gz
│   ├── c010ee0f22890aa003faa220e46e50e078cfbc06.nq.gz
│   ├── c70936bbd717151218e1975ab2144b746acb9a6c.nq.gz
│   ├── cb21f25f0c9ccecfd9a86773a00df677de2edeca.nq.gz
│   ├── cba1b9c2183f57ae5fa57ccc9dcbb5f1e38a0c12.nq.gz
│   ├── cf67df9b5c0ae940d460deb6b9ac133c6e1eb1f4.nq.gz
│   ├── d3ae07bfd3f44d17f5469e56972d81d4ed124540.nq.gz
│   ├── da483e0f6af5c36a52a63efa795e95c12e969dcf.nq.gz
│   ├── dd4b3b990be622da33c681ce8fead24a452af9f8.nq.gz
│   ├── e4258d72b5ec4d0b9da87b44bf1deb4d5ccfc85e.nq.gz
│   ├── e5cadfb5beff35f0a250a0fd88f01223eabf3f48.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e77ce33832aaf7ce8a3eb2c954141c48a9524ed3.nq.gz
│   ├── ea1f4e921877da39740640e9598526f4c6b39d1c.nq.gz
│   ├── ea46ecc1a233e4be3adc4851d8467dea0cf37a03.nq.gz
│   ├── ec6d13e79de2ad6c00b3027aa7be2343133d7c2d.nq.gz
│   ├── f289ab002c36fcf9a8782c9fa0353397cfd9b34e.nq.gz
│   ├── faee6bc901eeba0f614dec7fdb60f174c352df7e.nq.gz
│   └── fc6d14d3c72907d908c2767b70dd91e70e81da23.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d4ee7590e2b507fd68124cd8a593778ce3c1158b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 74 files
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

## Source repository

[Marco-Sulla/python-frozendict](https://github.com/Marco-Sulla/python-frozendict)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
