# Repolex Knowledge Graph of UKPLab/acl2025-lfqa-hallucination

RDF knowledge graph data for [UKPLab/acl2025-lfqa-hallucination](https://github.com/UKPLab/acl2025-lfqa-hallucination), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/acl2025-lfqa-hallucination
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4fc6162d569a8df5418df04c08810f4205f1eb37
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4fc6162d569a8df5418df04c08810f4205f1eb37
│           └── chunk-001.nq.gz
├── blob
│   ├── 02f90bddec196c9d8784e3e696b527e6bf90f4e7.nq.gz
│   ├── 0688a355e8e5a58a9dfc95bc8441265b36c418fa.nq.gz
│   ├── 09dfa3f3e7c08a333f2136348e550d85e3e94125.nq.gz
│   ├── 0bb9cd715fa989bc9644e670c5b420935cf7c5d6.nq.gz
│   ├── 0d32704bd0bffc5e7f39d0761b3fdb7fbf18f067.nq.gz
│   ├── 130123fc5691c60025a0836c8fb3cd018e19abd0.nq.gz
│   ├── 1579278342e1dd0c82e92799103b3d52f7575a42.nq.gz
│   ├── 188da7eab7bb9b26a75c83d1d347b1590f5c76c2.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 22aa6757b156c86190d0584e93deafcc808bf7fd.nq.gz
│   ├── 234bb4a40e6da58df827d174ce97f7c1ff0eca0b.nq.gz
│   ├── 2778d6579a7f9b1fb68b9397c8ca082a5dc262c3.nq.gz
│   ├── 2ceecb99605c5de4b8978ccfa49fbcaa49250053.nq.gz
│   ├── 2ed99acaf7dcae948091e8397a9ee58f6a19f4e6.nq.gz
│   ├── 34602bdb3699e143a169374e0eb569c8d8ddf104.nq.gz
│   ├── 39430f15afc335b89e5a379e89eb3f78c915833a.nq.gz
│   ├── 3add55ae50d83bf8934dd283d5183ed04ce10537.nq.gz
│   ├── 3d43012668db2518b7ed238abdd8fa20885962c4.nq.gz
│   ├── 3dc429a6613bf85898a47643fe31d4439fe9d973.nq.gz
│   ├── 41f3ebc300bfe1c607febbe8a7e26723c46bda19.nq.gz
│   ├── 4971323efc4b3f387057a742ff4978d2b791507d.nq.gz
│   ├── 4d9700866241b3e769d6713b6fc65505e04a4840.nq.gz
│   ├── 4f9ecdd2f3e068f3fa88c91e974fd5a1f3d0f810.nq.gz
│   ├── 53d7a7ea6f12bfd06094c5a3af7802427fdb768c.nq.gz
│   ├── 5839b479dd677311efb17f110532115c4bc13dfb.nq.gz
│   ├── 59206d55aec202b69bad010483da5c931fcb094b.nq.gz
│   ├── 5bcff765d390111caf53cfa759d024b1777aed16.nq.gz
│   ├── 5fc7105b94a2282e5670883377ff2c70a0414c37.nq.gz
│   ├── 6182d7f30482cd178376b074399f74fc824672f7.nq.gz
│   ├── 6542b19247407277311cd2072d54d3159e958346.nq.gz
│   ├── 68eb69b23434984ce6053d307b6b6b7f709a7e7e.nq.gz
│   ├── 698e9f972a96948e15606d89ceda254e571d2692.nq.gz
│   ├── 7580c53d9738fac37bc21382a6789b6d9e90683b.nq.gz
│   ├── 79ef9451da1ce7572f8475cd916674254303277f.nq.gz
│   ├── 7b0a2e74afb296c03c6672bf00d6f6c30fe6c180.nq.gz
│   ├── 7f18a09a25fd86529bfd003a6be0eb5a0b629ee0.nq.gz
│   ├── 7f25008dce76949f6b658d7adf8ff6f414281e58.nq.gz
│   ├── 80f9dedb22582266a9daa4b5a74a2b7ef60f99a4.nq.gz
│   ├── 8a9f4d695b1a3114febf4fa491c8ed7f57edc8ab.nq.gz
│   ├── 8bfd38e8be073717b0f71467cdd5b608da9491f3.nq.gz
│   ├── 8f8f939ea64de93b74c1f22fbb9fe39b69df4a9e.nq.gz
│   ├── 901b66e6b804c66cf0c0020a7c0d1d4b7db8002b.nq.gz
│   ├── 943926ed7f24bbf3ff533f416cc64c6d69f5f122.nq.gz
│   ├── 97621a000221a4df8baf31275b7130aa879881a2.nq.gz
│   ├── 99af38ae399d825b63aca95b897cb6a6a916472e.nq.gz
│   ├── 9b3703a912d40f58fb0fb57d20742e53d9fe7671.nq.gz
│   ├── a0fc3ef70696598dba8d168b36b834a8ceb05a3c.nq.gz
│   ├── a17c9bee20fadc8439900b35bc1a6411a1a94424.nq.gz
│   ├── a3515bc848c5047c26be40ddb1f3e532fc260848.nq.gz
│   ├── ab44408db6be828fd4746007a6066e0a40a9213b.nq.gz
│   ├── ae0e8af117548d2578d618a45ba3758c180aa726.nq.gz
│   ├── b1ab78239380d587ff1be9bed7db5d99bf90fb0d.nq.gz
│   ├── b35d5c53fa9b93a86444eb0fd1d4843d1eb1b7af.nq.gz
│   ├── b628c71d787cf9166692609d0c92a2710915d2c3.nq.gz
│   ├── b897910f6033da4b08460b966e5039eeafb57f7f.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c38d64232623fe7a4f82b187227ffbc215aa9e87.nq.gz
│   ├── c407062aa739da2be9da64047dfcfd20b650daff.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── cbb98f6b2f1a7efcd62706f4e8c65fe8784f04d3.nq.gz
│   ├── cde72b1cadfb9e66264b1f8ea8265489466ae2ec.nq.gz
│   ├── ce66e133e329aca7ca5db8aa1ef8f757d80d0cdd.nq.gz
│   ├── d57bd0712595b4f602f29df5c04e4d8e66705bd0.nq.gz
│   ├── d5f783a24795d67dca2c47cce451dd81a1ea1eb3.nq.gz
│   ├── d61d90f1e51288cd481d273079e254eaf34c8a0b.nq.gz
│   ├── d62fc66df4b9acdd5381753fde4173a5775b1ddf.nq.gz
│   ├── de196601d0bd5a40b0f97f1997b8eb50c86b9508.nq.gz
│   ├── e254880c10c478defca1ca6b6f7ca30480442934.nq.gz
│   ├── e268fe764ca4c94106798aa119aaae9b29cad80d.nq.gz
│   ├── eb6b3d1c896296581ba844b485fb71608f4d828d.nq.gz
│   ├── ed3a9d377ba3c30e6eb8b2a35e08e8dc814a0725.nq.gz
│   ├── f0e2b76bae7171a72be7badb6a50dfe6322722d7.nq.gz
│   ├── f47c06cc18baa434989aa2d46756a0b678957242.nq.gz
│   ├── f6d199e4871f7e6e933e079a68e7d0006ee5572f.nq.gz
│   ├── f797f815276004f3ba85bdfdc3dfa2b48122054a.nq.gz
│   ├── fac9fb9d71fa8592f707a7cd5680f263580b62c0.nq.gz
│   └── ff1a8b87defddf71bef5c24471a37ba82d4b2f25.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4fc6162d569a8df5418df04c08810f4205f1eb37.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 83 files
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

[UKPLab/acl2025-lfqa-hallucination](https://github.com/UKPLab/acl2025-lfqa-hallucination)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
