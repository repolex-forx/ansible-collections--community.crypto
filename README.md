# Repolex Knowledge Graph of ansible-collections/community.crypto

RDF knowledge graph data for [ansible-collections/community.crypto](https://github.com/ansible-collections/community.crypto), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.crypto
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 00d193fd380122715b57c90b3cf03648782feb90
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 00d193fd380122715b57c90b3cf03648782feb90
│           └── chunk-001.nq.gz
└── blob
    ├── 000a7f3855e3f06b74457bd8276b93a62d6d59d3.nq.gz
    ├── 00268608dc8e730786bf896b3d0576715cc1e431.nq.gz
    ├── 00bbb3ddd4f8b1617f96ce6840077ba5cb8b0eb5.nq.gz
    ├── 012065c8539f2bd3e61eecc74acf5a046956de40.nq.gz
    ├── 018477dc91851da4537534cbf80b5b4314a3abc9.nq.gz
    ├── 01ba7f48e6dc8617144b54e3f46ec22f11a4b806.nq.gz
    ├── 02bb22416aa4611b2e6a979d0819fc649065157f.nq.gz
    ├── 03bc85bd717b8ed7b104941a97ad26428ff7ae29.nq.gz
    ├── 040a5b94746a937bccfcd1046430da1e802cfa6f.nq.gz
    ├── 04122462d738313581d76374cb085280b2918bd4.nq.gz
    ├── 046123b4c7910bd95808f000cad28b4910423b94.nq.gz
    ├── 047cdffe6f12cc7aea176410c4f9da5136aa0819.nq.gz
    ├── 062ac5aae2d35f0c212076ff3a67af7ff1f1c27e.nq.gz
    ├── 077c32c7a2448c86229f0bee7dfd230f78f89a19.nq.gz
    ├── 0789e775f9ecf993a214f1dd7c8a5c08f84a8161.nq.gz
    ├── 07af7d264a49258523f08710d9874eed2e27cc80.nq.gz
    ├── 0850f6ea495fa0f1e9b94b8812b11e8c36f52831.nq.gz
    ├── 0853b92a4d333dc13aa64007fa063e832c5a6e98.nq.gz
    ├── 09356d7fa22f18226a574f84b0a2a2d187c484b0.nq.gz
    ├── 09395924466af79db390adb7074b79b3a0595dd9.nq.gz
    ├── 0a3ef2276c6d66f12c21120954af7ab9f5e28f56.nq.gz
    ├── 0ac8c114375cc385782da96deba2df9a2cc5dc80.nq.gz
    ├── 0cb0b36f6f0fc12e77a9521445449d2ea7848383.nq.gz
    ├── 0cd55a483703a55499dc4ef2a1673b71bae78461.nq.gz
    ├── 0e074eadd5c40409dfe9d44b24d9826ecf19f6f0.nq.gz
    ├── 0f5efdeeb7e63e760673ab29de4eae5311b832f3.nq.gz
    ├── 0f747303cad9d6e2158bdbd077193ef3711f593e.nq.gz
    ├── 0fe224ad92b837b309e9c16366bdf20544f6a567.nq.gz
    ├── 0ff99fd3d01a035e8e555f18a60a2333ddcc7df8.nq.gz
    ├── 10ec06484e084cb7d9cb70820c5208230d1c4d7b.nq.gz
    ├── 10ef9f7a325b072117346bf7a665b76e4c0e58ee.nq.gz
    ├── 1101ddd20f3c0d43b6dd40804685df5542a64137.nq.gz
    ├── 11a58511b5f72f9a77b111f51e5188d132c714b5.nq.gz
    ├── 11fa92876fe7943578d4fd4a7e5c33bfdccf1962.nq.gz
    ├── 12aa00052965191c65c0bb672792e830ad00be32.nq.gz
    ├── 134602c482e2a8e6a572fa945ba40cf5fbbd08ae.nq.gz
    ├── 141eff7648460127474f5f44af90c4114a02df0f.nq.gz
    ├── 145878790c6ca09612fed4731465ac18f1c0bf6b.nq.gz
    ├── 14f2ef01175a55d83d9ec03aafdcc3b435834946.nq.gz
    ├── 154488d7d2f7b2f9c4ded3f95af1fe943dab7035.nq.gz
    ├── 157dd54d4c55e3a5076fc9c218978a63a9d6ab64.nq.gz
    ├── 163ad08c884736715f317c66e01aa6f947400e9f.nq.gz
    ├── 169a128f72309b1cd632b76dcd5565b32b493fd6.nq.gz
    ├── 177f22695a7c8c2cae26b3c6499bb2c1e38e16b8.nq.gz
    ├── 17ba9ce40d83b7872a0e99c46d3ff98a370ed4ae.nq.gz
    ├── 1bc5844e2b69e43eef617f9a82fa63b1d13159e2.nq.gz
    ├── 1bf17e053a612aa6868dcc8d039cd248f97d874b.nq.gz
    ├── 1d3b278f8a3bb80982ce509da8acdc74b7d47dba.nq.gz
    ├── 1d561313cb2129aeb0eec424fffda756fac076bc.nq.gz
    ├── 1d6cf8554ada641c9a963a6f986822bf4be2da9d.nq.gz
    ├── 1df09a78b83e4c1f9ef989411e086453f936a3c0.nq.gz
    ├── 1e08f8a7f85d12afd61766799fe80756470074a0.nq.gz
    ├── 1ea7424fdb2c1260927b8c43357f5382a81db3d4.nq.gz
    ├── 1eef64cfd0d54703931cf9bdda21a9fb1939b7ea.nq.gz
    ├── 1f4b8e4f10ed86b84cdb431eca9be576bd8c62eb.nq.gz
    ├── 1f708ad63d43547079a8739dbe6ff3bd68bfb823.nq.gz
    ├── 21262115c29bb0f439eb5339bf7970008ff30bfd.nq.gz
    ├── 216e589d7ce28586f47d28012c0e1c3d3c2fc07c.nq.gz
    ├── 23e03a868ba9a17bd6e408cca1b679fdb0ef2a7f.nq.gz
    ├── 248270514d07d0c6afd87bc50cc9360298daa04e.nq.gz
    ├── 2502c27db30a20b15869cc8b55f50f07ab3c7a91.nq.gz
    ├── 25f92c7ada8faab8bc7933b79fed5b4b23bb1d1b.nq.gz
    ├── 26c710fe1334b82120ed762d77fc8dc2eb156077.nq.gz
    ├── 27290d60c92d1cd644bb8b4877debf3d926a9316.nq.gz
    ├── 2734fe60e6d415e4ccf8af567519fbebfb28785a.nq.gz
    ├── 279b5f6ad1f87163af19f3e13efac494c75fb98c.nq.gz
    ├── 27c24934b3804d31d84dad098e5f87c6d4048a50.nq.gz
    ├── 27ce6b08752cad6f018b31813b1fa52febd319a3.nq.gz
    ├── 2868bb8e908cfc49886772fcce44ff1e9dcf5181.nq.gz
    ├── 295a26e1cf19f924d950b13c71d35d367f600029.nq.gz
    ├── 2991d8c003cdde1b06fd5b10631b20f0dd709144.nq.gz
    ├── 29bcb85748ef846bd6dad36751435ba029e61ec1.nq.gz
    ├── 29c4179098aa9572afd1d77a8d17c92d27fa3636.nq.gz
    ├── 2a0db2ac6ca8a822e536248ac12f585e41cbd1cf.nq.gz
    ├── 2ae2ed2bd65ccfd97f526aaac35748987f35a6d1.nq.gz
    ├── 2b0241d9a0bc007dda8a34b29eb61966eab55d28.nq.gz
    ├── 2b2e8a6531f79f1d66b6ddca5527bd3257896999.nq.gz
    ├── 2ba1f7d2fd2660a8a607ddd331375b479e0f589c.nq.gz
    ├── 2c4875de8174fb67475c9485f18dc95097c33711.nq.gz
    ├── 2dc6408195411c1ac9604b4a15434a78a7c282ff.nq.gz
    ├── 2de55cb38b3b5002315f9b7c9544cfb18bdd4f9b.nq.gz
    ├── 2e1dc472f3aafa890684a51953601d98e1918f04.nq.gz
    ├── 2e51b8d86cab380d89284dfcaa26b4ba1b749938.nq.gz
    ├── 2e8ad10b8b6cfd71af9d7055cd04b4e9659ecd0d.nq.gz
    ├── 2f5e8de1b37d69c651352e924882c7135a2ea6eb.nq.gz
    ├── 2fcd152f95cb8146ef0d4c0a1c9f97751b464c2a.nq.gz
    ├── 304d1124c5593f806999d5876e1f04fda730bdf4.nq.gz
    ├── 305856b363167318092ec2f96d628d24ef466311.nq.gz
    ├── 306d1f39d6b55f306c820fc64f3f9e8078dceef8.nq.gz
    ├── 30ac4eab4b8c92ff68419dc52aec6a188b86b046.nq.gz
    ├── 316e15a563c1e1886df20a033c642a1d147d9f35.nq.gz
    ├── 326a499c3e3c56d5c9dfb63477b46aa79e4bb70c.nq.gz
    ├── 33220714055989ebc6d9a08f9de335a7ec91382c.nq.gz
    ├── 3407d490865150475f35c4c06f41d9bca22fbedd.nq.gz
    ├── 35cf59ccca65257ed51ab565568bd7295b06037d.nq.gz
    ├── 363df04d8ee667438d707017b7c4a0b75b1d886d.nq.gz
    ├── 3718482a8f00f4578565f194889786820be191f0.nq.gz
    ├── 376b22767e39acbbcd5a97829b81e0327acf2919.nq.gz
    ├── 37c5cbda72d97dd79f6e9fff65ead9f5f64a65a8.nq.gz
    ├── 383e0f2c0f9e59d487babaf0270be64ab0f9cd8c.nq.gz
    ├── 38590f2e4ec486212f404e5f1405e69f7ec27db8.nq.gz
    ├── 38f35b9b45fd5581e84a9b802e6c3a4a28b912e3.nq.gz
    ├── 391748605d21aeacb81550fea4f307c97dd8d7cb.nq.gz
    ├── 3b09aef75aba36123fb699797c8faa39baa2603b.nq.gz
    ├── 3bc499aa5064f4991e943db07ca85df3cff25342.nq.gz
    ├── 3cda74955344377170beed6b09125da08e717774.nq.gz
    ├── 3d5c5d153b136199fa2fa898badfadde1eb011cc.nq.gz
    ├── 3d6085eb14ad80a28888417c338bc349dd383fbb.nq.gz
    ├── 3dc496f3a17fd73c2e85425c5a0adbd218c0dd21.nq.gz
    ├── 3e82c4f98ee1f032feb1c36428b1cb3834ec23e8.nq.gz
    ├── 3fa9e71a49d125e3093792b4baca243284382aeb.nq.gz
    ├── 3fcdfa37c7cc251133e9734fadd45b45db78f4b2.nq.gz
    ├── 3fde6d37e40891f717b098dd1e29edb25148b8bc.nq.gz
    ├── 406cf38f9afff54c03444286acfea2bc60a585e6.nq.gz
    ├── 41e4bf663a14afb5b49325a7d47d40c7f4de4bd5.nq.gz
    ├── 4362bd2aa68d421e5eff7e140af006e9d8d6c13c.nq.gz
    ├── 43ef56114a117d90c307c4c5d722fa7c78e4ef3e.nq.gz
    ├── 441441622fc1584471e7b777d9fb74b83d465e30.nq.gz
    ├── 45668b960cdcecd8b8902289893f5006b1be42aa.nq.gz
    ├── 457176c91bb012a82e99017627ea3614de59e847.nq.gz
    ├── 4602f1185d3a5e708ba4282771ee66136f6a14e0.nq.gz
    ├── 46b52485ddc5d315e26ad00ba31e910739e9a9b9.nq.gz
    ├── 47e49b9f56bd6798aca6b1a15848e0f4b7ef5f72.nq.gz
    ├── 48476be5533fe832a254248cdcb4ae6dabba1ec5.nq.gz
    ├── 487fcc56113cd851ba44069dfe8f3f7b067857e8.nq.gz
    ├── 48af5caad699c6099ad68404ea716ae314492cb9.nq.gz
    ├── 4981d66efadf1541b3c7de11a9214441ffc9bf2d.nq.gz
    ├── 49f5d8595a764057a536527b10f6e97469b972a9.nq.gz
    ├── 4a877d9034c17a1be22f9cea4ebc0a9be642a914.nq.gz
    ├── 4faff0dc64a8772f633d354abfba66f2b49fc925.nq.gz
    ├── 4fe838395b146bf1787d748eff2a3cb0b93f8969.nq.gz
    ├── 501b296a4d6bd62f92d22a30cce0cf4a7130ac93.nq.gz
    ├── 51400ef0c1876cac8c1b8fc225e8719368b7a889.nq.gz
    ├── 51cc5748f071636fda6a4d506ce20d5599758c27.nq.gz
    ├── 51ee6d5e19c58ec7bb697eabb3060553206e38d3.nq.gz
    ├── 52034e087c871901f49aafdd3be5c8114f5d48bf.nq.gz
    ├── 5244f8eb742d2e5b57030858afcc5689cacfb4b3.nq.gz
    ├── 529509e4591fc78e77f8a3e1ed0a0587b8996d7e.nq.gz
    ├── 532df9452ea049116e7a017d9c1b58e531cf54c7.nq.gz
    ├── 5348c9fb01b271cded9ecedf5c041eeb1223d26b.nq.gz
    ├── 53b576cf6e910c4990fa3791360e6bbf331e9110.nq.gz
    ├── 54bf29e9f7b646d5083694a9ae4a39ab48e79406.nq.gz
    ├── 54cb6bec435c1afd6a6937609ecf2215e7c5a7a4.nq.gz
    ├── 54e26d6dd95fccaacd997a669fdfa47ee0a1b83e.nq.gz
    ├── 55da9de056c7412cf87aaa4d21db9e862cb599ab.nq.gz
    ├── 561f5cc4e753c7723d1d16fe9c383dd6f5f8253e.nq.gz
    ├── 57642df2959884f31178bd205450e5ca75799ac2.nq.gz
    ├── 57b6e9c46789a7d4d62fb3a4557f612901372cc4.nq.gz
    ├── 584401bcc820a99a49c98af5280f9d5b6df80191.nq.gz
    ├── 591e386ddbd0f97ee6d92ab20cf4029dbfd74466.nq.gz
    ├── 5926a36fb9b42eea476d7a73cafa6f29e7da8577.nq.gz
    ├── 597f9fd971715db5cef8b38693a3737dc31d3e04.nq.gz
    ├── 5987b18feaf49994d324f1a127e91d07b49c9590.nq.gz
    ├── 5991f616e7ad020563b152e256ed23c5eb8da8dd.nq.gz
    ├── 59da495ae62c115a5dc3019fa51c486888d3406a.nq.gz
    ├── 5a701d436e6491e68491efbdefc849554172b03e.nq.gz
    ├── 5b18c8ddf0c05f218b9f1dcc792b014fff262d6c.nq.gz
    ├── 5b50962f9f9d414408b62a944642d7d3f27f3242.nq.gz
    ├── 5c39e2021418accadf97410890a34e3bd3e1b7b0.nq.gz
    ├── 5c8b566889dceec59bc44e557d18d157ce97f1d9.nq.gz
    ├── 5c8bb848b102d01202601ada3bffa4f82de2ee33.nq.gz
    ├── 5d6d7091ded655d639f26a6569dfd6b280ab4b44.nq.gz
    ├── 5e40c0877058c504203932e5136051cf3cd3519b.nq.gz
    ├── 5e4f2565154fe3be5e1e342cd68d51448eb4018f.nq.gz
    ├── 5ee7812edbb236187b2434d8d01342f71c10b922.nq.gz
    ├── 5fad487f4f9a0300a53a7f67d1c9db925a67ec68.nq.gz
    ├── 6004b0cc4c356798ee044ffaac36b81d8ce9c487.nq.gz
    ├── 6059ed80efa9283983b34968537cb1a078449095.nq.gz
    ├── 60611f73403e74ab5ba48fbac06931588f08a5f6.nq.gz
    ├── 60878b7dfdbc9baf90d81290e3771412d90f3931.nq.gz
    ├── 61379183328eda620ac310b076a5c3d62cc5ca9d.nq.gz
    ├── 615e594ebee03e745a07b65b3381050a80fd74cd.nq.gz
    ├── 62135341cf10c2871dae3676e5b19e622b209e2f.nq.gz
    ├── 62589edd12a37dd28b6b6fed1e2d728ac9f05c8d.nq.gz
    ├── 62617a09cdc77401b16ce694f8c2b109efeb9b9b.nq.gz
    ├── 62c4b9556eeb79a6fdb204bed8de503fb7e943a7.nq.gz
    ├── 6371f68a0b0d251473907ec077fab18ff3bcf205.nq.gz
    ├── 6383f605b572621631255c71bd945bc78c99456c.nq.gz
    ├── 649911a9c4da5ad838ccd83b449717ef5734d6eb.nq.gz
    ├── 65afe8adc766c8524f39b4f23460db3676e6c348.nq.gz
    ├── 65fb136f2f1765d9ff609b65be592430834906be.nq.gz
    ├── 6609366cd959832cdc46bdd00241219bfdab1f1a.nq.gz
    ├── 6609983a22f6d0d53aee5dd3507eebe907f6cf19.nq.gz
    ├── 683beb4e0348d24d2c004266cb907693f1618a30.nq.gz
    ├── 68a7dc1bfe83bce7539829055a2cd04da1c25a6b.nq.gz
    ├── 68d2528e6908301c77c16f0e6273fbbfe8a31ad0.nq.gz
    ├── 69302bf8f0ebade3a824b6dfbacda2237c8a9ff3.nq.gz
    ├── 697760461a248ce6c94b0d5a8a8253b4ac1c5788.nq.gz
    ├── 6b080875cc14d91a65c7b34f5f542433d4c32e65.nq.gz
    ├── 6c2156135aea59dab02f46f4f9e56b6fa26a18f2.nq.gz
    ├── 6ca671773f0ede90432d5387f1c3e7f6945e62d7.nq.gz
    ├── 6cb09aa41add3de381a253f4f72ac67767dac6b2.nq.gz
    ├── 6d53e2ec886a65a2f6ce8c355d5845b1039837d8.nq.gz
    ├── 6d5f060bc8eba95af92ec6513dfe2c3b4c94d1a9.nq.gz
    ├── 6df47b6e65a15244432650a9f2ffeb65238a7d29.nq.gz
    ├── 6e06c2359ad046fac34ef8e0875da92c4588b1f9.nq.gz
    ├── 6edf5dc10cb7ccc043c705fbfaf54c01a846d1f6.nq.gz
    └── 6f0b200f5d8d24a73a41263cfbcddd2f84809c37.nq.gz

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

[ansible-collections/community.crypto](https://github.com/ansible-collections/community.crypto)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
