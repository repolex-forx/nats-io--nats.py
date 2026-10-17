# Repolex Knowledge Graph of nats-io/nats.py

RDF knowledge graph data for [nats-io/nats.py](https://github.com/nats-io/nats.py), parsed by [repolex](https://repolex.ai).

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
rlex download nats-io/nats.py
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6ffd84ce78b71a50076427c11168ede2de87534e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6ffd84ce78b71a50076427c11168ede2de87534e
│           └── chunk-001.nq.gz
└── blob
    ├── 00d225f379a4bba82f2ab4754452936e2d018003.nq.gz
    ├── 013f81bfc4141adfdf546cedee403fd6bbad97cd.nq.gz
    ├── 0150c79d7d675334d3c1b75894ccd19f27214d2a.nq.gz
    ├── 015b77dd18accd082cab8a8725695f7d6e9c439b.nq.gz
    ├── 015bc22d571d4001b7978c183ee1c9f2dbfd0def.nq.gz
    ├── 02edfd9fe70bab4fcb64fc85011cfbad2614c0a3.nq.gz
    ├── 02fba8726fef18c8d53f0c4e8511200616f567fe.nq.gz
    ├── 04574265df9d83aa50cbcd043163c7c76167514d.nq.gz
    ├── 051af0217d8d3f2e08932d05c6da92ebf109e5ec.nq.gz
    ├── 073cdff22460a874525d8fcceb828e68863ce0cf.nq.gz
    ├── 0753324d2e6268e3e73923e77801c29a29b12a28.nq.gz
    ├── 0850b8c29c38e4ce320d170187631cedd331bc02.nq.gz
    ├── 0a6c4df4bb07ae18842c4f6e3a835f0136099575.nq.gz
    ├── 0c5feb37d14b5eabdb4c1639bc3a151761be7858.nq.gz
    ├── 0cd389ab66e36599ca420b82a1ea686c3eff6e61.nq.gz
    ├── 0ce916decf45ec58dbbea2e2813825a069808c70.nq.gz
    ├── 0d424b8e6f002f705a8e12d4c6c36a12ebb3a3be.nq.gz
    ├── 0dfc5eb7f8c2d413c5ef98c2c99de96a495da459.nq.gz
    ├── 0e71faaec6e1cfc73f2d5f6a745e6f9613972de9.nq.gz
    ├── 0f54d62f2f2a79d37525a911f9df788f4c9ee49c.nq.gz
    ├── 11461c72b5e1b8a1502e56bff34b5bcef647c049.nq.gz
    ├── 1208771b36de222c735ca84ca57e2179138f5149.nq.gz
    ├── 1244fa748039014d52938848b0477429f8110315.nq.gz
    ├── 130494e69462f7137266ade8414c3cedb12f09f1.nq.gz
    ├── 1490ea138bffe5e4cfe17e3886ef5b303940b3d1.nq.gz
    ├── 149b9ee2f9fe19eb9bd16de91640a31df1725693.nq.gz
    ├── 158c3c37e2496957a0e9c6d18deb662dd4b95f60.nq.gz
    ├── 16c043406a2dea151f3933930d909768c6981727.nq.gz
    ├── 1761a300b0a2592d747a63d92967ced963e4c428.nq.gz
    ├── 19f87b03a2f434b79a1b69ee778fd09d424dd0c6.nq.gz
    ├── 1aba39c2e956797f50626df38765037927eee086.nq.gz
    ├── 1ad162fdcf9cc028557098962f1d22e5ca390ca4.nq.gz
    ├── 1aef42e2b0e9981c22764850bf13b5407104c1d0.nq.gz
    ├── 1bc9cf38bce3b7f6c7900d1c7ce918af877a76e4.nq.gz
    ├── 1c34ca6fb76c5429fd4a772162bbe0cd3910c2a9.nq.gz
    ├── 1d5f047885f9d5997eb860dd2d5fd83e1a97d93b.nq.gz
    ├── 1e58594dfd326d82bc3a2fe44477bcfc727be78f.nq.gz
    ├── 1f4cee53245345a33c05d2c3a8f5945b3120bab6.nq.gz
    ├── 1f663d5c5b9320efe1fee77c5f7d522bc9ece5f6.nq.gz
    ├── 1f7cc5d4e927bf156c10d178da50de702da2df19.nq.gz
    ├── 1ffd4b7b115c5bc0cc6fc0e1b353bbed8e30064e.nq.gz
    ├── 206a617acdb134af7419c91064147e9986c29357.nq.gz
    ├── 2099c21ab0bca20bec48cfdd18fcc87563c13121.nq.gz
    ├── 20a489529697dfb1397eb69e60b2a1490892c5c2.nq.gz
    ├── 20f5c07db99a477548b58b4506833d0007b13d60.nq.gz
    ├── 21ba569f7ce09bf1c06b5d279c787e14a87fcf6f.nq.gz
    ├── 21d6290af79fe5458d80be1c8ae35182fec5ff79.nq.gz
    ├── 224eff8c72d84f3a040b5bb98ae80567a58c115e.nq.gz
    ├── 2255aee16259251cbe97f3f82d4fb77f0cec8305.nq.gz
    ├── 228f57c51b4a8cb9b343cf6ce649014fd4d6ed62.nq.gz
    ├── 2392162fdcf49f1c1ef8ccf3e1f4a5a45e27344a.nq.gz
    ├── 245c6ecaa60e4374a785fff3c29b9cb3a49741ba.nq.gz
    ├── 251fefbc5360e28be1a0edb1d159f65376343cad.nq.gz
    ├── 25fcf08cb3df2547aa5c66cc3b76ed8bace6a24d.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 275f0f5fe9b34c04ef9575623c4a5eab1c40c207.nq.gz
    ├── 2776e1f226ffddd9d7ef1984d29b0d6d42714ac6.nq.gz
    ├── 280d7d6c90e3b8442a87335877aee0d5b7896eea.nq.gz
    ├── 284a31598229fca6f05b9337116b253425e0e5e6.nq.gz
    ├── 2aaff6ae0879ad80f4558e069f3be5e507806c98.nq.gz
    ├── 2b3122b9ab5ed3f02a449eb93c8b7929f839e334.nq.gz
    ├── 2b5c3312f476bcf3d34da350114d8e8d15c62c7c.nq.gz
    ├── 2b7c23f1b9600169e9326741200c18b04da93e1b.nq.gz
    ├── 2b808506fb317fde6b83ba6a6ec433757cbd62d4.nq.gz
    ├── 2c6206a98ed1e2138a455d0b9ff28b8ae862d786.nq.gz
    ├── 2c802747f6f860bda20577453a6e9f16b549c637.nq.gz
    ├── 2cd877f6f074529cf6ad0bfb1ce0f88623d74c23.nq.gz
    ├── 2dc0212ce250cc2bd5b1e11fe1750b5c38c5262c.nq.gz
    ├── 2ebc8fc1238aad9812626b81bc110409a05aa09d.nq.gz
    ├── 2f2ad7d665ba5ed5ea856a6b73d242c153131517.nq.gz
    ├── 2f59ec92073e395851a086e209a1e64f3193298e.nq.gz
    ├── 2fd3bb3dd5e624eb73db566086982be7fb97734c.nq.gz
    ├── 2fd5c500828279962ac3d197de0922af36d00edc.nq.gz
    ├── 30ddf3fbfbbd1f8286364ba9cd00c435543401e5.nq.gz
    ├── 30fb6c87726914684d176f6116bf6ba9ffb5fd2f.nq.gz
    ├── 312e9b2a110d59d1588ce6b9e52a4d6f9fb192fd.nq.gz
    ├── 32e08e20df9896cc53cdfca417080cab93f21d94.nq.gz
    ├── 343cc2d163b8ff4550ea1b46ded6287a0980c256.nq.gz
    ├── 36270cf222015ee353c109b0bad4ed177580e97b.nq.gz
    ├── 3658dc613ab4b8a8e4617e2da2f1e8127c1f93d4.nq.gz
    ├── 368b6e67007dabbb014a939a638332e2bd596fed.nq.gz
    ├── 36d249ba42820a179ee2496d1770ab82b244942a.nq.gz
    ├── 370a12368f9c06867901e31e9b3eaea3168e0266.nq.gz
    ├── 37caea2fffe8580a8c24e7abbda30f0b52d09172.nq.gz
    ├── 3a8b6f78df7ea549b68a78cc2af8a39d9c21e20f.nq.gz
    ├── 3aa971cf9cfd15e1a0bcfea187d1444adeaa1bc8.nq.gz
    ├── 3b1f7dfe1d5faefa2d319caf58f687a59538bf8c.nq.gz
    ├── 3d65ced20b0d8e1d9673e2051f93875d3ed8baf4.nq.gz
    ├── 3f66337f7226a24de8910fc5fa374945c7eaab75.nq.gz
    ├── 3fadd883626aeb43453d5d317e39470cac3ed3bc.nq.gz
    ├── 4028f6e4850b3dc0464fdef6daaef5fd936ff202.nq.gz
    ├── 41eb2f138d9916264b49457aeba819c1199e95bc.nq.gz
    ├── 426b408db1d0a217863431d2e05507212ca1b31c.nq.gz
    ├── 445962bebbc79d819edd651c4858763838ed13f7.nq.gz
    ├── 45ee9225bcc685b1170dd5694f42688a898bf045.nq.gz
    ├── 4816b811a34f8317e646cb2029e21b2f00f93358.nq.gz
    ├── 49cd5b2937abbb76d33706e398c7cd6b1664294b.nq.gz
    ├── 4bc01a0a1401f0247abcbee0e4ef2560e4d46a8d.nq.gz
    ├── 4c709b19a6831142a386bc7c129eb3f84648a9d9.nq.gz
    ├── 4d0f01fade1e4f5d34a4dd8852336faffa89c4f5.nq.gz
    ├── 4d24d670e8caad6cceeaf7008e40d8af5641aad4.nq.gz
    ├── 4e11c54ae8edbcc31c99d21e6acb6aa59e45ac88.nq.gz
    ├── 530b9e7e1f28f7e32296f024409cf791ef10aab3.nq.gz
    ├── 53aa0292cee3ae7f5588adf52a4fb722e32b7a0c.nq.gz
    ├── 541aca941e80b7eab91fe86e7e0e657dc1ce0460.nq.gz
    ├── 544b59f85f95a7cda4dafdc815f2de897c3ea751.nq.gz
    ├── 564138b1b8863c11cfa0ba119d9a8c99eb45ba06.nq.gz
    ├── 569b36cec70c0477625358464c34debf3aa2c0b4.nq.gz
    ├── 573fb2c05032cbaf8495ce2f3e8b0e5b44680091.nq.gz
    ├── 5a5f6fe4d585e3c6dd1e3a15d0799008e9862546.nq.gz
    ├── 5bce51c0e33d4827361db96a1dcd7c8c31f38541.nq.gz
    ├── 5d680baeaf04df467d6725ee909f76dbf0ae2c4b.nq.gz
    ├── 5d97df1eb1033f463640524c892cad57c6120cf1.nq.gz
    ├── 5e9e08a99648af3d180dc406f1fd3ba12afc0193.nq.gz
    ├── 61aa84587a8bd0cfa0d50bb5c07adbdd9d8c13a9.nq.gz
    ├── 6234e63fc0b7c143c29fc8342ec67931b17b9777.nq.gz
    ├── 6287125d0a7712b2dfa7e69f4616d08300d0ede6.nq.gz
    ├── 62ef64673ed77ca235beabc6432d9b7824cb5e70.nq.gz
    ├── 637418653e227341742b94cf0da40e5b65e6e540.nq.gz
    ├── 6381f542f123a7be274a0b9f1bb9d91f320b3e51.nq.gz
    ├── 63f9a5d558a6a9a37e694e159ffd9d9ca596b046.nq.gz
    ├── 64deb1e52582f086913b91ff0c3f58877560c0bb.nq.gz
    ├── 65d677e58e0fe3a737f8e2e4aa15d624400eef53.nq.gz
    ├── 66f6b0391f4da5076090a59caf727b0304778511.nq.gz
    ├── 66fd68d49899f72647b15506c4e47c376778e1fa.nq.gz
    ├── 67fedcd2e7d0c646df52cd4830d208451e4f93fd.nq.gz
    ├── 68cb21556d7e3445857055a323b492a439b67352.nq.gz
    ├── 69152c14fdd367b4208045d8c41aaba1798ad18d.nq.gz
    ├── 69a7d3a768c50f559ef95819502af39a60f201db.nq.gz
    ├── 6a598d07c3bb8a230e18a911f357803c8ed69da2.nq.gz
    ├── 6a654107d904eb36604f8794035d15ab3c18a51c.nq.gz
    ├── 6b1dc55e778ad0022b5bba943ceea0cf0382812f.nq.gz
    ├── 6ca5a1ef5ed89df2fc76cbf6de22565507ed668c.nq.gz
    ├── 6ca9ac5d308d0158b3bff1b5d86af61cb09b6d1f.nq.gz
    ├── 6cf4d9e91fdc6241fd94090401f4e99ca0011e9c.nq.gz
    ├── 6eb403b9bed06bbb1d3360cf15499367ff545b45.nq.gz
    ├── 6ee39eb079ccbb2fe1762c0dcdca232a6078bd24.nq.gz
    ├── 7019141d8fc6820aa6719bb19060ee6c5218cdbb.nq.gz
    ├── 70bc200a475be551a156906945f6c2383f06f859.nq.gz
    ├── 7158383b84b30fae5819174d97559dac315000ef.nq.gz
    ├── 71932cfc87fecfb8242bcd94a50e5008993aae42.nq.gz
    ├── 71a96d0f5a80fa36b4a5af3b4920913d1c259373.nq.gz
    ├── 74fdf08d8a25ede89b4b275606dbc480aa3fa46b.nq.gz
    ├── 75824c9973ea92d16bf337e43a3ecc55f8a6cb50.nq.gz
    ├── 75d7cbff052de9969e1ac929c5f2b7036eb7b67c.nq.gz
    ├── 75eb31e1921c681e6581f5f12eef75b1d16c5ff8.nq.gz
    ├── 760ba3a6bc41eb7bbc5db16040150bbb1a8f6cc2.nq.gz
    ├── 764188e681a4d4ab9e6545a4a4804d7b46a0870e.nq.gz
    ├── 767c223792c712788c2cdfcadc46e6e4a0a9ea71.nq.gz
    ├── 767c7cde7114fb3eaf60c1a7da235c2e77f03d60.nq.gz
    ├── 76a871f2c15a2c7de45f342b6919d0dfbb7fca47.nq.gz
    ├── 76f314d841be7a0b04a522697ee6082f12d2e49b.nq.gz
    ├── 76fa25cd710fc7e811d9ed932df5bb1655797d23.nq.gz
    ├── 786dfb8a460c4e3b69e350c1116ef1f847db31a4.nq.gz
    ├── 7885d2e160335223941e9685e9241b86882b3594.nq.gz
    ├── 7896d6425c1b9f515a5f2432e81e18c601fd9ba6.nq.gz
    ├── 78b85e94d118e98a7d39835fb59ee0a89d2ed5c5.nq.gz
    ├── 78cab9be6b2dc9ebfedcd0ed7273997922cbb043.nq.gz
    ├── 78f64d32e4de7c38c1f1cba83ab1bb333da1d076.nq.gz
    ├── 795ceecd0b8d7e26a42078fb970c8eef92840f22.nq.gz
    ├── 7a70341927469336dbd61f559bdac368c0f4ec6c.nq.gz
    ├── 7b964037472b92cf5e7ef6e11afa6854c99594db.nq.gz
    ├── 7b9c39d452e4159e531ea6d201a325160872880d.nq.gz
    ├── 7ba415cc6def6759894d5ef4c9b12d3ff9628d3a.nq.gz
    ├── 7c1f79fcf5c8b300f34c207f8d32d98f917293b8.nq.gz
    ├── 7cbd2e185d4985681f5035b7afab21c04a029ffb.nq.gz
    ├── 7d83f1b1e5663858b2d2353514a9f1caaeb7b687.nq.gz
    ├── 7e4c4c306f0bcf8aba64dbbd4d90b9a804e8cb06.nq.gz
    ├── 7e58589d4109a933d45e4246be542d0bd9955d91.nq.gz
    ├── 7eda9f0765dd4ad14a223d1f0fd2e4135c63778b.nq.gz
    ├── 7f184afa6bafdad1c6edf3e544bcde6850a51f17.nq.gz
    ├── 7f1a8db3ff481590bf0f38ef58a9f5ffab1b997e.nq.gz
    ├── 7f1b053530bf1aeb5d8208401853b6f39ea5cc62.nq.gz
    ├── 8283b4c85860b37ca3a68023b82b9f36802450ef.nq.gz
    ├── 828522a885bb496e04854b05d60cc1af53b46a08.nq.gz
    ├── 8337d40ebe381bfd54983a1c6c5e798b9511bb0e.nq.gz
    ├── 83996d9416310618e9921d34bd90ff8ba68b1346.nq.gz
    ├── 84041b15f674dc635709c310cfbca1763146e50d.nq.gz
    ├── 84518ea9485e20850c6903ed0a5927b51e4449e5.nq.gz
    ├── 847291a92cad012fdd38314630c1391da60ae118.nq.gz
    ├── 849dfbdf3e6c5d1b2fc0d3b797c09568f9ccd019.nq.gz
    ├── 86eec3250f404084a90b23bfadd7092446489681.nq.gz
    ├── 8733b4da9121c44981fb1579deed4393cd3d3a13.nq.gz
    ├── 8891434cdccc2cafdfe4469dfce52ab4e06f7d3b.nq.gz
    ├── 88d179c0f0c62929a9c58b3c07648497760a1b82.nq.gz
    ├── 88df063859b447f855983aa8fd45a63bec49ed85.nq.gz
    ├── 8a1579ab5e227c85826bfec18d41c2fa44a7f0df.nq.gz
    ├── 8af94e970085e741e2613e97ae3d65ee4d29a4e7.nq.gz
    ├── 8ce6768c3dcfe385926f8898b3b94633df9cedd1.nq.gz
    ├── 8d5bc08e8749789563f0e62ce85ea1d7488214d3.nq.gz
    ├── 8e930d242b736a327db4be94ba1db9a6f91db28f.nq.gz
    ├── 8e97550b408a869bd1daa4dcf3e900542236621b.nq.gz
    ├── 8eb4f032309ffab001a066c9075319206dc2ba53.nq.gz
    ├── 9011fe01d5878e885919cd0ec2c7ed4c243b5c9f.nq.gz
    ├── 9260240014ba0827f7606affef2bf2b2e921117b.nq.gz
    ├── 931c0771c7ad1c9ba1e2952b8196f6ad61434e09.nq.gz
    ├── 937aeed38e0be3ddf91c893fc0acca406e9f305a.nq.gz
    └── 94844714670b605284e18d48f21190f08e4d123b.nq.gz

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

[nats-io/nats.py](https://github.com/nats-io/nats.py)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
