# Repolex Knowledge Graph of canonical/bundle-kubeflow

RDF knowledge graph data for [canonical/bundle-kubeflow](https://github.com/canonical/bundle-kubeflow), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/bundle-kubeflow
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8107887543e75d9346c702091cd56719128af422
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8107887543e75d9346c702091cd56719128af422
│           └── chunk-001.nq.gz
├── blob
│   ├── 0177988ce77a6198fe0b9df7a7367b8dd1527db3.nq.gz
│   ├── 01e4e206a4f074d723fcfa3cbd882d93f461257f.nq.gz
│   ├── 024f8314357019cf7535fe7f285216badea3ccf9.nq.gz
│   ├── 03ddec5adda1f19ef6e6e4e12ad5aa8a8226a615.nq.gz
│   ├── 047177600d8e16e861ad362bb0e60c47820af407.nq.gz
│   ├── 05437133968ecb8ffaaeda1858b6c2f8deb5aaed.nq.gz
│   ├── 08d4e9831368c1c78de6bcd71df745f9d8ee629e.nq.gz
│   ├── 096d23b233dde781444d6ee90789b3bbc8de3cb1.nq.gz
│   ├── 09d3c53f7400cd9ec329724b3727e0f5e39bbea1.nq.gz
│   ├── 0f14238a45cea754e77224e614c30fe2a0c1bdb3.nq.gz
│   ├── 118b0bc06940340b1e25b4ac3bc0c23fa4fdf552.nq.gz
│   ├── 12383abb93bf0b8f1d716e9e8a535362bbe60161.nq.gz
│   ├── 13588ecd7eddc540f3a14ddf66f150474cea7656.nq.gz
│   ├── 13d50177f6ea023c29f3a6d582e4ea2bb83b3966.nq.gz
│   ├── 14bdf107a05a5e7c5a3d55a6ab4358485eb2bb17.nq.gz
│   ├── 15f90a406c2a9c4952f467de783c8bdb2513063b.nq.gz
│   ├── 1667fbce336089c27372e737b48b79142df962b3.nq.gz
│   ├── 1717d17ffeed23947bf81baec4947a855ed50917.nq.gz
│   ├── 198ba20a7b698c82c359810a1db99dd61cd82db1.nq.gz
│   ├── 19ec9589830ecb181560ced4b36e5aa658bf4fc7.nq.gz
│   ├── 1e66120bb36750b821b46614a91eff61c517299f.nq.gz
│   ├── 20fe0fbb35ba56a3d2cdc5a3a6726447c06e6118.nq.gz
│   ├── 2222dabe99cc7780204dc1ea823fc86871023ae0.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 266add61a113a2b6f9b60129940ac6b855a652c0.nq.gz
│   ├── 28689e8c6ea111d2a2c7840aaa73096e4bf95c87.nq.gz
│   ├── 2a7670a4618d0a3bc63afabaf31f4063b7241b50.nq.gz
│   ├── 32fac7f1e853612286e2dd9898186924e2283d43.nq.gz
│   ├── 352ddeb0d7df5a1345ece3375c368246391aa3fa.nq.gz
│   ├── 383bfe2d39aff6a01af5e65bada88a1f3fa019b4.nq.gz
│   ├── 390161a5de3fefd797b943017bccb87d0e0fc730.nq.gz
│   ├── 3ac5b035d0449b05f287b058e37f60ac032c5a04.nq.gz
│   ├── 3b287de9842a95ac00d71029ca101233f2590f49.nq.gz
│   ├── 3b673a96c032dd748498ea8731f04b0e5ddd8028.nq.gz
│   ├── 3c959b67709aeadd0971cede02081a16687496cc.nq.gz
│   ├── 3d876ba833522a0a7452bfe5cb28a77f126b3699.nq.gz
│   ├── 3ed0b59b654ba78da9755f6531e182da18f49c89.nq.gz
│   ├── 40ebe96d200b36818d17bc1258db783638071fcf.nq.gz
│   ├── 49f70c7232544df149b2781b84857f7046b5fc2e.nq.gz
│   ├── 521d96dfdf790d1b3d060b0886be898228665638.nq.gz
│   ├── 52240a438bfeed35728ce90653449cce3920e905.nq.gz
│   ├── 52a154bcdde81a934b773bc92c283d8e457c017b.nq.gz
│   ├── 56c1a69d9ae451f74bb8722d03d7f45f32cd5846.nq.gz
│   ├── 56d23e0abab2dde533d17e8a33b8836a5ea0b4b5.nq.gz
│   ├── 57f2bd3804c254725c197a6ef3c192970dd40cc5.nq.gz
│   ├── 58b9ffeef73afae053d50f3d6d4f29e7543bdf0a.nq.gz
│   ├── 595cf71bf70edb42e1f2a1847aa8c9fd47733a7f.nq.gz
│   ├── 5af097f4e557d78cd9de8863afc52e9e0ced8fd7.nq.gz
│   ├── 5afe218da4b94fd6ad4a44fceb7d45c8c9716b16.nq.gz
│   ├── 5d72013b81175ae7b601e06344fec5c157d62421.nq.gz
│   ├── 5e2c917b9d45fa9d961f4205e44d3f12e1257f40.nq.gz
│   ├── 61e90e1355f8217a435761db23d2b74e12ccb715.nq.gz
│   ├── 631db5b1996bd3ca5e4c0951d27280ce1157fd83.nq.gz
│   ├── 649753020debebfbb37f7c6b824ae69ff42ff70e.nq.gz
│   ├── 6806de2295763112b1243edb295a140c1551cf1c.nq.gz
│   ├── 69d7f52db7273ccef28eff7ffc652b5af0d26432.nq.gz
│   ├── 6a944ee0c120bffcca13a359b82816c17faa6d14.nq.gz
│   ├── 6c0e2137a92c26b321ddff08ad992289f95b7c7d.nq.gz
│   ├── 6c46935346416c1464fa1c7258c360547d504a7b.nq.gz
│   ├── 6d7509bda3571dc58445571facbec4ec4b5b2887.nq.gz
│   ├── 6fc30a10f6d9bf48cfa4abd7aa71da279f1603a1.nq.gz
│   ├── 70342db866a1d772aea8e677aeec88463befb4cb.nq.gz
│   ├── 71210c08358608f91def74922782b0e0a555c432.nq.gz
│   ├── 723733e8dea02e9b9b8fcec3063635558b53a375.nq.gz
│   ├── 751a4b381538e225509d9c0b3085d7ad2dc12ae3.nq.gz
│   ├── 7a69c4cdff4d928b1efef7b462cd49f72b5ccc94.nq.gz
│   ├── 7b902b5634240b02ff4ca1c3708a07a0469c269e.nq.gz
│   ├── 7bcf059562ac112fe533e78f847b5ccadd7beceb.nq.gz
│   ├── 7e6db2b332957951e144309f2b83b32ee25bbfc3.nq.gz
│   ├── 834e539f5be437fc625b77701e6c574c7c5f21dc.nq.gz
│   ├── 836022a001bd3d77c09672583bb335c960f9133f.nq.gz
│   ├── 83cd771a515bdfa3a589b1da8089f0c0d295f066.nq.gz
│   ├── 86f2779f7768d55f6f0e9e11338570bf5548f9a9.nq.gz
│   ├── 8bb7af53e56944653b91f9fd6cee7b81d57bd925.nq.gz
│   ├── 8dc354c385f7eb6084d86acb0a6ceb52798aa213.nq.gz
│   ├── 8fe79fa604aee787e65d9d552f64f77a0cf1f25b.nq.gz
│   ├── 913ed46e40927cdc356f7b5ccf0e0e9e219a8ac6.nq.gz
│   ├── 91bfa793903818c56197325b8ee4227871b6d6ec.nq.gz
│   ├── 979421947d318b96ac5aa4e3e82bc317831d52d5.nq.gz
│   ├── 9aa326dc209b40966229af47431aef67018d0b12.nq.gz
│   ├── 9ab8a150e709e07a79b7323a4389ac3582ea6998.nq.gz
│   ├── a14e0869c3e7785555f50a2f73e71aa0427553c3.nq.gz
│   ├── a21b80593f80918b9fa56a31059b9abf80cb7270.nq.gz
│   ├── a31fc0d5e77efac6ad7ba67835ad679f775ff008.nq.gz
│   ├── a4baa7fbdcaf395a00dedbf8db3ff6f10794f779.nq.gz
│   ├── a4cf252d97d1e224e85bcaf2bde9317fbc464069.nq.gz
│   ├── aa4b328c0ba7ef279d3b6340644bdc068cce003c.nq.gz
│   ├── ab2cd2dfa444898b68e9fd777f7960dea877b4e5.nq.gz
│   ├── ad2b9029fc27b34227e9ab870f9aadc1631ba494.nq.gz
│   ├── adcd8d2e0769c52f404624b6af7767d1e5fad173.nq.gz
│   ├── af33326858ac54a24dad6b4a4852f7bdd1dfa532.nq.gz
│   ├── b0115c112195dc4657cbb731e82fed6db4de8dc9.nq.gz
│   ├── b7a5c791bca066879dbd2374f2448dc0ce401412.nq.gz
│   ├── bb2eef6cde175d8945d2c26b94b524cad15e2390.nq.gz
│   ├── be8e549c11d571731ed0c1c0f765ee7b98187df9.nq.gz
│   ├── bed2d5d0d8acb7ab945ff944695d5fdc1254f4e7.nq.gz
│   ├── bfd66d1f885dbad3b3e9056d8ba73bad2c7f5845.nq.gz
│   ├── c0ea5ef1921594f7bb977ffbd8bf712d2e857237.nq.gz
│   ├── c2aa5652728c6e2a9a36c69fc29fafba881b31b4.nq.gz
│   ├── c65a06a7f92fae19f36856b80240f6bf43179e4b.nq.gz
│   ├── d24df32f268be8a256a2bbcfb3fb69981620aea0.nq.gz
│   ├── d2ca6b615012cf0d9feb2e0f8a2aa54eac24d51a.nq.gz
│   ├── d30a05c05608fc4b7b7e01bc182407ec32e84b3e.nq.gz
│   ├── d332667a33b3d7c19d321c1d6981aac0fb37c099.nq.gz
│   ├── d36c7a81307dbed9d5c4ad18e95c0f0b7c4efa80.nq.gz
│   ├── d50b0f77d9db84451e2b841f5a58b8bea497afe3.nq.gz
│   ├── d7a57a879cd4f01f4b971499acd6f973091b3f46.nq.gz
│   ├── da4c9af74b2c5d243e0b6b33eeae1a43db2430db.nq.gz
│   ├── de7a7baf46b2ef2efd1aeb1b0e74f1457faf2416.nq.gz
│   ├── de82730fba89ba3ac4f8201f290434fb55a7e75a.nq.gz
│   ├── e0caad3bac2694ad0e9c4e617ed43b551170314e.nq.gz
│   ├── e30826c4e7cc849a28b8aebb68275e1f7a3885f3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8e4a9d991bb225c4fdeecc5042692611464b313.nq.gz
│   ├── ecbe4f82d758d28e7951a374fc9d21ba36db59ab.nq.gz
│   ├── f0911907c94198aee5ed3da0e49e76ad33d00d1a.nq.gz
│   ├── f42dc985f267b1d5f30a120e54b6a296353681ef.nq.gz
│   ├── f4e01e3988fd0af3b9c06810c6297c5f65f45de0.nq.gz
│   ├── fdc4f6ee27ebc228f3bbfd86d7a961e142c3ffa0.nq.gz
│   ├── fe27a038f1cd10f8eec0bc01ec15321a6d1051e0.nq.gz
│   ├── fea00bdf0877873dc140e86ac04b2b25b37345b7.nq.gz
│   ├── feafd50aa8461e9bd43878d60e72a5a97b20fdb1.nq.gz
│   └── ffd8b11e72c121234c2462253eb5a8af9e5b3570.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8107887543e75d9346c702091cd56719128af422.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 131 files
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

[canonical/bundle-kubeflow](https://github.com/canonical/bundle-kubeflow)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
