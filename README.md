# Repolex Knowledge Graph of sympy/planet-sympy

RDF knowledge graph data for [sympy/planet-sympy](https://github.com/sympy/planet-sympy), parsed by [repolex](https://repolex.ai).

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
rlex download sympy/planet-sympy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a7c1a793870dbd1c5adcf817c2d167d8ee014b71
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a7c1a793870dbd1c5adcf817c2d167d8ee014b71
│           └── chunk-001.nq.gz
├── blob
│   ├── 038813f57ab96bcc87826372be53429095544ea8.nq.gz
│   ├── 046d634334ed20f7a8369e6720ab8b99a7049c51.nq.gz
│   ├── 06e942cbc7f3b3d67dd59120e28d5b5ecad9ad1f.nq.gz
│   ├── 08c16862ac1f948cd80818e0b4ada51d660c4506.nq.gz
│   ├── 0a39c48738f6f8432bc6d201cfd7ae2f6a3c80a0.nq.gz
│   ├── 0ae2be09ec4a80916f265f5a35c22897447a538f.nq.gz
│   ├── 15834df01c4192953a234d20fb7b4629baa998b7.nq.gz
│   ├── 168b805d7a079a771a8f0cb6ef1a1ad0462d99e7.nq.gz
│   ├── 1a5602f54227ea9ce4a47101a10cae9cbbca3920.nq.gz
│   ├── 1cfef21f1c44767885bc1d458cf26edd787ae32f.nq.gz
│   ├── 211f621c2b88c351e86539f40b91cb5074238830.nq.gz
│   ├── 247834b0d8e378e44038b10838fe11db3cfa4ef2.nq.gz
│   ├── 259a0dea829925d4817f79621cf492d2a4047056.nq.gz
│   ├── 287ae5fdc7884c823ff9a0076e621edc86563b2f.nq.gz
│   ├── 2d1fe4e02ddab1a7a1b3a62abe42a9133f622a2e.nq.gz
│   ├── 2d44efd6092be36f2318bebf97fcaa012dc9c956.nq.gz
│   ├── 2e7422c1b1686b3427fac1784c95b341fb9a4370.nq.gz
│   ├── 325db79ec6b41d16b30d2abd5a527ec517465c1e.nq.gz
│   ├── 366adf83d288d46e180dd397e9d1be40cc5f1603.nq.gz
│   ├── 37794605e00a110edac5b81439ff6862b7533a71.nq.gz
│   ├── 3ac7f63232519ac6136f686eb3601c46260810ff.nq.gz
│   ├── 458245cf20d01c8207f488047a98de3bdae0d414.nq.gz
│   ├── 48d54855d1f11206b1e463cc390b3d56bea05e2f.nq.gz
│   ├── 52a2d576e2ac48843e1c676d06c0fefac2c6b064.nq.gz
│   ├── 56708b1c252e661991c46f3ffe762a440b41e736.nq.gz
│   ├── 5a51979d6dbeba93c5ca23b98fab663c532c3bf3.nq.gz
│   ├── 61911fcbbe2cfacba4f363251a8d1cb214ac69fc.nq.gz
│   ├── 6c69a17e99d33a594243f8212bfe270c7190c6a3.nq.gz
│   ├── 733918bb3f802712beaf815831c0e58b9d9b52ef.nq.gz
│   ├── 73aa80dcaf9aa9b00813a45d9a4aa55082ccc5ed.nq.gz
│   ├── 825a4d2e4b80e29ea7573e1ff1db60d056fa7da8.nq.gz
│   ├── 82b356c0ca3f747f40e161242f46db97c5cb52f2.nq.gz
│   ├── 83dc649b21a5e6a7b7502fdac48458b2d9b88871.nq.gz
│   ├── 86994c23fc241de020414303cc127eb48cf4e38e.nq.gz
│   ├── 875cafb0ce312e6f3f7945f4d3af7a95606f5bda.nq.gz
│   ├── 8ef8ac7d3bef77aaab3ddeb1e540e43b4ed319d1.nq.gz
│   ├── 90b57647cfb1efc0ae2093b7437f907547aa3b97.nq.gz
│   ├── 950fce756916797d2b938d8fa22acae7bc933427.nq.gz
│   ├── 98c489d1112d05fa9966f8967b9b0a97af8bbdf6.nq.gz
│   ├── 9e67c691a4ce7b7eed5f80e1106dbb28c1ca5772.nq.gz
│   ├── 9e6af30fb1d35753f383c22bf470f4af0b5ebbdc.nq.gz
│   ├── a8b07a784077fb24a7f93344407c896132dee680.nq.gz
│   ├── aa5bee99b7f9822aec1b11e03131661499490983.nq.gz
│   ├── ad92033f187419863b46c269e50c054f0bfa1090.nq.gz
│   ├── b0283d0774d7fc1052650354fc91b10654848b8a.nq.gz
│   ├── b1e950bd67035ce15c0fd38c5d9fca8681a0033d.nq.gz
│   ├── b6d1f0aba337d3a06dafeea22546374b7c82209a.nq.gz
│   ├── b827f7a3f08bd658b15cd6f9fdbfab7af9d56bf0.nq.gz
│   ├── b98f8307fda66c03d57d156bbe52e942316ec186.nq.gz
│   ├── ba8ca6f7fd96674c7b856fae2c472c7a168e1d0e.nq.gz
│   ├── bc29902c954e1aae5a76842c6e3d97c633c21dcb.nq.gz
│   ├── bc99ab38f52bb69cdc8566dd95b40f1f55d4007b.nq.gz
│   ├── c24d649dd08a41fafbdd214531cf3d3c43252ea9.nq.gz
│   ├── c31552e3d6981bbef176fc2ea4f09b2d527af2eb.nq.gz
│   ├── c811912fe82017aa8e3989556454ced14b5b143f.nq.gz
│   ├── d0ca08e7c1e863ab116a47fbeae4461a750273e3.nq.gz
│   ├── d11d5ab2183c1f40180818bffb3e449fb44d1830.nq.gz
│   ├── d34bf5bcb443c6dd58da56d68dbc0f4a1b0d2376.nq.gz
│   ├── dc302a626c25fd951bf822899146966c23b0adde.nq.gz
│   ├── ddce1aa669b2714371e12677b57fdf2a42c00ab6.nq.gz
│   ├── df36ac3f8a92a47a781992f5cbe9ba0b364378fb.nq.gz
│   ├── e0f21f20070f4c82d4e79638788b4a356efb69ff.nq.gz
│   ├── e2967f88156193e5652fe8694a6fd4aeed3144fd.nq.gz
│   ├── e81c25aef10896c5ee01c9a6fdc43e8e1406adde.nq.gz
│   ├── e9156389612e3395b4d02908b00d632eef7d8d70.nq.gz
│   ├── e98a946d90b3af7a3a48786bd527dd03ed139d84.nq.gz
│   ├── ebc2118e3aa4ce1f24b427758443cebd5f2468ea.nq.gz
│   ├── ec47618c86e771a2aa3443ed032e9d4055378f80.nq.gz
│   ├── edec4e61f13bb890ceea5fbc86f78a7ec64eec61.nq.gz
│   ├── ee2af9d1a1a18a9f3ecf5f839dec7aeafac03df6.nq.gz
│   ├── efd37cba272bd26f4c173ed3f4d34bd8623d3056.nq.gz
│   ├── f28f87ea5c30f74f6a09b062673dc4d78cc8b473.nq.gz
│   ├── f31b534e476c47a89e786359a101d22bfbf090fb.nq.gz
│   └── faa40bbec2f7ae47b4274b0495c5607d82555c34.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a7c1a793870dbd1c5adcf817c2d167d8ee014b71.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 82 files
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

[sympy/planet-sympy](https://github.com/sympy/planet-sympy)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
