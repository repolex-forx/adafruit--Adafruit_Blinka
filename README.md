# Repolex Knowledge Graph of adafruit/Adafruit_Blinka

RDF knowledge graph data for [adafruit/Adafruit_Blinka](https://github.com/adafruit/Adafruit_Blinka), parsed by [repolex](https://repolex.ai).

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
rlex download adafruit/Adafruit_Blinka
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6021fc9ccf64473e8cca7cf329b38fd38f099ecb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6021fc9ccf64473e8cca7cf329b38fd38f099ecb
│           └── chunk-001.nq.gz
└── blob
    ├── 004ddcd5e7362e2ed2b2058440eab7588504ff0e.nq.gz
    ├── 006454532a5aeb42b30aa9fa35e9dc05150d1062.nq.gz
    ├── 00712fbbbc0c5880ccee350af6688ae02fdbf9db.nq.gz
    ├── 0143060ba9a7451f75a73c7cea934fcb8a6304da.nq.gz
    ├── 0161633ab6922499e25bc340cdb72a6ba3591493.nq.gz
    ├── 0202042b526f31dfb55aa115812e39628c3401e9.nq.gz
    ├── 020d9afcf26661d7da05eb01fe65948cd0575d79.nq.gz
    ├── 022f403279229caf88012cb7a1277418e2352ba2.nq.gz
    ├── 023a40eef55e5cc49e436d7998d0dd2a0bd85cfa.nq.gz
    ├── 0266b51829d9ba86f6d683de1e84c65ed9639c76.nq.gz
    ├── 0279c30eee7d05796fdec275bcc67033dc969f70.nq.gz
    ├── 0291c1b4669cd98f02f2d1c9d489ed13f1d9ca2f.nq.gz
    ├── 0297b272ce7b2b4f203b7d8b0897264071d1c9c7.nq.gz
    ├── 02cdb9985961d60cc5e1042653e10a974de5019e.nq.gz
    ├── 0323f6b57ffcfa3fa0001a2fa95fa18e63df82ee.nq.gz
    ├── 0333f98d78f3a61e686e7babe268eadcd0bafb02.nq.gz
    ├── 0353e69e4fdf6b06d57123028656a2637b7f77a2.nq.gz
    ├── 03803675287b970d4a49ea5b0ad135eca981e5aa.nq.gz
    ├── 03e7b661adb429b7534fc03ee364a87a4003755e.nq.gz
    ├── 04b8d14f60b2dc8a97efbe19e4ddfcad0cd2d027.nq.gz
    ├── 069c0c5481528e193443fa7290800998d68fbe94.nq.gz
    ├── 076d45f2c2bda7f19f4fc932ebc5c06a7aeaa152.nq.gz
    ├── 07e52d542ee7fdedb53b8c13019265f820e3df4c.nq.gz
    ├── 081b82d3c6fbd84aaac6f7cd75225112061f1601.nq.gz
    ├── 096899d8d184853fca6aca851fa4875279892948.nq.gz
    ├── 09cd4918bf01dd00d82f518293e0bb98070f61bb.nq.gz
    ├── 09ea130ea91ffd1d49b637c0ec3fa59e0a3123c5.nq.gz
    ├── 0aa3a55921a3582c65491d6f90c51fd0b3a4f951.nq.gz
    ├── 0b200ec675e6ab97e62c90fe855caf7295a48331.nq.gz
    ├── 0b2d857ef5ea95cb23b03f9b6f7cb57959df06ed.nq.gz
    ├── 0b491a1365f95f086bcb0add0c9c8e74c6fb01a2.nq.gz
    ├── 0bbe8c1575bd9cd5b037f6ac745479d482102a0b.nq.gz
    ├── 0c80293c46828ebe80101e6f3ddb6d4e2b3b999d.nq.gz
    ├── 0c91d2104dcc347754cb7ef9933b5b92101c66cb.nq.gz
    ├── 0ce256371e419bba40753eb97dba90350aa6a405.nq.gz
    ├── 0d1faf2c996ca88e9cd7229855f7cbccd27db3d6.nq.gz
    ├── 0f1698ce481ac775d2e98e2b0aea2aff7947c376.nq.gz
    ├── 0f2ae6afe2ac20c17ac6298894f01f1acee9b57a.nq.gz
    ├── 1019b598df0baba0a52d88e198e2654c35075b43.nq.gz
    ├── 105675dd25cc669f39f6bf345afedb7e2146dc16.nq.gz
    ├── 1064977991c1115cc349af360a444c6361992135.nq.gz
    ├── 10972f53d977ec0f0fa480e1714816b6c5fbf747.nq.gz
    ├── 10dc6a861074c0a58e2f9839ece912bf1d221b97.nq.gz
    ├── 11855b77f971fce605f371e60b3e70815a476472.nq.gz
    ├── 11bbce5f8629890a7409adaade8dc6fb71730d1a.nq.gz
    ├── 12136bdb7448d50e5d509d8990a824305a3d9af6.nq.gz
    ├── 1373c92d7f7f90a03825dd3ddf7ca41e933ba202.nq.gz
    ├── 13b37afd0d9cd323b92845f3b6782ace6e143fcd.nq.gz
    ├── 13f3873bffc03eadafa7a997f3d72550bb415835.nq.gz
    ├── 14121d3796e7e866cf6243ff1d6a679aa15ba24f.nq.gz
    ├── 1439b849445832bbb4293c756cda59c15eff74cf.nq.gz
    ├── 148032026b7102c5f89eb19a197e208bfac75892.nq.gz
    ├── 14b586a568735c6105f4162b9a024379bfbdf623.nq.gz
    ├── 164d4f425901469c1a52ac5aa6004ec76175990a.nq.gz
    ├── 1738bf375e268dd3baf5d3cd40b199a191986a56.nq.gz
    ├── 187a4d35aaa1d90ac7bc0a5d454409ba3fcd5c15.nq.gz
    ├── 18e0b413f27c0b11dcf5eced46432d12744ae912.nq.gz
    ├── 193179b5a003ff53aa9096b48859c5704357be3b.nq.gz
    ├── 1958777d3aa40e2b719570ed33797bde2e810e10.nq.gz
    ├── 19abbb32535d5231bc7182422fcca2ba34005111.nq.gz
    ├── 19e236a75814bdae56dc6ae1a2c925a918fbb14b.nq.gz
    ├── 19efc3461341b2634d2ccc054d2dd6cd617ce8e6.nq.gz
    ├── 1b725b9aff739376d43f15ce566fee89ec25a1f2.nq.gz
    ├── 1e5d6e479c28ff21bc42f8d02cc4945a048e3685.nq.gz
    ├── 1eaa05ce08fe7cfdd0c0b5b23d11fe3b06cd24f2.nq.gz
    ├── 1fb4c9abe3fb5eb40e0a57e2cd7c764119bd6e02.nq.gz
    ├── 1fdee5be845f73b8f94979ca6ff8b1a1b6842949.nq.gz
    ├── 20362337324eb4a5ed3961d79e901725adb782bf.nq.gz
    ├── 204b93da48d02900098ced21c54062ffbff36b9c.nq.gz
    ├── 2109ecaf3faee5b43af2a38907e60dba1245e408.nq.gz
    ├── 21b380e65eda0d7f94b0525b203ae6df63436e57.nq.gz
    ├── 22f3b7f22703c273abad37790f671a0dc28fa46c.nq.gz
    ├── 23ec888531ba35d4c0d6d7714ec7cff46b2656cc.nq.gz
    ├── 2408b00b33384334054f511874be861a1c89ed5a.nq.gz
    ├── 246aa0df2cd0d40a4b8bfffbe1cca0d410d725ca.nq.gz
    ├── 248a42a9c9b05e01b1ffc243e3c24097fc1c4e4e.nq.gz
    ├── 24a8f9019938ba762d40975394d33d2895e8ee4d.nq.gz
    ├── 25cdbfc12ca5607eab326538eb939da1fec32e89.nq.gz
    ├── 25ef6248814148ccb2fcada0d48d5a0cf0231c2c.nq.gz
    ├── 261e275afab0bebf43bc6e0d0112c2eeab5a9c01.nq.gz
    ├── 26a80723cfd5cea2d70a2abc27efa5353af5782b.nq.gz
    ├── 278101fd2afa5e689bf7313c07d379d01cc10548.nq.gz
    ├── 27b3ce80b259893ef079b36216fbe46a9c1073b5.nq.gz
    ├── 29f4734c7e7083c70a73a7ad5d14349476e8a133.nq.gz
    ├── 2a5464dd3501357936d40b3328f8cd33c82ebe44.nq.gz
    ├── 2be333d2301c6b5d06acea5a123f1f35e3b33443.nq.gz
    ├── 2cc033708ad4412e730bbd821722c5aafbe17abf.nq.gz
    ├── 2d2839bc1e4b28a8cc1b0d9cb0d10ac5abf864ed.nq.gz
    ├── 2dcc5394718eb79efd25a5c0706b79187e015b97.nq.gz
    ├── 2e61edf117a39166b8bff32996331f84182165c9.nq.gz
    ├── 2ed3024e028ab2385d6e3dba5b93502ab7937c95.nq.gz
    ├── 2f975cb69ef9c829221b6646d19ef02f0b3c0c55.nq.gz
    ├── 2fc91050bc24cdb5f955bd3f82e3e427cc756c39.nq.gz
    ├── 30102d166a9ac893adb4cd9eeb6377638bfcc464.nq.gz
    ├── 306b834bd953ed4e2b4191d52d6ad4edd01c3aa1.nq.gz
    ├── 314daf9c472f0350e5f9eabfe038d791d7655a19.nq.gz
    ├── 315d198d131df61dd8c3b767210ef7260fda6696.nq.gz
    ├── 316537236e337c5eb05368513fa8b42c7aad4395.nq.gz
    ├── 31a1cc5a3e8a35a07da0bc02672d8d141056bc81.nq.gz
    ├── 3233d477c04bfbc1683eadf6993235e75dfd4e8c.nq.gz
    ├── 32bbce119e4ba26b2658617bd76646a2802cd966.nq.gz
    ├── 33413759f739c9b91cf0f152d6180344313e0faa.nq.gz
    ├── 3466665c1dac9227c318f017faf695e85ae553a7.nq.gz
    ├── 34e6d66cadad38e04543e68664f9a07a790cd499.nq.gz
    ├── 34fb5f6ad426817e89f7e53c3ef96be585329b45.nq.gz
    ├── 35100d04d9db8293534c3e061eaac0749c254e63.nq.gz
    ├── 3574eb52c86c7645a230b65bfd0fd7f676d4427c.nq.gz
    ├── 3624475b9bea4362504d4822f285fde296536128.nq.gz
    ├── 362fa4a867cdcd744edd24fb40cae712b28d3d1c.nq.gz
    ├── 36869196661ba4e5113c0fcdc65e47ce5a54afe8.nq.gz
    ├── 36eff5b75522a5be088c5600acd7e036406bf3e6.nq.gz
    ├── 381bfafcebd464fdf643b638d32daf6fb102e7ad.nq.gz
    ├── 3894bb6b29f4250e39092cbc020673a76415a2e7.nq.gz
    ├── 39cb234f84c81c3582c58760caac597e2318a40e.nq.gz
    ├── 3a89c0d2e9a0b1ddb2efa31549e0861195ed5321.nq.gz
    ├── 3b7b57f1c2b558c92edf605b348276c56d2bb505.nq.gz
    ├── 3c31473ba99524cc0941722c779019c2402774cb.nq.gz
    ├── 3ed43a50c06e63be775c615e2577e4f49c680fe6.nq.gz
    ├── 3ee166a9bccff1eb29748eafc622ac2aac2ced60.nq.gz
    ├── 3f6f74c95d26a5484d474f0af33ff0d3b4faa408.nq.gz
    ├── 3f92dfc5fdda05635f28da16a47fa1a5c99c0dc6.nq.gz
    ├── 3fbc280ed2674079a4eaef962e9c1a19382c4875.nq.gz
    ├── 40f204c79a1a1f48a038f133870eef640e8000d6.nq.gz
    ├── 41f928e5bd08bd46a6a45389e0f80a25491b6980.nq.gz
    ├── 420247eb69746b9641e137237494a9122996c7b3.nq.gz
    ├── 4257108da849db9d610cdacc9177d89d9ca32957.nq.gz
    ├── 4501457ee253dff3879618f71e20760097470b63.nq.gz
    ├── 45a0aa61ba6707df16f9a8fb262106c9758ec696.nq.gz
    ├── 463c40123d10c168cf167253929ef7e48211f898.nq.gz
    ├── 475f414c8367b398dfab462dea61e644ee25677f.nq.gz
    ├── 47a112fef7e68d5fc1967fda19925cf26ae07a07.nq.gz
    ├── 47d46b05caa1ffbb18981d3d1cb942f6e6cdc1f9.nq.gz
    ├── 47f038f235527c7ddeddb7af8b89b40c4402863b.nq.gz
    ├── 48bbfb50d2eadc3676f247a992b1bf1f6c661eb6.nq.gz
    ├── 49d715831dd4b25610f3c28671f9add51c2515fc.nq.gz
    ├── 4bbde4aea8f41e1f35fcbe6bb7c498014e1b6bed.nq.gz
    ├── 4c18ddf4b1948a9e1e82811d9263891af332f837.nq.gz
    ├── 4dca3a62eee13aeabbc896d6b37c9b0a1637ac96.nq.gz
    ├── 4e3746371530acf08d65f9fc3cc6df46a3e3f6cf.nq.gz
    ├── 4fcabd4cfd99e900325c8a8cac9460ace91e5008.nq.gz
    ├── 507b021708993ec5087bbf9cfe6adf92900821dc.nq.gz
    ├── 50bec63fa20c293ac6e3165ba079a3c934717633.nq.gz
    ├── 50fc12e5a4d061731a0d8c9228096e56377016a7.nq.gz
    ├── 51185bc2eb6f1d0c8cffb35b9d69d1f2bcaaef88.nq.gz
    ├── 51bcb9acf7e4f7ea226d7d9bcd10b4562b827bae.nq.gz
    ├── 51efd0f6affc656e4f0a032c6c8ccb44fbde14be.nq.gz
    ├── 5379fd185b76cd582e3017461662928580d41570.nq.gz
    ├── 539aa35e38d0f474152b8403fd878deb44e98dcf.nq.gz
    ├── 53e18e8972883db67dc5821cc5d45256784550f7.nq.gz
    ├── 5429b4563311e593ab19e67cafabfad310639d82.nq.gz
    ├── 54cdc19d0cab5b4206c9ad4a4b9c7761b2258a09.nq.gz
    ├── 54e287130b8a5a9a07069819d6f57bf2e10a8651.nq.gz
    ├── 54f8dcdc143fc7a397678e9c8b296ceef840f718.nq.gz
    ├── 54fa6666f3f0fd317bc633c973928a18b2392501.nq.gz
    ├── 55d1f8203f3f9eea25051df94ff6bbd43ccf441a.nq.gz
    ├── 57e4aed141b0a0149ea03c8000a9823fe2d19916.nq.gz
    ├── 5830c30ef601bf17f6f52b6ef3892c0fdf082b99.nq.gz
    ├── 58830a0eb418768192ade66d024934ac371ac432.nq.gz
    ├── 58973ec7c95108e5deef2deb2d1ff7721ad3a1ce.nq.gz
    ├── 589ca9d88f5aec15c68eb5f4fb52cd44b937c65f.nq.gz
    ├── 5911edc5087b2e76096f1d0001a933137bee2aed.nq.gz
    ├── 5a6c7b188bba79cafe0ae9adf24a96d3fddfa38d.nq.gz
    ├── 5aca98376a1f7e593ebd9cf41a808512c2135635.nq.gz
    ├── 5bb9eed125eb88253a57362bb19f018ee6a9c0ea.nq.gz
    ├── 5c5d78d75a312a0802580ca765fdb4bc82cef6be.nq.gz
    ├── 5cc94cca4dbba0cd652e63934cac1d60f2b1f7d6.nq.gz
    ├── 5d824895159508f43ed5a2b7141ae61036559cc7.nq.gz
    ├── 5e183a226121117a6478a1f9e499654e6c8c7978.nq.gz
    ├── 5e2ac181064551278a1c6f7664b4b82f63459899.nq.gz
    ├── 5ed5a3a29df849654c9c092b266e5657713c9a3e.nq.gz
    ├── 5fe7ee9813c586ed713b23ba28a002bdcb92e651.nq.gz
    ├── 6147f71d3d287fdedbea0c2c9edc5bfa70b1eb45.nq.gz
    ├── 61c7ef61d1e1ac25ee31639c5eb9f915fd618701.nq.gz
    ├── 632e75af229015b75398a7ad4ac9f424d111ae3f.nq.gz
    ├── 63c85bd45d35f93c62c8e20659335c19a01f5e50.nq.gz
    ├── 662e2cee5634d21333ba9bb3024bd06122b3cf75.nq.gz
    ├── 6687f18233cb0805153f5740bbd33bd800293214.nq.gz
    ├── 66d237684a3407128d69ef452300e8a7629922fa.nq.gz
    ├── 6728b6d79331b0222bb97c70fc8038ed0cc2d710.nq.gz
    ├── 67957d34f9ab18d88910c46a4b8e4f3c806cfb1e.nq.gz
    ├── 6879c624606a7f98e7113cd7010e24c79f67c154.nq.gz
    ├── 6bc6884bf789a8c9ce00e99eaa05f2586cc9e884.nq.gz
    ├── 6c772c20b1d4dd2157ea5bf3ff7ab083e6c7f020.nq.gz
    ├── 6e4155a16456bd8cdd9d6995f3da23d003eaee19.nq.gz
    ├── 6e49c701df2ad1fa1b18f415b540433c90a79a74.nq.gz
    ├── 6e4dae5d670b6cdfd3842dd25623460b98c90798.nq.gz
    ├── 6ed4deb13740b28e6d01c68dc4748fd7e3076675.nq.gz
    ├── 6fd4e4acb1e600fb2fa2b1678e5ae8ae65a4caab.nq.gz
    ├── 7055493cb910ebc0915ff999aeb80a4b8a3e3c9b.nq.gz
    ├── 70b453ad1903b433eba868a3beb23a03fb48c496.nq.gz
    ├── 70bf88e41bcab3cb42f806ef0a01042dfa563db8.nq.gz
    ├── 71b390f8e1c0d348bc77fe3f27e895714ac3d923.nq.gz
    ├── 71f47a959763a0d016ffb36ac932295758b1b452.nq.gz
    ├── 74a9b4593e6f70acfa8422269ab57b7001730f9d.nq.gz
    ├── 7505def029a4529a94155120bf36a7f63674131a.nq.gz
    ├── 77428111b640d34853859bceb262f7ba4745a93f.nq.gz
    ├── 77cd5cbb08d90a8e17f2805f36a49b6e63195c66.nq.gz
    └── 77efaecdf2fab25bf16bef1c8fe2eab78d7bb70e.nq.gz

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

[adafruit/Adafruit_Blinka](https://github.com/adafruit/Adafruit_Blinka)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
