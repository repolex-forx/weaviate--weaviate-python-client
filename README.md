# Repolex Knowledge Graph of weaviate/weaviate-python-client

RDF knowledge graph data for [weaviate/weaviate-python-client](https://github.com/weaviate/weaviate-python-client), parsed by [repolex](https://repolex.ai).

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
rlex download weaviate/weaviate-python-client
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 671f0a5c6023cbeb3efe3311805276030ddc824d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 671f0a5c6023cbeb3efe3311805276030ddc824d
│           └── chunk-001.nq.gz
└── blob
    ├── 006f340e8675315b67a147bedf7180314102b530.nq.gz
    ├── 007e75ab79de0a3b601b94a0881767437a81279c.nq.gz
    ├── 01a9605065e0da162d4fea4c8ba902b88f085d56.nq.gz
    ├── 01b7cabc745c8269418fd6a20825650a69c30be8.nq.gz
    ├── 0332d4dfa482667ae1f7fa5cf1e5994c8c812a1f.nq.gz
    ├── 033c6d73bcb884e0152faa392f3b9e7496488cea.nq.gz
    ├── 0363795ab0d33145b7c3f0a3ebd1ea2dc51bb715.nq.gz
    ├── 050cda3ca559c1c76a1d82174e85f28e4e489b83.nq.gz
    ├── 0510601f8289bca7e40508ce3a5be57841f326b8.nq.gz
    ├── 053199dec1f1da8cabd89cc71b0b7e046609d57d.nq.gz
    ├── 058ee2fa472397cc8bfa064a06705ec499b9798e.nq.gz
    ├── 06071b40a11d8cd018efc6e570a9953a4afc555d.nq.gz
    ├── 064a9bd1a2aef903c52bbbe100d3214c62d6b7ff.nq.gz
    ├── 06705144e75bf5d14a48cfa8baa4231b13544e69.nq.gz
    ├── 06fdb883207b72792701ff500c69838ea44739ea.nq.gz
    ├── 07083fe9b53aa1794587c1916c0508b6cd49c3fd.nq.gz
    ├── 074599e94c9079bc7c9aed6095e5e3713960623d.nq.gz
    ├── 07b4ee74e7117c0956f4baac769be3e86aa03547.nq.gz
    ├── 07c6f33d2e208bcf9003d098f5c763a86dae48df.nq.gz
    ├── 07e4be385f57db39b9235e492b6b5bd6f95d6a72.nq.gz
    ├── 0854f8b0d83ee11eb2e1a20bd02e9191ecaf8993.nq.gz
    ├── 085b81eb0e63d97ae2b4c304f8666b012203ed45.nq.gz
    ├── 0885a5632e8ca50a71530a10d28c823e5e481cde.nq.gz
    ├── 08b94d26292f271ba18b392c20ebc0efeef95096.nq.gz
    ├── 08cad0ad77d94d99e39f486b12f081bbc89ae017.nq.gz
    ├── 0be4b87cfc8a3c201dd310ac0eb95a4a22fa3381.nq.gz
    ├── 0d7dc103bb767cbf52b6ae6c9c18047731bdb434.nq.gz
    ├── 0e89475ba4c283dfa1c8670dcd8411f029a11afd.nq.gz
    ├── 0f3cbc806b51a820f12e1745945d16c7a7932612.nq.gz
    ├── 0f4872e18254f0aff0a02e01d1d9d7e8a76c366c.nq.gz
    ├── 10b21900fe19711de58a0f18222e794d746d1d81.nq.gz
    ├── 10b924853d3fe8806e386c6444cdf2e8efd49ae9.nq.gz
    ├── 13272bd7625ff11169ef1dda40999e8ac169e8d3.nq.gz
    ├── 1431c466d927e266b087d00f87ee8415b613868c.nq.gz
    ├── 14e8b5e1df4473ec2d8390e364761746b8b125b8.nq.gz
    ├── 152a8c79441d42a39673a964e4516e282f146147.nq.gz
    ├── 1539276af7b00cfb68ed096ea6fed0ce001d3c04.nq.gz
    ├── 15b86f64d911b6d4b5c045612da9ca4bcde7167d.nq.gz
    ├── 15f2e06e85a41dcb8ca3f2d4225f299cb47fc53e.nq.gz
    ├── 16d654b9489c78253f40d57955fc5a82e556ff28.nq.gz
    ├── 192e190e1f172f526b183a77a1dd731a0c748546.nq.gz
    ├── 1999b8dc899f43f3b48fabc9276253b2adfced95.nq.gz
    ├── 199b786697cf70341fe965c670ab18a3854aa530.nq.gz
    ├── 19fe8b46b9d283103eaec5e53a792c633285ee35.nq.gz
    ├── 1a019b34afd4421fda24a2a77dda81afa2d4faa3.nq.gz
    ├── 1b1102768aa7cec28b729b210f2197a7b4d1bb55.nq.gz
    ├── 1c6a64aa47c3214dcd0f8e451efd16442e085a43.nq.gz
    ├── 1e0c8d088939e6400c14b2b7568b0576f34800ed.nq.gz
    ├── 1e2cde7bae2531e432efbbb3ab61d7d8b78c82ad.nq.gz
    ├── 1e52887f90f2111fa2a55ab47885c077fcf8af8d.nq.gz
    ├── 1eaecfcbc7181770697f04377abf38ade6f8639c.nq.gz
    ├── 1f3c299993349066add5f285730393a6f1c963b8.nq.gz
    ├── 1f4fe79ee3876635ceff6fd0d40542283aa4fd91.nq.gz
    ├── 1fcdcf370f26aeac1b2a70a96c12d83f0b28ed93.nq.gz
    ├── 1ff348d07f3ef30fc1f4934b390a0cb7decffa0d.nq.gz
    ├── 200d2dce0d8c529401f87e3e899e85a070e12fa1.nq.gz
    ├── 202cc2578a06e040c3b333305c538c89d5896a70.nq.gz
    ├── 207685ab0d34c88e486cdab0ffc53ab18822ed4b.nq.gz
    ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
    ├── 21462509b3d5418946eca05806d6ed5a58a9bf7c.nq.gz
    ├── 215940fbb1f2d3dbd5e9611e16812cb24ae5025f.nq.gz
    ├── 21692e7576669b3d4166c06e5155de1c24bf71cd.nq.gz
    ├── 21df40c9fe0927c5d3a0c96c0b0b4b9bf1b6b885.nq.gz
    ├── 225588581f4019f7c73793768d454d1ffb421979.nq.gz
    ├── 228303ccd298f5ca878469af49c127e4451bfd2e.nq.gz
    ├── 22f3147fb40ecf0dc93ae09720d1ec832c3fe146.nq.gz
    ├── 2331127b2b4e5691f380a7fa42b4d55504e7dba6.nq.gz
    ├── 233adba3664b52637ddf60a8cfae85dfaf979686.nq.gz
    ├── 241f7c581f017fd463a62fd5fec1ed6ca9845ed7.nq.gz
    ├── 24ab8f87845e95947502d812a46d4e10463df254.nq.gz
    ├── 263c722bc36836906bf60fb99e654eef5738a856.nq.gz
    ├── 267c35a0a6205d113fe35415fadb2991ae564880.nq.gz
    ├── 269caa2ef4b1be75e59e74e32b5726a811eb7f9d.nq.gz
    ├── 271648c2404571ea1fde1500f6c789f14ccd2447.nq.gz
    ├── 271ab1a43a751e8ff676d28cc3627d8b4767b3de.nq.gz
    ├── 2723d05a53e64b9231113516838fccd36792b063.nq.gz
    ├── 27b749ad7667a59ce9eb8f6d0c1a0741e101746d.nq.gz
    ├── 281da6e2d530c13f8b6930ad9f90e1b78c4ca80f.nq.gz
    ├── 291d4918173d981fa3e5fcfc55195af398b619a6.nq.gz
    ├── 29b87cf22899974c66f0c2898cc1a7c0db372542.nq.gz
    ├── 2ac5b56684b16d62e7d789f36fc43bb7e94ef9f7.nq.gz
    ├── 2be8c9bfceb9c3d7819dea7c93e4f0083f161324.nq.gz
    ├── 2d19e0747c4eb1a7ef4915040c7b971f128df460.nq.gz
    ├── 2d4a1070b5536e3b3c31181cf60393501ee955f4.nq.gz
    ├── 2d8bc3051c14d46c5bcbb8b25dce3038eda76095.nq.gz
    ├── 2daafffebfc817aefe8fcb96eaec25e65b3903e8.nq.gz
    ├── 2e9de5e0bfde9b042cd409b8b1d9f0fcbd0ae257.nq.gz
    ├── 2f1c7f029874930be37ecaf067298234c6d361a4.nq.gz
    ├── 2f798f7051b435779685b9050b1f2ac36b85acbe.nq.gz
    ├── 326000f9ab4546274fdd2adc2b7fb3e71ac1732d.nq.gz
    ├── 335dd53d0f05473893eeadedc98f870da5647362.nq.gz
    ├── 33e831ec2f671aa660479d000ed44e6adb0f687f.nq.gz
    ├── 33eb96db755cfac50499566e6b004c3cd6e421ad.nq.gz
    ├── 33f1c05f95013b59c3df572cc5aeac9df191066d.nq.gz
    ├── 343fb346355167b8547de2e478a08e14706f1052.nq.gz
    ├── 347538201045f5d7bd04fb5e0d9038f376a3375a.nq.gz
    ├── 34cdd4b6a9e7a23d982ffe0ba2b15fd923dedfe2.nq.gz
    ├── 3543025c58d644fdd15862e5cb44ae0ad3e70a65.nq.gz
    ├── 35538ad30e659ade03cd9b9d19020ead3ddfb433.nq.gz
    ├── 355936f96e089c28b7b53cefef8694dd9c2de7b9.nq.gz
    ├── 3560cbbb7283d8a4590a809632710c3f191a081f.nq.gz
    ├── 35c2ba0761a5ac28eea9a07f8d1b1ebf51eccd7c.nq.gz
    ├── 360a0d138cf23f6919a3e2f90c813cb31f570407.nq.gz
    ├── 3624a269f5e35bc938f437b896af4ee82eb736e1.nq.gz
    ├── 36cb498f0656b1ff88934aab0204c0cd8b5b922a.nq.gz
    ├── 36d8f7f0456dddde210e164b56bfc2fbfea766b7.nq.gz
    ├── 36f3fe3b446e2a236e7fcf1243e9202a66611ff9.nq.gz
    ├── 372d3fd8af7d439566c26710e1b2bb718ff03efa.nq.gz
    ├── 37a14a54b90580a14fc227bd9f0bee727823a0ec.nq.gz
    ├── 37c1fa60907eb3d815a073183d067632d4db9e76.nq.gz
    ├── 37fce39d3e807fda59c566cf90f843908b9b6537.nq.gz
    ├── 38c18775107833579cfcf6ff835d82ec245bc1de.nq.gz
    ├── 38f7f5b8545a2fac07306f183622c9a4564c10a9.nq.gz
    ├── 3b965dedf88e639eac94432d70a7fb77c314c55f.nq.gz
    ├── 3bb32ccfa9eacdc73329b073cfd5ed98965f8259.nq.gz
    ├── 3c6d9c6f0433768895201848cfa81c8690c3057b.nq.gz
    ├── 3d25fd4ae439b1a0e007983592542c219fae7dfd.nq.gz
    ├── 3d9465e342b399c914f12790989a91569133db77.nq.gz
    ├── 3e49055e8a6b52850f7dc5213c975bca49f03d27.nq.gz
    ├── 3f45a3d3b3c7f7ad4b700c48e8fc6b0cdfd2a457.nq.gz
    ├── 3ffa11a5686f0febda380b27fbbe450181d34ca9.nq.gz
    ├── 402a7e151e42c38d7546032175406a84f5ca35d9.nq.gz
    ├── 404a0fd081ec784f5e2d0a7d7f872625e75e6716.nq.gz
    ├── 409016d90b8f1b5243d88f37b7ae5e58c3f08631.nq.gz
    ├── 40de96d75a19c694d7c5bce227dfd8808082c288.nq.gz
    ├── 40f1d66f3c02e625bb670b0b092679dd74de601e.nq.gz
    ├── 42438734ec676e17b3417694bf29a4b53f782781.nq.gz
    ├── 438eb0bb3c13314f0fab77b378e9c3d7e89e28a9.nq.gz
    ├── 443621397d655ca88d5f46c09af8bb8fe57d0452.nq.gz
    ├── 444273958f587aac9d60163b5ebbd42d8b697094.nq.gz
    ├── 460ed4fd0017c78d0ab620611ac1721ec37e4f9a.nq.gz
    ├── 46371497f29647b150ef3250317899ade6178b34.nq.gz
    ├── 46567920994ab7707458e2698bacdef89946f468.nq.gz
    ├── 46923b69cd4dc2276e863c1fe78a3e3ab5022862.nq.gz
    ├── 469a3cceec2495b7fd6fe28527bb3f96137497f8.nq.gz
    ├── 47019b39ceb4ac7f69f4d57348188ca7b6c6a35e.nq.gz
    ├── 472ada39761813cde2a9df2f89d68c363d9e2865.nq.gz
    ├── 47590c37b6893afdf713024fe7b042db9ae5291c.nq.gz
    ├── 481d515e510eec4b84144515bf3c7fdda2af5187.nq.gz
    ├── 4839ee0da47cf9e7bed4b83c5dd5019c57986a4a.nq.gz
    ├── 4a12a52117540c2d3fb4fb46523115429ccdcead.nq.gz
    ├── 4b274f3dbb3320fc627880d605d8eb8a3dddf39a.nq.gz
    ├── 4bbeda301dbbaff91bd98496f92e24cb6aa5a797.nq.gz
    ├── 4c3f882e6661fab5fb50ddc944e0d9972145ec44.nq.gz
    ├── 4c4d7cb9ead67df99eb980aa7ee30ec9f7eb9dea.nq.gz
    ├── 4c55be1d9ee835dde08de15dbf78ba3202ae7d79.nq.gz
    ├── 4c5645dfb98e104c8ed2e1c4a2648aa4f2a77f2d.nq.gz
    ├── 4cb3eadebc438fb817b2c3c812e53902c52a8040.nq.gz
    ├── 4dc6bca8b01e43f45e20b5948e5e02a1d4e11114.nq.gz
    ├── 4e1841369623abc4f0a5c88889597bef635367ab.nq.gz
    ├── 4f1b82ced0f1ae629f77cb35b799db6b0793e742.nq.gz
    ├── 4f58576b91685be37ef1f6c7b6587184c56e1c7c.nq.gz
    ├── 4f89cf6d2214c21ecab5965bd1c503c28969ed56.nq.gz
    ├── 5023f55badd7734a74fe5546fe21148f3141f0d4.nq.gz
    ├── 50e06cc2fe2df08eed05971a75e24d8f6591a7c5.nq.gz
    ├── 510b4df23db2a8a586418477226d883ae89671df.nq.gz
    ├── 513764a17a0676fd01930ab45fd15afcbf4a4561.nq.gz
    ├── 516273c73a54847fd63ac4d0725304c49d0d74f4.nq.gz
    ├── 5253515a23a62909228cdeb6774a250645c299b7.nq.gz
    ├── 5335457d3b7176ddb0911a231a0ade79dde56383.nq.gz
    ├── 5406a39ddeb82121466b9ddf5887412dd1291e62.nq.gz
    ├── 545b3bbc4b8b16606cb087187f048fcefa97d423.nq.gz
    ├── 54cda8552c0400fda719e39e364bfb58366c3dec.nq.gz
    ├── 5537a3e3a78537ff564125ca48cdc0a29c077ed2.nq.gz
    ├── 576664f3f9b57e8b29e304dbe6262294fc719899.nq.gz
    ├── 5770a506355aa1506b196343aaf96e9216ef4d2c.nq.gz
    ├── 584f010163e52b44bb8dd81152c971841efaca31.nq.gz
    ├── 597b30f29e85e56973174373b753a4af72013170.nq.gz
    ├── 59e867f278fe6c78cba49ecf20abc621fa2de116.nq.gz
    ├── 5ae671ca5ed65430bc1dc8fed343b271c25cca31.nq.gz
    ├── 5af728c6afd07824ddeaf34e18d1fea636bf89dc.nq.gz
    ├── 5bb91fd64331af8177b26a4d065ec305bd5014f5.nq.gz
    ├── 5c2fbf4b3035f5c00d6b2c0286ca1d3297c123fd.nq.gz
    ├── 5c55085d0bac1fa810bcb3b0f06df957190fe28a.nq.gz
    ├── 5c5874ea97d0a016963a44af5b63deb3809b5fa6.nq.gz
    ├── 5ca75a7a0f60795c6f0ccda31e125373fa7f1071.nq.gz
    ├── 5cba315f79e45d101ca2be5b2627f3505c240722.nq.gz
    ├── 5dcaad634ef7ac312ab52243b973c1e4f3426742.nq.gz
    ├── 5dcadfaeb7f8935213cf361dbb339650e03a7cf4.nq.gz
    ├── 5e3b27293dac247d0cff3747d06e8a6469bc889c.nq.gz
    ├── 5edc5121f57b18b51bfd1550cd9db52cd4b4c390.nq.gz
    ├── 5f4118dec58f504b0c169164899200d0000199e6.nq.gz
    ├── 5f54a2f10ac0ef5290fbe87d78fd1396059c9bb2.nq.gz
    ├── 5f9aaa21375af3f874b7fcc13a1cb9dc997be457.nq.gz
    ├── 5fbdae8aa47492c6602936275b4eb345578f7d40.nq.gz
    ├── 5ff780a07200ac29b17812a2277f26112ebc0fe9.nq.gz
    ├── 60338750f6cfe445d09835aeb06d953cd55e8d63.nq.gz
    ├── 60922bf983faf41f0098d71e8036738341a63940.nq.gz
    ├── 60d2e4e1ff73d1a8c614dac9c556e24b2ec703ad.nq.gz
    ├── 61aaad1bac77c0876e32ec33ebaf0e677d8eecfa.nq.gz
    ├── 61eb3eaa32bb71d9e51eefbfd8472cdca63d992c.nq.gz
    ├── 61f6bade0ace4a28690e783b47bbadd1780f983e.nq.gz
    ├── 62fdcd833f1774998727924725a459b71a2e206d.nq.gz
    ├── 636a32b82217d34d04dabf5cc80b8ed6853c9a36.nq.gz
    ├── 63f7dd31e546bf6a4a5f7e2f5eb6c41a1d52523c.nq.gz
    ├── 648b54ff974b9c26c0f056b5da489888d349904d.nq.gz
    ├── 649a078324099a22dfcfb52a3d5f7bdd9fd0ca00.nq.gz
    └── 64c7fec6a2c61297106ed97537e10511a0b69ee8.nq.gz

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

[weaviate/weaviate-python-client](https://github.com/weaviate/weaviate-python-client)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
