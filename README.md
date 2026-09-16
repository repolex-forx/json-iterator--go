# Repolex Knowledge Graph of json-iterator/go

RDF knowledge graph data for [json-iterator/go](https://github.com/json-iterator/go), parsed by [repolex](https://repolex.ai).

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
lexq download json-iterator/go
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 024077e996b048517130b21ea6bf12aa23055d3d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 024077e996b048517130b21ea6bf12aa23055d3d.nq.gz
│   └── repolex
│       └── 024077e996b048517130b21ea6bf12aa23055d3d
│           └── chunk-001.nq.gz
├── blob
│   ├── 00807bae7b89e98c0d71b497057072b7612ee7c0.nq.gz
│   ├── 02a1895a0a1d73a6cdb29daf281674d4e50d028d.nq.gz
│   ├── 03dd3459714c29edd004e7efd3b29612f9314def.nq.gz
│   ├── 0449e9aa428aeba21696ecd1511880db12ee4445.nq.gz
│   ├── 045671f28b24ec7740007d6cc7a39858011ef3cb.nq.gz
│   ├── 0cf32522a0ec50fa3ac954442f492f226bddea0a.nq.gz
│   ├── 129737d5c987fca2f52240cbbf69a1f6d0661e70.nq.gz
│   ├── 12e42a13ac1c59ca5026532572ace5ff80c7511b.nq.gz
│   ├── 13a0b7b0878cb7e6f379bb548e526a0efdce3713.nq.gz
│   ├── 13bc97ead9aaa7b656b3b4552781a92eb764f2f7.nq.gz
│   ├── 1516b77b5586b3f76d96ec057a0bcec33e8940cf.nq.gz
│   ├── 152e3ef5a93c6e375ed1c3ea34e66e821ef5b9ac.nq.gz
│   ├── 15556530a85421a47fc1fa355773e29768a715a5.nq.gz
│   ├── 175a24e535316ee423758145d5da56d99a311b38.nq.gz
│   ├── 181e12fcec63579ccf3d127d96759490edec4e2d.nq.gz
│   ├── 1b56f399150d9c3012babf663da40b1e2ac3e939.nq.gz
│   ├── 1d859eac3274a44b956e5d559cb1ed2dd8843ae1.nq.gz
│   ├── 1f12f6612de98255335e5dccf6200355ef27363f.nq.gz
│   ├── 204fe0e0922aa0582eada026b3ee4af5f7cf25f7.nq.gz
│   ├── 2179e7cea82141411902d9c23ec13fbf68dd1da2.nq.gz
│   ├── 23d8a3ad6b1269c4396e45430a67521493915e2e.nq.gz
│   ├── 29b31cf78950654b3478784fda9d024212db75ff.nq.gz
│   ├── 2adcdc3b790e53e4192655b15680a596a52449dd.nq.gz
│   ├── 2afbffdfea7ed14c5bacb580d5f9ea8898adab4f.nq.gz
│   ├── 2cf4f5ab28e9c50b4553caadfc0d978edd0d4adb.nq.gz
│   ├── 3095662b0610038098235c19a7a5b13dd12dd4be.nq.gz
│   ├── 30d6c4d7f1348699f7478f73daf5810779746b17.nq.gz
│   ├── 313a0f887b6f412639bdfed98411843830275d8d.nq.gz
│   ├── 3295e6f4c275d31da22e2c5e0935c6a5dc6ad056.nq.gz
│   ├── 34edd4af8870847732e7f923d690b2641744ad53.nq.gz
│   ├── 35fdb09497fa86e5fbc84ad288cbfe8f012c9521.nq.gz
│   ├── 3731cbe1553c743d262fb90aa5adcab4f43bd850.nq.gz
│   ├── 39acb320ace720d5051e5178e655bafc0710b173.nq.gz
│   ├── 3c00b26949b092a6c69115dc93ad77d2c6a971d4.nq.gz
│   ├── 3c159b58d2ec32f920e410d89adedeb55081ca57.nq.gz
│   ├── 3e21f3756717ac3e2a8c271bcc27888a95cac2fb.nq.gz
│   ├── 40d8ca931799171e86c889d71cf0d50cc70b01f9.nq.gz
│   ├── 43c51d591267b62078cb0c6b7144f8533e15e74b.nq.gz
│   ├── 449e67cd01acba105df358ccac3c32f0693f3f1a.nq.gz
│   ├── 465eaec911656bf6ab7422bd1b16bd649ac9bed1.nq.gz
│   ├── 480985ffa2b2606725a6c61a045f115f5a7b9851.nq.gz
│   ├── 4b7bb8a29520a61263a60b064c64101dcbecca0f.nq.gz
│   ├── 4fd2a2c13e5c12c7d34c83b1c1466ce5f9bf1429.nq.gz
│   ├── 52546b11d75c5fcb14e7d4a19e6ef8eca38ef40f.nq.gz
│   ├── 5459495c93ed536e84525152daa6d02d94276d0f.nq.gz
│   ├── 54c2ba0b3a2d9716669b2bc4f99c4f0a95da2233.nq.gz
│   ├── 567f290ba54949a298c3fdbcb1b19b5b12d1156d.nq.gz
│   ├── 58296713013531babbf1c8bbf2e646ac489e1d39.nq.gz
│   ├── 58ee89c849e7bbff01577ce657502f34b8125c85.nq.gz
│   ├── 5af292da6dc4b981ca57e56561d52cff3e763216.nq.gz
│   ├── 5e70598a198b94455d085d1e7196348f745430cb.nq.gz
│   ├── 5f34f9d88108f4ba41ef0e3880d1bcb6ce1da2f4.nq.gz
│   ├── 614f7bcd54e044f92afdfa53056cb0a728709f24.nq.gz
│   ├── 635a24eee5a3751eb1c678acd2778c04346f00d7.nq.gz
│   ├── 656bbd33d7ee9d7dcd153603a21c66851bc19511.nq.gz
│   ├── 69315adfb3e37845daa6b9e6d2ac5e2adaa11113.nq.gz
│   ├── 69c6d549f6cab96f27e4812a1153ebcb6b1e869e.nq.gz
│   ├── 6cf66d0438dbe20df79f41293919436a304f2f5c.nq.gz
│   ├── 6ea75b57aca41a7224b7500576985e48dfe47616.nq.gz
│   ├── 74a97bfe5abfb228c2dec33be40f1292b9605338.nq.gz
│   ├── 75ce27afd5e423ac40b960d4e6720ffd2dc56c16.nq.gz
│   ├── 785899a9e787b3d7cc0040b295bc2e60a3837b4b.nq.gz
│   ├── 7b9202cf08fc9194971ac6c9616f189963c2790b.nq.gz
│   ├── 7c4be391e81a0487fce11e1d15e278dd39db4cc7.nq.gz
│   ├── 7df2fce33ba971b51129ce73359ca3c3038cfdee.nq.gz
│   ├── 826aa594ac6f34a832fd3a4b8e4dea654278dc3b.nq.gz
│   ├── 8353d19b40fe82e540ba3bb48495555d956672dd.nq.gz
│   ├── 836db5bc0aacef18f90593e5ca9b9c440e3912dc.nq.gz
│   ├── 8392e828d2f473c6f9f373ddd58c7e019c0328ac.nq.gz
│   ├── 86af5efea650f1190f3c02ddf86d672e5f46c37f.nq.gz
│   ├── 8974eb7f76264cff0ba13a9c0670d48e3f884c00.nq.gz
│   ├── 8a3d8b6fb43c25b814f25d221ce4e78381925289.nq.gz
│   ├── 8b6bc8b4332869236aa7b7374ee6b6803f5645d6.nq.gz
│   ├── 90d3a03a973531e7adcd4385120ad284d12800dd.nq.gz
│   ├── 916b57d0478eaf3a3325e1e3f45fcc0e19a0791f.nq.gz
│   ├── 926931a80d291369f393107e557243f9ffb02333.nq.gz
│   ├── 92ae912dc2482051af984a674696c3aca7668acd.nq.gz
│   ├── 92d2cc4a3dd5ce61d6d90d7b1c3c8cb155366c55.nq.gz
│   ├── 9303de41e40050de20fd5256bad35932e038b930.nq.gz
│   ├── 9441d79df33b45495d1628e71d13da7d35b9da24.nq.gz
│   ├── 9452324af5b17483f48e7b453c44266c3078032b.nq.gz
│   ├── 955dc0be5fa67651f73927238c3ba011186af65f.nq.gz
│   ├── 95cfdd568cd5bcd1dd1ce955dc20093743fe05b2.nq.gz
│   ├── 9893872a035b270f3b892ff064196305f44c4c1b.nq.gz
│   ├── 98ab4b5a4487f7503223ae56ebd58b19228875d2.nq.gz
│   ├── 98d45c1ec25500f9d7f7c944286e26bbc5d321ae.nq.gz
│   ├── 9a3165ed5588aa539ea237d3c7e1e24fd5e169f0.nq.gz
│   ├── 9d1e901a66ad36f15646eebbdfde5f80fae5a6b8.nq.gz
│   ├── 9d22ea92b4816f3d32e0079d99d1040cc2f97efd.nq.gz
│   ├── 9d418b3733f98522b70fe5ece6deb9bff46bdbcc.nq.gz
│   ├── a28bd8d38f59b981d185d698a93829f7b168b6b3.nq.gz
│   ├── a7018e89dd108929a143921af9cdd5710b771fe8.nq.gz
│   ├── a86625e9afafba5dec82b088f37ca04c3b67845f.nq.gz
│   ├── adc487ea80483cbc892f0438c3133705cbcb46cd.nq.gz
│   ├── ae4b80f2103c3e9f9ea1a16eadd8e553bc227fc7.nq.gz
│   ├── b0daf1e009ac319521f58a9d29bbb8aba4da4ac6.nq.gz
│   ├── b27220f184080d2bcb2eb2796b2f9d37e4b93cb1.nq.gz
│   ├── b45ef688313ec5063cd21ac84ee5ed87d3849c38.nq.gz
│   ├── b50e72fff1d66c9edbf470a21ba18204bf8c8825.nq.gz
│   ├── b73de698df45cd9d929f1d99a614421848df6805.nq.gz
│   ├── bc90f24f52c42679ca6b1b32725b0a75f7796cb3.nq.gz
│   ├── bcb491fe68cc5a0c39d0c3e038768aa1afb02ccf.nq.gz
│   ├── bd24db47fc878463f3a0b79a2320a2b57ec53f39.nq.gz
│   ├── c08b7985c9777428e1abb51ec278f46355654a05.nq.gz
│   ├── c1cb1afb051b201bd1ccfd24e3f5956ee87e9120.nq.gz
│   ├── c2934f916eb3031985b3e4c9ccc238cb5ec182fa.nq.gz
│   ├── c440d72b6d3ae1438fc92cd29e501ffac250e4e5.nq.gz
│   ├── c44ef5c989a46a629432c809faed5f77c0b676b8.nq.gz
│   ├── c589addf98c2813197e93ee3e3beb8b5db0e96b5.nq.gz
│   ├── c5a3d4260e466571f7d838c8ae128a35ae8ce0e4.nq.gz
│   ├── c5f2e6fea7968bf074a3c25f19ce13d15e8fc0df.nq.gz
│   ├── c871191f4023af8928c1691239b728fe0613c491.nq.gz
│   ├── c8a9fbb3871b0e32024cf102cfd6d5d175c3cda5.nq.gz
│   ├── cbebe5cd830128fb222d43dffd13627ca5f628ea.nq.gz
│   ├── cde43322763d643ac49f5fcbbeace048d972bb9e.nq.gz
│   ├── d04cb54c11c1e57eb1d9cd820b00f402c9ed5c3c.nq.gz
│   ├── d1059ee4c20e3739a39eb09c448c7b60a02f4d63.nq.gz
│   ├── d37777165bf66ba377be7324eb7686fb1716c617.nq.gz
│   ├── d3bc40dac58dbd5a9a1a3f365b15769121c3e8eb.nq.gz
│   ├── d75d01a51a802f33e0629b2164c336990389e08a.nq.gz
│   ├── d786a89fe1a3ddc36d7289ccccbe7a8d8d22295a.nq.gz
│   ├── db27d4ac86b667f53ca8e25c551e742f277d1c4e.nq.gz
│   ├── dcab2a4288947de355bf1ab32bdc88a2bf82652c.nq.gz
│   ├── e235dd6007010b881eeefe26d27b628b563a71e9.nq.gz
│   ├── e2389b56cfff3ce31c878ef99a4a55471d2dc53b.nq.gz
│   ├── e325ef3424b757105b7ca08ccbef24ee19e4efd8.nq.gz
│   ├── e38da7f1109bd0d488fa0ea75e869a9afd0c7dce.nq.gz
│   ├── e541ec8da164eca5e4272df68c84caad3e50ca05.nq.gz
│   ├── e6bb8aee6ab397087152de2234e4db5b60047803.nq.gz
│   ├── e817cccbf6fdbaeaa29123294b93ce35d9110abd.nq.gz
│   ├── e91eefb15becf2fdd007fd3c992814d8c4e2cfa0.nq.gz
│   ├── ea413a1e99025e13529810ef7167196b37e394f1.nq.gz
│   ├── eba434f2f16a39ce12253ed08857549d60941142.nq.gz
│   ├── ef60420daa6f1ac74e736a4912480e91b79bfca9.nq.gz
│   ├── f4e7c0b2c945a7552f9133ddf210301f5d39d55b.nq.gz
│   ├── f6b8aeab0a12dd61faf85156fd8dea10c96a8c9c.nq.gz
│   ├── f88722d14d198fe477bd69ae05bd405625be974d.nq.gz
│   ├── fa71f47489121bdb7f593f7aa3696d546dd64832.nq.gz
│   └── fb2e60fa6379dd8d40663ab50d1ce2edeb06e8ff.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 024077e996b048517130b21ea6bf12aa23055d3d.nq.gz
├── filetree
│   └── 024077e996b048517130b21ea6bf12aa23055d3d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 149 files
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

[json-iterator/go](https://github.com/json-iterator/go)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
