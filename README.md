# Repolex Knowledge Graph of softwaremill/elasticmq

RDF knowledge graph data for [softwaremill/elasticmq](https://github.com/softwaremill/elasticmq), parsed by [repolex](https://repolex.ai).

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
rlex download softwaremill/elasticmq
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 73a1c655e36ea1256a77f43cd1ea648014c51dd3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 73a1c655e36ea1256a77f43cd1ea648014c51dd3
│           └── chunk-001.nq.gz
└── blob
    ├── 004145cddf3f9db91b57b9cb596683c8eb420862.nq.gz
    ├── 0051d014ce8954c3cf3174d8552420cd8e265b11.nq.gz
    ├── 028ab070c7eb95033aaf6e0f628db2533ea46f26.nq.gz
    ├── 031760d9f3ade07008933203b05db51838ba57a3.nq.gz
    ├── 03610bfd6c611191b455ff0d05d4f94433c9f991.nq.gz
    ├── 03f21ac5981350d21e438dcf2948312da6f33857.nq.gz
    ├── 0460f1946e0930db31043cbd669511fcc2ca1cdb.nq.gz
    ├── 05c4477f1208981fbea928108013f8d2ba07e101.nq.gz
    ├── 05e726d1b4201bc8c7716d2b058279676582e8c0.nq.gz
    ├── 073373ea62be2ba03209c7ac6ba2bf9f259d92bc.nq.gz
    ├── 07d3346e4ca43a24f9c0f016c8fe667dc9c51b5c.nq.gz
    ├── 081e4838b8621be9eaf03172ef68cc277b24e8fb.nq.gz
    ├── 08df20f0b308129f51e26c0a889e7d8c28c9db85.nq.gz
    ├── 09dcd9b6fe8a427fe353b35a4aa6c39988bb4e71.nq.gz
    ├── 0ac5f7955e89ddf8a9d02a81cef593e3f3a89fa3.nq.gz
    ├── 0af86aa1b50e8781dffaedf5bc61be7f1f429bf2.nq.gz
    ├── 0e339f89119d1ab30ae67e7f94e19ea9a074abbf.nq.gz
    ├── 119579df4d8c88ff9101c36f12f55f17e2b48ee6.nq.gz
    ├── 11d858b34bcac8866caed51737f113a46ab388b2.nq.gz
    ├── 12f74ce001fa80b07594d4fc922651555d301090.nq.gz
    ├── 151774578b9034a208d6c8fcbbcbf92416e4dea9.nq.gz
    ├── 1806cdc90033b6bdba32654039b19fa286d176f4.nq.gz
    ├── 186885e47ee3308436ab8bb9e1d859703d39af45.nq.gz
    ├── 194b67ee01f1710bb12c821f57a4dca384610694.nq.gz
    ├── 1ac3bfc0b8d13ba517d45b6ee1fb611052f13101.nq.gz
    ├── 1e76892d5877f5fdc3154a388fac1d7ead08aa37.nq.gz
    ├── 1f238c3bc2ae1d2e67f01ee73fcb70fabf1c70b4.nq.gz
    ├── 1f652ce558247ba1b712d3d3602e312eaa154f9d.nq.gz
    ├── 2185175e13d5d15b3047eac57ef38e75c03b92e8.nq.gz
    ├── 225e49520462b8b4b15841fc6752d5c72ff4ed4a.nq.gz
    ├── 22a25d3728eec17082a02c2d598b51e76c779619.nq.gz
    ├── 232e9d41bd0c7048cef90599e213f7c00f097340.nq.gz
    ├── 2392e683c3eb438773665351c553370538ebaa9c.nq.gz
    ├── 2488d8768f9f947da43279e43c31c20706270a0b.nq.gz
    ├── 2575c29f69b4e644047068f916fc8619c50bd1de.nq.gz
    ├── 278f86d29b275d76ae35a03525643ad9c0607150.nq.gz
    ├── 2939e7400b28da19b049e16b2d6654642b16c846.nq.gz
    ├── 29855f8bd939b3f431402fd6bac51d7434062a35.nq.gz
    ├── 2acb5795e4c4ebad9036aac3587391f43f82c742.nq.gz
    ├── 2b24200e1c7cde1f03f5f485f48c712093403c81.nq.gz
    ├── 2b46021d04c9c91cf2252afbcc58272f507a2e64.nq.gz
    ├── 2b8610ff3043cce463a239852ce7c652ad4705b3.nq.gz
    ├── 30d8057fe372d764a66ed02d83c5858495fd5892.nq.gz
    ├── 310c97d6cd480c96f52c680d28601840556f4fc0.nq.gz
    ├── 3124cfb9088134a42796d501341c3b50f32da35a.nq.gz
    ├── 32327b4597094950a8b42536b12bfdc899b44d1c.nq.gz
    ├── 3263075c65b5e0d688adefdacb86b7f9c0a3ae1f.nq.gz
    ├── 3639bc5285a70ab851c514e4c7a6f03b8e92549c.nq.gz
    ├── 37c8191b7791d89de5e1051974d1e27c7c9ef728.nq.gz
    ├── 384b37dadef7ca76cc412c2d7b595d1ab2d79f41.nq.gz
    ├── 386e57d6ac33b2c19a98cdc7c60956aa03f18217.nq.gz
    ├── 39553adef9de77e8a74eb885d123fc47da9235de.nq.gz
    ├── 3a957a6fbec218da8181b7760eead8837142740c.nq.gz
    ├── 3aa0614c311fdac79ba89eea370529d3d60fc2db.nq.gz
    ├── 3b25b63a0262b42a7fd8929f337653293dae4139.nq.gz
    ├── 3cecc383aa01fda1076eed24950ce3a84a764a87.nq.gz
    ├── 3d301f8c3883e03161e95df9318977ebc2451f07.nq.gz
    ├── 3dad6734840feb09411bd162395c42f06a5ffdd5.nq.gz
    ├── 3e24ddf94059b2763a0c3ae3334d9f74fdbf2669.nq.gz
    ├── 3ed835cb573ce2f2df0036da6edeb5650df2d82e.nq.gz
    ├── 3f574c6e6b3f02e5e2a88366d3f723869268625c.nq.gz
    ├── 4039dea05b3d6a7aedfe5f9c78ead47afeaf7fe6.nq.gz
    ├── 41b35181f5307758cd4405761882cab8955065dd.nq.gz
    ├── 434d15d3bd5347c41624d12f7b4faf534665c58e.nq.gz
    ├── 442d6926726943a68e7aaf9490712f02cda3ef76.nq.gz
    ├── 445e02da05bdccb2e6ca17c1d3860d217078019f.nq.gz
    ├── 45244e961b52ed4e7346cd53d5c58ac32ec5fd05.nq.gz
    ├── 474ba047dc21970d3bdd842b7c468adff3963916.nq.gz
    ├── 4874d49c73b5e9b8a064343c1463dc439186412a.nq.gz
    ├── 48b75157099925c76f6e3662662c157c8851ea75.nq.gz
    ├── 495b73118e5f7b863fb0220901f3295529d56232.nq.gz
    ├── 4e8622d25b0e53def4f946b9c9456eaf5332d723.nq.gz
    ├── 5066752b414c3c358c5c14eebc80400bfdd754a8.nq.gz
    ├── 5174b28c565c285e3e312ec5178be64fbeca8398.nq.gz
    ├── 528e77c52ef434f88bad60ebec6ead2ebb1a4936.nq.gz
    ├── 54500e00c3b07549e26d11f226bf29fbd3439c90.nq.gz
    ├── 54cd98c68d0f6d0940427ba93bfa13c398e0b5e6.nq.gz
    ├── 55dc2691d2d88eb5b685518dacb3d4eee618f7d7.nq.gz
    ├── 5623b637ae39eb11a6f4747140beeceb9281fbce.nq.gz
    ├── 5661e00ab91285326a630987a3f83706d8b65cfb.nq.gz
    ├── 567f17b0d7c7fb662c16d4357dd74830caf2dccb.nq.gz
    ├── 56b316165bd2f535a7ef5e5c736cbfc1b8fd8e87.nq.gz
    ├── 572ca86cfb881b1f89164818810b11646414439f.nq.gz
    ├── 576e3a1cb60ead4847f351c03ab0260929022bf9.nq.gz
    ├── 5b1245e77e905248ecb2cc277422020ca53dc5a5.nq.gz
    ├── 5b213853f8e1b2eee033cd54259ee3c860dd0a63.nq.gz
    ├── 5c4fbde325f699d28e2fcc3adce8ae1d58a30e46.nq.gz
    ├── 5d2551f20953453b4a6f11b99bcba0b5ec4c5a7e.nq.gz
    ├── 5e41c33e7af323502ce7079b2d3006896fd8fb8c.nq.gz
    ├── 5f5fe1303f0c37a61b5bbb5b5accff1b36a0cf25.nq.gz
    ├── 5fab6f655376b2f8e79126e937be7e217966475a.nq.gz
    ├── 601cca78e350efe6d3914adb7cd9a2bfe567e7a1.nq.gz
    ├── 61a7c82101413e5d78d518df5425ffedb4f02825.nq.gz
    ├── 61a93ea6e1b7e2664eb1bea675282ec28cea15de.nq.gz
    ├── 61be8e3c6c7b2ae6bcf2573608bd13c82370aa33.nq.gz
    ├── 61e36849cf7cfa9f1f71b4a3964a4953e3e243d3.nq.gz
    ├── 6324d401a069f4020efcf0ff07442724b52f47c2.nq.gz
    ├── 63a9b2c18ae3abb3e1e9da30a7d4f64733e20b0d.nq.gz
    ├── 647a215c9afcd5f731f744229e55cbdbe1391862.nq.gz
    ├── 64ca9a81ea5a1b42ee521cfc83d6b8bc1b8bd8f6.nq.gz
    ├── 64f17efca109ecab0ebffd27a2043eee516ee4b5.nq.gz
    ├── 67d35109bf54c3cf357b6d7b3af5c796bfb303d4.nq.gz
    ├── 69f0bc315e75095c96eba9593b160ebd42565913.nq.gz
    ├── 6b640155016ed3b3c11ca0b41bd845c97850f0fc.nq.gz
    ├── 6bb50ccc8fd663dcb30e30f345529de7dbcc8814.nq.gz
    ├── 6bd7027a4563178c78db6fc333a9858df30c23da.nq.gz
    ├── 6ce67d45d494bdc9a2c439464d473631689a53e5.nq.gz
    ├── 6d13b9e978025582a8b5dac84849842d10e78887.nq.gz
    ├── 6d51a6e76fa54a5fa9501f6a9d0ff49136698fb9.nq.gz
    ├── 6f4247a6255c99f420d1df558d68745592862ff7.nq.gz
    ├── 6f9d64ec571c0524688762a4489436e06ffae93f.nq.gz
    ├── 6fa4fa052ba8d74f000c39baa5268c5175c72c6a.nq.gz
    ├── 6fdc98ca4b3a0bfa0b39298c632a2883b111df1f.nq.gz
    ├── 70ae99ccab52c4331558622053db717f3d96df12.nq.gz
    ├── 712e95c30c4be20b918b3eda075e06144bda92c7.nq.gz
    ├── 718d6fea4835ec2d246af9800eddb7ffb276240c.nq.gz
    ├── 71d04ad739465066910bec9106cb3d5d146f4566.nq.gz
    ├── 762bd9e0688e527d900ebba52bd566c07308e068.nq.gz
    ├── 76b4481cf0176ab5a16a037c8c7987b0f23c3f5c.nq.gz
    ├── 76f63e894476124c92b9d6936d4c9c73685466a1.nq.gz
    ├── 77053960334e2e34dc584dea8019925c3b4ccca9.nq.gz
    ├── 780149520e86df1a024f3a5fd2f6b87216dff8fb.nq.gz
    ├── 78acc2bbb4ed75570bbb40c8dec91353297a4be2.nq.gz
    ├── 78b28d58aa4e491c61ab37e9bf1743c7f1979652.nq.gz
    ├── 78cb5912a093120c0e34726bd16bbc57ace1d361.nq.gz
    ├── 7a181fe2c2063ea700c225ba94bff9a7bf83bcd1.nq.gz
    ├── 7a4a3ea2424c09fbe48d455aed1eaa94d9124835.nq.gz
    ├── 7a71664f7d3f8eba54435c4a0a8dc4ec218a06da.nq.gz
    ├── 7b0828bfa80fb3c4504510349e22dc4cf5bc0a7b.nq.gz
    ├── 7b76393efc3b47aefcdba7afe3b5753bd0e2f8e8.nq.gz
    ├── 7b7ee140961c73e1d71fa220ed32c9795de85686.nq.gz
    ├── 7b9a7c5fe4fb5722d68729c15e5f6ef7cfb99e57.nq.gz
    ├── 7d7542d19bec9b0c3260ca4dd7dab418cbe89ca0.nq.gz
    ├── 7dc19a53dda770975944b9c5d7b6999b4b1cd76c.nq.gz
    ├── 802b38ad3ad380fce0c1fd6214c249bfe6de1690.nq.gz
    ├── 816194631ca8843a9691e0fe53643a0defb06ac3.nq.gz
    ├── 830125c979fd7698e94d50c2e38606a38c802a37.nq.gz
    ├── 84377e05d60dd916cbc546519a3d576cd54b9a7c.nq.gz
    ├── 851b337221f4b688a0162fac1336a1557d0022e4.nq.gz
    ├── 85d3fa92340ba8472cbbe32481871159ec4e6cd9.nq.gz
    ├── 860dcab93497e56c38539ae93599a5274a6431aa.nq.gz
    ├── 871c7185ba5b0f285b2e840f2e31231b8b30f253.nq.gz
    ├── 87dbb030e4e249d7349c90f0b52e166539fbebc7.nq.gz
    ├── 8a06a78f48a3edc1142071b56f957dbb69db1ded.nq.gz
    ├── 8a26833e67ebea51892720213fccb9492d10bf7b.nq.gz
    ├── 8b980d2e97fe0544b086862e0bab40dbe8906cef.nq.gz
    ├── 8ed2e866e20d821f8fcba5c4a31926d90e3e03c9.nq.gz
    ├── 8f319354ce43158a1247c697fe91fec4be375eb5.nq.gz
    ├── 916336535198e0da18e7f2a2a33082eb602748dd.nq.gz
    ├── 92649595fd5fc331f5656e552fdc7007a61acef6.nq.gz
    ├── 93c5bcb6120b8cb7d428825a2c410c5b336e0cac.nq.gz
    ├── 9464dbf1a8e109b7f4d8d6013538b7359095766f.nq.gz
    ├── 95f4bab83f5485adffb408cd2a86cd687115a1d4.nq.gz
    ├── 9657cea481e8b9375f509158e290b4221e4ec701.nq.gz
    ├── 97148f0ea6c70431365c0b5f5a8d5dc73dad4354.nq.gz
    ├── 97ef5e9ad4a478e93d314dd88bda059fdfc0d134.nq.gz
    ├── 98117e1a6b49ad9a4a63e24535cdc5e0422d10d0.nq.gz
    ├── 985a27dfed88bee82de3c3fbf8c9cf66ad723aee.nq.gz
    ├── 99187c23b6521a4ba0cc9c33f11d41675be81065.nq.gz
    ├── 99f14d99e5aca610034cf59e36d5cb9dbdef9345.nq.gz
    ├── 9b35a8d2a72904dccf0e5d1a5948092153614306.nq.gz
    ├── 9bac64e8a9b40959aef7336cd1bdcda1fc881a68.nq.gz
    ├── 9cc240c27fc895dec2a8abc115f44f3ff091d4d2.nq.gz
    ├── 9db6a73e916cb475dd229f9710071ae21ae682f5.nq.gz
    ├── 9e61e25f03e7e5415987aaa613f2eadd45600048.nq.gz
    ├── 9ee015ad7572098bf92bc28db6d9d9d5e212f90c.nq.gz
    ├── 9f9651676a750b55be000fa977f22ba538995f04.nq.gz
    ├── a0033bac1f4e4138c11e8015490718bcc3d47558.nq.gz
    ├── a24307c70385ffd0a746db317b49625f13c4c747.nq.gz
    ├── a3b823c8aa9a9f84b4ed0245c152cf8bc88995b6.nq.gz
    ├── a414baf19cf9a3291019030b3a8ec73976f8962c.nq.gz
    ├── a4ad6d474037a30fe39f68d2658fc9c8feffae73.nq.gz
    ├── a4e95f686bea5526c3652d104cbef635c233c2f3.nq.gz
    ├── a4ecca4e5459107e80311d71e67e51d854288913.nq.gz
    ├── a5af6054ed8ee430ca735d2517c87206168b94be.nq.gz
    ├── a676769c85383869d2ff8f561f43121e24e8ac40.nq.gz
    ├── a679f205d63bd72ed59376c74dcd7e2777b60378.nq.gz
    ├── a759e6f7d194e3e536eb05817e7f1c0adaba839e.nq.gz
    ├── a881fc8ca366ec2e792615ce51c25b4f974e3633.nq.gz
    ├── a89c873d93746e05ea456fb80373c920f217b0ec.nq.gz
    ├── a8aa8d17c0716980f66605cf7ac7b9473af28873.nq.gz
    ├── a8f9358d56ad471711ca6e057afa912dfcf3a459.nq.gz
    ├── a9d54d7198c1246d3fa04492ff54c45fe8cda4de.nq.gz
    ├── aa59dfd35976fb5be38f1988642679fc0e8ad56f.nq.gz
    ├── aab1fb86c19425666f76e96d9419ef331138427c.nq.gz
    ├── ab05ebff917cb4546b77195853da35a38b5ca4bb.nq.gz
    ├── ab45c5517589046aed2f4fdc04ea77782a6fdf9b.nq.gz
    ├── ab9d7ccfbc23b8c93288e7bdd18940b11a8fdcfc.nq.gz
    ├── ad4a8d4cdde8d39aabd481634caa0484bd466e03.nq.gz
    ├── ae759eea3b539c33048a5496c7ebdc1b3878f5ff.nq.gz
    ├── ae938a6a0d8110071c5a6cb7d5701a882e77dbf7.nq.gz
    ├── aea5406e22f385b6d7954fa81d4f4673c24ea684.nq.gz
    ├── aee8d1331fa35a88d785e815b404291b32f4a950.nq.gz
    ├── b14db0705ab86a731583d36ddb1ea6d27d0ade95.nq.gz
    ├── b177e83f8a52439d413928fe64512e53ac960a47.nq.gz
    ├── b194de60bc45e7ff2ca2b1adc1f504c6c38f9f14.nq.gz
    ├── b22cc5bd6b749ec8bbb75a35febbfd51470b7010.nq.gz
    └── b23de97979d0f78c8025a3fe49f801d597a7eef4.nq.gz

7 directories, 200 files
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

[softwaremill/elasticmq](https://github.com/softwaremill/elasticmq)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
