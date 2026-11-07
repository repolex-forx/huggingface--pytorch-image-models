# Repolex Knowledge Graph of huggingface/pytorch-image-models

RDF knowledge graph data for [huggingface/pytorch-image-models](https://github.com/huggingface/pytorch-image-models), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/pytorch-image-models
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 43b549bfe9d680bc94284cfd0b611152d18e97d7
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── 43b549bfe9d680bc94284cfd0b611152d18e97d7
│           └── chunk-001.nq.gz
└── blob
    ├── 000eac61e777197ab3e80a266a232181e923e2a7.nq.gz
    ├── 01b8113dfdb83170d6e2d0b34d2979fa480c8a55.nq.gz
    ├── 02108b32139423729aaee69cead12e53c7f0b781.nq.gz
    ├── 029b9217d3afb4df99866e368028592d305606be.nq.gz
    ├── 0368f87b7090f2578d73a2a1e28016f9d8664a18.nq.gz
    ├── 04654a1b2a9d45037b734dc46bc405dd77060ea3.nq.gz
    ├── 046fe9a544998324e5448030610322af4b9fea74.nq.gz
    ├── 0561374dd4ff8f2f97f62733711ee736d61d711c.nq.gz
    ├── 0647004aaa5f5e5cc098a658570fb4d6c79c9176.nq.gz
    ├── 0754164169796ffa3783388b4c7426ab42bce471.nq.gz
    ├── 075f03e59daeb4bca6db4145b0106b43e41eb14f.nq.gz
    ├── 076b29c6309c3cd6955bf9d69e5a7e74ffdecbdb.nq.gz
    ├── 0778c8cd4a54f4f217dfa1277762e09407d326fd.nq.gz
    ├── 07f4cbaf95453c180860748568f17c2165e9194f.nq.gz
    ├── 0821be7fce9b6485f1cf01c9aabf7ded03d552be.nq.gz
    ├── 08dc9f5e9c9811ad90ec2cdea24e6cb1d5a8578f.nq.gz
    ├── 0972b527612b283fd242cc5eaeb6e767ea106c66.nq.gz
    ├── 0a4cf875c5b91272d3f9c7452d86aa4ecf1b7d25.nq.gz
    ├── 0a57b4c9a2371864e02873cb6535b0525b47b2c2.nq.gz
    ├── 0ae3e0889deee7e53f90f7cce073b61385166390.nq.gz
    ├── 0c64168ab4e053c11fbfa1dfdbd676b347ec4bf9.nq.gz
    ├── 0c950b6a365a6ed6bee2563fe3084294c7930004.nq.gz
    ├── 0cc45a63d7e4232068f9c8e69bfc7365f83d81fa.nq.gz
    ├── 0e8f3363da191729b5e4002fb3ea9fac1dc8624f.nq.gz
    ├── 0f54d25f893a0482720c8df66ef7ebe9455da732.nq.gz
    ├── 0fca95f054edb8ae85147b7e6929ffdfb3e3ed96.nq.gz
    ├── 101d01966cb0d3b34aee2d31b8359845aec85383.nq.gz
    ├── 10f16ac38031a20aaff78e08500e29471934cc76.nq.gz
    ├── 11b79e8761394cc01398a7138ab8c07c86c34b65.nq.gz
    ├── 125cdbaed1ec9dd3def7b375676e7cc643a348c6.nq.gz
    ├── 126a38d9262209cf36687c04c33f899280dfb6fc.nq.gz
    ├── 12c05e6b11fed863b5fad9f3422f390299ab715f.nq.gz
    ├── 138728814a5bc0b61b05105e3af2954b02f37ab0.nq.gz
    ├── 13ab3b091d83823878ae97e936a06d06727276dd.nq.gz
    ├── 143c3aeda8f95f40e52f1a425a517b4bea0fae24.nq.gz
    ├── 14af39b747eeb28a8cb969a6767e3fc6fad01c26.nq.gz
    ├── 151743c9669f689fe4f43dac8843b48d85160238.nq.gz
    ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
    ├── 164cf1bb2f887dca81f7e0010ae5eeff1b816a2a.nq.gz
    ├── 169fb82d905d264b4ac938c4d9c2dd03937dad4c.nq.gz
    ├── 16b024a358bddffde258a61dd2e39cafec3e6c71.nq.gz
    ├── 16b4e156357ef16e04820f9622e293a3c8e59843.nq.gz
    ├── 16d4ee184b5532d19626fe1381dd64a5a88b1c23.nq.gz
    ├── 1705eea9b64a86e1b3ad2f5952126c1fac6991e3.nq.gz
    ├── 17194cbbb82cba5ce7d7af25a5f46b1e1262b8e0.nq.gz
    ├── 175a7324bb440e4339f1ee33f5c3dc292cae4d5d.nq.gz
    ├── 178cfa9bd591774258bd239fa1353728008fbeb3.nq.gz
    ├── 17e8d77cf454c22c13265d085c7685762ae1b2ac.nq.gz
    ├── 18940850d32aa8e58d7827f2bcebbfe4d732af3a.nq.gz
    ├── 1895b1d33aea654f39ce1bba9eda8eba50dd0983.nq.gz
    ├── 19b3f2cac0bbe0f65f4e3cbd262bf442b52ec5fc.nq.gz
    ├── 1a15186ca94f4835ba1750a4b28e39b68a9a3c61.nq.gz
    ├── 1a1ca5a4143c4145ea28997def2e46e6065b23c7.nq.gz
    ├── 1a3f01580f932a58943ffd8e37cf83f2026e42d3.nq.gz
    ├── 1a532819017d2c316efd5928a04d32b2c4dfde19.nq.gz
    ├── 1b70de6e5489d2d7517ce3d5b3ee0f8134707491.nq.gz
    ├── 1b9cb9cbb723f595727e233ec055b3f372346ddc.nq.gz
    ├── 1bd149fa7b66715e46e9ed75a99500dad81c92cc.nq.gz
    ├── 1c42c24b7b9cc3120e972159af055780c2526de6.nq.gz
    ├── 1ca28a2e01d857500edb3aa1598aaa71477411f3.nq.gz
    ├── 1cc6fb366365b85c5eb56b8c40fc7c1f748d6cb9.nq.gz
    ├── 1d4898d89052c73f5021716149e014c796df0a22.nq.gz
    ├── 1dee5f86a2e40d3582001fdba1c49b6d61a4e31b.nq.gz
    ├── 1e2a947b88c672526f7d96b10e2fbb73540ef824.nq.gz
    ├── 1e37d1aed851a1fb503da12acc8e9fe06cdfdfcf.nq.gz
    ├── 1e449de9aed6761f0b1575181a7c7a86f7bd537a.nq.gz
    ├── 1f232707fa14e65535d79250ffa030461d469b35.nq.gz
    ├── 1f7b59a0054e7a2fda15a23ca2437b4cb9f179a4.nq.gz
    ├── 20216741018bd4fc96c29ea25bf241dae7a45fc3.nq.gz
    ├── 20f1b319a54ff2f9017fe4bbfb8a053a995f83fc.nq.gz
    ├── 230da12b84e25f3da3fe54cc787912d37e418daa.nq.gz
    ├── 24ea42c27485c2226d6ab6f87de3fdb8ea6adaca.nq.gz
    ├── 256d9e5aae22914d9cf833b77bd6fb9c5be04a3d.nq.gz
    ├── 2589b2f9dd3f0d1e02e1d5ddc1fbcd5c143e02c6.nq.gz
    ├── 258c2abd446e75a02f09d7f68f840a06a3c6986e.nq.gz
    ├── 258f1ab238c9623c6b033f184f98f88221bd3b14.nq.gz
    ├── 25b1ab7dd11eb3d6ea1f02e1e31aeb5f6dcc42d9.nq.gz
    ├── 25b4802f945fce5853f796c893c11498eac12583.nq.gz
    ├── 267d3e8f1708650051abd160e4ae251fc16bdb31.nq.gz
    ├── 26d239959dd83f7fa59c1c2224bfee330ec73258.nq.gz
    ├── 26f53bf1e336f4a3a3d4fffec3da1f73e9053163.nq.gz
    ├── 278799030f7f6bdc9d1756ceb0aab3ea11dd20ab.nq.gz
    ├── 279a82abf607f6401adca0b6cf9d0364527ade0c.nq.gz
    ├── 27e2d209b545f0f61d1c2fdc2286b16c5cd3217b.nq.gz
    ├── 284b4e7ca1fdf6ace57d53b79405da07c76c2e2c.nq.gz
    ├── 2956bb1dd797270b5524e4a303ef36adb7727065.nq.gz
    ├── 2a92188fbddc1d77111a4356554b47229145c5db.nq.gz
    ├── 2b53ca690b9dfca69d3e824f5cc5b9d4731201ac.nq.gz
    ├── 2b884d5ea2968dafa9bb0545cd243b64b6f25cef.nq.gz
    ├── 2bbaf5beae911d60f9d2bfea95ea21cce337dd44.nq.gz
    ├── 2d3afbd0b3e99d163daab6d9e50a97bd67826b5d.nq.gz
    ├── 2dbd8558e1c4cf87dfe0aae29be7106230ef27bc.nq.gz
    ├── 2e1d600ab1f3eaabc566f4dc3fafc658d7c50039.nq.gz
    ├── 2e9bd0a0bcb6a9e1beb057d48fd8aca688bb4079.nq.gz
    ├── 2f3a6912e9ab05915139926f3c258286190440b6.nq.gz
    ├── 2f77e919cdc5d76d29bfc56dbc96e814aee0dc9a.nq.gz
    ├── 2f7a88a776d9ba6888f0aed1d1213d7629df4f08.nq.gz
    ├── 2fa3eedf8fe34e7759e6a70dc8fd2e41dfc3ba96.nq.gz
    ├── 303b022bb2123225227bee7917b9238876f05cf1.nq.gz
    ├── 3079f0058ebcfba7d628da20cd561408b86136d7.nq.gz
    ├── 30d5fad3a2344725aa02351d8fd3746698a8f190.nq.gz
    ├── 32238d84c743c96a8ca1867f881981548006d760.nq.gz
    ├── 323a48c73c7e099c8fdc2b45645d09e2beb95c18.nq.gz
    ├── 333d11a49fbd22a252c36d41d682773ecc6e131b.nq.gz
    ├── 33723baf489f210b1b79a8e9e033311fc016630b.nq.gz
    ├── 33fff6a427f28aba99e6af8f1ae596db80d025de.nq.gz
    ├── 34094225262c4d115aa5b0b411f0092ed394fdc0.nq.gz
    ├── 34fc6f3d451d56530465f036d1589b9f503fe334.nq.gz
    ├── 35169c95ea0205fb61ed7f0824b6b79a7319f494.nq.gz
    ├── 36105c9ca48eaa672f1cb98dbfb963391d3d409e.nq.gz
    ├── 369349d8bb3b1142cff3d067c988bf382365d11a.nq.gz
    ├── 374d807483d5df7ccf6d4fc08e2c63b6659f5dc8.nq.gz
    ├── 37d2b7547fc9216fba28199c02657000ebf82393.nq.gz
    ├── 38fe3380b067ea0b275c45ffd689afdeb4598f3c.nq.gz
    ├── 39049dce66659310fb032f585f695a4804e8242d.nq.gz
    ├── 39117f0e5ecb61cba6b57ab77709d028538b9b3f.nq.gz
    ├── 39172aca883d58f416b48b7f3ccf8d79a3565bd7.nq.gz
    ├── 395d9c2796d3403e30202b2cdce6fa32e75469f3.nq.gz
    ├── 3b835892951abf0fecd5722729f9da71d605ab54.nq.gz
    ├── 3c31a1a9cb299975827f3163561fd7ca4c88ee52.nq.gz
    ├── 3c3c570b635c5963cac25a6b9ecc0ae00bb85ec6.nq.gz
    ├── 3c5a70d07aadfe220f450cb3a517554b4229258d.nq.gz
    ├── 3d6b92b8605fbf9087db5c963ec1bfe5b79848b7.nq.gz
    ├── 3e02a2f7cfece82d8329f02c2ebe1be1039d3c27.nq.gz
    ├── 3e199c0abc738f87490f1ac918957e05bf425fa4.nq.gz
    ├── 3e6c46e1943a93036e3fc6fc9ed0d2407dd50e7c.nq.gz
    ├── 3f52c6cc2e7230813abedda4881da927980443ed.nq.gz
    ├── 3f75401bdef9a938680c37db88a64bef442ee0a4.nq.gz
    ├── 3f924cf91a0090f2a8527169191cfbf664696e39.nq.gz
    ├── 3fa5c2cbef536c76414be2a00be2c9175e327a31.nq.gz
    ├── 400f0ef4113575c33c582a6256ced96e8fd64cda.nq.gz
    ├── 40aa98768951fd69bbe9c2900e94acc362a02027.nq.gz
    ├── 40c550cd02e6c49b1eaef818736b3bddcc540d44.nq.gz
    ├── 40e24a78d6b462772b6d95cf3cc15cbf54795850.nq.gz
    ├── 40e8f5550b2655dbbba0f96431458a89998f146c.nq.gz
    ├── 411563c1ccae85ed62ed26ec79cf50d37aea36e3.nq.gz
    ├── 41a021381f5e2e6d3205ff88308a280ca749876d.nq.gz
    ├── 41ed8e399cd2283e4fd78af742af889d2b970f03.nq.gz
    ├── 4336819097f8777b9ca64ebe49bc0bc77ae3c5f5.nq.gz
    ├── 43c994c2d3617f947bcb5adf1933e21dabe46bb5.nq.gz
    ├── 45c85aabd00ca5ebf7bd6fa85c674570fe60f9c8.nq.gz
    ├── 4689c11e1a302b4ffaba6e03bab043a5884511a3.nq.gz
    ├── 46d77d317f46ca9339b374abb75483107c3fa39f.nq.gz
    ├── 46dccacc9c772975114bb469d2b643208850d144.nq.gz
    ├── 46dff17f742a80a01d4d665deb3e610c5b20595e.nq.gz
    ├── 46f6150bcb0cbe04b8eabc524283f4e9ce60a3a0.nq.gz
    ├── 478a285eba8c43f77a65df5e72ad2bfda7093383.nq.gz
    ├── 487c0f1c51bd5975f94d2c346be749fdb9cb4f47.nq.gz
    ├── 489781736de08e5cf40bf76528a735fff4a3f61c.nq.gz
    ├── 49ce29edd899b2728d4f1a216a09af64604ebdc1.nq.gz
    ├── 4b85d747cb1c6ed33dfdbe76d3e0d4fd1191e36d.nq.gz
    ├── 4b9305ebe36afbec5758a860388354146adcee0e.nq.gz
    ├── 4bac240333476e2306bf793de38470ce4622541a.nq.gz
    ├── 4bba590def2d46c315a7430001b511c92f05009a.nq.gz
    ├── 4d19b3f9146b71f79c8f55a5e4768b7f84897b8c.nq.gz
    ├── 4d4eace758b019b333cc56bd6a6684e2f4b91ee1.nq.gz
    ├── 4d8dc9656f5dd45ebd6c789f7e498ba1f9323297.nq.gz
    ├── 4de164ab8ee2379c5338d4cc1444bf82d63aeb20.nq.gz
    ├── 4f06054d098f83e12a69fd78deb223d7e84b80d5.nq.gz
    ├── 4f73d9bf3d3bc9a5be2a4bb4da80436ba8da8f4f.nq.gz
    ├── 503e1df9c2d6ed1d03b1504cb28bce2bd5eb1a58.nq.gz
    ├── 50794a017f335e2f515d2aa6e1daf5535a820e59.nq.gz
    ├── 50be9c8a8d36f40596a8866bb6d27bc8df300ecc.nq.gz
    ├── 51b4b07252c969b8b9a7f6082fa738514bd389e3.nq.gz
    ├── 529b7ef4037cdd9c5b925efaeee072aeb4124675.nq.gz
    ├── 536273c4b385650beafb88fbb66820977ec4e5b1.nq.gz
    ├── 538d26f6b2f04efa4a6636a85f69c3312928b3c6.nq.gz
    ├── 53d09c1ab9a0ddbdbdf3abd6c3ccfa8ef5264e38.nq.gz
    ├── 543d46ca2a2bdce2e0df738577ed0be9194d0355.nq.gz
    ├── 55238fe873d93666468e3fb7b255f2280effde15.nq.gz
    ├── 55b106b0c4098bc447acb110592c2b24123fbd27.nq.gz
    ├── 560e9b970c65a975cb6c9ece4c9790b3045f1cb6.nq.gz
    ├── 590f8a7e8862f668000cf2a9712977c995968599.nq.gz
    ├── 5976cfefe0c24becec069b685b897fae807a0a97.nq.gz
    ├── 59bad95d2bdb4dd1f1c5f148de9d9a780f99f488.nq.gz
    ├── 5a02a0f7ab54f635d0dee84cd3e702300dccf50e.nq.gz
    ├── 5aae7aef51564daf6762d758ea533f2a35820c89.nq.gz
    ├── 5b0c2843878f53b208d8e63535a912301df20335.nq.gz
    ├── 5b68a91e0c471f62af0b46c3bc98e7922b3dff66.nq.gz
    ├── 5bf6d19e7cd7a1e2f8f51270fbf1bede9e8aec6a.nq.gz
    ├── 5cb603dee615ab83bf6b0dbc4e2489ed432d9dad.nq.gz
    ├── 5d4427bd440e42294d9b746744a7a03898a64912.nq.gz
    ├── 5e4aee34028d5e1ad033a868c66512c74baf341b.nq.gz
    ├── 5ec8834d231fc40aba1fb85a2ace5b399c5cacc5.nq.gz
    ├── 5f2f36443927181ed48b2bdebc24889fea92ff94.nq.gz
    ├── 5fdfb077106d7026828e56447805d13101c7a7da.nq.gz
    ├── 6050511813b872999486abdc23f5d4a3f0f7fa54.nq.gz
    ├── 6051f26dd10bdd6013eed001379b299f1d6581a2.nq.gz
    ├── 614433919818a6ef3a998c74d6727db44d62e8a8.nq.gz
    ├── 63e4e6492800b7fd2aaf72d9db88ac0eae23c63a.nq.gz
    ├── 661cf2ca479eff2597c8e2bfd9a577549d479e81.nq.gz
    ├── 661e4414e67aa745bba93555051fb6ea605d4400.nq.gz
    ├── 66d880040d980ba8b08dbe98d8aa03a0c2ab1a2b.nq.gz
    ├── 6871454df66dba037e930125de6e81c758a80c66.nq.gz
    ├── 695d5693176ebc8c2f6c66a7a95de2e8bc09723b.nq.gz
    ├── 69e30127816ae7a5a28d94bc2bc41f2192e68023.nq.gz
    └── 6b2061ea7540501fd577bf15d92067ea7b35b4d4.nq.gz

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

[huggingface/pytorch-image-models](https://github.com/huggingface/pytorch-image-models)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
