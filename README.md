# Repolex Knowledge Graph of frankie567/httpx-oauth

RDF knowledge graph data for [frankie567/httpx-oauth](https://github.com/frankie567/httpx-oauth), parsed by [repolex](https://repolex.ai).

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
rlex download frankie567/httpx-oauth
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8570ab5bff5cf10c802abbcc9cb4f80de2510b16
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8570ab5bff5cf10c802abbcc9cb4f80de2510b16
│           └── chunk-001.nq.gz
├── blob
│   ├── 02f07cc876dd85bc51ec89b950b96dbc6a28702a.nq.gz
│   ├── 04dbf17c6cf1ef4289457b4461a0e90bdbd2e52b.nq.gz
│   ├── 0c1e0ad02669b3c2a5f57b298054d6501c9b043b.nq.gz
│   ├── 19b009500b2252790d62cc97cb834f90a295b7a9.nq.gz
│   ├── 1eef42390111138d1affca1526e3a4250046aae5.nq.gz
│   ├── 24548fa3131044dd9b55be47f6adb77c135c1388.nq.gz
│   ├── 2493f54cd0709e6027e288d86063b4be1088644c.nq.gz
│   ├── 25891452a27702a96cc90abe06ef29f4399ea33b.nq.gz
│   ├── 29aa3db8588c73ec021483cba1dd9c5eff76fdd4.nq.gz
│   ├── 2fb984b16b0433a6526aad5afd241c2c8ba6f5ce.nq.gz
│   ├── 354c149a091c1c7b0e4b90bab12359a9ba55898b.nq.gz
│   ├── 4045a7e18466edf3811a5fe086b51784f7a3f6e2.nq.gz
│   ├── 4638ff322bfb0a862794cbed55fc746b25efabe9.nq.gz
│   ├── 485b1eeaf5bf79468efb778a4b636adb79cc782e.nq.gz
│   ├── 4e1a077d4ec24b0f12d5d394d6700dfd7101997c.nq.gz
│   ├── 4fcb2aff5d6ea8b074ad52e0deeec5b855c891c3.nq.gz
│   ├── 55a598cebd000dc9d84dee7e1d122fad1b6a67e6.nq.gz
│   ├── 58104488701c9d7ca4ed507bb19246f2901a8258.nq.gz
│   ├── 612c7a5e0d17657e51018285d9850b8fa8e76174.nq.gz
│   ├── 69aad0be4292f0fa017993b05b253bf4194bdfc3.nq.gz
│   ├── 6a2b8c52611d8b4a601008d4abbeacdfb80f93b3.nq.gz
│   ├── 6e5defdf1615b8fbc240fdea166b466e8f184c5b.nq.gz
│   ├── 73f24b0891a71fddea5745ab527b2ea8f372f231.nq.gz
│   ├── 85f0c0f2abd60c0b393dfcdfa2a6bc1db7d11085.nq.gz
│   ├── 85f47bee65d49e41dfe2e73f71d15bbb9fa3f4b8.nq.gz
│   ├── 8c5ccd7d057f76bd2cc392c4f89a3f460ec9cc9e.nq.gz
│   ├── 8c6994fb02c5d9cc4161b6b9b4d57ee18bf8f068.nq.gz
│   ├── 8d1ba9f258a4774a798f4a6a60cf774a0924639a.nq.gz
│   ├── 8d57cd60df926bb27596c6faa6c01ab5a57a9d09.nq.gz
│   ├── 9419cf8e1518c0cef5465858413eb60822bfceb3.nq.gz
│   ├── 9613f2d006f1d7005d25a101744452e82ce14c47.nq.gz
│   ├── 96417bcfecc26de19d58430cd6807bd064211e2e.nq.gz
│   ├── 96f4f8b2c33c5670b2b77ad98e8de92d94c2d948.nq.gz
│   ├── 9ce14b041a62c805fcf7c4ee0d65137a22192186.nq.gz
│   ├── 9dae659898aa43a7e0dc57e8cfaf038ec7cf5666.nq.gz
│   ├── a71fac2c387ec53d9f498299536dea7efd75d7f3.nq.gz
│   ├── abed5f28b570e7b249829d29dac941dd8a4bf19a.nq.gz
│   ├── acccfdf10c1ad1e61c160fdfdcbebac4dbffe439.nq.gz
│   ├── b17ffcf542e40a4fb57f576c72d313df94a6e42c.nq.gz
│   ├── b60b2d3389b66c74785514e08298dc265f368f5a.nq.gz
│   ├── b713651f08001e79dbd99918038c2964f6502d5f.nq.gz
│   ├── bcf79b8945beacabd091d9eed63efc9de5de31b5.nq.gz
│   ├── c1eefb611cb9d4bcff0b41799bd3015faf011ed9.nq.gz
│   ├── c2f0949d3f03adeba8ab50d00bd08041f423c6d5.nq.gz
│   ├── c7a358f3e6012b3f873af6e7724da7dc121e45ef.nq.gz
│   ├── c8cfe3959183f8e9a50f83f54cd723f2dc9c252d.nq.gz
│   ├── cb16f75fed4089917dd933a53427972289d71f8f.nq.gz
│   ├── cee8ae0429e0ecd179d46e81a35b61e2f3553933.nq.gz
│   ├── d0be2bf7a3f79b3955273aa5ee301849361ca371.nq.gz
│   ├── d78e10164394b740d16f47125c9f8dbf3ae87992.nq.gz
│   ├── d98e0522d2051fd655494a1b7d6319f56f535ee7.nq.gz
│   ├── da20704ac1d0af13798a6b7d1d2632eee4a42405.nq.gz
│   ├── db5a8c4d217560d2c9317296c7aa6b69649cca65.nq.gz
│   ├── ddabd924ed0765a03094fad6d3e2c1185d7f4959.nq.gz
│   ├── e16467533dd3d41da6d9275a8cc874e0a2a6f885.nq.gz
│   ├── e3b2b18e1ce53ebb3c056c3e75f383509f3e682e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8f25a0b2fd023cae7c275624dfb37ab218c58f6.nq.gz
│   ├── ef49b9ffef1d0184aa71266387fb4a742432f15a.nq.gz
│   ├── efa4507c8730ac213b5806642e50fb6eed09d39f.nq.gz
│   ├── efdda079aad9c1a91695f3ec735efdf90e98c34a.nq.gz
│   ├── f780d7dc3d5f83065c3eb8a9c0cba3b40df98155.nq.gz
│   ├── f85a0f56fdcad838252147e6a8c2e889358836a3.nq.gz
│   ├── f9d1a1961ff12b0548938a8a6ffb9029c9b2f980.nq.gz
│   └── fc50b4f25b822726936a52ab871449ab7afdd2e8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8570ab5bff5cf10c802abbcc9cb4f80de2510b16.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 73 files
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

[frankie567/httpx-oauth](https://github.com/frankie567/httpx-oauth)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
