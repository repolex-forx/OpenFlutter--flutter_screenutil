# Repolex Knowledge Graph of OpenFlutter/flutter_screenutil

RDF knowledge graph data for [OpenFlutter/flutter_screenutil](https://github.com/OpenFlutter/flutter_screenutil), parsed by [repolex](https://repolex.ai).

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
rlex download OpenFlutter/flutter_screenutil
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 65a9f0c031f8ecc11d2f5d6649f5030c676c1be8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 65a9f0c031f8ecc11d2f5d6649f5030c676c1be8
│           └── chunk-001.nq.gz
├── blob
│   ├── 000d3624638e1d3d74f9ef78edbba23db8f94846.nq.gz
│   ├── 015cecac7d5ef6a5e66c57af745c043b815ea56d.nq.gz
│   ├── 06f08a0a82e375745cb1bd944c57c670262223c3.nq.gz
│   ├── 090d48fdd6d9100d4232c75ed39ea4a2c4099394.nq.gz
│   ├── 09d4391482be68e9e4a07fab769b5de337d16eb1.nq.gz
│   ├── 0ba8f43096dba945ae0b376661f767590352a7dc.nq.gz
│   ├── 0db4a835d873610fb66d0c3e3455f6aaa30df776.nq.gz
│   ├── 12150f8310ac996de89e51253b2632753132a931.nq.gz
│   ├── 1552f05f27981235d9441c45d1a92c29c075c650.nq.gz
│   ├── 1634cfb91cdcf281be711a9d008637b137cbfb26.nq.gz
│   ├── 17987b79bb8a35cc66c3c1fd44f5a5526c1b78be.nq.gz
│   ├── 17ba431125b4b5e7df0c768da15f4aded702e6b9.nq.gz
│   ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
│   ├── 1c19f4b86e14805d1ac6fbc3603929b7a65ab1bf.nq.gz
│   ├── 1f83a33fd4f2c45c5ffa5b6c1b729c431fd445fc.nq.gz
│   ├── 21a3cc14c74e969ab1548274a8512ebfecc40f78.nq.gz
│   ├── 2717536b548342116d0d4edc505fb17d6e259674.nq.gz
│   ├── 28c6bf03016f6c994b70f38d1b7346e5831b531f.nq.gz
│   ├── 29758b70d57005d2e4ac221641e89adc187af521.nq.gz
│   ├── 2c4c500025b66ea97758c5a319e154b34bce4640.nq.gz
│   ├── 2ccbfd967d9697cd4b83225558af2911e9571c9b.nq.gz
│   ├── 2d6636ab6bc67ddf913700be930462671dd5aeaa.nq.gz
│   ├── 2e1de87a7eb61e17463f7406106f6c413533cecf.nq.gz
│   ├── 308a2a560b42f17aaf3c36e4e9c8cd07182fbb7e.nq.gz
│   ├── 30c99b94f4f67cdc6ccd5fa1316a04e9707fe977.nq.gz
│   ├── 3233525b24ffc7d2395052ba137efd7dc55f905d.nq.gz
│   ├── 33a924cc583b33727fbcebf58d8d7bcdd2d80ba9.nq.gz
│   ├── 33fd5801e7134249aa03257b3190f0e700055870.nq.gz
│   ├── 350eadea50a8ff59874d0a411a08c6f4fb40ddb4.nq.gz
│   ├── 36e21bbf9cf407bfa7968f28d35675da72c6c6c0.nq.gz
│   ├── 3718ec2d0c1c6ed7e9557c2e7227e2b787f3b7a7.nq.gz
│   ├── 3879d54755798567f0f318d63340508d5668eb96.nq.gz
│   ├── 3d43d11e66f4de3da27ed045ca4fe38ad8b48094.nq.gz
│   ├── 41e81b8a329ba65a8ea13218f774063960cd563d.nq.gz
│   ├── 449a9f930826851b495d039f0c0d57f247536615.nq.gz
│   ├── 458b635539fa0e8bda9fb554934db1e39da52b32.nq.gz
│   ├── 459ad37075175659abd11a6e53e7185776d1bfa0.nq.gz
│   ├── 4972fd047e313e9bb7145112f450da69a019ab23.nq.gz
│   ├── 4a3c589b5d61241d296eeabed1e56c1b9a40ba2a.nq.gz
│   ├── 4b5dab7f2918f05a4c082cf377f8e9d6394a7e3b.nq.gz
│   ├── 4cde12118dda48d71e01fcb589a74d069c5d7cb5.nq.gz
│   ├── 4d3d1276824463eb614713858344429211c7d576.nq.gz
│   ├── 4d6372eebdb28e45604e46eeda8dd24651419bc0.nq.gz
│   ├── 4e686a79ab083c59dbe699980786a1973d2c1de2.nq.gz
│   ├── 595fb867a920d0fc4763db9885635c1488e18ca8.nq.gz
│   ├── 59a72e90be12e0aef464a1c3173b632db6237fd8.nq.gz
│   ├── 5ae702ecf2d5244f9e121fe91ed0038d71d97da5.nq.gz
│   ├── 5bbf3ed879302f938bc5d225ba53fcd4f8db394f.nq.gz
│   ├── 5dbd65c7d3a60f68494a89a0ca167147d5a3c878.nq.gz
│   ├── 6226fa6e5f6a37e39e36e718ded81bae6b178d6f.nq.gz
│   ├── 65018bec3c17f88217dd2161e4c029dfccea5fb9.nq.gz
│   ├── 66a65d1e4a79f230031ec0e0959a721039e7282f.nq.gz
│   ├── 6760a4dfc32443611da3b58076e458fe513ba277.nq.gz
│   ├── 6a84f41e14e27f4b11f16f9ee39279ac98f8d5ac.nq.gz
│   ├── 70693e4a8c128fc4350b157416374ca599ac8c7b.nq.gz
│   ├── 72271d5e41701cfbffad74d38640bf9cc7c1f7be.nq.gz
│   ├── 756bfa07fd728782f597af786bf7b153d123888f.nq.gz
│   ├── 75b2d164a5a98e212cca15ea7bf2ab5de5108680.nq.gz
│   ├── 786d7275d005d474c8a29cf94a94775f8a40000a.nq.gz
│   ├── 7f48c4dddc98efd19bc42b85773feec4660845ea.nq.gz
│   ├── 80128d231cab4e8042d94df18c225117d5846ff3.nq.gz
│   ├── 855ffc6a31c846a3f4b0e0ca2cb875a78ca8d68b.nq.gz
│   ├── 88cfd48dff1169879ba46840804b412fe02fefd6.nq.gz
│   ├── 89c2725b70f1882be97f5214fafe22d27a0ec01e.nq.gz
│   ├── 8aaa46ac1ae21512746f852a42ba87e4165dfdd1.nq.gz
│   ├── 8b6d4680af388f28db8742ef7fb8246e2bb1fffb.nq.gz
│   ├── 8b9ce6b21479bccf9d58412e6fc125614303bb85.nq.gz
│   ├── 8bff408992babffb21efbf6ce396274ca9a9d861.nq.gz
│   ├── 8daa1fcc1a2d4562f5444d1142a686dc62db2d2b.nq.gz
│   ├── 90dce397da7d640a3cf2e1fd28e206f9f7f3c12c.nq.gz
│   ├── 919434a6254f0e9651f402737811be6634a03e9c.nq.gz
│   ├── 924ea8d896bc8cb8a934e0813a7c39f722fcf065.nq.gz
│   ├── 939785b57343f6a4e2d993e945fcf543d3f3d98b.nq.gz
│   ├── 94adc3a3f97aa8ae37ba567d080f94f95ee8f9b7.nq.gz
│   ├── 9625e105df39e8429814f3189a8015087720cba1.nq.gz
│   ├── 977e38b5d1d2d22110ccc434c93af7a7ccba5e84.nq.gz
│   ├── 9da19eacad3b03bb08bbddbbf4ac48dd78b3d838.nq.gz
│   ├── a461e815eb4768548210a3093666e767778366ce.nq.gz
│   ├── a6d6b8609df07bf62e5100a53a01510388bd2b22.nq.gz
│   ├── abf90408efb47c1dc4fc3553d913de7f41ca1cbc.nq.gz
│   ├── ace01515583dc8950023466c5cec3ea25cca549d.nq.gz
│   ├── b02c5485c957b761be64f4443ceb4b6ed412fcef.nq.gz
│   ├── b050030a1b87f959b62c28b124f32f3ac1c22304.nq.gz
│   ├── b1886adb46c085de842f1283c1a3c25151bfc988.nq.gz
│   ├── b190d1e5de29b11cd24bf6ee1c3ad0c8d1872b6f.nq.gz
│   ├── b1fac45f02e2f98395fd96a7e4f4a39e257ac0bc.nq.gz
│   ├── b637809bd38634f92b54d825ce87dd1118dd5126.nq.gz
│   ├── b663ddd50125f63d17482af444fb72fa5efd37bb.nq.gz
│   ├── b749bfef07473333cf1dd31e9eed89862a5d52aa.nq.gz
│   ├── b93c4c30c16703f640bc38523e56204ade09399e.nq.gz
│   ├── bc2100d8f75e6efef413729756e448e910f7304d.nq.gz
│   ├── bdeae8455b4b7c27cf51fd32ff1f9ef0c024f3c9.nq.gz
│   ├── c04e20caf6370ebb9253ad831cc31de4a9c965f6.nq.gz
│   ├── c0e6f6358d8a0ac09660ded9590461e83c03aea9.nq.gz
│   ├── c10f08dc7da60c948c794965285a3fc9a649c9f2.nq.gz
│   ├── c1696446982a42124083484b42af4db71d84d5cc.nq.gz
│   ├── c422723045cad070fc334314499599a31bbbf636.nq.gz
│   ├── c4855bfe2000b73c8a50783b40073676021cbb68.nq.gz
│   ├── c4df70d39da7941ef3f6dcb7f06a192d8dcb308d.nq.gz
│   ├── c857d9fac6834f9e11d10b9f39bd9a7a9a312002.nq.gz
│   ├── c8828146726377ba3aa93dd7887a0613e3739a00.nq.gz
│   ├── c8f9ed8f5cee1c98386d13b17e89f719e83555b2.nq.gz
│   ├── c977c4a42589b03a022ea58b0a45322dd9d9a72c.nq.gz
│   ├── d0e1f58536026aebc4f1f70e481f6993c9ff088d.nq.gz
│   ├── d0ef06e7edb86cdfe0d15b4b0d98334a86163658.nq.gz
│   ├── d19bdbbcc322e39f0beba897d646321aed0cfebf.nq.gz
│   ├── d207307f86d774a11794ba71daa9d278a7680100.nq.gz
│   ├── d3896c98444fbe7288d434169a28c532258a4466.nq.gz
│   ├── d3b6a4013d714b88229c524e79414b8881c70bc1.nq.gz
│   ├── d492d0d98c8fdc9f93ad2543bb4f531803e9df72.nq.gz
│   ├── d5f1c8d34e7a88e3f88bea192c3a370d44689c3c.nq.gz
│   ├── d600e1577d24b7730a7472e7417113ba605f9a1c.nq.gz
│   ├── d6bc89bfa41044d97801b0c5dca62744f788cf4a.nq.gz
│   ├── db77bb4b7b0906d62b1847e87f15cdcacf6a4f29.nq.gz
│   ├── dc139d85a93101cc0f6e9db03a3e1a9f68e8dd7e.nq.gz
│   ├── dcdc2306c28505ebc0b6c3a359c4d252bf626b9f.nq.gz
│   ├── dee655cc42ea7c763579e3b22730f1c1b8ac38d4.nq.gz
│   ├── dff6597e4513dcf90c13b17495c78dd1069cdb20.nq.gz
│   ├── e0f0a47bc08f30b550b47b01de4c9206b6824dd9.nq.gz
│   ├── e56278b3d11e93e8f5346b9f22655671d85e24d4.nq.gz
│   ├── e65b201248cd77a33e380c1df6305b86759e647d.nq.gz
│   ├── e71a16d23d05881b554326e645083799ab9bfc5e.nq.gz
│   ├── e7c5c54370372a4cdde7288a32733998d87bd767.nq.gz
│   ├── e8895216fd3c0c3af4c4522334775f41b7deb42e.nq.gz
│   ├── ec97fc6f30212d34d53ab17751bcabdfab1891d4.nq.gz
│   ├── f091b6b0bca859a3f474b03065bef75ba58a9e4c.nq.gz
│   ├── f2e259c7c9390ff69a6bbe1e0907e6dc366848e7.nq.gz
│   ├── f3c28516fb38e64d88cfcf5fb1791175df078f2f.nq.gz
│   ├── f74085f3f6a2b995f8ad1f9ff7b2c46dc118a9e0.nq.gz
│   ├── f9b0d7c5ea15f194be85eb6ee8e6721a87ff4644.nq.gz
│   └── fa1a2cd35b5bdd6a2afe9ab6faa1df4c577c19fe.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 65a9f0c031f8ecc11d2f5d6649f5030c676c1be8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 139 files
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

[OpenFlutter/flutter_screenutil](https://github.com/OpenFlutter/flutter_screenutil)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
