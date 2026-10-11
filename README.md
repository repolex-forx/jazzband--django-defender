# Repolex Knowledge Graph of jazzband/django-defender

RDF knowledge graph data for [jazzband/django-defender](https://github.com/jazzband/django-defender), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-defender
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── daa6235cafbecd4900df3509b00472bbe8c60f4b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── daa6235cafbecd4900df3509b00472bbe8c60f4b
│           └── chunk-001.nq.gz
├── blob
│   ├── 097d7a8c6c0a3428024d58d4767df4eed5350cac.nq.gz
│   ├── 0d1bba7d889c46c6df77653ba4861e2966a564c2.nq.gz
│   ├── 19798dfdc03072cc952cae958edfe2698e7cea51.nq.gz
│   ├── 1dd839824e741bc6dfa4f2b155173d9122dfe419.nq.gz
│   ├── 1fd65aaf673cd80fcae7e39b64095decff1b17ba.nq.gz
│   ├── 2bc656dd107ff48b69980c9f0938599fcd76fa85.nq.gz
│   ├── 2dbd15d10d26ebd3ba94a379284fd17c3125d909.nq.gz
│   ├── 321b98a48ae92ddfd14264181cecbd901955c71e.nq.gz
│   ├── 43011a09290ae9a32dee0e06bc2f089bc2967400.nq.gz
│   ├── 4e6a92c443efecb47ac790fb7170e4a27d8069fd.nq.gz
│   ├── 5110d75eb34cebfc87b83ad461255f5c5c4cf5c3.nq.gz
│   ├── 5a1698593b06fe406dbfe66a4d68a084ec6a5ee9.nq.gz
│   ├── 5f244b06d8895f4b74463cf316a36e131d0da3d5.nq.gz
│   ├── 600a9dfb61fbb994bef09e5a642eb89a42add649.nq.gz
│   ├── 604e87b008b60f0947b17e9bb9a3cdfd2ebfe938.nq.gz
│   ├── 6866099167ccae73926b2ec546ffa1b6ffc1e5c7.nq.gz
│   ├── 6c9135ca73e4757ecd3b38c6bdb7cfe3bcfce2f4.nq.gz
│   ├── 6d08b2c6a3bf8f7594de6ba34df7f2a99b45aff2.nq.gz
│   ├── 6d19b3cd1ea4d40788f9cce945c2ef8a848eb394.nq.gz
│   ├── 6fe2b76e3fc91ae8a6b140757424cc5137df9ed6.nq.gz
│   ├── 6ff1d7eec4aa4ad2a64eecd96370758e864ab75f.nq.gz
│   ├── 729958a136e08322ba12e3c869cace7720a988a0.nq.gz
│   ├── 75ef8fa97c150390324d84c2b1b2c77a03fea645.nq.gz
│   ├── 7a437674678280bc6ab8e34180931e7a7d4afcb1.nq.gz
│   ├── 7d31e652ca642cde97a0ed5fb27bb80da890c2eb.nq.gz
│   ├── 8238f789a2f4cba14c11abea0c85b1d773db9ae0.nq.gz
│   ├── 86cadee0f300490f078cc628277dc184507e016d.nq.gz
│   ├── 9156509cb89cab6226693813ed63b930a5afb372.nq.gz
│   ├── 9168ab15d9ec735f570c69a1f9b6edc9838f5b7a.nq.gz
│   ├── 92b574bf68179d718818a029f8eda62933475993.nq.gz
│   ├── 97bb79b9838a2709bb72c1362f53b927b2460ba6.nq.gz
│   ├── 97d465f07d7b5026a584d45cf1bf3abfbbb44e20.nq.gz
│   ├── b11b80e9f9dcd8d72f59653d9c45dc68da2306c7.nq.gz
│   ├── c401e7a29c0327fb2b9f2c234d7256f54dbaea05.nq.gz
│   ├── c450ec6ba1dc15d2d155acf46f25c8243144537c.nq.gz
│   ├── c4bff05f9afba1c28aca66314c5176f9f8d7a5c5.nq.gz
│   ├── c83d2fb4d40cb36a7ca241e2f72abfebae9e1cfe.nq.gz
│   ├── ce162f8191cb51820185dcd5966dfd20f4b36cae.nq.gz
│   ├── cf57a05bfb0429e61c08734442e9ec5dff3b974a.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── e06d2081865a766a8668acc12878f98b27fc9ea0.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ecf33e16fdba18277ec8ec97176c953ad99dbbe8.nq.gz
│   └── f0b76c0d12c764295ba4a12f1e070a4ce401e9ae.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── daa6235cafbecd4900df3509b00472bbe8c60f4b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 53 files
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

[jazzband/django-defender](https://github.com/jazzband/django-defender)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
