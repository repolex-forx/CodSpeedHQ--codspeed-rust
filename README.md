# Repolex Knowledge Graph of CodSpeedHQ/codspeed-rust

RDF knowledge graph data for [CodSpeedHQ/codspeed-rust](https://github.com/CodSpeedHQ/codspeed-rust), parsed by [repolex](https://repolex.ai).

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
rlex download CodSpeedHQ/codspeed-rust
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dccf5f4a5d4ad018905018be4a9d7f56141b4268
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── dccf5f4a5d4ad018905018be4a9d7f56141b4268.nq.gz
│   └── repolex
│       └── dccf5f4a5d4ad018905018be4a9d7f56141b4268
│           └── chunk-001.nq.gz
└── blob
    ├── 0044814c58c1b514a412f99aeb3735f672e75f53.nq.gz
    ├── 0124694c3100097bd689c030e03d24f1ac803f78.nq.gz
    ├── 01421b5801e1c0ce7ab08f888aa6bc281bfa7ff1.nq.gz
    ├── 020ae248dce6730c07ec40b8d42c6657b0bca9ea.nq.gz
    ├── 0240b1dbdcffb578206269646b621dcf71abb75d.nq.gz
    ├── 028895a3c7490277f4d5f4eb658d2cd8e43b0e2e.nq.gz
    ├── 02e04a6a57bafac2af6e66b817f4b3cef7f042ba.nq.gz
    ├── 034d06ce444b0f15106eab142d0c5155787ddefd.nq.gz
    ├── 03d0af6e8a8a69ebb8acb5a83e4ee6cb30509fda.nq.gz
    ├── 04e1917bd83e5c06425d81ea861ec881285571d5.nq.gz
    ├── 0508fe95601b5766b6bc8a7b513c67d822ece9fc.nq.gz
    ├── 050bdd302dbb289c298ab5b45acd887cc6e46459.nq.gz
    ├── 052a60a8614d252e8d60ae776d4ea9bf760ef2a9.nq.gz
    ├── 05f314e13f3b23cf494a8365d1dabfebac294812.nq.gz
    ├── 069cc771c353aa9cdc24cdc54232e67a336da316.nq.gz
    ├── 070e1b5b6ac6601421147354f402cb87eaca79fa.nq.gz
    ├── 078fc47f5a766fd794afc5e322bbf69d2770cd48.nq.gz
    ├── 079ea07b2ae1936165e263779488c18b590bd03d.nq.gz
    ├── 085afd022180ad773b993d5c3780353bc5c29796.nq.gz
    ├── 0875e2968ee3381fd7b43f7492296837edc6b88b.nq.gz
    ├── 08cbd17e15f8c4e7b0052f738a28acd251a3824d.nq.gz
    ├── 0904ddbb841a1ea3b722a48a7524e4499391d190.nq.gz
    ├── 09f9e6292a16d9e5bf3d609b4dc1819c69dff6eb.nq.gz
    ├── 0a9496765245e0cfde1760731e424ed2ecefaa8c.nq.gz
    ├── 0b7beed41d60a91ae1d2ff7e3fc04c9a5ee1e02b.nq.gz
    ├── 0c9605a178c9804a303997e064e0d757fa3c8597.nq.gz
    ├── 0e334f62223a54a7cfe1393f977cce33dca83d2e.nq.gz
    ├── 0e5b7ea0a5c78ef2d6b604e4d34ed3cdbb33654b.nq.gz
    ├── 0eb33b5b6a7d7c78dedf232ad2dbb7e5cc19a5e7.nq.gz
    ├── 0ebb851e2e22c1845b06e88fffb7c5c1b4285781.nq.gz
    ├── 0f7cd1da03e2c758c947ba0cca559300a656d3f4.nq.gz
    ├── 0fb7f536dfbe1af09af98671ee79995fe84a8bc7.nq.gz
    ├── 0fc4f2c09638b1d48eac98c32f93eb40158deb07.nq.gz
    ├── 10c033996b9e05934c940eeb8dc5cf3ceb5945cc.nq.gz
    ├── 10f545ba3398f89ce93ee93b4a1410edcdbe4798.nq.gz
    ├── 1153da44db38750fe5c678848e783a1676956874.nq.gz
    ├── 1187671f23e3674d3d8da9236e8f809f29e35d65.nq.gz
    ├── 122c58e7f208ad4531cbf449808a1483129bb7e0.nq.gz
    ├── 125035f35d5f92db1d6418bcea2c66683e7b75d6.nq.gz
    ├── 126c94e6f546fbf9570ed8c46947bd90a3175f21.nq.gz
    ├── 13b4caa591a661448627c666bfc16a891649f9e1.nq.gz
    ├── 142c7fbda0f83c6cd5a65c84de0a72380a0e051c.nq.gz
    ├── 1440ba83859371e322216bc581484247752278e4.nq.gz
    ├── 14aeb07817dca9e7035c0ee0fcc5b5a2ea7cea65.nq.gz
    ├── 14e3c106d1dc671f8b9fae85d76105b1ba97ea6a.nq.gz
    ├── 14ea77a3a6f3b2c299a6abd7c26d00deb41f6c3f.nq.gz
    ├── 1695033b0b90ad5837d326114c07ca260e468059.nq.gz
    ├── 16e4361c04497c0aef6375e8fe9404d15fb111aa.nq.gz
    ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
    ├── 174be99ef09125fff6b447a15eeadd6037cb9a55.nq.gz
    ├── 18eea054adef37ccad082d4b038b7749e4e87972.nq.gz
    ├── 19956d2bc7c30cc3a3b8f916c85cff69870c3be9.nq.gz
    ├── 1a1a10375c95c0546c97ebe92430fa99f8c45642.nq.gz
    ├── 1a9adece0fe357742f4f9a1884be967de07f412b.nq.gz
    ├── 1b893aedb357cca36a8f978c4e3460b14eec7602.nq.gz
    ├── 1beb0910dd7ac9395838f01c686d0e75e6f17286.nq.gz
    ├── 1c075159ed8fa9da2de41ed3f7b75abccf1b0b60.nq.gz
    ├── 1c0daae0313bd7055464b1d5b7680fbfe638bb3f.nq.gz
    ├── 1c70d2b94c966b4e80d5dc50e9cab7e7efcb02cc.nq.gz
    ├── 1ccbc1a259f80805937a5f268becdab4ff676813.nq.gz
    ├── 1cd31ee85929956894be990207719106058111cc.nq.gz
    ├── 1e7caa9ea89a3016bc73f03b5e4c167711a21374.nq.gz
    ├── 1f80dec43bae5c9ae199c0a9d92e64cf0a60b750.nq.gz
    ├── 2070f63f82d67faf390070e1d60164652b2613b2.nq.gz
    ├── 20ed3d41dcdfcad353fe2c515dffc78ac1c2723b.nq.gz
    ├── 21c914011e554d178087e4746875a704c7e1a9be.nq.gz
    ├── 21e11754c08c4caf12e4a546b2868e931704188a.nq.gz
    ├── 22f006f1313297d0382fd098a0dc13a3ac9e7de1.nq.gz
    ├── 22feeadc0bb749bbbaa7fc8e843081e1decd3a2b.nq.gz
    ├── 2306ef7e4ab7b02a7af3a00630614df15a9ea4e0.nq.gz
    ├── 2351c9ef6870ba49a0b4efce4dd0f62c00775cd2.nq.gz
    ├── 240d955941fa3de97b8c78394d7ff662743ef5f1.nq.gz
    ├── 2412672b8610b50f4131a3b63c1d5597d07b649c.nq.gz
    ├── 25310e417ab4b99362d35fab3059b2809e50ae7c.nq.gz
    ├── 25731487628cbbba686887a724a5f913395810b3.nq.gz
    ├── 26203d1da7106e9e2a02f425ffe8860aae7f5660.nq.gz
    ├── 263e6eaf100bd3022fc422a08df9a7f80bd83c8b.nq.gz
    ├── 2675f8c2f54c5169c8bdcab14a70bac4eb59abda.nq.gz
    ├── 27cc48be31e142b1d57e86d6a172567ec9ffc24b.nq.gz
    ├── 27d63d86b51b399ce76285ff539227552ab17fd9.nq.gz
    ├── 28eb4af589b20a88f8a97602fbcd52b45a2f7a7c.nq.gz
    ├── 294dd12568013baa183474ce509879a7a7bad69e.nq.gz
    ├── 2a029156761bee85a1953a137d102076f4a17c8a.nq.gz
    ├── 2a10e41f6897fe7518a8289a512394bef016d4f3.nq.gz
    ├── 2a4fb3f4c316abdb4a5005dfdf7300a4cf0c8e14.nq.gz
    ├── 2b026c6a4855792c684d155ed1a25c91af72aaf5.nq.gz
    ├── 2b1c5e8d35b3ba16b1fd0820118b413d461f2df9.nq.gz
    ├── 2b5654c14354790b9dccd8460926199a8db817bf.nq.gz
    ├── 2bd00512b08466c1f4c5dbb32d655e17e8dff978.nq.gz
    ├── 2c53cafa69dec2c4f168c77957e4454bc7584c4f.nq.gz
    ├── 2c5770d2588b86dac06579a491f2ca38bad7aa86.nq.gz
    ├── 2c8f7ab39f02ab83f1eea381cd8a41aac17d02c1.nq.gz
    ├── 2c96eb1b6517f2617f9ddeae9f07f5fd7bd7ddef.nq.gz
    ├── 2d79917803333b6621d32f3bbffe589de97c66b5.nq.gz
    ├── 2daf86a420c05259da98109b47644242cef6a08a.nq.gz
    ├── 2f614ac0e8c246cd8094e113a8776157bc051366.nq.gz
    ├── 304775c48b075a71f2f6508254104365ef6aa779.nq.gz
    ├── 32f053391a28dd1332f47469267de287207087a7.nq.gz
    ├── 3514778842593214fec0aec6a7d1dad6279a1806.nq.gz
    ├── 35756b95ef701e0d42e1b54b1c339cf097562877.nq.gz
    ├── 369032a64a61c81de9f0710b1682e0024990f603.nq.gz
    ├── 36c2478c6b3d2460c1d82339ff322b028154e77d.nq.gz
    ├── 36c6b448b3cb284aeb56dc882322cbc50f9b8c6c.nq.gz
    ├── 36d7f67b33dde013b257c4e414b4a2bfc48d701f.nq.gz
    ├── 376c4756ba90a3937d18986a2e20b4900cc0ffd2.nq.gz
    ├── 37d0a1a707881b2309941584e2eca23cc6f4774e.nq.gz
    ├── 3882f087ad9c8d79eef4700c07f9049c1f4196f9.nq.gz
    ├── 38a8ead678c7ce17edd1a57bafa4c9ec4cceeb08.nq.gz
    ├── 3924e1b65360c7113fcb6f614b65bc38371de766.nq.gz
    ├── 39ad162b74015588467482bbf0a0e04c1cc3363c.nq.gz
    ├── 39b2ff662241ee6d469caef24064fdc02e877ed3.nq.gz
    ├── 39d0d759c16051e4fdd98e4c917720a7da9fcf77.nq.gz
    ├── 39def18e7acd885a614678becac29c7eb01f7144.nq.gz
    ├── 3a1cb001246904ba977f6a3c5f0eb29f8c1b91a9.nq.gz
    ├── 3a78d6c1eb4a8dafc0612bc8c7b48a4ece851e21.nq.gz
    ├── 3ac4f1cc7acd1626e54f2a84be9ececc32a62111.nq.gz
    ├── 3b596c8e5e424dd8dd68428c3ce417f99469c16f.nq.gz
    ├── 3bde49a83973536cf04dfe8137e61fddb28a3e6a.nq.gz
    ├── 3c952620975890ddbd64f1d175a7af275e61c57d.nq.gz
    ├── 3de73101980f0eb5ecc3c2ef74453b17575270ab.nq.gz
    ├── 401b7f92309861dae074c2086baf7c890f3e611a.nq.gz
    ├── 40b1f31ba5c1c7bb32488955b8ab93923c29e700.nq.gz
    ├── 40c57f3c5d11c490f776fe4bd09246ab1c007d7d.nq.gz
    ├── 41311a9321b319dca4670304a60cd9413b5d9762.nq.gz
    ├── 41dfd872e289a9a7a8092facf2c3d0cf7fbbdc76.nq.gz
    ├── 4233b276615621bd445d1d9506eeae9287ae39ed.nq.gz
    ├── 4258a350dafb8460d13ac247028463bef654423b.nq.gz
    ├── 449f9030cf2e89d9f508dcc049293b2f9cd28377.nq.gz
    ├── 44a5fffe14bfae0a89d726df09c3c2de246050b3.nq.gz
    ├── 44fcc63439371c8c829df00eec6aedbdc4d0e4cd.nq.gz
    ├── 459a716f58c558acbfa5d6427e1cb38a80af844f.nq.gz
    ├── 45a09da935da7d0d58f09ce621bfb94585538a03.nq.gz
    ├── 472c1f84d930aedc4e0114dd3f6931edda2458eb.nq.gz
    ├── 47b4a110e5705dae26715498f15f016c94308375.nq.gz
    ├── 490f3370e6b9095e0263a74fe55ddc75dc70a8d5.nq.gz
    ├── 495dea4cd44603ac1839f5bdde8bcf6081dce7f3.nq.gz
    ├── 4974b637dfdbfd2d2b8fe2c827dc0ceb1754aafe.nq.gz
    ├── 4a29394fb9014b7c46278c2b93e45e8deb65b7be.nq.gz
    ├── 4a66dc5c0670e9b9681f1b7ac2853d7917eccfea.nq.gz
    ├── 4a854358b6e115b542851761690a1be346cdbb97.nq.gz
    ├── 4b8a4bec89e14d53b385046a8910b9ed8359f1cd.nq.gz
    ├── 4bce39468f74a5d8fed08e2fe077a136f81864b3.nq.gz
    ├── 4bd4f98173848417cd1dbb2906afe54ad39ffdd8.nq.gz
    ├── 4bd51d94f6966718f33e69d03990a26e4336db26.nq.gz
    ├── 4c0ed2600c379d153360b5feca8588d9424e757e.nq.gz
    ├── 4cd1b183d75f8edcc22d5912d354725079de9c07.nq.gz
    ├── 4db4de8d532e95f61f8d1c0219cb164470f94db3.nq.gz
    ├── 4ec6118c4c51de636b06a7b8aff4bb082084441f.nq.gz
    ├── 4f335c0eda6049d5557912475e79d1a923aeca87.nq.gz
    ├── 4f926debd8159f54d612c9af08555aeec5b87e6a.nq.gz
    ├── 4fbae76b8da6e647c20516d51e2b4cdc0c758976.nq.gz
    ├── 4fca23b0810c0d7374b2a1c43d0fc615ff8237c0.nq.gz
    ├── 50eaa06284d4e1c206137cf6b89fb82c0bfc3bf4.nq.gz
    ├── 50f264351957b1e13fee6e06e36769e0fd7adf89.nq.gz
    ├── 50ffe5e5a3044ae0bec24971d2b4934acb9fe9bd.nq.gz
    ├── 513a5cef702030ec5ce8c3ec5c3e2ffc1de7a659.nq.gz
    ├── 5227ffb6ed38df45675fc850517d688364972fd0.nq.gz
    ├── 52d22332b86a564f5f19bede8460fa10c3116fb4.nq.gz
    ├── 52de1ce3d905b7e16d46d6555cacd1a649692a12.nq.gz
    ├── 531eb56d67cde7f45c7cb18cd0dc44fcf877808c.nq.gz
    ├── 5330f06b9f76204b7b04b80f49096531c486ddbb.nq.gz
    ├── 53706d608ac10fcb05312ca2a2fabafefa6969f4.nq.gz
    ├── 53c4a4dbd8f7ce8c2ed1b32b2a3bb134ec022ca7.nq.gz
    ├── 53c835aaa23002664a3ece03a07dbeb4841c52a1.nq.gz
    ├── 5543796eb3a291cac355b977f8b83d6edb3a3e82.nq.gz
    ├── 560fe5f8bca261bbd9eb556c77e2e6a4dced2257.nq.gz
    ├── 564f9f9c0838d8d5eccfb7e1cebcff3ec879656d.nq.gz
    ├── 566483edb1b76d1628f963ac03ecb855d6504df3.nq.gz
    ├── 57ef0e6c78e7f14a3ffaddb05c340b8fa7a52c5d.nq.gz
    ├── 57f60dce120f6635bcfdd89fe000c2b6061740b2.nq.gz
    ├── 58e4eae4774dd934a34e277b01f5bf16d08419e5.nq.gz
    ├── 5a038a4373a5bfbc9515af8798c5337ce68a747f.nq.gz
    ├── 5a0bf0317d75cdd3dbf2e58cba1cfc99f9085458.nq.gz
    ├── 5ad06bd84d6e727f921f2ef0edc15bc14e67288a.nq.gz
    ├── 5b221272dd03f76a3e4539192bd35d5e9cc45236.nq.gz
    ├── 5c292c77a22a632fc15633d0b50093862384f24c.nq.gz
    ├── 5cbdc82a80f47eae7c47e6b0ee9506311884911c.nq.gz
    ├── 5cfdd09d6e27be4ea5b4d76042833ea20bee4008.nq.gz
    ├── 5dddb940f5946cfc5a688e5c04f38beca11b8379.nq.gz
    ├── 5dde253f0b02cfb8eaa4cb5b9fd8a4a9a4027718.nq.gz
    ├── 5dee9dc46fb3560eb050fbb5941faeb28d6dc83d.nq.gz
    ├── 5e4eb41dedb5b5fe1b1d095424123b20beffa448.nq.gz
    ├── 5ec824b9c18e7777d881f7610e368f22b5913d1c.nq.gz
    ├── 5fa6d558d02c47e26a312483bb1549e18c18168e.nq.gz
    ├── 5fecd89c3190d4b9012e70a5daa1e0fe2a388a07.nq.gz
    ├── 6140f9a4222cafd869cd03ef829fdd8f1d1e5e6d.nq.gz
    ├── 6190868a392e4a9aa32468bf4fa69fdaf92f1a79.nq.gz
    ├── 6262889e1490c8cc4bfd369a9c6a648912de77bb.nq.gz
    ├── 628c23cd37beed8723406aa7cac30f0f5ada3b87.nq.gz
    ├── 62beb20774373c036a21e4b9e7770952a43a045d.nq.gz
    ├── 6320f54b296a7a6b210910e017f4ebcaf285289e.nq.gz
    ├── 63719753d6122df138de07aceef33ec85dff5e16.nq.gz
    ├── 655739effcd80b33b7596a8de5c44b9208eb313e.nq.gz
    ├── 65d4b62aad3c27f51074813078cb7cd4bf91fb4a.nq.gz
    ├── 661ad40fd981b421e5d1c6548bba0c18b4528efb.nq.gz
    ├── 662ce5d10ca45c6c900f808469c364ca6ef704c7.nq.gz
    └── 666d95c059bf1dbbc16c99a6d50a4875608f5861.nq.gz

8 directories, 200 files
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

[CodSpeedHQ/codspeed-rust](https://github.com/CodSpeedHQ/codspeed-rust)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
