# Repolex Knowledge Graph of kivy/kivy-ios

RDF knowledge graph data for [kivy/kivy-ios](https://github.com/kivy/kivy-ios), parsed by [repolex](https://repolex.ai).

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
rlex download kivy/kivy-ios
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fd363d49eddb5ac06766348738bd89c7d46007f8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fd363d49eddb5ac06766348738bd89c7d46007f8
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c06587a270d156c473620744c5cf1e01da9044.nq.gz
│   ├── 092a8fe4e555c3a76d26f39f05f0be6547027af0.nq.gz
│   ├── 0a3ca07267b0f0af3533587f3900749d4ad8ae7b.nq.gz
│   ├── 0f0e72247b4e77730e1c189258bdd62338c8647d.nq.gz
│   ├── 112030b9b28118b2ecaa852607da0c0fe52c580c.nq.gz
│   ├── 12335e8d9b94518ee98823317935904681e6e33c.nq.gz
│   ├── 123f90a92ab93921ebc16b189e2258c64ec6fefd.nq.gz
│   ├── 12423d766f1a4970a22ec3f0648c393c92da2b09.nq.gz
│   ├── 12d3c841b185b745a2daee9abe7026d1c7330981.nq.gz
│   ├── 131b395116e27fcea87097996ca7882a401ec85e.nq.gz
│   ├── 1325da4901ccfd85cd4b06ff2766f381ab97ebba.nq.gz
│   ├── 163efe1b3323042a210965186047a0cd1f9a785a.nq.gz
│   ├── 179bf83b8d51318992a8a29cef76ebdfad55d584.nq.gz
│   ├── 1a4b61bec111b2e8f6f2731adf48f27f05df7a44.nq.gz
│   ├── 1adf0bde67bc0f288b2cf2198d40db6e226ab546.nq.gz
│   ├── 1b27bdc271c146d637715feea57a3f7e44f9eda7.nq.gz
│   ├── 1c496805c7267cdb8b1b808ce85c5a3b0a57d979.nq.gz
│   ├── 1d86370790ed946fbb7745ba49102f4c889ce25e.nq.gz
│   ├── 1dcf8213fc972ed7c503c35867455d3bafc715e8.nq.gz
│   ├── 1f174f07e1592869edd703a227247854ef608de8.nq.gz
│   ├── 2255b156629a21d98d9534db510581cd82577978.nq.gz
│   ├── 24b5117afe4553dbaa852de1ec363fdf5d23ee73.nq.gz
│   ├── 265032f67a985495bbf79f3c9a085dca8ac1b90e.nq.gz
│   ├── 27c9989f5987447d1bdf04bb8d65d230a7507be1.nq.gz
│   ├── 29cace99ec4800c9c4e6518ddc108c5a2b80f294.nq.gz
│   ├── 29d18faa24b01a0961febdbc549acede3d161a63.nq.gz
│   ├── 2a390ef7145909e02aae10460fe495d744b8d70a.nq.gz
│   ├── 2d46077497cd91b5221d6817f1b95d9493a84afe.nq.gz
│   ├── 2d48ee06da60c1d7e0c04084e08bb3159ee26d58.nq.gz
│   ├── 2e4914f22916075a08783f5ae9bebb049312d01c.nq.gz
│   ├── 33aab2fbb739234d4348d01f863723b05b44f806.nq.gz
│   ├── 37946de312492f82e4a946bee3e0c03206bd6e05.nq.gz
│   ├── 39c5c8b82c3df044193f7668707f6c705c4ce131.nq.gz
│   ├── 3ae849751e41f98a8b602742f128351f1a8636c4.nq.gz
│   ├── 3b0b6b0cd4f28796406bd1ab7ac4d1f1088363c5.nq.gz
│   ├── 3b9a9bc56c6efff7fb94a66fb1baac2c0f29dc10.nq.gz
│   ├── 3e34611ddbdd5361f92e09b637e9b9cc35cd2b4a.nq.gz
│   ├── 3f1ba5ebfdca951b6afc94b515d4d57493c5d889.nq.gz
│   ├── 4140c47dceae6119b2498e797965b320e3a6ca4a.nq.gz
│   ├── 4157b9e31b137e5e9e73e1eaf764019308a932e4.nq.gz
│   ├── 42ce1ffc241397108f47a8f4e28424d22d1c4030.nq.gz
│   ├── 442f324d32dda0ad9ed4b57d7e1083ed51bc2855.nq.gz
│   ├── 45b6789cffa10d91aa1b3feb0a0ebe892fd81f3f.nq.gz
│   ├── 47e7806626259968a09408c121ffe3f6080c3d6e.nq.gz
│   ├── 499af2b33c18e999033cddb431603bd3bb45b1ec.nq.gz
│   ├── 49e0e66eea93632c33f174c4bc75b6abf96f2270.nq.gz
│   ├── 4d32e802cc8b414a4348dcba46bbcd64fe102ea2.nq.gz
│   ├── 4e3506010a8a57901c413ef0dda95c8e0299719a.nq.gz
│   ├── 52c24a28b8b3911a8422580d0edcdadf07233b92.nq.gz
│   ├── 53e499af0b63526f47385a71eb1ad041a79cd51c.nq.gz
│   ├── 546864b4e3b6c499cc59f8713b4d51da68e7644f.nq.gz
│   ├── 5785de5e362cd5328ea1b340cf5eea81fe133d5a.nq.gz
│   ├── 589c88a4a4b1ba6dc4673ce9ee2858ca01f9b827.nq.gz
│   ├── 595dc93aa6bdb8f17bfb7f53cf26ed0491c6a2a4.nq.gz
│   ├── 5a98e22365c2397020eb94d0fbca0e77a56227e7.nq.gz
│   ├── 5afded7c7dbc9581cfb5de26eb1b73c33aa4a6f7.nq.gz
│   ├── 5c6886618f0ad9109ee88c8cec4f0c5de426d5a4.nq.gz
│   ├── 5dcba939408546d26819f362e710a0318f9046ef.nq.gz
│   ├── 5e15bd620d21186f7f55ce798f8c57409a3e0cbb.nq.gz
│   ├── 5ea852bf3d16f3b8c0c05b5ee0cb8f4bc9ebdafb.nq.gz
│   ├── 5ffc71f390d6a8c5b979b3998790edccb95c6e07.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 61d7737191024c55782fca51b4b8272f1745c164.nq.gz
│   ├── 62dd2e00a8b139f3ea18fbbb4ff9f14a6209b537.nq.gz
│   ├── 68b804f11a8c716fb20a9843f663a1cbb26fcf7d.nq.gz
│   ├── 6afc34e215f2c2e66af42c1c8e82deaa2b821eba.nq.gz
│   ├── 6afe98d089112aa55e21e7ac244bfda3ab5ac9a2.nq.gz
│   ├── 6cd2752049823da6ac9560539f77638397dfc04f.nq.gz
│   ├── 6d09a4118b45a78f8e3afe0a76ea8939883725fd.nq.gz
│   ├── 6fb3aa89b6cc1c98c6788ee726f64d3ebd5ab9d0.nq.gz
│   ├── 7556e3885626906e323f7d0f4be6f249d5a53dc7.nq.gz
│   ├── 76a614b813a580c5a58f42b893466c876cc1774d.nq.gz
│   ├── 7b2bb227de84cf71133d814dc0989c924e036166.nq.gz
│   ├── 7b5faec55be53654174df2856bc5f3b09cf52843.nq.gz
│   ├── 7f275b1403b60f8422f1b1b0dd4b99e3430f5eab.nq.gz
│   ├── 81733d66ab8d35320753509bf97b20ae45fea50d.nq.gz
│   ├── 8213a0f18421bd61059cb4b76f8a76359e3dd5ef.nq.gz
│   ├── 826bf1c003275de3c021f473125ed8e72b4a4f08.nq.gz
│   ├── 8340062efb0add4b86a11b21c988aa6031bc68ba.nq.gz
│   ├── 8393219396ba42e8cb4d3c53388f2affd88cd561.nq.gz
│   ├── 8615439d405ba8f8fd17c63771988df32463e058.nq.gz
│   ├── 876b4b8cd22aac190a8a5227c809d7cb8ff4e0e6.nq.gz
│   ├── 89cf4940ba29a84a7ad5986f585d2a65dc641146.nq.gz
│   ├── 8bb1f56e37e8c1ed610c5a02fa56215b368c2702.nq.gz
│   ├── 8f493427d606a29812d23dbc8d9b71894c866df0.nq.gz
│   ├── 8f53e8216e6767f49e96aafcff3d9b0226f9bbc2.nq.gz
│   ├── 8f63b3d8824a562df8d272f5d44b4abd3f495835.nq.gz
│   ├── 8f84e71f131a7d125a248612a83d3d0e3ce5dd09.nq.gz
│   ├── 93a6ae83fb69528634119516d7616a03ac37f66f.nq.gz
│   ├── 93db8cadc6172f3d30e7dea79ec0abeaee506b32.nq.gz
│   ├── 93f46b63fa2a649d6a93a47f164f3f8add95f15f.nq.gz
│   ├── 941b7138d2155506698fc4b800b6af9b980ca1a5.nq.gz
│   ├── 9771a6bacf0e9793b437a3b036f6754189b3a424.nq.gz
│   ├── 9bf85e3ea461601e440214969d9d8674afdedcec.nq.gz
│   ├── 9e53ceb19ce457490f40a4ea16affa3d5978b290.nq.gz
│   ├── 9f8411370c12361784535494daa5aa19da3b31ee.nq.gz
│   ├── a2a7a145f0b7b0afe4218e06596698dc6ea23af8.nq.gz
│   ├── a7fbbd238d92687f3dbebdc90f461e623457404a.nq.gz
│   ├── a9a9299290aecf262b98d3bedfe86be3ad290e82.nq.gz
│   ├── ad0100e68fcf44f886bd6de8eba3507f75d6ccc3.nq.gz
│   ├── ad9b3717a4e37d0b01b2ee9f4a7f124c3013e9d8.nq.gz
│   ├── b187af4e4e7363e18e797e8f9e906fb16b6e44c6.nq.gz
│   ├── b26d31ea5fe95df5d517fdc1d2f3f3d5c2db363c.nq.gz
│   ├── b34d87c7e2c4204073f5cda9b78adcc37562d283.nq.gz
│   ├── b434e20fdd7cb106474b2c3bfff3b8057cd04329.nq.gz
│   ├── b6d133817b9bbfb8a4f51d4634446930d0396301.nq.gz
│   ├── ba7ac805a2683cd9f689d19de423985334e06a15.nq.gz
│   ├── be4c35793003af0e3cc3941cc289a65d8427da7f.nq.gz
│   ├── c0cea074670be0e58c8d04578857f455469f6416.nq.gz
│   ├── c31b7baff1a565d9054fbb94ebb6d85704f5d4b1.nq.gz
│   ├── c776cd68b54c89b04a894a42edfd337a40188f4e.nq.gz
│   ├── c981f0b7854d237467c4e6f4bc491f430a2fa09f.nq.gz
│   ├── ccf92d2cce5667f8109b55db520ad528a341e750.nq.gz
│   ├── cd499182a0f6bcf39bd8e111c965065879f33aaf.nq.gz
│   ├── d19fff55e0a02ba76870c2f82ebec42c0f727127.nq.gz
│   ├── d28f12f570ab4b2c043036a9f81f4dbfc66c78ad.nq.gz
│   ├── d52b403650a851395a0813829af780702644f201.nq.gz
│   ├── d52dd53b9eafd8c2eaeedba52537c262ada8d9b2.nq.gz
│   ├── d8f1caf5f825b0a9dee330814fc1bc04a8b11367.nq.gz
│   ├── d99e271319f80b7c904d6d3782bf67beb070a7ea.nq.gz
│   ├── da0643ac29dea980c7559f2c223e47d5f75d1560.nq.gz
│   ├── da31168085696af9fe1a3d8b6496cd915f2a977e.nq.gz
│   ├── da95efe4b8db26b8314833694741b319e30bcabf.nq.gz
│   ├── dcd93829f8d28c104b04b674d93d18022c502c85.nq.gz
│   ├── df5ef288dccf0c2beacbfce6f1af69b19c866b24.nq.gz
│   ├── e4c389714e1a7ef917c295799dbb68609a36824b.nq.gz
│   ├── e561cefedb9e57a79792c198ecb937cd68464073.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7aab4bb0343c3c8ec2e0c99d10bfd8c44c4318e.nq.gz
│   ├── e8861c73d0e07daf57acfa4b0b03112142215bc5.nq.gz
│   ├── ed860888b7bba6edbd42096c90922fb1e2c78291.nq.gz
│   ├── efe06231972927750156520acd374bfe619188b4.nq.gz
│   ├── f00865d63103b4ecd4d36035af0b673be1996bf3.nq.gz
│   ├── f087222fbca2c11f8188079c235ca999f2acabb6.nq.gz
│   ├── f40486cec7f5db2789ed3603f1e676c1942db391.nq.gz
│   ├── f5e9f45eb7b570da66e83ec7503b7552f62fe133.nq.gz
│   ├── faf863ec4fe88991ec941e71e49fa61428899892.nq.gz
│   ├── fc814b57a7d512bb96b8b72a4a066e10ba338160.nq.gz
│   ├── fcc9cbef67e0a069df25ea64939561096e5aa1b0.nq.gz
│   ├── fd30c97c8a38a6cf32b73305c9d2d90bcf453001.nq.gz
│   ├── fd3cb9ef17837e2b77d35a0de083801473032691.nq.gz
│   ├── fdb4214d12613ae2467a3353d9ead47e498eff25.nq.gz
│   ├── feab3aa6fc1549d7e1feec1ce9fd89e0ca55a1c1.nq.gz
│   └── fefa40d5f6188617cfc008b6ba9f0e8ea46c725d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fd363d49eddb5ac06766348738bd89c7d46007f8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 152 files
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

[kivy/kivy-ios](https://github.com/kivy/kivy-ios)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
