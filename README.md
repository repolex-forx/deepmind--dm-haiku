# Repolex Knowledge Graph of deepmind/dm-haiku

RDF knowledge graph data for [deepmind/dm-haiku](https://github.com/deepmind/dm-haiku), parsed by [repolex](https://repolex.ai).

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
rlex download deepmind/dm-haiku
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5e13a6667200701e701090e1893421e074f442a2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5e13a6667200701e701090e1893421e074f442a2
│           └── chunk-001.nq.gz
└── blob
    ├── 00146fdcab9405155a780be7491fede5d191c7ee.nq.gz
    ├── 029a3562cdf23687998f2cac344bf02eab7684af.nq.gz
    ├── 0569bab5a2b3ccbfa4f17c6bf0a4c057642c91e2.nq.gz
    ├── 059c3def531f02ab2373625739ab3779c3f7f517.nq.gz
    ├── 091007abfb33b3a6e29b6e6aa7222940768474f9.nq.gz
    ├── 0a61abd648b0e960672f5d2712adcb38eddabc0e.nq.gz
    ├── 0ab6eae496885d2653445002a936e298744f8d47.nq.gz
    ├── 0ae2db372efd83467ca3004cc34cf0a00f7bdd8d.nq.gz
    ├── 0c06dd7c679bb3546de200344248b2f789408c7e.nq.gz
    ├── 0ccaab4b7426bbc115167c2fbf85eb1f7292b930.nq.gz
    ├── 0cd95878ab4eb406d39deef8f87101e66a6caca1.nq.gz
    ├── 0f3badba0e5cc416c11100f052f8acdda06b83d4.nq.gz
    ├── 12980b2a3ff7fe6defa106948d43867d535009b2.nq.gz
    ├── 12ab1b35a26d4dd1bf0ce67851fbc9db0ee28cf7.nq.gz
    ├── 1459d2955c795d023b5bb3ef531ff93e3182ae52.nq.gz
    ├── 153e5ed7ab13e27aacb88153991b126a1c90af2f.nq.gz
    ├── 15ee2022cf0a0ffe0bb4bf8e5924d859a938b9aa.nq.gz
    ├── 16f24cc7144676398ab6472c69b4619a0640a5a0.nq.gz
    ├── 17fb2a4734254f7a9d145c3f756805e8b38499fd.nq.gz
    ├── 183d505cffb949d77a92ba79120bdfac051b5205.nq.gz
    ├── 19d920f02f8f40ec9c3bdbb7dc3edd71e9d250d6.nq.gz
    ├── 1a21c1f8c48b401248ce4af60e26464104efdb38.nq.gz
    ├── 1b22795292c11b99550b9d48afe2b3c9ef68252d.nq.gz
    ├── 1d90512629480bf7be0e87aaa74d91a651c7dd7d.nq.gz
    ├── 1f068566d7574ce82ce7e64f800dfd1130644f4a.nq.gz
    ├── 2047c30014b6da790729ba218fbf595ce4a0184b.nq.gz
    ├── 21ca01a0589169dfd7bc092362fa4806234fef7c.nq.gz
    ├── 247d2b32a2a6b3b469b3a162650a28a24130dad2.nq.gz
    ├── 248215d9ad02fde9d67a619e4bed41820e517160.nq.gz
    ├── 263f7fb4155b83bd570779fe068aba234dbf4acf.nq.gz
    ├── 268485fdb5063035053465a99f6709d7161cb3df.nq.gz
    ├── 2882fa51db5c5045497fa80e4f7359eca7f20266.nq.gz
    ├── 2a381946aa65a9462a282e7f0d9f445e692f384b.nq.gz
    ├── 2a43901592c9f5e44ebe5c45ef823934f2e1a6e4.nq.gz
    ├── 2a49a6e954f9c12afbd276c78564675c4cd392da.nq.gz
    ├── 2ec949ef9214601922ae9c17bf6d705dd7250373.nq.gz
    ├── 2f799703e18082ff45ebbc17accf16a449cda0dd.nq.gz
    ├── 30fbc447d04b59aedd23ef85e76c09ea149189af.nq.gz
    ├── 32f1cee0b7790f83e6a1f709708a3d90235b73c8.nq.gz
    ├── 35245d0ca836fb6cac65fd40ea5e8ceb958c3831.nq.gz
    ├── 364c2fd776e0985ef56d99a55c1a33c0067dc297.nq.gz
    ├── 3916952ab8cc46ad4589cca2f94519e93edee31e.nq.gz
    ├── 3c360129fe1ecee8c2c2a3ba3605cf39f13c73ea.nq.gz
    ├── 3c3d1a53ee962fe9cc770284dc81e154cfcd2e12.nq.gz
    ├── 3d3bd66898ad24fb4a85d9011ba34cd10b0a1510.nq.gz
    ├── 3d8c8b0373d9fb5d8f608ea4e430170484f0ac79.nq.gz
    ├── 3e153e75b35586305df174498fa2b294df4beaf9.nq.gz
    ├── 3e67e9985b5cd86e02011c3a1ceb604928cceace.nq.gz
    ├── 4000c91d65face7324efa1b26dabb422568cb29f.nq.gz
    ├── 4009e408e70497621b2e88d2a56a1141b752abb3.nq.gz
    ├── 409b0e3c425ffce2875aa4bce47578f573b33fef.nq.gz
    ├── 40be31d50546bded77d624957f9e10bff60c5059.nq.gz
    ├── 416c3651fa580f3d8774e2713947604b6092b451.nq.gz
    ├── 41e2786b169d7f804ee0547bd2274c38da523ceb.nq.gz
    ├── 42bb12027fad55c3567401241d4dcfed55bd035f.nq.gz
    ├── 43aed3bb55288e8177ca20ed0f3c0e27ef78641b.nq.gz
    ├── 46a631ccd3be09c07a218446c620b6df1da6e319.nq.gz
    ├── 47b0df8ad83c0430980b11da4572168521318d94.nq.gz
    ├── 4840bff565b2ba29122a5d2490b6b3f3d95c98f2.nq.gz
    ├── 486b7b06f26ce08aacdea1b65a52d96d1f45fe4f.nq.gz
    ├── 4876c1f7a5e93fd38ea2357d2cc18405db2c6d33.nq.gz
    ├── 497e3f337c9bda5aef6d0af9a0f7c45492e1dcee.nq.gz
    ├── 499c30d5b8c2dc740925ae0ccf03d7076a9981de.nq.gz
    ├── 4a18649c4250031eaea0672a7a9dba9e24d2e3f0.nq.gz
    ├── 4a3493b2846269f4a69f7cd2bda0fda9de464d21.nq.gz
    ├── 4d377c3e1233eb767fc2815754897e869d768504.nq.gz
    ├── 4ea4906bb434214b2afb24b9ec71a9aba9c6bf38.nq.gz
    ├── 4f937ec88f4a577ead2877a820b924b175d23606.nq.gz
    ├── 5076c8c84d908823ef230bac100ad83fc920dc89.nq.gz
    ├── 51285967a7d9722c5bdee4f6a81c154a56aa0846.nq.gz
    ├── 519d4ab4c71fbe77805278d5408ec413467c1024.nq.gz
    ├── 51c0b32293f23fc302fd16fd00b51b5c47fe21d3.nq.gz
    ├── 52286ba9703ce65fa6bd3886271820db42ce4bd7.nq.gz
    ├── 5330c98edbde338618fda8e4bb1906b40e1ff074.nq.gz
    ├── 53e3d4cfe82e3742fa2758dff8c741bb9d9cb64f.nq.gz
    ├── 5400a389f8a6abfc1b5ca8325d3cee69aeba42ed.nq.gz
    ├── 540cc07e6849a716831f0dee1fea92fb36d23208.nq.gz
    ├── 5749b591d3e5dac6fc53c6fe2353ce58e60e5431.nq.gz
    ├── 5755810fda92d06eae5736306e47f51aeef6d887.nq.gz
    ├── 57dd53fdb22c9f1352f78ec702edfab5b532447f.nq.gz
    ├── 590e07f43298d82cf5a32ed5e279cc66ac6b68e7.nq.gz
    ├── 592f4d79d78f92d8aa3737a231cf00d5735aa7bb.nq.gz
    ├── 5955400e7c379d08b008a5188d0c36ec66a7a54c.nq.gz
    ├── 59a5705885a37dcd8a0386e17f67d7f9cc2aca65.nq.gz
    ├── 59c42e278456bbb699dc5328022116bb9bd52d22.nq.gz
    ├── 5ae01fc932bdc07ee3b834cbb55a785f25392bdc.nq.gz
    ├── 5d8884dba5cef4208f422ad743d9b5ddf2aa8568.nq.gz
    ├── 5e509bc5022e42e678127492b708291fc4690cb8.nq.gz
    ├── 5fff91a4332e0e5bc9bece719d104d55bcc0ef30.nq.gz
    ├── 60370dd45ee6d116b5338f90a2bfe8f466eb8abb.nq.gz
    ├── 6183c48748875e30a278ad63c1872c9f50e0cccf.nq.gz
    ├── 63ded8999e991c095ba9b1a5cd36bed181b9dbf0.nq.gz
    ├── 64c7ab990b6f38b0746392f313521df4f19506f0.nq.gz
    ├── 6563bb16c77b2268228bf0a8b6e5e5765fd4b90d.nq.gz
    ├── 65fb908de2ac391816d2f4fb71b27d964c935b72.nq.gz
    ├── 67950affbc8b05887269c41292dcda429a368101.nq.gz
    ├── 68921e86bbf85c89e583758d5a7a8f0e3e1406af.nq.gz
    ├── 69c5063d0a0e79a753bf05c5e55a8873f9df07ae.nq.gz
    ├── 6a222db9804913dfb49012315c78bf906c29cb2f.nq.gz
    ├── 6a4d49b62b50cb3a90983173aef09ac8a1a4a84c.nq.gz
    ├── 6b6a4e2341ece40fd18b3f0749cfb9cee1d07eba.nq.gz
    ├── 6be1330e23ada794fd68b6adc47b91a9f30c6700.nq.gz
    ├── 6d46cf867524e9264a17c257687f492bdc56608c.nq.gz
    ├── 70c1cf0cb053178ccb077e7206167de957adf2d0.nq.gz
    ├── 7136540b6a96bf287aecccdf1e7b778f9832c203.nq.gz
    ├── 733a480e05db854b77aa95f051373cb1124cc013.nq.gz
    ├── 74114ece3022e55ba29fdb573648ae75e61b1987.nq.gz
    ├── 74adadc6b407e44ba7c63e4addfef8e6e00b0af4.nq.gz
    ├── 756bf4334313e53117946e3ef2a37677435197a6.nq.gz
    ├── 77d535cda5b8d97518e8e1d4a153bc572a384d23.nq.gz
    ├── 785d765432eac1d44cad291561c36956080ccfe1.nq.gz
    ├── 7c2a4780155e4d4282e889e2514b0aa384c1cbec.nq.gz
    ├── 7ca0d42ca4638a27d192f45e3cb6268d97462eb1.nq.gz
    ├── 7e1b2137fd208bc990f607bebff2ee4ea436381c.nq.gz
    ├── 7e571610961968773533bd15e231e13eaddadb82.nq.gz
    ├── 7ee051d7bcd7e988dbba5fc074eb590b209c37dd.nq.gz
    ├── 7f088a2d641be18352438276027d261a7c067345.nq.gz
    ├── 7f94ac68cb3c879e65f10217d19c16c4c57adbe0.nq.gz
    ├── 809c60dc2fe01c696826218cf1bf60a08d39bf3f.nq.gz
    ├── 812e2b9a39db5b6c152be1027fdb6c68cb38216e.nq.gz
    ├── 81523679eb66d12225e7d41cddd21816de99f181.nq.gz
    ├── 827cba92dd10fed4bd0a9cdc1f8fd00f7c99fb47.nq.gz
    ├── 82e8f7d5980e5faa815bc8ed450af071a22f3061.nq.gz
    ├── 839570ca33b411cdd5121b9bec740c95afd9999a.nq.gz
    ├── 84d8417355ee2bcb0135e2682758d3c5f2010c94.nq.gz
    ├── 85311e065ee3877bc03245688a6434e4ef50a851.nq.gz
    ├── 85535e32938ae5b8016e53b1c37d41f7f8241e97.nq.gz
    ├── 86219f2002f376f462de88ff0126842e3454cef8.nq.gz
    ├── 8792603bd68ee6bc5acacb13714283b1fa6101e2.nq.gz
    ├── 87a93f9db61a6666b2ff6d50355371bddaaa4559.nq.gz
    ├── 88dd68ae75aa8b77fa09f50b86961c6db78dbebd.nq.gz
    ├── 88e22634773e1a5ab19babb23686ba4d89d705d1.nq.gz
    ├── 899be1a341dba04bb9d516c0acb4eb4232c09c60.nq.gz
    ├── 8b4566e13e8cb0cfe77f9dd216aa8a0449a6eabc.nq.gz
    ├── 8c26a6ee39317f58ca8a1bbcfe5040a07035576d.nq.gz
    ├── 8ca191503a64613608fb5925574370806caa0e6d.nq.gz
    ├── 8cf3e0edde3e762225abe19b385e64ee2253caa3.nq.gz
    ├── 8e12bc0308af278b605c2071a7bb119e2b8f6633.nq.gz
    ├── 8f5b7fa830a4488fefbcd258a914184357837690.nq.gz
    ├── 914a41758b558649b6d2ab1b20eb06d796ee7e7d.nq.gz
    ├── 92668044fefcfd2fbab122152d5fe9b48bd8e4ff.nq.gz
    ├── 95526f4385d40ee2cb57eede7f99f9f51fca2c39.nq.gz
    ├── 967be6d24d3c4f729411f879cce3e5aa36cfd465.nq.gz
    ├── 983aa07294ff07f19519b3d84771240068f3a35b.nq.gz
    ├── 9846de954dbd43612b3883bb07bf93044735b464.nq.gz
    ├── 98acb5cc45b8e8133862b2408e647affac004815.nq.gz
    ├── 990685b243fdc5801a281de6234e52c04a265962.nq.gz
    ├── 9c600a3d6278135f3a2cc2b6089769a067e3e52b.nq.gz
    ├── 9dfbc30cce76127d9d6d0a598529c2429da4bd3a.nq.gz
    ├── 9f54b68781c6e8878cc0730882c5da2a2960626c.nq.gz
    ├── 9f58c46ac1eb74b68a4c2763c5aa23411d3645e8.nq.gz
    ├── 9f9401329c8c8d49f7c51d6262f4f69b9e27e92d.nq.gz
    ├── a0e2ea64f265616dd00c69f0c72bce0ad11551c6.nq.gz
    ├── a1a66c9601cb2620e1d0f93d4772af4c64296516.nq.gz
    ├── a26927454c823805b332d4ba406bde3893c02cf7.nq.gz
    ├── a3d87aff3421a617b7791c245e523ef95198c892.nq.gz
    ├── a4f7fc0eae0d272ab4aa1805485eeed60bfa1dd2.nq.gz
    ├── a62fba3321282b6fb5d2bfc4d117b12afc49c65a.nq.gz
    ├── a6e05b0602ead50beb251b22fe275acb77ee6d42.nq.gz
    ├── a7ee28c3c32148347e666c2ece67d81d618a5a16.nq.gz
    ├── a82312353147f6f6f87d7b35c36c3a2a368457a5.nq.gz
    ├── aa978b8719ba6488e50998e878042fc9328a3f51.nq.gz
    ├── abb3417b4377efe71c3079d3f676e0b687f10987.nq.gz
    ├── af55deb2ceb19c8c7481db7cd4df2b9eb22c24c0.nq.gz
    ├── b07de99b6bb807e732934188717087272adb023d.nq.gz
    ├── b0ab37c2114932c6e6ff4a01140ade8e7aaac1bd.nq.gz
    ├── b13d972b282c1893f862831287ff8e0c5e5820e6.nq.gz
    ├── b36076bb24e4707f571892fcaa57b932f0b2919a.nq.gz
    ├── b4593e86988a26b7c529e6ef1e119e70835850a2.nq.gz
    ├── b8c3eea54d769833dc6bbe35ce1a3ffd2c1c568c.nq.gz
    ├── b9c715a1929b1eaea1cfc7b38ca40d9e8d114b33.nq.gz
    ├── bb7cc1ca3af125805ef3e062e2833a7002e499a8.nq.gz
    ├── bc38d350e74a0678d53ec8e745726fc96e1d793c.nq.gz
    ├── bc652c2864cad0fb48a3d823ea86e9961e3f6ff0.nq.gz
    ├── bcdfa03ff5919e6bb25e39f822c81220ae97fa2b.nq.gz
    ├── be5e3d8d496113c808c88672cd321a06ca1b367c.nq.gz
    ├── be89ec1b56f1d04932cc91bfb46c5a041aa36eae.nq.gz
    ├── bec7fce3b501b178a25450b026a8958931d994f1.nq.gz
    ├── bee00db60d72d85b91773f8f1394f99fe5e6d40b.nq.gz
    ├── bf54dffbd77c940193558535a520e20e3ff888eb.nq.gz
    ├── c055f8c7ac5b6b16bc079f7db4f09b00e59323f5.nq.gz
    ├── c5640b41ad33598b735fed859cfde3b9903372a4.nq.gz
    ├── c5c8f3db4b0c7cf1b973a795aa487004728b7e0d.nq.gz
    ├── c68c716b69c47a19ce020d8012cfa9784ffcc5b2.nq.gz
    ├── c78608a9c3c7d72b97b7a0fcc3b30da38f8e2530.nq.gz
    ├── c87fa4ca80ac213c0ed2ddc5316ad2795baa858b.nq.gz
    ├── c8f8e4abd7484e9d0465a52c216b881d8e86fdc4.nq.gz
    ├── c9e653b3fd945461b52a49316b8ba73acf2462d8.nq.gz
    ├── ca1478ce647557cffb225c70f7726cef11466f49.nq.gz
    ├── ca6f6483e67e7ab1858c68a463bab93718a7fa9c.nq.gz
    ├── ca9d6922efc5f856a474d849811d1874dcd34b47.nq.gz
    ├── cb0e8b4540b062c15e935769cb1b77574586c0e2.nq.gz
    ├── cc9875f4b6425745d056f417562d7f5fe1a8f56a.nq.gz
    ├── cd03f8ac4615f8dd29708cfbc95ec47d4c269885.nq.gz
    ├── cdada0c0c819e2afa349d5c8bce8200331cf4190.nq.gz
    ├── ce705bb9a87f3e232ed7232b4aa007f37e6169af.nq.gz
    ├── d22e9e0df74459ba78379f49e90cacc285798a45.nq.gz
    └── d27e855871825c6d59e42d253dfd49e10adf46e8.nq.gz

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

[deepmind/dm-haiku](https://github.com/deepmind/dm-haiku)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
