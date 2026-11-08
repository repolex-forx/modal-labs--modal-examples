# Repolex Knowledge Graph of modal-labs/modal-examples

RDF knowledge graph data for [modal-labs/modal-examples](https://github.com/modal-labs/modal-examples), parsed by [repolex](https://repolex.ai).

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
rlex download modal-labs/modal-examples
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a590d8b608e526771378dc1bbf0dcb8b03ca0309
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a590d8b608e526771378dc1bbf0dcb8b03ca0309
│           └── chunk-001.nq.gz
└── blob
    ├── 007da278c3c21578934cbb19e9b4d5ee6bbee851.nq.gz
    ├── 011b1bf1842d92336949b90bb46c0dc4915a48c2.nq.gz
    ├── 014f3abea00c5ca2870623a88b04e57045f45f9d.nq.gz
    ├── 0206458a1cc71675c05b711b264d49ad8e678a75.nq.gz
    ├── 0225789f2468e24f172d80771a3a054543696a04.nq.gz
    ├── 022c2d13a1b7d79a979ccd6a51b80c1181d06478.nq.gz
    ├── 02937e1470aeee2799d5294ae1b6575266bb1416.nq.gz
    ├── 037df8253d28d8994ad2e5af52a3a6072fd6fa65.nq.gz
    ├── 050cb1fbd177a2b45e5518b714d58ce31eb48357.nq.gz
    ├── 0580e3fe7f84a97f7fe2d71248c8d4894c6dd12a.nq.gz
    ├── 06e5981af735237fdaa091b669d90c01f2f2d843.nq.gz
    ├── 07f3657040ecfdc0cca7e1ba403840380cd5c32d.nq.gz
    ├── 097e0131e46e973f3df775c88dd23cc54006adf5.nq.gz
    ├── 09946a4a49f1f21bd488f6234761493e500beeac.nq.gz
    ├── 0b70f3f202cd2b076172fbb3d50b158d829205f9.nq.gz
    ├── 0bd500c0939fdfda91c306b43259afec03879418.nq.gz
    ├── 0c080a07a171380c1a53b23e8a79753d2f9c4793.nq.gz
    ├── 0d6efe155a91aabd8113186e3844c9f3763193b8.nq.gz
    ├── 0dbc6ae19b233cd0a1344f987b86ce2cd1330859.nq.gz
    ├── 0dd408fc72194b828303107ee0e84dd4fcdee1cc.nq.gz
    ├── 0e424ff02894687683e1fb83e98c482fdfd952fa.nq.gz
    ├── 0e4dcb841babbb5668dfd62f9851f54e8c0bb6d3.nq.gz
    ├── 10548dd75a2914f79bae4de1ce57027e57bc4301.nq.gz
    ├── 1303e8bb50266544f09f7cad1649dc217e2b60ad.nq.gz
    ├── 1425ea36b010077a04d48cc4c5e24595e44c0d11.nq.gz
    ├── 143e39789cbfb95065432963190852bd31b2b9d4.nq.gz
    ├── 168458ed083c9fbd454e947face5ac0b89d72a7c.nq.gz
    ├── 16e628209cd52a8560338a896031f462babfc67e.nq.gz
    ├── 175f01dbcfd1bdaa9eeb46884c6e44229c6a6d24.nq.gz
    ├── 1aa0f5b8bef6d3b6560a7057bcd928ed958e98f3.nq.gz
    ├── 1c7b40c1c4528703cadba345cfb0e0b0b014b4a9.nq.gz
    ├── 1ceebb003bffdd44eac9cdafb5a6fb9d10c50f06.nq.gz
    ├── 1eb6556986183493045633ed1c5ed41d64a2e1c3.nq.gz
    ├── 2006ae76b5d5b4c881de307d14121169674a98f9.nq.gz
    ├── 210d2a973b4db8b45dddc184c0885e39e9029a81.nq.gz
    ├── 23995930b1fbca4884c36993f1dadd77194b9e3c.nq.gz
    ├── 258345211a9a23a38280c8e4443114b30b01285f.nq.gz
    ├── 27b8621ac99b5f0970ff88b9a112695a81d6c2c2.nq.gz
    ├── 27d5bab15122940e230b2a0f4c62b1633b94a499.nq.gz
    ├── 27db090e81fb3078c602a90e90d2c4a13b1cd175.nq.gz
    ├── 287fb8be25eaae4e40e2d96ef64cf77c99290f99.nq.gz
    ├── 28dc67fabd6075d76c882cbca504d43e932a7840.nq.gz
    ├── 2aa1199f12f8f831954565d3b57c486174200167.nq.gz
    ├── 2b974cf1172397c04b259e6e97eb8f0570213e9b.nq.gz
    ├── 2bcdfd92bacb5e2c34ba4e08b63112abfedaf538.nq.gz
    ├── 2bec1c335a7d84633bd455f0cf13f120ff0193b3.nq.gz
    ├── 2c5a0e3b2fbd79ebc5a355a1e30dca7ebefd98c6.nq.gz
    ├── 2d40b1496ec3ae9b69bb15b836edf4e5506ec81f.nq.gz
    ├── 2db09689808a02d92454e470f413e405f61ab139.nq.gz
    ├── 32d8dc0694f263673d106b1dfad8e5727a02db9f.nq.gz
    ├── 336a3f9a33e3ddfb05bda13dca731e292b2bf6ac.nq.gz
    ├── 33f75e2df32ef429fbc57d43bbc5216fce82df70.nq.gz
    ├── 36206a8c30a58e3011bbd2dfce46670e3a2049ca.nq.gz
    ├── 3696f99aa4de82d50da446e40e507991b0662a0e.nq.gz
    ├── 380d7328be9c112c73fe000dad0ad795ecf0f39a.nq.gz
    ├── 38b5a15552be369f01fd4b91d72d65279ca3e8c6.nq.gz
    ├── 38c8d13c135d14723ce90fbcb2a33be0aef5b390.nq.gz
    ├── 38e5fdabe28dca57ad0c2baf37c62b6a8f3f3a2d.nq.gz
    ├── 39a6d0c1a479da8780157ba367aed95090a2bb30.nq.gz
    ├── 39dce45d42c28e05bedc05cdf6d7442bee3583a5.nq.gz
    ├── 3a3544071db3f63f9e2cee4a6ace9575a142830a.nq.gz
    ├── 3a63bb20b931d80e97e6805d2156ec0a4e4ad5c0.nq.gz
    ├── 3bd233cf2ceacd4dda4bb46a148795bcd5b961c1.nq.gz
    ├── 3bd3d52fceb7e14feb3e722e2abec4bb51bd61de.nq.gz
    ├── 3cc62958a389fde0498ad9becb99efa89cb137a5.nq.gz
    ├── 3dcd712f2245b4fdad76c6c2d45e2f4cdec96899.nq.gz
    ├── 406598cfd0efe0a4a95c82fe4b75d5df7f0c5a1c.nq.gz
    ├── 40741eb1b90d8bd2f34fa371eff194c67a6501c4.nq.gz
    ├── 4198341747574776aaf89c936786e1b25aaff4af.nq.gz
    ├── 41c44fdf12b610cdcdfc4d657969d28db5133f7d.nq.gz
    ├── 436b4034d83a4ad1e3b03be469075915ab12a080.nq.gz
    ├── 45853897cc01144b176485160f65f3ba325070cc.nq.gz
    ├── 45c41334c142b39a744c0bc0fb9b2d2d6aef06be.nq.gz
    ├── 45ffe612aca4b36377f5d4a54c3bdfebc58778a8.nq.gz
    ├── 46663eda1c1f8d0e25cd625181c11a22019952d0.nq.gz
    ├── 46e0fa4ded2b727be0a0607eae16441982a5ecbe.nq.gz
    ├── 48113a1b44dab6b2612137960048a30221029bc1.nq.gz
    ├── 4892f96dde37bdc8ee1c89ff88c0d5da892662ac.nq.gz
    ├── 4951205055d356af224be5f50c1b359533577883.nq.gz
    ├── 49f147cb98ac4e372f0e8f973221aad8f87b1057.nq.gz
    ├── 4bee6989e5b9f71fa1f95c8d296cc1c079bef696.nq.gz
    ├── 4cc17cedd0e609e2ff70b50a9eb367a2a2ba5ae8.nq.gz
    ├── 4d307aa4d960b3f7615d91d4989fb1306cfd4f7e.nq.gz
    ├── 4f4d2df55531a19f65f552f83b863469a3b9a88d.nq.gz
    ├── 502068498344ad1e59b575d6a7eb2d4bf9b89db6.nq.gz
    ├── 512188e01e206a2592b02e60440c8985eb28b5db.nq.gz
    ├── 51906ac7bf847eb4f5d19d96336db3cf3d7c6443.nq.gz
    ├── 53c6d6913f09837d26e0a90e08fabf610f4f64e2.nq.gz
    ├── 53d2b224e524c53c44fc33b58f70118fac19e216.nq.gz
    ├── 558c1f3af627dc57e79993a4902c41b022bee478.nq.gz
    ├── 55a5dce8b6935fadb708df29dde21b75a9f11378.nq.gz
    ├── 57834ec9aa46303a3ad6243c611c9cc708724a5b.nq.gz
    ├── 5784cc06246a7c6489746e898716339a4415e879.nq.gz
    ├── 58d5d7200684e34361cc0dec33d1055a80ea440f.nq.gz
    ├── 592066b88a7b55568d808166ab5a80067398fa0c.nq.gz
    ├── 59a1896c3961ccd1e6e03dad38c7bc0e957e64f5.nq.gz
    ├── 5a6652327a8782418be50475c1de32a7939aeeaf.nq.gz
    ├── 5a68c21ae84eb08365c637c569185b82f19e4a1e.nq.gz
    ├── 5d1d395aee1453ab48db691004d4efa4b2e4fe78.nq.gz
    ├── 5e083eb7dd31c8deeb97d6a96b48cc98d8070586.nq.gz
    ├── 5e192c9b4fd87ec9cd72bfc35a88bc33023feefe.nq.gz
    ├── 5f6b6c7f93a69aece3276768a8e79fcf7f136025.nq.gz
    ├── 5ff5c104e973ba93cb8b89b680010c2ecf747c4e.nq.gz
    ├── 611af60a0c8bc2b92b9dfd8ad9b5407e82950356.nq.gz
    ├── 615dab286b5bc29dfdb244bdffb8c032af463ff7.nq.gz
    ├── 630a62cf2db7965f777bb298cff74d289224ddc7.nq.gz
    ├── 64aa999e2a94edf2b048e99e69c5a83e26dd8098.nq.gz
    ├── 66a0df67c308da285ebfb3914030a0d071d6fe8a.nq.gz
    ├── 6876c43c63e5a5afe2f01530d85be5358d10b8eb.nq.gz
    ├── 68bccdf772f5722813fde0b147274c17406eb93f.nq.gz
    ├── 6dfec25584467f739f6300f12fbd0bcaa2bfa9f0.nq.gz
    ├── 6f67e02773ab4b0a5f7929872f71cae94dc927a0.nq.gz
    ├── 6fc284e5a303364df8c52f2783c4953572dc48dd.nq.gz
    ├── 711f0dd8bfa0169cc20d5e3afa14cd29e3550d44.nq.gz
    ├── 716d6c66d2bf46358c255007d6577414e297ce64.nq.gz
    ├── 71b96c1710ade168af3bac0e328fda556b9af336.nq.gz
    ├── 71bd0099b7b0bf4a300962093a22901b2aaf96ab.nq.gz
    ├── 72246f7f223b1ee3396e5d8221e0127a3cfeb08d.nq.gz
    ├── 727c883471a688848763a0ff6f477d6a61ec9e9a.nq.gz
    ├── 7312f76bc9dd8ff03dbfefdf82f62c3c042c53ba.nq.gz
    ├── 7385ff8295c2f6359bec0b9d5227366ba18e9417.nq.gz
    ├── 743b897b0f442a0e5a0afba1bfdfc2684598a55a.nq.gz
    ├── 7571ed1c231ca0086181d646e0d923ae367bca44.nq.gz
    ├── 7775b429a2828fc2d62b48c7c10facaf02c37506.nq.gz
    ├── 77a8556d0a4a88de1732200baea1cfe33c419678.nq.gz
    ├── 77b8523a99c23d568f5b0a35dbf9f63382fd186d.nq.gz
    ├── 78f48bb05057ce93c686e482f602d234945dd7d0.nq.gz
    ├── 7a622d5efadd5a3140e6f9d60b34848fe28268fc.nq.gz
    ├── 7bff7d6d5edbfd8389940049bae4c1cfc6045457.nq.gz
    ├── 7c2f13a089ffeb66081aef519426bef488eaddfd.nq.gz
    ├── 7deef20dbb00c00ed0732c18388d2308ddd66de1.nq.gz
    ├── 7df8b5041c97fd14d11ea917e7411b666c704349.nq.gz
    ├── 7f24cd1e1abb697c3bb2021db7bce7a574d4b4cc.nq.gz
    ├── 806241c09ac1ba7ac6a7a34a4bfaebe0ee7b5ce4.nq.gz
    ├── 8063ba566863621fa407d38e623fd53efff6de2b.nq.gz
    ├── 817856fc9164c6e129dee1a5528f0221884e218a.nq.gz
    ├── 81be8ac5f8e7a37f17472cd1a7d53c2d02bce7d6.nq.gz
    ├── 82698213cd1520e03679cba2d7f23104192ce243.nq.gz
    ├── 832e6e3a2703d4ec223112a60cc4ea503b8758b8.nq.gz
    ├── 86d1a56f8e3474a76c386f2ea62cdf1405c7c02b.nq.gz
    ├── 8773e34078510333b47b888b27d32dd8ecfc52f2.nq.gz
    ├── 8c2043ace80439b7b3cfdc427629cf33a84a2e38.nq.gz
    ├── 8c4bd71e128becd649200d6830e9bf5cabd663e0.nq.gz
    ├── 8d0e3532496c16ae86b4c136a5d833ef7cf77e02.nq.gz
    ├── 8d4f5593272fd0136f28b05f72498be5d93fbbc5.nq.gz
    ├── 8d5208e32982e353db8c7021a224552a7e788e8c.nq.gz
    ├── 8dcdb794079a88feb734dbc144cf22c7228d7340.nq.gz
    ├── 8f9a6f51082d1e5adf606b773adaede01a3f48dc.nq.gz
    ├── 90a12aa93ee45e3734b730457c1becfbd59b1787.nq.gz
    ├── 917d0c41129692684eda38b4b36a3d241e6f3e42.nq.gz
    ├── 93222ccecc6354b91698e99dee2c9cfa2b85b4b9.nq.gz
    ├── 941cb4e1392266f6a6c09b1fdc5f79503b2e5df6.nq.gz
    ├── 94fca2e1aa0dc3c00d594ac49e483ce3df96408b.nq.gz
    ├── 95393363d6f343c8f8b43bdd1b9277a9da0eb3c2.nq.gz
    ├── 9674d7a44b23328f6645a3c91de136099e04332e.nq.gz
    ├── 96989d83dd8988ca6ed7595dba92f7ddc10836b1.nq.gz
    ├── 96f5fd62fb3fa6d78d528826e9d51c8b40643a68.nq.gz
    ├── 972fc8b9e706263544e547f7cf0646d8ff7342bc.nq.gz
    ├── 974b65cc9f50e6dd5c7114fa695409549096fef3.nq.gz
    ├── 99d7d59b39d18d7c91cbd8cf5ca36d3f8209af01.nq.gz
    ├── 9a44cf41a481bafc88549d0dcb56ab3a832bc03f.nq.gz
    ├── 9a7cfa71559d71e8ac8317160d182380f01dff03.nq.gz
    ├── 9ac7f50460f4f85579d47dbf7722dfc3a4b3f335.nq.gz
    ├── 9af6df63068eb03982cb4a24d50aebc9515d80be.nq.gz
    ├── 9d6514b14a247621e5449921ab5ff8fa1aaf315c.nq.gz
    ├── 9dac36e0f8b9683c13e2aa7fc889f9ed37cb94dc.nq.gz
    ├── 9ea86d29df95a2b92d3df80909d78e18093f8792.nq.gz
    ├── 9ead4400658bd15ea48a4d9aa1403c8c41f6196e.nq.gz
    ├── a0ab7d2710eeee842d390596721a471f0780c616.nq.gz
    ├── a10240dd581037d2e05e3939bf0e3349f4d1d71c.nq.gz
    ├── a1d9d8d59891de1cfb52c5602fc5db6459657c95.nq.gz
    ├── a1f8df503446da89c60a90d9439da00cba9ca711.nq.gz
    ├── a1f9cf79318780e3295ce703f50aaa9aa21a94a7.nq.gz
    ├── a26287a76cf25c1d370035ddc2e9025923182c7a.nq.gz
    ├── a4476989919620dfcaba0b9477bc6fa1e9fd4aae.nq.gz
    ├── a49c48ffe09175b0926e696ebcf2a39ccdf39efa.nq.gz
    ├── a517a29b2fa8f3d29274d00204f5c79c311c2f71.nq.gz
    ├── a8c4c812db7936b9ed5e47df27be55c6f32ea7d2.nq.gz
    ├── ab0588e22096407aec1beba52a51ee7cc0e04c47.nq.gz
    ├── ac55cbdc9c3fc104980dc194fcd819ebe47e9e6d.nq.gz
    ├── ad933d6b17f7c2002eb7699a67c4187350102dd9.nq.gz
    ├── b0b85fa9ebf0c21a2aab39eb3b65b2d555b4af04.nq.gz
    ├── b0d30d1ae9d75ba3140ac76ad4181720fafcafd4.nq.gz
    ├── b6bd1b3acbd5e76f435917f47a90574e9fc217a3.nq.gz
    ├── ba70ce69ca66a133909b49460f6c1c2b5e0ac435.nq.gz
    ├── bb0e31d67e4e9d0f83abd4c570e93add9a0b1d7e.nq.gz
    ├── bb50f254163619bdeb151feff0b36b129de86d13.nq.gz
    ├── bbd1002cdbd0d1c6e96dbda866ca375177eb4088.nq.gz
    ├── bcabc8fb8febd5631a27e3d60e6178812db663c0.nq.gz
    ├── bcfc5057b56c3d6854bfb469fe7068555c87e235.nq.gz
    ├── bf220f069d5d1c52cda36acc862dbb718dba561f.nq.gz
    ├── bf30ff3cd792dea3ba52b36ff8ea74f52ffca8af.nq.gz
    ├── bf7bcfe78ea2c22e6f467fd9d01cf6caecb46b4e.nq.gz
    ├── bfc6a7b20075a749794ceb6152d995e8deebf291.nq.gz
    ├── c0794ae4fd0c2d30172e4cf48fa9fb7effa7ad6f.nq.gz
    ├── c0853de00f57c257aaa9926926e1e323efac2200.nq.gz
    ├── c0cab313acf43adc60cfb11a215f82450f397a6d.nq.gz
    └── c0fb2c610b316bb31116300ab6b089306d642c54.nq.gz

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

[modal-labs/modal-examples](https://github.com/modal-labs/modal-examples)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
