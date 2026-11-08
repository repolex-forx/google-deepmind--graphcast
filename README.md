# Repolex Knowledge Graph of google-deepmind/graphcast

RDF knowledge graph data for [google-deepmind/graphcast](https://github.com/google-deepmind/graphcast), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/graphcast
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f2f2c5117d2f864e2d5e7c2f9f220db5e1049dd3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f2f2c5117d2f864e2d5e7c2f9f220db5e1049dd3
│           └── chunk-001.nq.gz
├── blob
│   ├── 00aa032837106fc5043c11f8d4553a23ea4f6a16.nq.gz
│   ├── 00c2249940cb4deec2a1d229a6b4e15b31a5cf04.nq.gz
│   ├── 05fe62b3c58922cb7058d3cfd75534cd8f1996fe.nq.gz
│   ├── 06b2738eaaa9be19a539b1838f8ce2929d7a6c13.nq.gz
│   ├── 07ee26892df2ed82a4cb4fe1fc2216c5195ce3b1.nq.gz
│   ├── 07f00d170b702ae0467aa802595ebf4666f5ee6e.nq.gz
│   ├── 0b0546b656bba484b937b0935ccc451ef486bedf.nq.gz
│   ├── 0cd8a6c1689c056513fb9553470d5ed5fd7c53b1.nq.gz
│   ├── 0df1708676f0053bdcdc3263ecfca2fdfebfcf40.nq.gz
│   ├── 12dd9813998bea1703c590a037e396a9609e8680.nq.gz
│   ├── 21bfc3e48b5b3518affa9ceb46484191d2bfb9ae.nq.gz
│   ├── 225d4fde69dbe6c7320ba2af408ae9d86fef0706.nq.gz
│   ├── 239fc84995fab4f2c7b4af45df8fa72b52bdc78a.nq.gz
│   ├── 24663cbd84063e404ecee5dd52f4c7017515b761.nq.gz
│   ├── 24f4da1fadcd54455df4075644a455145d1d27b1.nq.gz
│   ├── 275b57eb07daa36f4176f1a17841120c1625ca71.nq.gz
│   ├── 28931c8cac2062b8e3799f9a3adfac6fda361b7d.nq.gz
│   ├── 2a3a012a56636f44541b3b2d160857c793a5a030.nq.gz
│   ├── 2d27ba268ad626994866e0712553ad7e3811dc22.nq.gz
│   ├── 36a299fb8fae0693443d8eedde318d241d18697d.nq.gz
│   ├── 3c430c642178eb2101b92f184cfe2e74091430f7.nq.gz
│   ├── 3df1a57909bc851e205f6868c66b5db67c9135ce.nq.gz
│   ├── 4106dd7f58d0f496cccc42c96de6a99ed9d4d820.nq.gz
│   ├── 412368e73f74b6160cf05f752f963f0820024fb0.nq.gz
│   ├── 45b13dd4df2ec1a04295ad46f9447a6ef99387b3.nq.gz
│   ├── 474705a28ff609320e095089b13adc9ce156b469.nq.gz
│   ├── 47629aa0dfaadd2cac85f6a4899b13808b5d809e.nq.gz
│   ├── 4a959b04a53c9611d8b536c22f811882b1b2ff54.nq.gz
│   ├── 4da9a89188ef1115673e882194e25b6bf2742adc.nq.gz
│   ├── 50a3a7b87c8edce399bfc76a3c5db7dddfe91c1a.nq.gz
│   ├── 50d57c38886754be7cbb284c91b26b26935c8094.nq.gz
│   ├── 56a8151b3bbb8f5308aeeea696af909f5ba69945.nq.gz
│   ├── 56c0eed043d21afdac232c98c020359bfb7259aa.nq.gz
│   ├── 59ff3f07c2f2648516d5e2658d81b89d8ddef2c7.nq.gz
│   ├── 5a23c74b8d9a611ba9ed6d7bf737b3c32d238526.nq.gz
│   ├── 5bcd2719ccff895052f8594b40863d2c5f6c9459.nq.gz
│   ├── 5d5ffef7f8b83426af9d0eedf6e80eef9e011ba2.nq.gz
│   ├── 60aed583ac0987c529ef610198f1a1ad60a3112e.nq.gz
│   ├── 6757b693d32113ffd13f09c3137d74e748c0ea8c.nq.gz
│   ├── 69ae1a4403dfae275a497c5bc09d3d201af43037.nq.gz
│   ├── 6ca1108117420067ed8d9cded29489429e82a346.nq.gz
│   ├── 6cc7b068bd63c362a4771b045f95c53930807194.nq.gz
│   ├── 7061baf899321619990b00d56f259baa360a7daf.nq.gz
│   ├── 71f01a722e45c320ab9318706dd1d044b05ce14e.nq.gz
│   ├── 772597ee92bea148092e3ad5d3a6096d995e1a4f.nq.gz
│   ├── 775c4174e85c3ba66081d7714f443e7c5abf873c.nq.gz
│   ├── 77cd8b1d9347c63b413cca3a18db1c4c02ed22d3.nq.gz
│   ├── 78079096c57789f845b105e99da096ed415471cc.nq.gz
│   ├── 83ed51845aa00875715659d1da5135dff7d2ddb1.nq.gz
│   ├── 89cb50ed8bed71d19bd24a1556d4cf47b0c75e04.nq.gz
│   ├── 8e3b92f297941be35a8b08e5aae8e28260416a9c.nq.gz
│   ├── 92125ebc7c44e21fa76ec4314661525a1c18a2d7.nq.gz
│   ├── 954c20fd47a60d9395248d3f734e0c967b268525.nq.gz
│   ├── 96ca4aa31ab37c335296ab79c8eb4b2f742e8e33.nq.gz
│   ├── 982cc108bd139849b399521bf0de2aa289620ee4.nq.gz
│   ├── 99ca505101cb697e3914b416489297090a41538a.nq.gz
│   ├── a11b497362ca27597b2d386e2c506654798c7880.nq.gz
│   ├── a128b4abc6524037a33eee860e2884ec57b7030f.nq.gz
│   ├── a28f419f19ca80afc45e4791138db6e22846125c.nq.gz
│   ├── a471964d58f7570cc9b4f253eac121d15b049809.nq.gz
│   ├── a570e4b3ac3c1d7caecd289075139f235ffd32d9.nq.gz
│   ├── a619e03dd9b3da72e3a9f31f78f1c08d3a94aa71.nq.gz
│   ├── b30b39bd576f206f20e4aa1fb826be3e614053c1.nq.gz
│   ├── b49afaf268b10e3876ef70b29c191481b0e7c24d.nq.gz
│   ├── b7d6f471095525b4a37d723b0342b208edc83579.nq.gz
│   ├── bd11420ec4f561f0cd5aaac409ccb870303630d5.nq.gz
│   ├── c0de73bf7c45d114a11137b35fcff7bc32f948e4.nq.gz
│   ├── c10f308745123c855a69b5f5458aa3e58f836e1a.nq.gz
│   ├── c16e4b882df2b17bbdfd268beedda8bc7a704399.nq.gz
│   ├── c749886022cf890ab98d0fb64edfda2a4519880e.nq.gz
│   ├── ca4c0c0c24da3a84a8ae62f49ca7a13caa1cfe68.nq.gz
│   ├── cc825c4098eabc62e2c541b7045f33aab3be6a78.nq.gz
│   ├── cd941932e39607155db7a098b3877c7de7acf4e5.nq.gz
│   ├── d3a8763f39842f4b6c0063895481ac5673d28ce9.nq.gz
│   ├── d479e1d21d2d2f77d0343b331fd81f2cd81658eb.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d87443700815d13c475d4574c68f308ced3a46e2.nq.gz
│   ├── d9173acb409a56186988f90fa74def4d1caf19a1.nq.gz
│   ├── db64e62bea5481125760ae738208f303a336c781.nq.gz
│   ├── df3f6ad0a27b56ca1fe54c239bce79585b77d37e.nq.gz
│   ├── df923b61bc4ed28901cee926e8add7bf8c30f24b.nq.gz
│   ├── e85d9451a8b06aef26eecd751141c6737e1ae2f9.nq.gz
│   ├── e9821ff0a1aa1d0262c3fc5523438018e9d9fa82.nq.gz
│   ├── f3122ce18d96f9788b7e01078a9c7f326555731e.nq.gz
│   ├── f75902b8474e1c95dfec451fa914577ca0afe549.nq.gz
│   ├── f7c94ca7ae20a5d80c48496e308358e5ae5d65bb.nq.gz
│   ├── f875c5adb69dfeeb4de2ffe1b96af1233d3b1495.nq.gz
│   └── fdfd4f5c179c59c9722bd33df272e6b23489cdd0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f2f2c5117d2f864e2d5e7c2f9f220db5e1049dd3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 96 files
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

[google-deepmind/graphcast](https://github.com/google-deepmind/graphcast)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
