# Repolex Knowledge Graph of pyca/cryptography

RDF knowledge graph data for [pyca/cryptography](https://github.com/pyca/cryptography), parsed by [repolex](https://repolex.ai).

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
lexq download pyca/cryptography
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 622d672e429a7cff836a23c5903683dbec1901f5
│   │   │   └── chunk-001.nq.gz
│   │   └── 91d728897bdad30cd5c79a2b23e207f1f050d587
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 622d672e429a7cff836a23c5903683dbec1901f5.nq.gz
│   │   └── 91d728897bdad30cd5c79a2b23e207f1f050d587.nq.gz
│   └── repolex
│       └── 91d728897bdad30cd5c79a2b23e207f1f050d587
│           └── chunk-001.nq.gz
└── blob
    ├── 0002462ce85dcda4d1038319b5989a3f859a6213.nq.gz
    ├── 00074f5b05074bef1a130a9bd3b83dee6a90e0bc.nq.gz
    ├── 002fbaf4b0474fe45eac36dcecbb761859f76e4d.nq.gz
    ├── 004faafa66a585df2bfdd7312429dbc2a2716dd0.nq.gz
    ├── 0063b7eb3559397d93e92e9a753083bdefd5ef48.nq.gz
    ├── 00aa6feeaedc6f0fd53c19543aab327e77bc1af3.nq.gz
    ├── 00b9a7ac737ac0c2e2e7877e03efb5fd5a41838e.nq.gz
    ├── 00bc99d2227cb303417ca4dc10f74014dbf23626.nq.gz
    ├── 00c01e29939578fc56b7984958ae33a311c83ffd.nq.gz
    ├── 00c7a7a2d1e0f66e0a9c59a6bfd1bdb990e972fe.nq.gz
    ├── 00eba5b24b9f0529727c7e3a8a30790737d3e682.nq.gz
    ├── 00ff94d6934dcca82d84cd79ca7ad3b9427949ff.nq.gz
    ├── 0125a15548c5b3580ea5faaf7b6f71941c9a5656.nq.gz
    ├── 012685abfb625ad9960b046e4406623f97721f3b.nq.gz
    ├── 013a42f31942df3c7b9e17631c9e8df41469ef57.nq.gz
    ├── 015225bd03a2488403a68e1b6566eafe174d09d3.nq.gz
    ├── 015ab9846574d6be8a748a95b2c9c796e3b6151d.nq.gz
    ├── 0169ac7b3505caebffeacb4a456158e58093bf56.nq.gz
    ├── 0178d1645637831f57fc993ccbeb96446f7a47d8.nq.gz
    ├── 01b6233a1511844c3158a3c38447d1a2bdc2a823.nq.gz
    ├── 01b78d23b7b407cef90210c204677b9c87ba4e86.nq.gz
    ├── 020cdb2b8a876e54df86500c3324b5f8b21a94ea.nq.gz
    ├── 0223ad6fb49cb81033589ed90bb7688143d6f557.nq.gz
    ├── 022c8fb9ed6530610e7f17ed49a618040170b778.nq.gz
    ├── 02410690abb08654a7a9a31c2966d8ef6cc73c45.nq.gz
    ├── 024ce6fe61a32b958029380d8889241e4f1aa554.nq.gz
    ├── 0262f3bd73e5f138a47c41f1f65f34821a8b0f05.nq.gz
    ├── 0270ac158a02731f63a3b76bafb7d9ebac6bbdc6.nq.gz
    ├── 028f8e476fd84cc7dd9df7f7887ddfefa16541a4.nq.gz
    ├── 029aff02f86d4a5b2c17f80a3fb25c5cb6d17a4d.nq.gz
    ├── 02d207353f7f24815ba94c4015affc2277d2e1c9.nq.gz
    ├── 02d8e7220f2a3f78f3895af930915fd8d627e243.nq.gz
    ├── 02f4ebc136a7d204bacb9e5401d9886887b3185c.nq.gz
    ├── 035cd9b3bd94841f7a3584923d68862091802cd8.nq.gz
    ├── 035e2a53ceb0625162f2dfd0413f64556b94c930.nq.gz
    ├── 038434047980393cb9702de354f156a8b35b6b2c.nq.gz
    ├── 038cfd3c78bcda32ce7b237f9935682fd796be9f.nq.gz
    ├── 038e4d7a80a7434a14deb1eda6bf448908e4c7ff.nq.gz
    ├── 03a220395bdafe898a2591237886e20391c9bf0c.nq.gz
    ├── 03bb3eb2da91023c0267415b2c20535445090165.nq.gz
    ├── 03c821b4eebdec3f4727e9a69df9f9bf72c8f6c8.nq.gz
    ├── 03cbded5142a4c331fceb6f0a72377d659385319.nq.gz
    ├── 03fcc4e9677d18df2ea5cccd74f6e4f2ebca1c6a.nq.gz
    ├── 04181c641731a6996e976783f78c0335a551147d.nq.gz
    ├── 04572d2e7e5742dca6d25fc4f3886437993bedce.nq.gz
    ├── 045a240802ddccc82037ab43c833535fd416374f.nq.gz
    ├── 046deefaec87e8b260943886eaf9a534281e0e1f.nq.gz
    ├── 048e55c68b3e25d9f5efe4bd32f322537c7fc107.nq.gz
    ├── 0494c8fe5bbbb3fcc13ccd5ef1b50f35f16baa1c.nq.gz
    ├── 04b3b4fdaf784b51fbbaad356da2edb3731f5320.nq.gz
    ├── 04c3b030850928ba6c7e0d6f113769b2e8022d4e.nq.gz
    ├── 04c7861586a01328d8c2b88b451622b76bfa4e7b.nq.gz
    ├── 04d7fc6b7447f1a90a5b0920f4657e4468fb733e.nq.gz
    ├── 04dd4289764e8b0ad546c7dbbed900ded8697846.nq.gz
    ├── 04e1ed45067937640ad139f9b63648b38c1fc566.nq.gz
    ├── 04efaa0659ba5a46a9131e8283db71b06ccf8b25.nq.gz
    ├── 05005ead705f244292e29076fbfe4ce4d8861e76.nq.gz
    ├── 051064fa0a07b081499dbedc88683d0ff48d39a1.nq.gz
    ├── 0512dcb8405b28513f2e0a881aac2c9157466664.nq.gz
    ├── 0525c1c703bf67790da5af6856ab7872c2e64469.nq.gz
    ├── 053a608d7e63f75c05ad719553448a7962b78297.nq.gz
    ├── 05478d70b58f584fe9ac34a6baed1f547117175b.nq.gz
    ├── 056ae6dc1d52ba0e39ff56f200f479cc6df308b9.nq.gz
    ├── 056cbae44effba97a6dccafe08fd7d33ef3a5780.nq.gz
    ├── 056cbe1a95c3cb119c65b433631278859b43ddbe.nq.gz
    ├── 0574924b5d6691a2b222a1dc8de01c8329d70559.nq.gz
    ├── 05a2bac1da8277d987f78747196c54d7b74e3766.nq.gz
    ├── 05a5e8a2420efac03ba7babefe38b25e4027c821.nq.gz
    ├── 05a904f5f8209a5135d41c7cad0d0cea141876d6.nq.gz
    ├── 05aac5c641559ca8ad958560d7d8101a3ea0295f.nq.gz
    ├── 05b0c3d93f40892d34ab00c745d3c22e176e4faf.nq.gz
    ├── 05e4b3ddbe858be291fe6dd035a511f584a84c30.nq.gz
    ├── 06086a2d11c7534679bb7b97a0f7bc403ac356aa.nq.gz
    ├── 06393d236b5d2dd1a8b7f099390223adbde98a52.nq.gz
    ├── 063bcf5bfcc9b90850e1d19bb9e775637b9829ca.nq.gz
    ├── 0656c31698490085cbfc35d2f74158078555ca18.nq.gz
    ├── 06792ddcc4c7516e2247ed0cc78d8e1a8aa546e8.nq.gz
    ├── 067f8a8ae5ba9eac2de42c480e966d1c56bdbc07.nq.gz
    ├── 069fe30238ee3970c98287cc467097765c18df92.nq.gz
    ├── 06de402676e73381ca3a350daecd3dbedc7dfaf7.nq.gz
    ├── 06e9ff56551be83c522e7bd5cc6aa5ba1045aff6.nq.gz
    ├── 06feaeab0d12248d580701ea4ac4453f3d648fc7.nq.gz
    ├── 072a99143d6e3fd6c69e4454d61894f34e6c59b9.nq.gz
    ├── 074e99bc5ce21b3520b96be093e061f3478147e7.nq.gz
    ├── 076390b63690d76c9d92f1e05cf99a6053b4d74c.nq.gz
    ├── 07cebefeba830547b70fd9a5cab48e72609e9cdf.nq.gz
    ├── 07edb8cc42574cb46529e55dbaa078c98ab0f004.nq.gz
    ├── 07f29d1d8a2df082c003caa0e83feb7a1bd3c219.nq.gz
    ├── 07f50154739d5d1c1ab356e7a5b30f618947775f.nq.gz
    ├── 080aa1b5b557f30c600e059ca3535dbe616c332b.nq.gz
    ├── 08125f0a9d48339b6b32f2620f51e25a2d3a7b36.nq.gz
    ├── 081f951b80d946602710464608e74347c20d5215.nq.gz
    ├── 0823c084ac87121ea83d6b5e012aabbbce8a468e.nq.gz
    ├── 08260919768f0c6c18cf3c0695298bba9545968f.nq.gz
    ├── 08308af1eca81a70adb33ba6242db92352c00247.nq.gz
    ├── 085053c5783126247abdcb63fdea92f351b8a229.nq.gz
    ├── 086019012d3b34bef4a2c4d725ec1f020007d70e.nq.gz
    ├── 0862d17835c4cbb68c3ab89379fcd044d87c5d9d.nq.gz
    ├── 0865461c6b5faebd4f21614177043ebab55c94f0.nq.gz
    ├── 08733d745c3ddc994f358193dd4b79ce359583d8.nq.gz
    ├── 0875c0b9e717af8796c50d87c71d69a6701a7a16.nq.gz
    ├── 089956a2ef0d7bfb306a920854b49b4dc4323078.nq.gz
    ├── 089bcce10e729c5227907d30673596fd71d576cf.nq.gz
    ├── 08c416c58cba8dc4b41c860589ee471650b495fc.nq.gz
    ├── 08c480f5921b93a1c43b8dde3ebaf930162551a9.nq.gz
    ├── 08d31db26b4f732dc10815554a6900a6bbe07eef.nq.gz
    ├── 08d87f834c6c719ec2bf5980b0448c6b6ac887b5.nq.gz
    ├── 08e9c1292ba8b03459f528d22505cc8ba5345852.nq.gz
    ├── 08f2245ef6cde76df2b473062101201986e19d39.nq.gz
    ├── 08f4df8c2f8483d889f58c56d1689be65abd858d.nq.gz
    ├── 0902491b2dba8262968fbedfa0df6f0305afcb06.nq.gz
    ├── 090b6a3c0daefaf47394a68350465294181bb138.nq.gz
    ├── 09176f9bacb734005b4ad44d2e612ba6634c1899.nq.gz
    ├── 0922a4c4041a90b1e884f56522f82bced398c80e.nq.gz
    ├── 092ba9af41d485787dcf7357916a3dcbf95bdca5.nq.gz
    ├── 093963aeca5a65ea853aa93e8a6292afb6f2a55a.nq.gz
    ├── 09497b4f2b57474175dd6e701e879a8bbbf21849.nq.gz
    ├── 0994f9a25115dfda2de5d9fa6d117ddaf16d4ea6.nq.gz
    ├── 099c7f342272f1838f30c59f63def106323960cc.nq.gz
    ├── 09b32ab00b50fb66c83f1d6b40e1055afe81a350.nq.gz
    ├── 09f46b1e817f806873c4a4bdd7b8466046b5f64d.nq.gz
    ├── 0a0125195856957c4b31001aa92780168e7f88ff.nq.gz
    ├── 0a1b85dc68062b841567516aaee37b7deebca480.nq.gz
    ├── 0a28cb0edb36815170492f32c87a4ee8b5acf986.nq.gz
    ├── 0a36a716dcb339604efe7a621b4a6094c80c992d.nq.gz
    ├── 0a4e150700fa7c754cca75eaf6a32664a1be50f2.nq.gz
    ├── 0a598fcb8eb03f9d1169377e3e311ca826bf3569.nq.gz
    ├── 0a7044cee81616eedbf305a3093429e088a3cd49.nq.gz
    ├── 0a8c99dd3e41c40c284ab4595a8de2f0cf0cf85a.nq.gz
    ├── 0a8f1e9811441b6537d94ce6b0bd61f17515bff8.nq.gz
    ├── 0a9b3475abcfc9cc47f988ca69d9fd6f9995f380.nq.gz
    ├── 0ac1c2662160a0cf4df916c21ab21d1df4066ca2.nq.gz
    ├── 0aea1572a8f6ffb3ddb81ada9b647918a98d80a5.nq.gz
    ├── 0afa906d2f558528b77ba93b8fa2a54cc1b12d9c.nq.gz
    ├── 0b0461370dd2038ed7b68376465b6efd33ef40eb.nq.gz
    ├── 0b09ff61fd857e9d1410130457f4a20c2eee6973.nq.gz
    ├── 0b1df249d80ba188bbc8cbc120424ad08189086c.nq.gz
    ├── 0b43179cb1c25e02ac2994021489b745ccbbb39a.nq.gz
    ├── 0b43f457e1bc753f08a051dd68610b83be603dbb.nq.gz
    ├── 0b4edbfd1f47397e5c4c45aca884510f63057b38.nq.gz
    ├── 0b72613827c52489147621a86305176019909a80.nq.gz
    ├── 0b9c295af8c19a2d89859032ce081b62114635aa.nq.gz
    ├── 0ba99ad0e1da671360159b080b504f42dbfb2edc.nq.gz
    ├── 0be709cd1792f5e006a945e0ed7794c5550cf1d3.nq.gz
    ├── 0c0a57ffcde801b0c34ca7f27d6202bca06094dc.nq.gz
    ├── 0c2b0427bc8c7952e919da2b5fd6ae4c91aefdc3.nq.gz
    ├── 0c5139af3ddea4d7b01a54641277535d99491107.nq.gz
    ├── 0c9589fe174a33c594e2b492743886d2f1ea38f6.nq.gz
    ├── 0cf3170d7b2b6e3f325207f331a747e98a09be97.nq.gz
    ├── 0d0b95030b17b3cbf7e8e987f766118d0b5ce2ed.nq.gz
    ├── 0d1b587f5b86f58d1f4b3058d8723c962ccc0c37.nq.gz
    ├── 0d2c2d4445e867077be2e2eb26ba4dca94414657.nq.gz
    ├── 0d42a6735911037fadb05f355fa869c3a5cb2449.nq.gz
    ├── 0d4d65ff97d04d23cf81b3459aa7a8fb03d46b6a.nq.gz
    ├── 0d568cae3edb59a589ba9d5226a9cb6ff714a4a9.nq.gz
    ├── 0d7fa96f9426e499583659641f2bfac8bee7908e.nq.gz
    ├── 0d83ba8ed811bf32cdcf5855acb9dda9da4ad1fa.nq.gz
    ├── 0dbdac7c5da826434f101b6c4e4f39592aa9edcf.nq.gz
    ├── 0dc1dd99257b19dc306a90c5b93125abcfe047ef.nq.gz
    ├── 0dccc598515bee09afeb3d87342d294aa941fa05.nq.gz
    ├── 0dd3bf2394262a3a3b6a3ea4d1a522993e40a44d.nq.gz
    ├── 0e04ef3c5cab32d3b9c89bc8b390fc97c0d57950.nq.gz
    ├── 0e159fb1504b6e4b8cbc6b340e12cd6609fdf9de.nq.gz
    ├── 0e2d0b675ca2f3642bbf47b985b06a56c3e8fdab.nq.gz
    ├── 0e4b22f8566b54339dffe620ae707f490aecc3a0.nq.gz
    ├── 0e56a03d42fa14c1ca88061ff93a8df29b69b28b.nq.gz
    ├── 0e71df281b894ae1709f86955ce34c1f506cd0dc.nq.gz
    ├── 0e7f71937a505464f0ac067c9007c259f6f9639f.nq.gz
    ├── 0e7fd9d329f4de993fbe1080b3a8e083975372dd.nq.gz
    ├── 0e8ceb243676c00f04d7a526c0814627cd1917c4.nq.gz
    ├── 0ea24f106673cdb45e2c7651d49274093de734b0.nq.gz
    ├── 0ea3361d0b1808118e30dc880fce72bf3959e753.nq.gz
    ├── 0ec2d1ad567017d6298affd3cb36434b5f8d635e.nq.gz
    ├── 0ed03dc2f605a98b3708ce8fb60bb1f48abd38bc.nq.gz
    ├── 0ed348e85e7a0d2e651940659247c233fdd48366.nq.gz
    ├── 0ee5c2afa0dcfd4fb6d93ae4ec9f148bb276f2ab.nq.gz
    ├── 0f05f4c071f3cc3c430b74d093dd4ee48f531b91.nq.gz
    ├── 0f1552d614509d6b790dc4394b9a398e609a8fcf.nq.gz
    ├── 0f3d5f6b372fa9c58d4611f6a250da745c6c46a0.nq.gz
    ├── 0f3fbbb01a192281454dcfd134ec032ea8a04e88.nq.gz
    ├── 0f50249b3e69e671566eb4fb8c3c18988378a0c4.nq.gz
    ├── 0f742ced57eba4d0bb3af7241b2297f6265d5973.nq.gz
    ├── 0fc29492adb450e25e91ec7fc493c22b83ca5a68.nq.gz
    ├── 0fe447b1cdf9c66a3984335850aa7487b118391e.nq.gz
    ├── 102aad68b778e7530ada927d0339a2ffb34133fd.nq.gz
    ├── 103e0940fe5c2648487c6b00e493c7c6db0032d9.nq.gz
    ├── 103e4c11d56d3944b2cd5fab92abdbbb2cef8f0c.nq.gz
    ├── 103e96c1f117ed06924569fadb6a2b680fbd5456.nq.gz
    ├── 10615751dbd2c88091bea2e8f7017f2da56b6132.nq.gz
    ├── 107269aae08d38d41409d786d6dba4b4358a3b8e.nq.gz
    ├── 107f102c98d4592cf3828ab04ebcd51051388068.nq.gz
    ├── 1091927ca901374b695172a1458eb322fd8a00fa.nq.gz
    ├── 10b9eb22bfcf1818d9857fa6f35bc64668cbe766.nq.gz
    ├── 10c15d0f5cb36f19ce23b3a4255e92ef27998c9b.nq.gz
    └── 10c725cc0ab0c9fff5a978a3d5278ccce52d4e67.nq.gz

9 directories, 200 files
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

[pyca/cryptography](https://github.com/pyca/cryptography)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
