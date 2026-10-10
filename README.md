# Repolex Knowledge Graph of pola-rs/polars-2.0-benchmark

RDF knowledge graph data for [pola-rs/polars-2.0-benchmark](https://github.com/pola-rs/polars-2.0-benchmark), parsed by [repolex](https://repolex.ai).

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
rlex download pola-rs/polars-2.0-benchmark
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2d368574ae96ea27439906c4ae751e94fcd55532
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2d368574ae96ea27439906c4ae751e94fcd55532
│           └── chunk-001.nq.gz
└── blob
    ├── 004cd937b8fd8754a50665e3c36f4cac482f6328.nq.gz
    ├── 004e54d9f5aeb952e03bb111c2dc5c5c25011acc.nq.gz
    ├── 0096d4a8467b352e3111df4cc0a64e36b8ad5a75.nq.gz
    ├── 01ed9be8899be868f55bc635aeb9be77e2f02b07.nq.gz
    ├── 01f308bdbd662f7ce82db2837425798a3db63816.nq.gz
    ├── 0222b45be45d956585dc162b9902f8f86b2eb207.nq.gz
    ├── 024040ad95e6b4efefb6ee487cbf5bf29969933f.nq.gz
    ├── 024c2c9a7881b687e0e627c52df123936d7c8377.nq.gz
    ├── 029e31adb864b206cd16e3ba10da68bd7a36a6bc.nq.gz
    ├── 0609f6240bd3e656c4251d6747b4633bcf4df924.nq.gz
    ├── 061e4e5281f48ca92f32f57cbc3f7e87d6e9e172.nq.gz
    ├── 06d26302f2c228c141c5dba0513c3ec056671899.nq.gz
    ├── 074af060894120e7cc13d4c3228a2b7a1406e669.nq.gz
    ├── 07d7fbccd4c6f2ba3ea544a632b3c4684ab898d9.nq.gz
    ├── 07f1ff5af192795159bb97b2fe0c4eee5d0a1385.nq.gz
    ├── 08436d47b88bdf8b9308afc45782e339c4594647.nq.gz
    ├── 084dcc182aebe829a6f0261d91fdedf638d6b8cf.nq.gz
    ├── 08c97b54e4c90bce43ff1af42dce5dc68b80d258.nq.gz
    ├── 09060cdc93941ff2ac6a9e2fe808bdbbbbf597e7.nq.gz
    ├── 0944dc20ad985bd206edb55d3191ce51b6480af0.nq.gz
    ├── 09e63406d7ea8fc58f69a7065d9375284f20e95a.nq.gz
    ├── 0a41da7b0ffd7e78eaa1bafc2239c1809e07d8a1.nq.gz
    ├── 0a4f134bdf36ddf076da5f84624a082869e4a9ca.nq.gz
    ├── 0a50d99ef7852342f11c3abea5a65f0d2c90a168.nq.gz
    ├── 0a6dd70fed68e20bc161576a995cc8b7f3e64baa.nq.gz
    ├── 0aca55d931a819c8736c2375e636e52570069ff8.nq.gz
    ├── 0b5987247deee17f9ffbd90089ac82e310dadf87.nq.gz
    ├── 0bb9dabf682d772a380a5e61d80f71eb0866b74f.nq.gz
    ├── 0bcd1316dcca3b9888a6d2b7dce5955d067a0eba.nq.gz
    ├── 0c1c0600c81db95f378c6da91563a59c1107ef7d.nq.gz
    ├── 0c2c7ce13af324d0d0c564dd8960708a52b44319.nq.gz
    ├── 0c7f304b75762bfac3716cc730fecd5653d47fd8.nq.gz
    ├── 0c96f8fd48514a8795e428ec019f9ea2bccf0e75.nq.gz
    ├── 0d13b4da95096a73236e0f4752fb2c476e9cd474.nq.gz
    ├── 0d5037c44542ba6584e907eed424c2a7a001226a.nq.gz
    ├── 0d9be56606e879f96e19073ac817ccbc27327403.nq.gz
    ├── 0e501a47a42ae649e7a73990d877de6a7a0dd492.nq.gz
    ├── 0ee34fff1eb66909a715679ef1797dec590f15eb.nq.gz
    ├── 0f0d1c75b4feefa5a8723d6d03c94835fb027594.nq.gz
    ├── 0fd9581498805f11e3b62aa3a2f1c4479d7aa7ae.nq.gz
    ├── 10460aeb52578e3ce12a4b7d55d58f8b3c3263c3.nq.gz
    ├── 10c8a6ef083d661b3c5b04a8b7cbcd44f3ef90ca.nq.gz
    ├── 11007139ef184435f6cda2b47537892470365bdb.nq.gz
    ├── 112ff67d327be31d24b166d2843d51082169be0f.nq.gz
    ├── 11f0b9facfe944cf22b8574c62403475c63bb16c.nq.gz
    ├── 12ffefd3dfb55e40405b8fb6029910beca8f5241.nq.gz
    ├── 13376eca88d5bb65b3dc301366c8383acb065a35.nq.gz
    ├── 13c0de79c0f22cf1081bc570efe794a83f406587.nq.gz
    ├── 13f747a9a4222f8168d897570dfe8096e57f723b.nq.gz
    ├── 14b2d5bd40172b4dbb06f8d3c28f00a615c06079.nq.gz
    ├── 14f2289d19d15eed4b28224db10a83316aa22011.nq.gz
    ├── 150962528b9d11aa97b303b1f334850bcada9200.nq.gz
    ├── 154d6ea56c463964de9f7a99f6c6ab1d41f44e42.nq.gz
    ├── 159b7a7a07e56475955c549f96de10077b6e5d51.nq.gz
    ├── 161d09a4e4744aa61c5e7f5b333eba4fd6727d0d.nq.gz
    ├── 16c09ca51ce9e14321719307c948ff063807607b.nq.gz
    ├── 17b2c8962f2a9ec1a6830713017a2132bf37abdf.nq.gz
    ├── 17ca62f2bacfef8dd9b986a705788086a04f7e73.nq.gz
    ├── 183c1e8e1eb96c04cc372bf9a46ec67e199e699b.nq.gz
    ├── 19a28bc4966128bc624a998b97d63f5a99b1ef16.nq.gz
    ├── 19eeb25671a2f2360a684de4cd9f715d249b6759.nq.gz
    ├── 1a5e78bd3ffee1375ad4085c661c73424b547107.nq.gz
    ├── 1b0665942cc4896fd4d68572d66497263e8feed6.nq.gz
    ├── 1bd22c01836eb6b6c964b0c0b1f9a79031a3fb96.nq.gz
    ├── 1c065b04bd32af835e3abe9bcf14ebb2e9d545f7.nq.gz
    ├── 1c375cd98e1bb698d606769081bb2ce9a56f6623.nq.gz
    ├── 1c696eab36f691930646fd4971dec6463a77e571.nq.gz
    ├── 1d1d27d34d2c98f5ff9f3b49eaa480255e3df05b.nq.gz
    ├── 1dd291872e7b00b2772d63f54609bba39149da77.nq.gz
    ├── 1e235813d9bc5ffd7c06c55fdcbb79af764860d9.nq.gz
    ├── 1e7008ea906db3eb66e7dbabdd94f74041f48ce6.nq.gz
    ├── 209e18900ee00dd4ac6d3b219ee71c41488f6afd.nq.gz
    ├── 20d92fa1d3e23876a0b6962c0426e74057d04059.nq.gz
    ├── 20ebabc8b4f66187867b4344dbfb8eac6632eaf7.nq.gz
    ├── 221a44bae0ee827b87a41a73b907850837e1a7e0.nq.gz
    ├── 22b0a1a977ab65a31aff27b94111758bc3876c44.nq.gz
    ├── 23d8415b7dfb48346c63f629da1dc3222c3ffc9b.nq.gz
    ├── 23df9868a34b6cf978b8c8d8d733843c2f2c4a61.nq.gz
    ├── 2420200bac6f48a6a9137b475e5877745cd995ba.nq.gz
    ├── 242df8105f073358548b1365153faf230ea0995d.nq.gz
    ├── 245ff6066b6a5ad6f29ea08db7b6d011038f835d.nq.gz
    ├── 249bea8bf2aed44162ef13a7736bc45f10ecef5d.nq.gz
    ├── 251892f1d6ad43b232b9f09296980a1687398782.nq.gz
    ├── 267b6caa06e7a615af463b2ab170ebf9b133f4cc.nq.gz
    ├── 2701b6c54be1928fa55661190f846af40c4fee5e.nq.gz
    ├── 27dcc29e1942aa16c3344288ea5c52646a2ad74c.nq.gz
    ├── 280779097ace8dbd4586c898ad54d974ff0361c2.nq.gz
    ├── 281c25fc85896416f3f7282db5c4620c9a0526bf.nq.gz
    ├── 2917d48373aa310ae897f72f5fc0fdd45226f0be.nq.gz
    ├── 2945253b1e7349fabb161622d9381d313973ea6f.nq.gz
    ├── 29f446b2ee4cde3256a99d67b3fe1809141f9adf.nq.gz
    ├── 2a07fb2c389519e96c30026ffe3969d4a8af8872.nq.gz
    ├── 2ba5a6740ccbab306f65ff00747977d8e5a5a6c3.nq.gz
    ├── 2dd1325f54eed02cc334bcb73c61c57e0a071b6f.nq.gz
    ├── 2ee555062686563f3c66e8c9820c5ae833fb94d5.nq.gz
    ├── 2f0166e9cb3746238c526496a61ed10a1897bce9.nq.gz
    ├── 2f2bd5b055b2b7ecdcc19ba3e0334a0f488500d2.nq.gz
    ├── 2f85c19ee12a3f9ed895705355ed7837e4785574.nq.gz
    ├── 300a8e254264b4b7f83e501db8415aee6a75319d.nq.gz
    ├── 303a28f1ab3613b629c845d80e1132cac7c78105.nq.gz
    ├── 30f02488748eabc60c981fb8380746083a37a292.nq.gz
    ├── 317d6a6432c942db76a29a5b023d07905b0f5bd8.nq.gz
    ├── 32ee8dce5784544fab312a6b93bb72077668d160.nq.gz
    ├── 33dd7d663358fd46a06f26e5c1d6d5e3f778f0f2.nq.gz
    ├── 34735d53cfb2e64a0907b5f75658b8078b4187c1.nq.gz
    ├── 348dbcef2fe2e9142a31f8db799c987a8af15071.nq.gz
    ├── 34c733ee2fbbdd77b7ebde118347930787000e49.nq.gz
    ├── 350f2abcb4a2b5bf403c1420cf6f9d6e302681cd.nq.gz
    ├── 352e22c0c71bfda6210f65b50de8bd88344e56cf.nq.gz
    ├── 358939dbdb368c3d0c5e2c8c78bc831286cbf784.nq.gz
    ├── 35ce3609bde2d4f980628d5366ff0ce4c7b048a4.nq.gz
    ├── 36f628743dac1afe446873e5f6fb1fd7b4266d5a.nq.gz
    ├── 36f8261387e504de239fa806852cfa504a107485.nq.gz
    ├── 374eabfa24fd55c226a57c727a3e4a9948d9d95b.nq.gz
    ├── 37d3925c4e13c4e36245ef014bc41f938120191b.nq.gz
    ├── 381031ab16207009074255cf13df2fb6be38b236.nq.gz
    ├── 382e99dc8957950cea184e55dd07f2fd9d1a89f3.nq.gz
    ├── 38489932d0220e14fbdb93c2c1959a65181687e0.nq.gz
    ├── 3948287637bbda464893fb86dd02763dcedec997.nq.gz
    ├── 39ddbdcce25f7f624d2a0afa05092174042b086a.nq.gz
    ├── 3a1ecf0c41b586097c4964429500d33674160df4.nq.gz
    ├── 3a8651cbc71bbdbca3f5c94056f35ff6f7604c6c.nq.gz
    ├── 3ad02f8718320fb5d450aba9c13d0fcf8a453abe.nq.gz
    ├── 3ae49b2aa43128261c4b82e52d1dbf46b6350d22.nq.gz
    ├── 3b4d994e3e305ff0dccce0c72c4433759c47e8a3.nq.gz
    ├── 3d36aa32f018e7d3720aca2ff0035732e071b138.nq.gz
    ├── 3d5f8ae795dc7e2e72b35c44909911faf63ad43c.nq.gz
    ├── 3de89a91b399ce5a64e24eb5295ebeae61bc7b5d.nq.gz
    ├── 3e11277f8a2bae52b6f94354afb103d2882ca6d4.nq.gz
    ├── 3ecc2d3a0fab2145658f0b726788300afc8dcd41.nq.gz
    ├── 3f61b8288595218ee3878297c1c35754db869370.nq.gz
    ├── 40bcbe329cba0616fca02277502be97a1ceee612.nq.gz
    ├── 40de97cfee4190341555d656ab7a33e478c09476.nq.gz
    ├── 41c83a566dc153b0619644691900b8087d3a5964.nq.gz
    ├── 41fc8ca66a8bed39e3904707f439075e8092f677.nq.gz
    ├── 431b2c88b7c65e930408876a8ab646098d3f993e.nq.gz
    ├── 44658ef6ead6b149b5e1492c84a04d1b15b70b19.nq.gz
    ├── 44a8ce4d4228ed1a3e275b314a59bf8fdb4c0426.nq.gz
    ├── 44aa07079d9512c7c087a00a6ff3abe72ae01e95.nq.gz
    ├── 454e817288b2a6c2bbbd2c22c612200f2737ee0c.nq.gz
    ├── 4651d81a6f912195d625640a4979e42cfa289968.nq.gz
    ├── 46c83064ccd00fd0d228434408d686e2556df995.nq.gz
    ├── 47d37ce51372c023c561c011168e09b43635eeb2.nq.gz
    ├── 47f7bb94e629cf863c3e50f4ef8f1baadd4f0f5e.nq.gz
    ├── 484fcfaf81482dc1f5ddd0cb76b98886082d7466.nq.gz
    ├── 4a04aa1bed474dad85aa65b2e72e500ad4c09aa2.nq.gz
    ├── 4a8579d4d1c842938477f3b4b2a246e983b7a6e1.nq.gz
    ├── 4aba411fd329e6aedc8be1fbb7cefc41c53aa586.nq.gz
    ├── 4af2c2715251dbad715558768f85a122e875c51c.nq.gz
    ├── 4b5db917013c3e2766d952cc3936c552778cf9a6.nq.gz
    ├── 4b7fa290b729fbf3adbcc3160f828b0d2c5dfae4.nq.gz
    ├── 4bee65c34d173852c47128964fa84f846ba21372.nq.gz
    ├── 4cd66364bfa40c15f84421bf358e10d06829b35b.nq.gz
    ├── 4cfa36d10729ba9453f95f3fec21504be2c252bf.nq.gz
    ├── 4d3a0d64e7e92beef84f43441ac47b0d919a4b5a.nq.gz
    ├── 4d78fd953b8ab94f92e5c323ccd064ceea5d90cd.nq.gz
    ├── 4dd6be18ddb95014b982ffde1e11b5a1e4be5cd8.nq.gz
    ├── 4de819e0e737215c56f8dfc61e5bcf1150434e29.nq.gz
    ├── 4e67dc82bcb2f174e9ac011f4e91d8807656ac54.nq.gz
    ├── 4eba1c852a94e3419aafa4d90f8eb6187a94033e.nq.gz
    ├── 4f4ad4e83b5a2b69c75e1f9860d8d79d74d19011.nq.gz
    ├── 4f5a60ce9976d0aa555daa93bfe551124d0d89cf.nq.gz
    ├── 4f7c83fd0a31a1432f245c5663f60358d0510646.nq.gz
    ├── 50930e42971da5fdeb1a131f667aaa73d20f5840.nq.gz
    ├── 517ef1525564e114bf3ddb96982e92a42c58a5e1.nq.gz
    ├── 51a6fa41fa167065629aa11cef3e23e538114a5a.nq.gz
    ├── 52172b08bb6002dadd6f867f1c5cacde2a0cb4aa.nq.gz
    ├── 547795afb30af96967d898754a780f10ec8868db.nq.gz
    ├── 54c62a468dd634ebe0d715e6e60b425e5ebbb221.nq.gz
    ├── 55074e55d036d0502f0a19cf0a321487ae845b89.nq.gz
    ├── 5545270e904649d3cc54904d665b54ca66cd541d.nq.gz
    ├── 5584581642c78cd058bada13bf158786f529028b.nq.gz
    ├── 5595cdeb2b91028fd1c8a07193613cb66c054aa2.nq.gz
    ├── 55b9773ed69388fde65cc0f9703de266ab1db9b0.nq.gz
    ├── 55c35a9b76b83b0098cb51b3e201e10c076cf575.nq.gz
    ├── 55f0d817c297771e7e497295bf6fef716d8974ea.nq.gz
    ├── 57192c033e317357c01e9f840d5abc5fd8a0f9c2.nq.gz
    ├── 583bd3cf35dbe53e866584d6648ab3dcaec5c524.nq.gz
    ├── 58eefd736cbae8ed17160483c74397b0cd324203.nq.gz
    ├── 590369d1c4282d3ede4cb0e410627b2130f15804.nq.gz
    ├── 591d83c2f320dfa41600121ee6b5f4d44e8ab104.nq.gz
    ├── 5928a4824d473c252934fa369b86e8cb35ef45ec.nq.gz
    ├── 5930ee74fbd4e5b22c2055077d3afc03f5ee3c80.nq.gz
    ├── 5a4772f129b727f255c4071981e7acb1bc7dd027.nq.gz
    ├── 5a709d69ba998484f813447610eb32a96c26e881.nq.gz
    ├── 5a86d7ae2dc1dd9ccf745cfbad05a6e2ee5908bb.nq.gz
    ├── 5a8d5b81e9c3b357e8a63faffe1a99af1cf27104.nq.gz
    ├── 5abe9e5782a2643e2b88c898c8d2ba0bdb4e360a.nq.gz
    ├── 5b8f734e76528fd5dc7138591bd66821ef6147c8.nq.gz
    ├── 5c3452f6c150a962a870d440ad51e25024d815f3.nq.gz
    ├── 5cb11082baf7e8315e8a3646a111865ab7fcc0a7.nq.gz
    ├── 5cff81087059783362e94dd9cc32e35e95297814.nq.gz
    ├── 5dc7cad3db3634ec492dbbf9eb79ec900daf6b24.nq.gz
    ├── 5e1c2a72f0b350dc15cdc7d483e0e87090b2a729.nq.gz
    ├── 5e2d12711c5e3bda4a0f74fb6433f95eef0d19ee.nq.gz
    ├── 5f83f90715fe2b88b59367b7c01989d53b8866e3.nq.gz
    ├── 5fb9922af4dafc9680e4dd99065d47947222dd60.nq.gz
    └── 5fbff835b9277eda9a00616f926c688fb221c57d.nq.gz

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

[pola-rs/polars-2.0-benchmark](https://github.com/pola-rs/polars-2.0-benchmark)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
