# Repolex Knowledge Graph of hardbyte/python-can

RDF knowledge graph data for [hardbyte/python-can](https://github.com/hardbyte/python-can), parsed by [repolex](https://repolex.ai).

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
rlex download hardbyte/python-can
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b4f82abede25ff83376be793a2935c41f81c3869
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b4f82abede25ff83376be793a2935c41f81c3869
│           └── chunk-001.nq.gz
└── blob
    ├── 00f101e4e5d4e89950e56001f15ca394655e82e5.nq.gz
    ├── 01f67bd8e4329ff9fc196edcfb52644730997fca.nq.gz
    ├── 0229cc10a5c5b193f848f3c54437c086b6c98dbf.nq.gz
    ├── 03425caaa88e2d8d737d97b712615c5d38467209.nq.gz
    ├── 0740f769dd6b7e5fe2455e79eaea262b9ab846aa.nq.gz
    ├── 0798de910fbc70c5b9b2fcc83e705ee31f7238ea.nq.gz
    ├── 0a936f1dee2e87f386f41ff8936fcbc57b9ebcfc.nq.gz
    ├── 0c35b36246dfa72cffdc869d67dd8d6017d49b47.nq.gz
    ├── 0c8ba02a4cd8dead95141d71041386a66847fa6a.nq.gz
    ├── 0d259f0842324f2f81a30ca5aae7831ebff47c7f.nq.gz
    ├── 0d400c18c813c0e87f5a905daf7f4115db6a42e6.nq.gz
    ├── 0da43fe32e34760c24201f4ec9338fd872927f7b.nq.gz
    ├── 0e0c49281b02618a4389ad7eb813c43cfcd3f0f9.nq.gz
    ├── 0fe9b647cfe82ea77cbb29b27916d070cb6150c0.nq.gz
    ├── 13274a4c47eee26ee33e6f9e88e649239bebbc28.nq.gz
    ├── 1337bf738c97ce8b9db758479ebb5bba26fb2121.nq.gz
    ├── 154451dd8d74df844e19fad8489d5c6fd92ab57e.nq.gz
    ├── 173944e0d02eb7a5c9cc2ff224d52849bff02aed.nq.gz
    ├── 18ad3f873162eb19091485a2f078537f27d66088.nq.gz
    ├── 1ac9dd61f36e24e13f2dce500226810eb103ff47.nq.gz
    ├── 1ad035dec3a6422afb4eba66bad6c4f9bd73c739.nq.gz
    ├── 1b401639a2f0fa70660f24e7c214c12af8715afc.nq.gz
    ├── 1d730a74b46f18af96d732414b0e6360e63f0af3.nq.gz
    ├── 1e1d62c23595fa4c59aa13300adee8dc5a8cfdd8.nq.gz
    ├── 1e289bea6e06a149aada60fe22e9ebeb4ddb759e.nq.gz
    ├── 1fea9ac5048a2d0cd969a5fad4d27fa1fbcac6cc.nq.gz
    ├── 20e8fba75db57cdf03e0d42278b924b748bd697e.nq.gz
    ├── 21dea465ff8ea986a636329cf33248f9fee14090.nq.gz
    ├── 226d3cdd52f47b1d59ad272b187c00b43c59f3cd.nq.gz
    ├── 22a11e643cf697d36bbaa17679e2e36f4c029109.nq.gz
    ├── 22bca706c74dca22113a7578d07b47581d0516a5.nq.gz
    ├── 25375d1b80fcf39afe18534e6fd792b4ee4cc2e0.nq.gz
    ├── 271e90b1be128423d6be3432f15ddc2e034248f1.nq.gz
    ├── 2951a63b1bd6b698a2d7d3598da1e0f4f26f89cb.nq.gz
    ├── 2ce0446b212c989e8240f535148178d20771117b.nq.gz
    ├── 2ec4df238d568072a86a3a6bfa55ba29df3937ea.nq.gz
    ├── 2f4194b311e00468ee61ccd4750b1a2dae7e6639.nq.gz
    ├── 2fa19942a50f3a185d32d768b59d0e15e52d7560.nq.gz
    ├── 329ccac533de0c704d03b6e863a2b88fb200a613.nq.gz
    ├── 332a7e2349ed71ff46643b7b6ccac546fe87d70a.nq.gz
    ├── 3654699c51a91ef7d892b83ae925b2423bbc0afd.nq.gz
    ├── 3a231dff7d8c0a55629c14b393562c6a76f1a76d.nq.gz
    ├── 3bc1aa42e25e42b4cb202f5b3a05238688f13a71.nq.gz
    ├── 3bdd281d2880896686e52f3527a33bc953db5743.nq.gz
    ├── 3c850a7304b9266c5573a95ab35095d08857b138.nq.gz
    ├── 3e60ca641b9636358af64b54e802f377f38f0321.nq.gz
    ├── 3efb20f6cb68c8f9770c2bc7d7c5e2f1418a0d60.nq.gz
    ├── 409485112b519fb29a46d37da511dd4b38b06eab.nq.gz
    ├── 41778ab6a371ea4c55333fc5845bdc4c1fad1a7a.nq.gz
    ├── 41b3a3cd0ef9a87968263f3b01aad3710c662140.nq.gz
    ├── 4265cc3e6c16c09774190fa55d609cd9fe0808e4.nq.gz
    ├── 42ae8dc5f3a0f65eb747e1c2f41469840abdaf22.nq.gz
    ├── 42ed29b1396b43d7808360f78517af1502d97a3f.nq.gz
    ├── 4311ff9a49f486ad8b08561e435a24ab565b69e7.nq.gz
    ├── 43c29302ece4df2c113c84c90743d5c95f99b765.nq.gz
    ├── 43dc0cd172426f23265c62013875a4e38a700a98.nq.gz
    ├── 4403b60ca9dbc092f3c4489e82f5690dd4b142e8.nq.gz
    ├── 4527dc23e533b202a2bb5ac763e92b6fc0f81e18.nq.gz
    ├── 48afb4c863867a8868c909b256db8667e1295916.nq.gz
    ├── 48e7dba05d76625d4f36e5d2b590076383b6d0b3.nq.gz
    ├── 4c737f2dc81da645c2b7628c1681e8e7bb1553bd.nq.gz
    ├── 4e6431576842242711406fc2919faafb46bab3da.nq.gz
    ├── 50095589cb4f76fcf834680f72110315e609dfc9.nq.gz
    ├── 5009c97568c1513499155aa257776b5ef767d85e.nq.gz
    ├── 514c31244352bb12042d9722393c2e5f9a0d21e9.nq.gz
    ├── 5186043645141edc25fc05d091d29bcbb224ebd5.nq.gz
    ├── 51aec65a458bcaa1eefba68328a2d1147c0539ed.nq.gz
    ├── 51fbcb1ce2a09a0958dca94157ac6bdf6528c543.nq.gz
    ├── 524908dfc6c14250598a498ec809392895c01a58.nq.gz
    ├── 528e86d5ea014a68f8e742af24193579cab48f36.nq.gz
    ├── 537356643e5f6abf6636b262fbfa602bcf4b7688.nq.gz
    ├── 53a9c973b7fddbe26dba74a0c90fc91ead2795ca.nq.gz
    ├── 53e83848843514827c17396f6d0187eaac776ad2.nq.gz
    ├── 55b48bfe43852caa6c267b60df7338820e694676.nq.gz
    ├── 566ec77554fb143d29d1dea98c6a9bb1d932f103.nq.gz
    ├── 5687308adacdbea9a9300e729977333b3b997772.nq.gz
    ├── 56ac5927f266528d3d29d9b0808e3b520deeb578.nq.gz
    ├── 57ebb368d510dbc5a51cd7541355044a33413b0b.nq.gz
    ├── 580a994fcec2ca491fd1bb9ca202318b8cc1caed.nq.gz
    ├── 5a17e7e8d0c149ff93f8d57b2300ae194952f219.nq.gz
    ├── 5d074f6147181a028ebe12cab6c9916b67383645.nq.gz
    ├── 607db6c8a93581d27b3ee98cd77cde573852a00d.nq.gz
    ├── 612148033e2346f5bf88c04568b4dc0408602562.nq.gz
    ├── 6190a58d80c1fa7dbf0283eb8e96502305cb40d8.nq.gz
    ├── 6441ad4e51ce268a18944996467d878039db104d.nq.gz
    ├── 64950f7f480793bf7845d11a65f75143cb90e1d3.nq.gz
    ├── 65b9dfff6e32e279aae88f51bd237e2066b4652f.nq.gz
    ├── 65c5ca88a67c30becee01c5a8816d964b03862f9.nq.gz
    ├── 6645ec33836465efa8486747c6dc9cf399fb084c.nq.gz
    ├── 66c171f4d1716838c88e6f98459d162bd1812d7d.nq.gz
    ├── 680ed1ac6f175af4cacb86263f9211822d831f2c.nq.gz
    ├── 69670139946a2216a5e92c00182dbcf8b5dfdce7.nq.gz
    ├── 69894c3d0599e2e2a46ec167fd97587d0e2a66f1.nq.gz
    ├── 69c8188697ce4e07528ccd58a91bc23bc5cc9d05.nq.gz
    ├── 6a09a6debce23fb244e53f3f95043f92d460b4a2.nq.gz
    ├── 6b04fdfe0f2e2b77812484bb8020b5fe80e89741.nq.gz
    ├── 6beb4fa43cdac73a28ab7c6ec879a6e5a38e76a8.nq.gz
    ├── 6befbe7a95d3df8d9d9e0743d4196f8ba939de6c.nq.gz
    ├── 6dc856cbf677f4b570d37bd0ac3127296e8a3f0c.nq.gz
    ├── 6e279c2feb000f5809efac6d1b5adcc72e9714df.nq.gz
    ├── 6e75d8d7d04764571ff37e7a31d4a2d2e3f2684a.nq.gz
    ├── 6e802a3d41bd3e523e9258658df562ccaf2c7cd7.nq.gz
    ├── 6f751bfac58a0d6511bba11dcd71359d7eb75688.nq.gz
    ├── 6fe79adb8e04afa6135e7eecaa8b9b33aa515b3a.nq.gz
    ├── 70463c491502f0712ab68cd096f93722d9594bbf.nq.gz
    ├── 7050b9f207afcdc90d94c91fbe630bf67e87f5a7.nq.gz
    ├── 70ac601faa0820e95c435ea36c5b7e08c3a2d0a3.nq.gz
    ├── 710922290c70bba41d14b4a24de555cd7ed5964f.nq.gz
    ├── 72442592ba75a6061637487edf3264337c136bfb.nq.gz
    ├── 7274498aa3fa9c97138bcb2730e6a52fc1b3a604.nq.gz
    ├── 73371af4c1d12400769d2c918f756b89e8c1c370.nq.gz
    ├── 74cb43af4e586de40c11f97e7935de8834571d1d.nq.gz
    ├── 763fcd72b88f3199892935d33c01d6343f1808b9.nq.gz
    ├── 77458ad75952e683e5657aa2e25d1f1f665148c4.nq.gz
    ├── 779365893bbecaac90ae6ec0f08fffb41b8007fe.nq.gz
    ├── 77a2c7f5de1acd01421dfe42f90defcb8b1e6da8.nq.gz
    ├── 77bd02faea6af1efaa95e35723d7ef8a004232ac.nq.gz
    ├── 77fd0d2e0e58f7b1fefba72beb6d83acf93517d6.nq.gz
    ├── 7986142be20e466b44e915dfb29351730c35c353.nq.gz
    ├── 7c78f5d063bb2e47f9be990212a58fe7e35707cf.nq.gz
    ├── 7cfb13d8d08e828649c2b5ae5b71411b606a8542.nq.gz
    ├── 7e8c877b4c4751e1ce576bac1b7e4c4c28dcb2df.nq.gz
    ├── 800125b7301b57d661e42f3555f4dcd58af695e3.nq.gz
    ├── 815ed6fa0f7b52a59de31e1a63db066feb283f21.nq.gz
    ├── 81e39d0df8a3fe5a9d2f8ba95d361b33ff63c4c4.nq.gz
    ├── 822de2ce0b887a0552668e68dc76e25ddeb6352d.nq.gz
    ├── 86ed3136216e06f6dbc50156dff2126266419577.nq.gz
    ├── 86f1c82ddf115add5baa4dd92bba996c5f06469f.nq.gz
    ├── 8768b412abc89aa8c3db7f7a7169f3f3d033e9d5.nq.gz
    ├── 881f16132cc1b52f4afb17d11c8aaba430364d88.nq.gz
    ├── 8b13618084e1e94744e3271e2ee47d338728f5a9.nq.gz
    ├── 8bdd77b83d893f8b0ed84d107eddbdf2aa18d405.nq.gz
    ├── 8c7b09949f2b07beeeda1e201ef5e26bfa525ef9.nq.gz
    ├── 8caf9eab4b69aedfb52d0b66f823422dde22adb8.nq.gz
    ├── 8d9d228bb1cf996ffc1575fb44477d76d7ce2000.nq.gz
    ├── 8e23670343965472793502f58c1e8a3219c708fe.nq.gz
    ├── 8f1158c009ff1a451c1e50368b7da993f9a5eac9.nq.gz
    ├── 907fadabba7919d166aa1eaadc94b8986e262b1a.nq.gz
    ├── 90b5f7adc0643a40f3e73c9d5505d0bb46164026.nq.gz
    ├── 90cbe372c7cde92f1ece5688950d29c306d2e51a.nq.gz
    ├── 9123e1bc89b7f56722078753c419974f459a4dee.nq.gz
    ├── 93ed79c35a4a0c26d13f43b733889a8ec04435bd.nq.gz
    ├── 941d5257369e974bc6969fd92c900828246abfb3.nq.gz
    ├── 9466bde4360dca3203d43ab8bd61be6b35bc0b22.nq.gz
    ├── 94cde0e60f8b484a568a02db937d998f9d633323.nq.gz
    ├── 96db1748cd41f3d601dd24023273bdc10463bfaa.nq.gz
    ├── 97a37868cb4d228c4b110d78589a820f8846e25d.nq.gz
    ├── 9a9cc7574a21a455fbfdd3b3f58d1f3a907ec20f.nq.gz
    ├── 9c742e2fb9eff2757fcea3b299bfe4dbb4a6ec59.nq.gz
    ├── 9d042f425b5badf6d25c1281775d47cc599f8241.nq.gz
    ├── 9dd55f8df0ecde61db8b4cc962a97224779ea4e4.nq.gz
    ├── 9e544f052db6346520b8963dbb071392246bf3df.nq.gz
    ├── 9f0e355346e2abf376345b925090c491f2871363.nq.gz
    ├── 9f203b2e0d685fc49a09803d9de6a1f5d1678cd1.nq.gz
    ├── 9fbf5c15c507c6e9030b12606880695910ce9af1.nq.gz
    ├── a1fd769fb57c1174b04b25ff2982380022287021.nq.gz
    ├── a21ec4438aee6113868b0bd16d5d20424c6dc4f5.nq.gz
    ├── a2f5f361fe3e5ba344e8b159ae3882efaa176afd.nq.gz
    ├── a3d6c7fbd8dac430a21732fbce68ccaa83551db7.nq.gz
    ├── a3eafcb4d6b8aabb3416c885c5d6a4c3d147a2d8.nq.gz
    ├── a661f62350e9935e68de2298e7e8e330147bb53e.nq.gz
    ├── a73e07aa2a2b70b3c12ee3e36619085b1f74dbc2.nq.gz
    ├── a896a6d7ca36d8842a0958d26bcf4f66c0593916.nq.gz
    ├── a8c61d2defc906961fa0b1a3d0acdb3af5670bd1.nq.gz
    ├── a96313b43d52ab270e9d770bd21202fb9e596b50.nq.gz
    ├── a9c6ea922af8c9bbff0b2cb4415b3c1adcf9a504.nq.gz
    ├── ab34ee7aefec446acb11a62c183271464dfd0753.nq.gz
    ├── ae045448d485676acdc267fc3d28cfb162f76a8e.nq.gz
    ├── afedf58d42f6911446846f83b3ec86a8dff13d38.nq.gz
    ├── b1bd636c15f9612df9c83abe82dd164555f52e83.nq.gz
    ├── b2a049d832b65066ed21298e97fae73a50cf5f16.nq.gz
    ├── b3a153a271ae3f6e36c4fcb16a7a0f4d954a4bb3.nq.gz
    ├── b48782259aae1ecc84185c3d39c2858e8c2d4069.nq.gz
    ├── b6f4676b7317502b92a910ada9f14583013a66cc.nq.gz
    ├── b757ad04dd59f40db615ba936433d3cbb6af1f32.nq.gz
    ├── b78420e4ed472fa4cdbb9b4745bda543b37ecfbf.nq.gz
    ├── b7b0e46ab5c1d5853ace042ff8df93d22604c2b7.nq.gz
    ├── b91ca231e9fb66208eac7585c7b7358a55de0f17.nq.gz
    ├── ba33a6ea893798e011882797e39885e4e0e57bb6.nq.gz
    ├── ba5b991c9729034d5a4524f57262f4e0758ae270.nq.gz
    ├── bc711d86bd3065c8b3b4aa9eea4956dd669b9dff.nq.gz
    ├── bc954738a6ee0275530a2c1eb20bda6934332294.nq.gz
    ├── bda4e1cced9dcd85abcd729ddbaf9c0084680d40.nq.gz
    ├── bdadcb08da5c044577a9a740b50378f079c489ee.nq.gz
    ├── bdd69eef235a268bc5cfdf8562bffc00ae76f2a6.nq.gz
    ├── bf313ce4751a7c57fc6f6b124ae76ea2884d4fe9.nq.gz
    ├── bf7aad48686cd92f6d34923073841478d6417057.nq.gz
    ├── c0015b185e1ad0defd217eb8927853cda5c75e6d.nq.gz
    ├── c02bdcfe9588a6acde9d0ba0167230b2b3ad9b19.nq.gz
    ├── c1a6c082df73e5037eb8d12758f3869b4342d02d.nq.gz
    ├── c1af8abc1e5b93dc82396ad49920b3d5d0d2da83.nq.gz
    ├── c1d842180f175550279d4272f104538eb37ade3b.nq.gz
    ├── c3905ae477210f58338a8c88ee2207b6509694d6.nq.gz
    ├── c3eb5519986f2798692b2783a1d2d517dbe62c89.nq.gz
    ├── c41a83691cff0b0653dcfec360e9186621756d56.nq.gz
    ├── c4c3c90ef34fda8b9f31fc5a8291901d908b3024.nq.gz
    ├── c54238be17c6dcca7ff3375d0f70fe6d77ae4311.nq.gz
    └── c55a93bc5d44cef736571041661fc84551ef1b16.nq.gz

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

[hardbyte/python-can](https://github.com/hardbyte/python-can)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
