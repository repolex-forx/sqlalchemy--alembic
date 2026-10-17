# Repolex Knowledge Graph of sqlalchemy/alembic

RDF knowledge graph data for [sqlalchemy/alembic](https://github.com/sqlalchemy/alembic), parsed by [repolex](https://repolex.ai).

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
rlex download sqlalchemy/alembic
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 723d9c2cc83b77b071db967faf49640295b6f15a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 723d9c2cc83b77b071db967faf49640295b6f15a
│           └── chunk-001.nq.gz
├── blob
│   ├── 0127b2af8da1d11127062dc22de75206211c081f.nq.gz
│   ├── 02626e2cf6d4cbe7f57dc95fce2399ea93df0dbc.nq.gz
│   ├── 02ccb0f6de8d6654b151721a0fe4f9441d194318.nq.gz
│   ├── 0374b2a4bf632a53e377e6657a6bc702e13b9293.nq.gz
│   ├── 093add6e97a8378c413db5a47944247d9f216321.nq.gz
│   ├── 0b23a63a091e364478864bc2ecb33ee3755d0ee5.nq.gz
│   ├── 0b5511c6c583bd032131fbf8e5db25b2b8c82fab.nq.gz
│   ├── 11016301e749297acb67822efc7974ee53c905c6.nq.gz
│   ├── 1534a681aff4634e7816b98192e2f09b8890ee6f.nq.gz
│   ├── 19ef3e828f5fca56539b726289e0a2949fa3d1f3.nq.gz
│   ├── 1be4a4a2290b0ce0c0b5ae17cbae34263731f4c0.nq.gz
│   ├── 1c0d958d37f57ce11b4e7317a2786b618d688828.nq.gz
│   ├── 1d2b3446e40f0aba6e6820d0232c7301f46be5f5.nq.gz
│   ├── 1e58ea5fa6fa9c2449bda5c406563635933a22ff.nq.gz
│   ├── 20360f478c66170906a920ae98bbf8945d0b2c52.nq.gz
│   ├── 204cc4ddc15b1457cdbacb2c238a625e19c49100.nq.gz
│   ├── 23697220e1f411cf777052a15a666468b1ef062d.nq.gz
│   ├── 238b58e044c88a2349a0e973e63ef97d5a38b742.nq.gz
│   ├── 266a20660d6e8de99cd09e9ce73b6b606d4a0351.nq.gz
│   ├── 27395431b19bbb56bd1c2b4a2f93a5b1e477a1cf.nq.gz
│   ├── 28381e63cde4b51ab4873bcc16b08b747393492f.nq.gz
│   ├── 29d823a9ed829954f5981186d4981611f9d8c0e7.nq.gz
│   ├── 29f6bff55eab7ca0312694de7e0ec9092d923529.nq.gz
│   ├── 2b5c4ba95e6be4ffeaddac92212378f520b54a4d.nq.gz
│   ├── 2d114c893a5fe93154537667ef577d0afa70c6f4.nq.gz
│   ├── 2d28b02d43361d14c1c4a6ec7b09560f81964d71.nq.gz
│   ├── 2e2491bd74d91db75fb7dbdd347683718d4854cf.nq.gz
│   ├── 2fd07a95b604b1607ab7347dfad67cb16b220160.nq.gz
│   ├── 305a4441eba4f503cf9500643a86e5f76f4b1287.nq.gz
│   ├── 310f5cdcb48dd9a5a242e6632f4c471962b2859b.nq.gz
│   ├── 32ea5d9748923114b344597ad789f2607173331b.nq.gz
│   ├── 36112a3c68590d6a8e07fea0ce70a5afb38c951a.nq.gz
│   ├── 366f464194bcc2cbee5a36389064a240312d40d6.nq.gz
│   ├── 37e7312e0e15851146eab91aaa60e683664d445f.nq.gz
│   ├── 38c80f358a6929b8edccb344cbf3bac675c7ddd5.nq.gz
│   ├── 38f1cf06dd5e2693639d7c230d301dd2ff484763.nq.gz
│   ├── 39df47a963a27580a9f74911197a0f2922c3a341.nq.gz
│   ├── 3ab58e30f6c922717d127dbf9b6827e415a74fd9.nq.gz
│   ├── 3d10f0e46cb36643685750db6dd5084fcbb33c32.nq.gz
│   ├── 3d7fe7e18222fd54e2e49237a78327cd641e7917.nq.gz
│   ├── 3da498d289ed11e1eb140384db8d601bfcd524aa.nq.gz
│   ├── 3dd49d9108bd9b7b11737fdc2a307be08456d008.nq.gz
│   ├── 3dee9fc9903f74fd06adfaa837f22af51ec6dcd1.nq.gz
│   ├── 3e8bee1e41d921f1671b012085ffa3a37a643d68.nq.gz
│   ├── 40b940a764ba8cfac497065c64cd584fe6a0ca16.nq.gz
│   ├── 41e186c602af70840b4de4b00c0f7ea60223d399.nq.gz
│   ├── 445ddb25125aa63994052dd4ecea1362dc91656d.nq.gz
│   ├── 45778ae77e3065994d699d9b9e02d7f4041a260a.nq.gz
│   ├── 478a7ba0e8e6f473450138d41ce231d0b9127a84.nq.gz
│   ├── 493bda7f487ba83a4723831a1a03b21a967bfb2a.nq.gz
│   ├── 495057e6df09ddaa3da2872fbcb780d91abd03da.nq.gz
│   ├── 4cf111d95c2bc854b45ca1e0884442f3836a20ea.nq.gz
│   ├── 4d5c5824b472b9c4dc19ce1a30dba9273a834a74.nq.gz
│   ├── 4e88101e232a4d87382b4e5728bc1fef0c8bf321.nq.gz
│   ├── 52622d3e9cdc3ae207e403501270844401f6fc21.nq.gz
│   ├── 5746979d87377dc3c645e18d2ab98c685522cee7.nq.gz
│   ├── 57798ad1fadcfe9f5c8f279143ddf4f931044808.nq.gz
│   ├── 583101395dad19df5de1b3c24798c349ec1b7334.nq.gz
│   ├── 586691b2654af4fa2cb11bd4e8fd9061410166cb.nq.gz
│   ├── 587ea86c711d6ed9f2b9f2a8ebd85d84ac5b1ecd.nq.gz
│   ├── 595ed0b28a3bcd1f8e208b1b8dfe6c7efe6b49bc.nq.gz
│   ├── 5cd4d9b14db6d6e9446ec9a7e488990c731d2399.nq.gz
│   ├── 60242bd640f876eaa24bc0dfb41de3cb96406a6f.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 60e8915e6451eee438167a4ad6d45f4c5b11dbb0.nq.gz
│   ├── 62f21fb69135bbf5b0d57cea3a6bc0d1f73eec13.nq.gz
│   ├── 649cf508dfbad0592b8f5308cc3040ea3ee5a4b5.nq.gz
│   ├── 653b5dfbff676efb9052d59a6854565863747c5e.nq.gz
│   ├── 66e503b643cc943ee2100583c2f880dcd617e69e.nq.gz
│   ├── 673fd65aa32b6b92c406786347d36f49d498416c.nq.gz
│   ├── 6925fcd3d5ffd30cb3c12cbb3021eaf850ebf4a6.nq.gz
│   ├── 695b3d50326d86e6ddffe04e64643b951d5e15d9.nq.gz
│   ├── 6c3d1a93907475d2bfdcbafde9216b1728b223f4.nq.gz
│   ├── 6da038f108b376f57e8b0c8445eda977b6011bbc.nq.gz
│   ├── 6dd8111b213c1092a5217abbd1c21f2c2ec02724.nq.gz
│   ├── 6e7dcd2ca53c0a7dfc9719f948bb5d36b9971411.nq.gz
│   ├── 723083e2832f53662a390641db65e733efa8350f.nq.gz
│   ├── 72cfe60b9663a2614ccec4113004d27d818fdf0a.nq.gz
│   ├── 733a0470c3524cff14b8d3a54298cb7055db5599.nq.gz
│   ├── 73826c56868cae477f586cc21e99fdd9042c1048.nq.gz
│   ├── 74102e4bf54ed791aeacd57ffa3c90e7c462f04a.nq.gz
│   ├── 758fca8756c8bac18ea91888b6de484a11618018.nq.gz
│   ├── 75b0dd6a48bc048bd265ecd0b10f614224e3a408.nq.gz
│   ├── 75bcd37aeec53d4afb2447a0f7aaf8ab5ef4c160.nq.gz
│   ├── 76846465bead038ac27e7460c8dd9079f4850a1f.nq.gz
│   ├── 76a8a4ef2a9fbbf8df6486f0ade1c362d14ce98e.nq.gz
│   ├── 76b65e0eb0b662574af8ec235a9ebed0df583e60.nq.gz
│   ├── 7d3f535791c3790a1eadbb12fb84f687d24a9d02.nq.gz
│   ├── 7e54739cb828e909804993cf5343b33d808c241f.nq.gz
│   ├── 7edd43b0c9aad1e751220c1bd2beacd31873d5d6.nq.gz
│   ├── 7ef074f57893180048c6193455b0dd1d507c0603.nq.gz
│   ├── 818c0cb4074d7bf3f81e28fd665571349d6f9df3.nq.gz
│   ├── 8194030b79e0ef94bed9beba44e38991fb7c9265.nq.gz
│   ├── 826ce4444a19b8644cabd9f1bae3c143f7ee13c9.nq.gz
│   ├── 88cd1a25ee5359c7bd36c167c0e846567afb94d6.nq.gz
│   ├── 88d96cc708b4c054db9918b0be6b3333577fc85b.nq.gz
│   ├── 8915c2dd0d66c738cfd3de009d64dd07de85362f.nq.gz
│   ├── 89296343ea63634868499747eaa8f75f1f85f833.nq.gz
│   ├── 8964022c062cd3febf354a73448c150152a57ada.nq.gz
│   ├── 8be1a2566e63db0a7391446054b724d1e68b46cf.nq.gz
│   ├── 8db56606ddf7c4c7b0c47e061f6d94e4ad506209.nq.gz
│   ├── 8e667d84c8a46494a83c38d950e57e96abffd7b7.nq.gz
│   ├── 8e889b9fdb31fa840350a627d472f14619b91538.nq.gz
│   ├── 8eb9bf7012570a089557be0a9c9140fa48eb165e.nq.gz
│   ├── 904a916d057c71351cb4f844c73a0528289eebe9.nq.gz
│   ├── 931e4e2620e571170ab3534c8fb7e81fa6a42870.nq.gz
│   ├── 94c1f8584bab095ee3ddbbfd72f39e90909ff9ba.nq.gz
│   ├── 98e4f9c44effe479ed38c66ba922e7bcc672916f.nq.gz
│   ├── 9b9a020793ea3cb77c2a30aa3e72c07970d98804.nq.gz
│   ├── 9ee6682edc33ef307fe629b3523279e6d36ba7a2.nq.gz
│   ├── 9f2d51940080a1a7c954a8916dab86f00d5a4aa5.nq.gz
│   ├── 9f32f5a229f29acb80062198f857a07d7a7a2cfa.nq.gz
│   ├── a09214bbb9b2104315e86ab782092a95e1550e92.nq.gz
│   ├── a1901cfc03b6e75b548e472462c4c2dc2593315e.nq.gz
│   ├── a396b40a5cd4fc16cd6ba787f779e052fc0957e7.nq.gz
│   ├── a4530b8928e4e9897474f4ba742986b320c3f9f2.nq.gz
│   ├── a4894bca5593e718317054381085c1517b3939c4.nq.gz
│   ├── a63b3f2f9f2a7bfd879e5b06a05f0c6a64277b8f.nq.gz
│   ├── a73f1a630aeef0ae4d37dd6cdb8dff49db4870df.nq.gz
│   ├── a76d92520017c98963ccda37c923e0a192c47610.nq.gz
│   ├── a869ecb19310908f4f889cf4bc43e55ad50b1df6.nq.gz
│   ├── a9a8de58962444e8025d004ee4a218c0d4445ab5.nq.gz
│   ├── ace73359bb75740c5658b73c31431804f76745f4.nq.gz
│   ├── adfc93eb0c2fdf4e8104faab95bdb4bdd210fbaa.nq.gz
│   ├── aef15abdd04e1da44f5e8504fb9358404c8981cb.nq.gz
│   ├── af028305cf165d2c4134525ac0a1665fd236807c.nq.gz
│   ├── af1b8e8702f4986b4e17ca129dab18f338803da4.nq.gz
│   ├── af478101e2f2e856e1108e840c98c3862e5842bd.nq.gz
│   ├── b03e235f9a94f5893b5d33eb8756eee57a26853f.nq.gz
│   ├── b0fa765e544d13e84408fa37cef8cbde79f2e3f3.nq.gz
│   ├── b3a1e8c08977ee51af70ba3c5a87a9851c974c19.nq.gz
│   ├── b400b2582dc527baaf6b743ed6a3ca1fc3526fb1.nq.gz
│   ├── b54c54a7cf571674fc9e601d96fc001782001fc7.nq.gz
│   ├── ba8929edaa80f61f81f7f73255b68c22f3a57c67.nq.gz
│   ├── be5dbb5aff338b3321807af88062fb3772a443b2.nq.gz
│   ├── bf695cf23bfc41c296cdd2c0bed37b6c1ad97875.nq.gz
│   ├── c0b2b4ae130ed685be0b2df0b78531891568d8a8.nq.gz
│   ├── c1a5c17f4e7e1216baf6416a4a65e0e7cb8ef642.nq.gz
│   ├── c1bf062ed666396520b4614be61b8079ca64cc12.nq.gz
│   ├── c334174ed08f3c23545cd8987f6c3c16df0bd936.nq.gz
│   ├── c4eef3d77fe33ac6bc59ba7fa3d06f19ce93ab72.nq.gz
│   ├── c4ef92f27a43850681d8fea41831c0468779b18b.nq.gz
│   ├── c5fdc8db0c59cc166be96864bd1d0a0a268d7b2c.nq.gz
│   ├── c8280ad55e2f7bc8741ff6f15d5d8fb89d26ca81.nq.gz
│   ├── c93fa4b5d3799a9938d679c6862f101e2ada0d01.nq.gz
│   ├── cbca097151efc4126b4172033dc74c5d5de1a20f.nq.gz
│   ├── cc136d8bc467b0bd1ad33a249812eec6e025acbe.nq.gz
│   ├── cf58bb83dc5a8dffd4dd3dd96dc398943200904a.nq.gz
│   ├── d1549d4d900efaec9e10017a2c195212c6209cfe.nq.gz
│   ├── d4a2c5521847f6d34003b49b2826ae49b1d84c29.nq.gz
│   ├── d4fd8d239909a751f8041b640c7de56f4b1d169a.nq.gz
│   ├── d580a46c9c2ec1074b87701cd77d2e4dca203286.nq.gz
│   ├── d69736e64d0f18f1e7359ba9dc56b1111de9d23f.nq.gz
│   ├── d78f3f1dc54c13a52b64e8d668c2baf708eb20bc.nq.gz
│   ├── d7d6d79fbd4dc07f170a23a71804c25015a28bd0.nq.gz
│   ├── dcee6fa4b6f0b109519b6c6279b09ffa4959ce9a.nq.gz
│   ├── dd8c4c4b2ba53bad1ed7a4912c959afd577a6362.nq.gz
│   ├── dfd718d3b9ba72cdc7b5f14fc5802e2bd4fa0dfa.nq.gz
│   ├── e0681ea18c2b7dd1f8d5a3f159b930a94c438ae2.nq.gz
│   ├── e0d0858f266ec27b243e8b92301fc7002e1f2745.nq.gz
│   ├── e24a4b4842fa50a78a0968e5e69d17edbc4ca5a5.nq.gz
│   ├── e26416092f842d64bdb83ae2c68f5125dd467e41.nq.gz
│   ├── e37680771bc5afd215d970171aacc6b344becaf1.nq.gz
│   ├── e587cfb45581074ff8b1929eadb3e665bef0e21d.nq.gz
│   ├── e69db6320b164c3e79fb1aea135443c3089330d7.nq.gz
│   ├── e937b64eeed2fd980c214ab87505d75041b581ad.nq.gz
│   ├── eb2676cee8c98f19f978be0b490ce0aa6ed9f7ca.nq.gz
│   ├── ebe6a0f68d944383cf31dccc6bc4553539808e2e.nq.gz
│   ├── edbbe051b1346947f7643c120f73b7aa500f1303.nq.gz
│   ├── eeb032a163bd95f78c3865555ad09be95f5d031e.nq.gz
│   ├── ef0d3c6eef9c95a4d79e775d27603f067c8cd869.nq.gz
│   ├── eff3676e8490d042857004b3d0bd19ffe859ea84.nq.gz
│   ├── f046ec91427e2f4edd53dcb5409b21955c8fd0af.nq.gz
│   ├── f28e9de40ee3ce38acb9f676e1d603514e3060bc.nq.gz
│   ├── f2f72b3dd8d3748b36cb7acfcda7abf8468b6926.nq.gz
│   ├── f3f5fac0cf5c1e56d44f42051b6d829f7026c86d.nq.gz
│   ├── f5d6d0d97d33bd0dbaf331df0795451a6ef72a54.nq.gz
│   ├── f7338f5cc2dcb4a56347d0d874fb427261c45a09.nq.gz
│   ├── f8c99d2b2a6f047abc02a7ca3a2aa472af6c6ffe.nq.gz
│   ├── fabe0e20fb3e7dc492b896b48eefeb0b1f89c167.nq.gz
│   ├── fb38d9aa498259f96db47200f2594450e47e0b38.nq.gz
│   ├── fd30bf8fc71bee8c420ef6865a608fcada933112.nq.gz
│   ├── fd75881881349c9804d7ed24c5c312af09c81a23.nq.gz
│   ├── fdacc05f68ff5abb9bd31a924ccaa48ba8d23de9.nq.gz
│   └── fef4c9c3655d6307f084867c3ed00f9bea24fd2f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 723d9c2cc83b77b071db967faf49640295b6f15a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 193 files
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

[sqlalchemy/alembic](https://github.com/sqlalchemy/alembic)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
