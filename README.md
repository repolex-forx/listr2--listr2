# Repolex Knowledge Graph of listr2/listr2

RDF knowledge graph data for [listr2/listr2](https://github.com/listr2/listr2), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download listr2/listr2
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 51524728c0754fbe133ea7453baad473b2695302
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 51524728c0754fbe133ea7453baad473b2695302.nq.gz
│   └── repolex
│       └── 51524728c0754fbe133ea7453baad473b2695302
│           └── chunk-001.nq.gz
└── blob
    ├── 01507d93d8db8c6a2d5a85fbc679019c591c3210.nq.gz
    ├── 01b40f31a93c3c5436e6638a0b9193697142904f.nq.gz
    ├── 021511f3ad18d09f384dcab75990f39ee917e4a8.nq.gz
    ├── 023a01123fc6141dc58c3b8d7640fde7213ee08d.nq.gz
    ├── 023d9c2e2423189535c3f18de090211ac55673cf.nq.gz
    ├── 024eb7419bc5919940eabf61ba7d6de3693ceab4.nq.gz
    ├── 04111eabd4ecfd7f4eb4193c0c8b98493ca3489a.nq.gz
    ├── 041e191f2bfda6343a30ae1f38f36af2563501bc.nq.gz
    ├── 07149a11025cd71b3f4d464b6704c9e90c1332ce.nq.gz
    ├── 07d94786cb580d98a31e4ff785bd0c8bb414a2e9.nq.gz
    ├── 08d169bb39b540fc99c3d76c83f1e350db146533.nq.gz
    ├── 08f886f68077929ffea9222cea2c5be91192fae9.nq.gz
    ├── 0b7780e39ea0a84a0d77a7ed27b5aa58414ce653.nq.gz
    ├── 0ba3aa9c9311ac11be211060ac4cfebd36004eae.nq.gz
    ├── 0cd3efdc55ecb51748cc2329dfbce2a48b5cb7b7.nq.gz
    ├── 0e5725a5122f8683fe3327c9b237355e709f5677.nq.gz
    ├── 0f63572cd438bc38568b8d953b0bf89ec20f4eb5.nq.gz
    ├── 10050b85c616a675869c29a2033a2a617fbf3876.nq.gz
    ├── 10844b4d64a7fa47adebdeaa709621e66814a287.nq.gz
    ├── 121edb88706ad41dffcbcaa1fd2ef9e27867fb7c.nq.gz
    ├── 1413dd7c26fbbf38b9ad573b6924700d08887a43.nq.gz
    ├── 167e9a4196d1adb885d8f8c33a9c492604e48bd6.nq.gz
    ├── 171fcf098c25cd9e0be18e2da7c9fcb7fa76fca8.nq.gz
    ├── 18959bbb8ca43fc72e1fc7711eabceca12fb47ec.nq.gz
    ├── 1931ad960ec1dee94a8e4155c5cf8cb2c2f45170.nq.gz
    ├── 19786f6478e9da84b0a17949428da49efd4854fe.nq.gz
    ├── 19f750d4ff104e789f93bb2ee6d4af050785df60.nq.gz
    ├── 1ac4a25cfb85184a785fee166ed58a16a1f414a7.nq.gz
    ├── 1b0150dc43b1f4218267f0c9d8f1ce669ac74d06.nq.gz
    ├── 1cb85e26ffed172e9da973abb5c90403ec0225a4.nq.gz
    ├── 1d1a8145bfc8918e666f42075c84eea97fc68613.nq.gz
    ├── 1dcafb185f36fd361d905d8e81e47b0f217db8de.nq.gz
    ├── 1e0a5ec01bf0b44b16fae2bde30f00e46e9d5361.nq.gz
    ├── 1e6a3d84cda3ced173d9e84fb332cd2b6aec8cab.nq.gz
    ├── 1e889648980e8f530bf22b3a2fa80cd23f160e64.nq.gz
    ├── 1ee85b6fb8a4929eaaee0ae4c037d121928ed88f.nq.gz
    ├── 1f158058d02287487f472e3b0ac0298e9f25800c.nq.gz
    ├── 1f7355e2f69d28b434cddf9a216247be06e7dfa6.nq.gz
    ├── 20941db23b1ea6b1aac9e62e0a191bcb4ed5e871.nq.gz
    ├── 209e3ef4b6247ce746048d5711befda46206d235.nq.gz
    ├── 20f50071d21aa51d7fdcda5e73fc761a1f7bcdd1.nq.gz
    ├── 23a87cf19a3700e3debeb260d3cffc549aa88d94.nq.gz
    ├── 24da6b916315fec24bd961a22a6efed2e0732e42.nq.gz
    ├── 25add096220219a7f3fa7d97c6fee039bb0d4905.nq.gz
    ├── 26e0045b04f2e9cae306fc637957546c4374069d.nq.gz
    ├── 2848a49046ed709361136cd458a8f6de97317a3b.nq.gz
    ├── 2890af6efeed812ac70bf842e27cbf586f74daf7.nq.gz
    ├── 289cd1091377631c613e2f4320fd7bc31f1af0c1.nq.gz
    ├── 29307d4aac08764f5c47c3e1bd11fbe39648626b.nq.gz
    ├── 29795c30d1dc34a7eed0c5ff43ba4ff4660605ea.nq.gz
    ├── 2a1580f921c7dd98a2ced9b72ba5b6931b63db58.nq.gz
    ├── 2da685943bdcc0e2a355f1024eee96bb399963a9.nq.gz
    ├── 2e7805fc7785bc6266112a1ee803c0699bac54f7.nq.gz
    ├── 2f13cf249ba6f1b335091432686f77e47403fa76.nq.gz
    ├── 30a2413b03e58ecc8f4acf5dcfb644a7df359494.nq.gz
    ├── 30a9f23d8164d6f6745bd7156f076c723bbca7c8.nq.gz
    ├── 316a650b459c272f1290e8986f725afb8cd436bb.nq.gz
    ├── 3189cc2f239625b4c5aa3c5d4b68ab162f72d89b.nq.gz
    ├── 320397924267839351a8d8b20157c47ee76d36d4.nq.gz
    ├── 3307c9bc98f308a7a6686042041885004e989ca4.nq.gz
    ├── 35385b469a18156b8a5fb578a8f4df2613a93b4c.nq.gz
    ├── 35674528998f1032a7aa3f98f357aa22174f74ea.nq.gz
    ├── 3569bfea635c76073db67b15305de0156c70817c.nq.gz
    ├── 35ec660326eb39fa34644f1d5bb968aa61a70350.nq.gz
    ├── 3631dd70eee7af3440408cc7f7ef8685426b3318.nq.gz
    ├── 36ed3c9f222b6a4ad2d1a73ccb41e211b03a6680.nq.gz
    ├── 37e2f8c25df24fec2f58ac4af74e829eed939442.nq.gz
    ├── 37e84a4afd552e16151241a090a0dc8bce422d1a.nq.gz
    ├── 399a49e85b7cda026b21705a63962600ba4b82d5.nq.gz
    ├── 3cbc7a78cacd260f4d0d7db66ef1d5de897b059c.nq.gz
    ├── 3cdca38eab4def05de32041c5edd938a10fb9920.nq.gz
    ├── 3d85bca4b8ac0099f637b6620a295d49477f0734.nq.gz
    ├── 3eae7e5a8dc52d41faaf11ef5e97cddef4b86736.nq.gz
    ├── 3edbed6f86420009a189056b64c48bcb48a45ea0.nq.gz
    ├── 3fc75503795f9ddf86690c37170d6faa841fba0c.nq.gz
    ├── 3ffd1fee594c8366b99077b34a97a86fb23acc70.nq.gz
    ├── 4168938a94ebaf980c2eeb6806670c7080595886.nq.gz
    ├── 43bc556481dbca058e6e3cf664459f7f9620b6c3.nq.gz
    ├── 44502aacac736f004833c7cb1c4b41ecd960c2df.nq.gz
    ├── 44a6046d3c7070d16069569b38fc702573e19653.nq.gz
    ├── 452b841f28ec0ce1485958379019021067cc034c.nq.gz
    ├── 45a953d682266a3d63af88b4acc86b20e1fdad0e.nq.gz
    ├── 467e644b6ace399ec57ef253ae712c4e4c36430f.nq.gz
    ├── 47367400494dc3a2ce8b37b2f845dd8f5719631b.nq.gz
    ├── 474471e4a48ac1745a8a2e54528104b1c70e5e8e.nq.gz
    ├── 47a3f71a4e06f96152736773eacfd571572a2208.nq.gz
    ├── 4812ef5ee4c29df5232cba51d7202b68e2cb82ee.nq.gz
    ├── 48f950b8d47ee83dac2cafbc5147820769e5ac98.nq.gz
    ├── 495cc5940f91b501defd1d8ad753d2533cb1799b.nq.gz
    ├── 49dbb469d04eb90b8bcf810b4de530244a4e55ef.nq.gz
    ├── 4b564c1bfc618a593da3f6589c30046130f1dce4.nq.gz
    ├── 4ba4ef764d1003b9c03200b2430ffbf13119ba3d.nq.gz
    ├── 4cbf4175a3e468657c266c012a1881723c72bc9f.nq.gz
    ├── 4d74fb3cfeaf8477e9d92da88954a7085359411a.nq.gz
    ├── 4d87fd7c5b2eca722c5453f1d8d98caa21392bc5.nq.gz
    ├── 4db0ff3ba6b79481458cbf3ef10c657398a449d8.nq.gz
    ├── 4e10a4f99726d65d959caf64d5089d89021ee253.nq.gz
    ├── 4e2fdf8c9c890c36b16ad5d40c2b390bda817196.nq.gz
    ├── 4ffe381bfb22d87bbd218343823f6ca095efcff1.nq.gz
    ├── 50625e703c8d42813f570ba32a08d73d56723302.nq.gz
    ├── 512b73f5b06edf6ac20f2c26560f41425d50136a.nq.gz
    ├── 515738d54db5ff47f496b624e86051d69062b324.nq.gz
    ├── 51d724fc5129a8ac477d581a8088397a0787463c.nq.gz
    ├── 51efe0d096bd509e693aeaef4273bd742d543e08.nq.gz
    ├── 5211c15d3f977d4b46bfb9f51076b4da9bc85dc4.nq.gz
    ├── 52269ceaf54c2ab862e8aebcd2258fc55bf0e0c6.nq.gz
    ├── 52637e2c0e38c625d32de9b44af027bc2741735a.nq.gz
    ├── 52992b8f347b42e789bdd8a16de674eb86ad72c5.nq.gz
    ├── 536ac68902a905f12798ab273e551c82fa21ee27.nq.gz
    ├── 53b8fda8bd1483f29d0c3a239ef023e711ca0679.nq.gz
    ├── 542c6ac984d2b837970c737c8a267f6b19ab42b0.nq.gz
    ├── 5542f1175cb7d995b19e3dc59f88164db83c244c.nq.gz
    ├── 556d30a2ce6d3edf21782108bead25df977f6a5e.nq.gz
    ├── 5625f1ebe9df6352b2859b5ed102fc7c39501d5d.nq.gz
    ├── 56bb78db7bb050bc9152ad530dea2ea921ab16b1.nq.gz
    ├── 57e1c18defd8650c032cbbc602bb99bdc5144e9f.nq.gz
    ├── 5a12f217e244ebc3cbcfba6177a9c23d53d3547e.nq.gz
    ├── 5a9d1eb810f99d27025a6d1efb3d761cd01382af.nq.gz
    ├── 5ab29312526e315fc3d1edb23fed3491cbb461d7.nq.gz
    ├── 5ab7704db64bf1ee2c93ab5dd7e8e8e60c7e03f1.nq.gz
    ├── 5ba35acdec35817eb90c4039816e10a4859fa218.nq.gz
    ├── 5bd936b80a24fab074e0b008700ec6d8ad269837.nq.gz
    ├── 5c6207682c2354c3fb934d4a45aba8ce4981ba1c.nq.gz
    ├── 5cd205a00ce3aed97937105c8c339587c8c55695.nq.gz
    ├── 5d358bb2dea08825280c02f6ddae22084993e001.nq.gz
    ├── 5d3f749573e1c516ddb27aa43ee7efe25722d0b4.nq.gz
    ├── 60293a4c3f4f5406300cb294054c0cbfa3bfc889.nq.gz
    ├── 6284d301cd0b9addbfb09d6b3ed4270b6a78f04a.nq.gz
    ├── 631dfadbb7e797e90604d0ba9bea81caff7f7cf6.nq.gz
    ├── 64876ed20fb72fe47ebfa73d6e357e859e03be38.nq.gz
    ├── 669438a172ccf5b19f8fa7b4ae5eb38872d7eea8.nq.gz
    ├── 670ab44f5055bf5753e74ff9b1b57e1dc051375c.nq.gz
    ├── 67d511d4d28efdf36e242fd3fb2f2e5bd0a799b4.nq.gz
    ├── 6969499d84217b5510ba10125c6f0d2cac48fc97.nq.gz
    ├── 69e1e8be49b60074edcdd3e4005899a374668144.nq.gz
    ├── 6a8fa09ea9928beb66f7e65a4610fb61f9354f70.nq.gz
    ├── 6a916bade3b7442d88ec8b8d39a6034ac5af14be.nq.gz
    ├── 6aba32ece5446d34f7f84ae9cd700ca8222f0342.nq.gz
    ├── 6b6c384f77d8ceaf1af0d47fa3db2a61101c7183.nq.gz
    ├── 6b810f02ee5acbd2bd4f0fc23dc8495266f34e0d.nq.gz
    ├── 6bb08f2a6de2c664c54c3b4315863be7687cc4fd.nq.gz
    ├── 6d158805c624a513738ad015351206859bfe3f57.nq.gz
    ├── 6de0bf2d7ea7f7e89c978a3e930ec017d25412b5.nq.gz
    ├── 6ecf3dbe4ea8636934d55e4d455e9b08c1a75929.nq.gz
    ├── 6fb4b70ec9d62b8358829b6f3d2ae8844d4b9e4a.nq.gz
    ├── 70894a084fd2f5350667e0bcdfa504415f7df892.nq.gz
    ├── 72bc4f1faa9d4a8d1dff2ccbc848190cec4ef13e.nq.gz
    ├── 7330aef52c6c3043964e455b4988bee0c14ccc86.nq.gz
    ├── 7357e22bc64da3a72edee7634019845511fe3bcd.nq.gz
    ├── 735801a7a287ad3c3a7cefd7fc985864d0260186.nq.gz
    ├── 736478c9baf0af991bcb39c55da44f8c5ee213ce.nq.gz
    ├── 73d3a8c83e19b4b283eaf9408771d385586e0152.nq.gz
    ├── 7426831b7a07b7ff0648a4eddcd2733a74158d4a.nq.gz
    ├── 7668ee76b4c67482b7ccea953d41782d797011b4.nq.gz
    ├── 76ad8ee39b8d290e8cef18bf7bd8fda5c9f29dac.nq.gz
    ├── 775d26892f831de36770def23b9c10a88c48869e.nq.gz
    ├── 782513ffed440e087961ae5001ee81675db40c18.nq.gz
    ├── 7866fcca20833caf0da0eb7168ec50e9947666a3.nq.gz
    ├── 79446089197e76eaa291e6e94d9d09e42042a61c.nq.gz
    ├── 799f7e6f9de8dea88fe5ef7accebd142ea118394.nq.gz
    ├── 79d549bba37bdf4cc174a84643d8f82a452ce38f.nq.gz
    ├── 7a868d6ffc0546d5ae51dec82ba64e6b03ecb46b.nq.gz
    ├── 7c7f9933140db502e1667f075e6728aa6c7ecf34.nq.gz
    ├── 7d47e4935ff4577ea5e0a77f004a590fdb86d750.nq.gz
    ├── 7deab48eba334e2c31fc55209e142431d29d3331.nq.gz
    ├── 7fb71395fbff3944b10022b25b174ab014424313.nq.gz
    ├── 8032f3b25c203865c596f353d4352c9d0fc176a4.nq.gz
    ├── 8199728e9c2a281db764ac05a11fbb458921f836.nq.gz
    ├── 81bb6905e9edc37b1049f9c0450c70e41c9dc4fd.nq.gz
    ├── 82556fe53f9021c394c4cb38b9d0a4e06c8055d4.nq.gz
    ├── 828b49de138309bafee27d8b09e43cab7f31bb9c.nq.gz
    ├── 82c45429ca811641afda73a136bcdfd26942e8fc.nq.gz
    ├── 82ed09bc7bf565b3998aa7ae20a2cfb7e4d043cb.nq.gz
    ├── 833c24907857899dd55a3e749336d26ad1ae9c48.nq.gz
    ├── 85390dc1bd2dded44157d82be7262f3ed0a56f54.nq.gz
    ├── 8563bf4e5f61cd2100a4b9bdd908e0370ee21291.nq.gz
    ├── 86999119ab2133e1a850f5996d012de992b45e28.nq.gz
    ├── 87d4370032a0915f994cb60e886b3474d8d6ad7f.nq.gz
    ├── 87f99ee23b024e07c13eb73500f97df86c355bc7.nq.gz
    ├── 88a836d7e92692db946a118148b578d20ffb4bda.nq.gz
    ├── 88cd96ab9e2c9a8581a98bd51ed1fe9a647662f7.nq.gz
    ├── 893bb0f6d37ec7f1773e9835e5d4674035410200.nq.gz
    ├── 8a2d2e46b684002db4b47e1b6223c8f4baa0aecd.nq.gz
    ├── 8bc6a908b8a2b49f30660613b476644a5031e7d4.nq.gz
    ├── 8c0756c96b413093b5e19e636d4b69d4ad6906a7.nq.gz
    ├── 8c6492ca8e2ce80865b32f8c59e1f717a1d46353.nq.gz
    ├── 8c6ea0c2ed78010db498d397d6a30149bd544a0a.nq.gz
    ├── 8d2bf01c8282b07011c8d21f843812f13df2841f.nq.gz
    ├── 8d32f7c775b165dd7443e1f33f1ed4da690ee5ae.nq.gz
    ├── 8e92346d4213a71c7c00fa481653d3f41f68c14f.nq.gz
    ├── 8f6a3a741c5083289ae8aa281ba77dd23c545046.nq.gz
    ├── 96edbe43e47c06714d5e0dc0d7a216bf61e48976.nq.gz
    ├── 974e9909805095c8e39aa114f42c445294250825.nq.gz
    ├── 99c5945b8b320b1bac308a193a26501ed5ed8499.nq.gz
    ├── 9a69acbac0bd9338aa69a023dd69d4ea77aff3e5.nq.gz
    ├── 9cf4dfc14a96560bd75a9ff65adf468c197f1971.nq.gz
    └── a0ad0439028a852a2d7ab9207c524c0c380096fc.nq.gz

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

## Source repository

[listr2/listr2](https://github.com/listr2/listr2)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
