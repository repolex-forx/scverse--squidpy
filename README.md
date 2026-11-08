# Repolex Knowledge Graph of scverse/squidpy

RDF knowledge graph data for [scverse/squidpy](https://github.com/scverse/squidpy), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/squidpy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7123a38b0db38966ed05898b2d9961eeb9071427
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7123a38b0db38966ed05898b2d9961eeb9071427
│           └── chunk-001.nq.gz
└── blob
    ├── 016369f97e961c68a2bf9173f8f6b68bc853323d.nq.gz
    ├── 01866fec2475704264fcb8ab691eb26b492e2182.nq.gz
    ├── 04c00f56ebeb4464c3a0a1d55eac297f160db33d.nq.gz
    ├── 056031d7e0fc711b8d89030a80c89a3ce0698e7a.nq.gz
    ├── 0a87862881a8f31d0b445bf15f645e1df08e9e64.nq.gz
    ├── 0b76a01105ec57b7e7a25d540ed4b5b850fcea1f.nq.gz
    ├── 0cb9fc00352d61c7462920a5f23ca9a4432cb93e.nq.gz
    ├── 0d1cf123676b075110d82843cc9344e7b9a94f36.nq.gz
    ├── 0d93dbf354734fee79b804a047b0b3eeb216b9c6.nq.gz
    ├── 0dace8aecab540da02804fb1f635f605194df359.nq.gz
    ├── 0daf62436bcfc630b1b9fe8310486eb0920b9455.nq.gz
    ├── 0e1d5ee6992e87eb79457abe552da7656b4ae5a2.nq.gz
    ├── 0e2c1ac291890017ae572e74389ce94c84c23454.nq.gz
    ├── 0ea3b15853098d041b34e34b10341b04173360ce.nq.gz
    ├── 0ee26f591a1539c21683ad228ca812ead92822e4.nq.gz
    ├── 114ceb7c21b433326d6592acb9c52768490b9012.nq.gz
    ├── 138dec65438af680e67717bb979f843b36d950a8.nq.gz
    ├── 13b15293b96fced9bc92ab82dc3a5abf52a59b4f.nq.gz
    ├── 13d63d0b9a2b5b946bf95f67c2222987b855bb71.nq.gz
    ├── 15226c41e67416b2e103a08780e4397b57ed3f79.nq.gz
    ├── 152a7e9d3da81d2be0e35aa3272ca7cdbf204456.nq.gz
    ├── 1579143a22b4f5c5c771ef2383d6ca373adf4b87.nq.gz
    ├── 17a0af2cc9b93ca79c623e3bf045eceb47f38348.nq.gz
    ├── 1a345a57c22b0d3fba33ee48ac2db7d3f780ce31.nq.gz
    ├── 1a6bfa27cc411008bad1cf854f0738d1d7564f8e.nq.gz
    ├── 1a77fb453c9ddaab336a5aaa6c44e766900d6431.nq.gz
    ├── 1a95f7c71a031ac121692ea7d65fa93c7355439e.nq.gz
    ├── 1bf59e81653817384fbd132e7d52e1f9fdd20ab9.nq.gz
    ├── 1da01d84f9b99a024e8a3a8cec66fe94d9220fdf.nq.gz
    ├── 1e6b865babc5d7a5adccb82524a16b58745ec2c7.nq.gz
    ├── 1f91ffd7ff279483a692d8a56e5b85c0ae54585d.nq.gz
    ├── 1fb306de3db656a50f4c07fbcf7d462d0248178a.nq.gz
    ├── 2003442e2d1851b9dca8664b7446a68931769b1b.nq.gz
    ├── 20a1e69ae78c8a85adbb5cd19e3ca016d475dbaf.nq.gz
    ├── 2299b573765e2f9e367f62e1bd09fda1d3f76c7f.nq.gz
    ├── 236335fdddc295a884044528e69ba7fd1e8f3f12.nq.gz
    ├── 2401abb24c84838cf3cbf0bf518d27b8566b0f0f.nq.gz
    ├── 258907ce422d209f2c625757b6c3f60dfe8543bd.nq.gz
    ├── 2657bb41a09faf63b6e36616ee9c983e6429fdc4.nq.gz
    ├── 296f322b0ef7fd9853445f26eccfe220eaed0978.nq.gz
    ├── 2976077d8f1025a42df47d47e722e5ff4087cb5f.nq.gz
    ├── 2b1072f48d1828cfc171a89d8cbc9d633db0c4bb.nq.gz
    ├── 2c87ea2aa9280f727b70cb92e12568ed7f545c0f.nq.gz
    ├── 2d5809c57240ed3f2c151020c48330bda61d9659.nq.gz
    ├── 2df5488501bb485497c6345ac9360ba27ba72887.nq.gz
    ├── 30401fd366afda86d29fb0ce902e97b67b9a8fd7.nq.gz
    ├── 313ff7364d4fe40d002768346b18e42dfed884ea.nq.gz
    ├── 31e4685416880933d762c8088aed4c7a10d6392a.nq.gz
    ├── 322793040792b8440f6bb6db6e29660b8e54b266.nq.gz
    ├── 32e974359e99287d1de3be9ddd4e42fde850e9b5.nq.gz
    ├── 346dc6d15e9a55c611ea74b1906a50d24fc853c9.nq.gz
    ├── 34bd061f90f7b28e011b63a28086dd66cbb9fadb.nq.gz
    ├── 35c22b21cf23d36ec3b1603c27df47fbc7c9c57f.nq.gz
    ├── 35da6ecb203d764d6d352af1aefeb71162435129.nq.gz
    ├── 369494f019f7f016c4824cb3bdde6909d1cd0b5d.nq.gz
    ├── 389efae05a77e02c070f00294fd7a9af60a34519.nq.gz
    ├── 3a0436a84f0fc153e740fc653eb2fd6eb55abbf3.nq.gz
    ├── 3b5a15f69bb65fd0f8d578f6f2972ed9dcacc076.nq.gz
    ├── 3bd22e102747913f060160f86f066ee885110f0a.nq.gz
    ├── 3bd508a45d4da935690e093232b0615e9fefd699.nq.gz
    ├── 3c2cd8554d48cf5344f93959317238c01921c648.nq.gz
    ├── 3c5b1f537999399c04e4e9ad59d64190f3b331df.nq.gz
    ├── 3ca1ccbde64b29fe7bb02ed810bc0e67907f7ca4.nq.gz
    ├── 3cb1c473d7e50c3565783d7657cbbbf0320319ed.nq.gz
    ├── 3d14e8ebd328cbb55b967af5d6e0cae9c4a89378.nq.gz
    ├── 3d8d00fa1267fa1057954e956f383139e09a934b.nq.gz
    ├── 3dd670b00748aff68a084080389f91d8821c939d.nq.gz
    ├── 3e71af3dd19d2398f4990391f9627022e8fcd949.nq.gz
    ├── 3fe9858d79f2c46b3569e63f351f1b399c31784a.nq.gz
    ├── 401bb523ec61208bf5cae292de4dbeb7f7c807a7.nq.gz
    ├── 4039d27765795652880ec5cb575a95998231731b.nq.gz
    ├── 406f5dc6f3bdba28ab15764cf23eeb0a6cda9ae8.nq.gz
    ├── 41448693a3e0e1f459384148c1f36936343d368a.nq.gz
    ├── 4193896c4cd0a55c6c161d599665ac095859f7ab.nq.gz
    ├── 419ee039f6a5a9f3d4cace77a16a3f54333b15b6.nq.gz
    ├── 41c1b2f16d802b8b6b55f5b29b430f32a53548a3.nq.gz
    ├── 4334bcee1f62b4bfe368fcac9c291ff54d41dbbd.nq.gz
    ├── 43864851c380823dfcb1d2d425974f525eb04f10.nq.gz
    ├── 43c13c29076663e6c579b4e1af5e4c90868728e2.nq.gz
    ├── 45dcd551d402e434ba5947cb57a974e33ab40cca.nq.gz
    ├── 45e2837ad9c78680575d7d0b09291b4f864b0fee.nq.gz
    ├── 460b9d421f20e725f8a9b1be70e3b86d3942e4c0.nq.gz
    ├── 465772cd2ec5308242fa4636e389921ac4115afd.nq.gz
    ├── 466d65845652ae9755a512bd2c53d6d415d58071.nq.gz
    ├── 467e35a67187ba3986ae2053066edbd698a63356.nq.gz
    ├── 476ea172760524829d830ad7fe83564f6ef461ea.nq.gz
    ├── 4818e5c2e4516adc99c871e86ee6754d443f5afa.nq.gz
    ├── 482d2445d59c93d0572bfde682591580e59911f0.nq.gz
    ├── 4b5c3fc386ffe285ea9fdca11d39ea3e2eb7be55.nq.gz
    ├── 4b84b2814b08c7253c3dae3decba5c988aa60282.nq.gz
    ├── 4bb28bdfdd3cada4ec0ac835b2f75b3aae908b82.nq.gz
    ├── 4d0938745f85fc426f0090310e58f00ee02eb8f0.nq.gz
    ├── 4d2f75571b96bb500d6ebbc0bf039a4cedef5ddf.nq.gz
    ├── 4dceea346916b6d226d764f958a719371acf0f88.nq.gz
    ├── 4f1365c695534410ff2ce45f36da23e3b466e3bd.nq.gz
    ├── 4f214197b414c35b3e9f5d870d87a6a0080a617e.nq.gz
    ├── 5183d5b7948d2c450ab4c765473baf51535f4c48.nq.gz
    ├── 520ab38eb0ad0a0331d44db5248440b47ddc3300.nq.gz
    ├── 53d05211e907c2b9700a63a53e197d235925dd19.nq.gz
    ├── 55861f3c549e051d0095f51498f632ab511dca86.nq.gz
    ├── 55ae52f1bf6d1b1aa0cb703a5fdf14fd027c4ac1.nq.gz
    ├── 55d849fbc0bd58db3edbca2c5e76491416b9a828.nq.gz
    ├── 56affb7011902d1bee5eacb03be11d3de9ef534a.nq.gz
    ├── 56e4d5c52f2eda8f01580abac376978f5d035f22.nq.gz
    ├── 57466fc612ba40189f3a6e49a616b51d0a8cfb21.nq.gz
    ├── 5a5a3c78a0d6f53f3b2eda2effd6c4a8c142458a.nq.gz
    ├── 5b62547f9aef3da3a38806baf365ea8c059675d6.nq.gz
    ├── 5d60d6f564d031ebcc73552ce235f437504c498c.nq.gz
    ├── 5df02f0977b1babebd9c77c3f7e0a057fbbade7b.nq.gz
    ├── 5ef88860674ce2ffef6fc397ffd6a28d4911c9c9.nq.gz
    ├── 5fbfd031ff36612da0135141fee5c732c7eac2b5.nq.gz
    ├── 5fd68a9e0beb06bbdb2fdedab9ec734c3cd3ac90.nq.gz
    ├── 614700d5941dac81b8a18342e8e1e3f5d87934bb.nq.gz
    ├── 615cb45c3cb42076d59f30fdf2594b26b3e2fd5d.nq.gz
    ├── 6162f944971bcf6d37a108af0e616e0a59bc9efd.nq.gz
    ├── 62988dc6905e7cb693fbc098f1c6bfb1090ad324.nq.gz
    ├── 63a810ee193bf1db765db302a4e38d0b729ad1dd.nq.gz
    ├── 64a8a9970b3dfb8477eaa234f68a077b6fec9c25.nq.gz
    ├── 65c0f3df1dd0a8bc90c1b0b5c7bc66a1d9ab2ad3.nq.gz
    ├── 66b374db7f9e1dbf3469fbc61899a4778bc92826.nq.gz
    ├── 67180e3419deaf7e62a03a1ff4244c109bff914a.nq.gz
    ├── 6854298d2f9bb851c1410eecf9c5d683a7268d3a.nq.gz
    ├── 687f83796732230e97221f5d3760fa3bcd81cd04.nq.gz
    ├── 688a66cd7891f463f50cb38bcba60098f6e30a7e.nq.gz
    ├── 68ed309e4a7df78de2e199f446d8704904278807.nq.gz
    ├── 69559a9469ecc0de6a7781fe2f37a7ced05d7abf.nq.gz
    ├── 699bfc08e7559e169b42357dc7e7157a0b05ede2.nq.gz
    ├── 6bd3c82d2dbc8bcae885af95b1765dd2bcbb4c64.nq.gz
    ├── 6c37ded96ddc8d94b951ebf4c35d35b082bbe721.nq.gz
    ├── 6c680d4c73b25c7c833736f71823987688da82f1.nq.gz
    ├── 6ce12c337f6247fe016cbe2323cdc169eeb855a8.nq.gz
    ├── 6d0bcfe4167466d5012a4da4386d73c3b150f750.nq.gz
    ├── 6d37dcd709f7edd24890bed859f3d4bacb15b235.nq.gz
    ├── 6d5abe98c6cb6e34df3405c362c7b3ebcad12cd1.nq.gz
    ├── 6ea67170944450966f664760b8a1d6b29155edb4.nq.gz
    ├── 703975fec4f1f26f0c1a7d2266acdc4d65e7d87c.nq.gz
    ├── 71703120b075a9cc36580ff051570ce9bf7ea6c9.nq.gz
    ├── 719a970a66ab2d19bd6f8ad57d528b5136183517.nq.gz
    ├── 71ab0bc8fcde6b8bf63218c24eed084ce0cf95bd.nq.gz
    ├── 720bb1a54dbc0ae337f0c392cb253971e37b65ff.nq.gz
    ├── 72a54b7d8414d352736cacb615886fd4bc969676.nq.gz
    ├── 7420b144fb10c0061d966ee9a353bd87a5009514.nq.gz
    ├── 75b3c25e45444a9ace183d73668386909e83f1a4.nq.gz
    ├── 780eacf0aa27eb573d0d72a10fa4f2c88a7866d3.nq.gz
    ├── 788de04ddab72a00f07325418d3ee542f6a66a06.nq.gz
    ├── 79c8dd4814fa4d6e42c22db9132b459eed8ef623.nq.gz
    ├── 79d3d8356ff42e954b24c73d12722de2b5af11b7.nq.gz
    ├── 79fce55b0bc97d9a35eb5c44dbdabbf3957d1120.nq.gz
    ├── 7a0825a07290a74d8ec1979ad6e403d085be41bb.nq.gz
    ├── 7a670f64a83a2b6c59f49dfdaf53584f332a2bf9.nq.gz
    ├── 7b42ca87bc563ef085d0138b41e54e8788f35ac5.nq.gz
    ├── 7b97b0fb9cf4a7bc8e3a958fe944545fc0e1bcc8.nq.gz
    ├── 7bbbf91943749ebe246d1ec3468126b685015573.nq.gz
    ├── 7bf80269545434cce93e1555e730d4ead1e1cc2a.nq.gz
    ├── 7c6a480d5f547768a04b4d4e3e1eaafebb8e1a70.nq.gz
    ├── 7ca060ddb37ec3b06579125aacfe264d96bfd38b.nq.gz
    ├── 7d2cd82035da60ada402881f1c3bb4bd2fafdb6b.nq.gz
    ├── 7d780456c4884d278b6025c1b854536e4da8f18b.nq.gz
    ├── 823d0d9b1bf635bdf1565cee0e83ef512ae2ff98.nq.gz
    ├── 82860258fa850a3cd83c43c5c2999c1e3914438a.nq.gz
    ├── 833a0d90237c7153748ed362b10133a33f8bd6e9.nq.gz
    ├── 8514c4641540e6051105583d7ef12a34cd3d0fba.nq.gz
    ├── 8546c7a91a8e26a8ba0b3d25acf73eb407a4db37.nq.gz
    ├── 8654ab25323f9ef64ca8fc8df678af41af90e231.nq.gz
    ├── 86a16082cda446702a52f15dcdd1132b296fcad6.nq.gz
    ├── 876d9585dfe2462a00b28edf5200c08a2b7ed9b8.nq.gz
    ├── 8827e16ebd4ea677ecc72f12782532b760d6747b.nq.gz
    ├── 88aaf1b09584bd6ae64fc5dcf217ada8e3e93a48.nq.gz
    ├── 8ab221a32931cf0b2c756a74bd53eef15166bfb8.nq.gz
    ├── 8b1935df25a0c32fcb1ef90711f52a681d951efe.nq.gz
    ├── 8c2951c43a5e9859f1568f931b1a718454fc7ff4.nq.gz
    ├── 8c5958585a4cb7c23e2b589cb9529958a24802db.nq.gz
    ├── 8c666df3cfdb87ad0c520d6fb4785ba9ee278e49.nq.gz
    ├── 8dbcd0bc0bcb1d8022dfa08c6174b092a3a5520e.nq.gz
    ├── 91676412a854e3308b1b7df382c9008a260cd3b4.nq.gz
    ├── 919250ba966e5d4014a6cfe3c7122c1f5b66d31e.nq.gz
    ├── 923d689f3a4eaf0f38f3a9ac300a2c85aec42208.nq.gz
    ├── 92cc6dc8b749f59a9f02fd72c53c5a5652cbe24c.nq.gz
    ├── 940e30377966a5919344fc08b0614339a7772660.nq.gz
    ├── 946f4d68084d58f9ac4b4458a4eeab2ec5291f99.nq.gz
    ├── 97d85cffcff409d53775a0150247ad71e2c32ccb.nq.gz
    ├── 97da46451759c9ab078ba5d9ee20cf5d974a54c9.nq.gz
    ├── 994519b5839b16bba143bd2e6ba4162166dd24e3.nq.gz
    ├── 99733c5859204b36461873d015e0dbdb8fdc6bb9.nq.gz
    ├── 9a6cf8fbd396d475a55137d77a8c833ce359a16c.nq.gz
    ├── 9c354c2aca6377a34c183c4aa302fdb93b576452.nq.gz
    ├── 9ca87a9b787300508fce7d1ef48cb451e9362847.nq.gz
    ├── 9d6ebf288c2bd2f061f4c6881da8f6133cd76a23.nq.gz
    ├── 9ddb075c12d62e85c73ec71b4ffbd5824b153511.nq.gz
    ├── 9e8f2fc8bca045bc1ae440b928037c53454fb621.nq.gz
    ├── 9ea3127eba79055c5c76231eb3ef0f3e1592043e.nq.gz
    ├── 9f8f2208c4bdc0f0b0cafb4c0d0b5c79d32c32da.nq.gz
    ├── a0c262fa4dae9a73a659d1f86efbe481ec4c36ef.nq.gz
    ├── a0dcab6c71cde7fe22d5ea32f9c0d26375f67e3b.nq.gz
    ├── a1d50655bfde82f937b3a1e4d097de205f5b84ff.nq.gz
    ├── a41329609f36e77da565c8bb7bcbfe02fded6f2f.nq.gz
    ├── a45e95b8eefa669f668676833d1a73b1fe0ee8db.nq.gz
    └── a4748fe515e5d6d1620a1e776bdb2103b903608e.nq.gz

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

[scverse/squidpy](https://github.com/scverse/squidpy)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
