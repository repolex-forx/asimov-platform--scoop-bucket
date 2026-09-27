# Repolex Knowledge Graph of asimov-platform/scoop-bucket

RDF knowledge graph data for [asimov-platform/scoop-bucket](https://github.com/asimov-platform/scoop-bucket), parsed by [repolex](https://repolex.ai).

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
rlex download asimov-platform/scoop-bucket
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2319584757b109d92d2199e8380d457517391374
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 2319584757b109d92d2199e8380d457517391374.nq.gz
│   └── repolex
│       └── 2319584757b109d92d2199e8380d457517391374
│           └── chunk-001.nq.gz
├── blob
│   ├── 0214fd84c4d037ee6137f55406516bc034f5de22.nq.gz
│   ├── 095d49d603dfccf4e33733881ccffc7d7b267ed0.nq.gz
│   ├── 09a7419068c93e7653982edb3304fe01f51d9956.nq.gz
│   ├── 0a1c7c4b4f398974a30147aee24a0522cb646d2b.nq.gz
│   ├── 0c8b859bb7b639500d30de93ab439f767f073564.nq.gz
│   ├── 130a9763ce7dbbee4823dc28fecc5fc74c82a7fd.nq.gz
│   ├── 24b9018906c6c8d83294fcda43cfd7eb44e10410.nq.gz
│   ├── 2766bbce5d9daa951e92ff28419542762f9411d3.nq.gz
│   ├── 2a2a0ffe42052f8f08de0b6a52c97bcb54534775.nq.gz
│   ├── 2f6a3f6b126bf40c74ad271e8449b327c8f2b9fa.nq.gz
│   ├── 39193d776a7fb6f4c3a1d9f231a0135041ff09e6.nq.gz
│   ├── 42a6ee189847ae84fdec41d2d21de1fa9ff7a7aa.nq.gz
│   ├── 439422db55b7d58c06ce0109f07df668127aaae8.nq.gz
│   ├── 4895d54667cdd8de073d7ebfe9fd666bbd93289b.nq.gz
│   ├── 48ef2243981d16af299294b570e0dbf174831cad.nq.gz
│   ├── 563c612a0c419cc08a3dca989f7e5fdcd77cecf0.nq.gz
│   ├── 57d97399a3fef0d3c359d9450a862bdf5b372235.nq.gz
│   ├── 5c64841c5f755c9abdd29f2144eede3c6d39c0ef.nq.gz
│   ├── 5e620e890b281386be0d607a8a7f290bc2a98dce.nq.gz
│   ├── 5f0c7b70cad1631b48abf35183e4bedd8c4f2da7.nq.gz
│   ├── 662a152476d7bf2cdacfc58f769fe6e9b3ed6a33.nq.gz
│   ├── 6a49c4699d54422030c289e2635858bebc64e500.nq.gz
│   ├── 6e7e0526482a4c3df4de3162ac725824fc161a4a.nq.gz
│   ├── 74e68b0adc2bafce285350858daa62dadd677c3f.nq.gz
│   ├── 76535ec565fe989311a827a779612e0b58432e03.nq.gz
│   ├── 78fb7a7a957bcd9d09776d2fd86c067579d791d8.nq.gz
│   ├── 7901b193cb42cd82b9a5da321f4385c0513e76c3.nq.gz
│   ├── 8102ff8da3000df879eec49c5303b983cbc1691c.nq.gz
│   ├── 82db67c2c930879126ed4f1f1e10ec0964c89177.nq.gz
│   ├── 84467aa9488f63787e8dc81b9786fd9251b668a2.nq.gz
│   ├── 91d84ccd97604b669594b4673e7b1f6681546b96.nq.gz
│   ├── 97ca0b25ed8d05d5979283ee89f2266472671f56.nq.gz
│   ├── 9b5539849b131e0a558f28bf940dc2f7b95f8cd7.nq.gz
│   ├── 9bce8b4c641aa872914f300aa9199b8efc6abdbc.nq.gz
│   ├── 9f313b0a4eeeab3ec23e8523b1551699dba3c715.nq.gz
│   ├── 9fac57db7d5bcea07462c5f9cdd976ec09d61482.nq.gz
│   ├── a82a2023cd13892341bd494907c2acbe0141024f.nq.gz
│   ├── a9056e417edf13d8c7c2dc45cd6d6a9ca869ae30.nq.gz
│   ├── ad2198c24891cff9dc61a9b02e9734b174c96098.nq.gz
│   ├── ad312d5fcdc6f90d6dd56d167a5bf51ff4c18dfb.nq.gz
│   ├── ae738359299145d457cba5150a55754ee0cf16d1.nq.gz
│   ├── b400eda3bc381af1fd56dfea3fcb138b0076f0a0.nq.gz
│   ├── b416786a20e0d9053ce266927359255066edcf5a.nq.gz
│   ├── bc483129df7ce5cdc60ea86755c63938a5bb707e.nq.gz
│   ├── bde86454b5901a92be768026cfc6af8c7971ee2e.nq.gz
│   ├── c221b4adcc42881dbb7dee36ee5edabc1eaca517.nq.gz
│   ├── c7aad86f8865df0e6997e88783a2551f4e234da5.nq.gz
│   ├── c86901ec81b30f30f56e79071b071b627dc1f669.nq.gz
│   ├── d03f20890693f17efa9c8af9286ceaacf3e6e791.nq.gz
│   ├── d1ec30ab21ccc90b487751dec95b3a838559e168.nq.gz
│   ├── d98d5cf53fe9c20134bf99d188472aa086f6d219.nq.gz
│   ├── dd36b0c1ccd865bfe09058d8fa18b5c569821c5f.nq.gz
│   ├── e10e31b8da888913858a8dd0ee7ff05387afba0b.nq.gz
│   ├── e37570470ca05a05a772019cc655fd1679656b66.nq.gz
│   ├── e5279eb5ef84a060a348600c9a414d6e32c29aa2.nq.gz
│   ├── e64434e1ab67f78622c53127bd9e3bc8f894dab5.nq.gz
│   ├── ef592cfdf876f437c51e1707a028a19dace281bf.nq.gz
│   ├── f7dd672bb596d3010e8da0c99eab327647a4ba46.nq.gz
│   ├── fdddb29aa445bf3d6a5d843d6dd77e10a9f99657.nq.gz
│   ├── fef01ced5fe0f2b52d081a4c7d0da82093fbcef5.nq.gz
│   └── ff5531db6917708f99aa5bb4f5daa1c4734479ac.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2319584757b109d92d2199e8380d457517391374.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 68 files
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

[asimov-platform/scoop-bucket](https://github.com/asimov-platform/scoop-bucket)

---
*Parsed on 2026-09-27 by [repolex](https://repolex.ai)*
