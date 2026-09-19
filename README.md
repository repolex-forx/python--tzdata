# Repolex Knowledge Graph of python/tzdata

RDF knowledge graph data for [python/tzdata](https://github.com/python/tzdata), parsed by [repolex](https://repolex.ai).

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
lexq download python/tzdata
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0c324fb674e0451a3a28a7a6b7a0312f1d0f025d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0ccabead4a1bb57df8556b979690c00a0570f87f
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1689a67198a38ad6a0052e8625cab4661bdc8167
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1e593a4124a29eccab092e27d397bcb201375671
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2191b766baf44f4b6a2013a8061748eccbbf22d0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 41c98f67781feae34be44e8c12a433b66e204da5
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4997cab882668ef36ced53c797a7eecc229d6f66
│   │   │   └── chunk-001.nq.gz
│   │   ├── 53f247e8b897d76321f883e67639ae85c62fbf3b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 78b32761e93840e82799a79bdb573688b0e33f02
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7e71c6bf79c2a68dbaab908e51aa4f5985a65d08
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8d488ea4d6b2f17018c2b55d64bd8c2334dd8bd0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8ff985ad3ccc30fd6bfeefb6015c6ea9724ff5a5
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9477a0f54afa67e8d9d84d38dce14f6105ad674b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9c40927da8ccedcff274840f47a651695e0528ed
│   │   │   └── chunk-001.nq.gz
│   │   ├── b6ab832c0171af80d8829ab2af3f786b57848335
│   │   │   └── chunk-001.nq.gz
│   │   ├── b7c033f0e0073b2b89f5ac5856d2991f319f565f
│   │   │   └── chunk-001.nq.gz
│   │   ├── ba0b73f2572a03456140671415ee5deedc58e2e9
│   │   │   └── chunk-001.nq.gz
│   │   ├── c7bf6888a7562595d75fe4e0c75158935c2ff580
│   │   │   └── chunk-001.nq.gz
│   │   ├── d14cebc1f27c90ca244dac9f12327fffc14d5cf9
│   │   │   └── chunk-001.nq.gz
│   │   ├── d6e72f09d1332a828a9bcf0dd29167b67e16b7f3
│   │   │   └── chunk-001.nq.gz
│   │   └── d957cfa07a39fc025a51d06b459aa168a41c8614
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0c324fb674e0451a3a28a7a6b7a0312f1d0f025d.nq.gz
│   │   ├── 0ccabead4a1bb57df8556b979690c00a0570f87f.nq.gz
│   │   ├── 1689a67198a38ad6a0052e8625cab4661bdc8167.nq.gz
│   │   ├── 1e593a4124a29eccab092e27d397bcb201375671.nq.gz
│   │   ├── 2191b766baf44f4b6a2013a8061748eccbbf22d0.nq.gz
│   │   ├── 41c98f67781feae34be44e8c12a433b66e204da5.nq.gz
│   │   ├── 4997cab882668ef36ced53c797a7eecc229d6f66.nq.gz
│   │   ├── 53f247e8b897d76321f883e67639ae85c62fbf3b.nq.gz
│   │   ├── 78b32761e93840e82799a79bdb573688b0e33f02.nq.gz
│   │   ├── 7e71c6bf79c2a68dbaab908e51aa4f5985a65d08.nq.gz
│   │   ├── 8d488ea4d6b2f17018c2b55d64bd8c2334dd8bd0.nq.gz
│   │   ├── 8ff985ad3ccc30fd6bfeefb6015c6ea9724ff5a5.nq.gz
│   │   ├── 9477a0f54afa67e8d9d84d38dce14f6105ad674b.nq.gz
│   │   ├── 9c40927da8ccedcff274840f47a651695e0528ed.nq.gz
│   │   ├── b6ab832c0171af80d8829ab2af3f786b57848335.nq.gz
│   │   ├── b7c033f0e0073b2b89f5ac5856d2991f319f565f.nq.gz
│   │   ├── ba0b73f2572a03456140671415ee5deedc58e2e9.nq.gz
│   │   ├── c7bf6888a7562595d75fe4e0c75158935c2ff580.nq.gz
│   │   ├── d14cebc1f27c90ca244dac9f12327fffc14d5cf9.nq.gz
│   │   ├── d6e72f09d1332a828a9bcf0dd29167b67e16b7f3.nq.gz
│   │   └── d957cfa07a39fc025a51d06b459aa168a41c8614.nq.gz
│   └── repolex
│       ├── 0c324fb674e0451a3a28a7a6b7a0312f1d0f025d
│       │   └── chunk-001.nq.gz
│       ├── 0ccabead4a1bb57df8556b979690c00a0570f87f
│       │   └── chunk-001.nq.gz
│       ├── 1689a67198a38ad6a0052e8625cab4661bdc8167
│       │   └── chunk-001.nq.gz
│       ├── 1e593a4124a29eccab092e27d397bcb201375671
│       │   └── chunk-001.nq.gz
│       ├── 2191b766baf44f4b6a2013a8061748eccbbf22d0
│       │   └── chunk-001.nq.gz
│       ├── 41c98f67781feae34be44e8c12a433b66e204da5
│       │   └── chunk-001.nq.gz
│       ├── 4997cab882668ef36ced53c797a7eecc229d6f66
│       │   └── chunk-001.nq.gz
│       ├── 53f247e8b897d76321f883e67639ae85c62fbf3b
│       │   └── chunk-001.nq.gz
│       ├── 78b32761e93840e82799a79bdb573688b0e33f02
│       │   └── chunk-001.nq.gz
│       ├── 7e71c6bf79c2a68dbaab908e51aa4f5985a65d08
│       │   └── chunk-001.nq.gz
│       ├── 8d488ea4d6b2f17018c2b55d64bd8c2334dd8bd0
│       │   └── chunk-001.nq.gz
│       ├── 8ff985ad3ccc30fd6bfeefb6015c6ea9724ff5a5
│       │   └── chunk-001.nq.gz
│       ├── 9477a0f54afa67e8d9d84d38dce14f6105ad674b
│       │   └── chunk-001.nq.gz
│       ├── 9c40927da8ccedcff274840f47a651695e0528ed
│       │   └── chunk-001.nq.gz
│       ├── b6ab832c0171af80d8829ab2af3f786b57848335
│       │   └── chunk-001.nq.gz
│       ├── b7c033f0e0073b2b89f5ac5856d2991f319f565f
│       │   └── chunk-001.nq.gz
│       ├── ba0b73f2572a03456140671415ee5deedc58e2e9
│       │   └── chunk-001.nq.gz
│       ├── c7bf6888a7562595d75fe4e0c75158935c2ff580
│       │   └── chunk-001.nq.gz
│       ├── d14cebc1f27c90ca244dac9f12327fffc14d5cf9
│       │   └── chunk-001.nq.gz
│       ├── d6e72f09d1332a828a9bcf0dd29167b67e16b7f3
│       │   └── chunk-001.nq.gz
│       └── d957cfa07a39fc025a51d06b459aa168a41c8614
│           └── chunk-001.nq.gz
└── blob
    ├── 001289ceecff85fe0d0f376a6bc394329445f13f.nq.gz
    ├── 00841a62213e6cccf7f0b7353e5e8ae214185486.nq.gz
    ├── 00a27264c2cb3e28f2f46e5c267e12d575236a9d.nq.gz
    ├── 00b57bb13fbfa802e61f8b93d08622163a35a9a4.nq.gz
    ├── 00bc80a65e9a7aa470d63fba1ce1b29ef173d922.nq.gz
    ├── 017bb2e34746c8a11c6955d49cc492c974412801.nq.gz
    ├── 01c47ccb86ccbde2bf9ad0803298e8df87178a34.nq.gz
    ├── 01f536b3ba3833dcb5c4ee25d6e18bd3772e860a.nq.gz
    ├── 020e33d976179e8f61a6040caaef3c8eb7f348bc.nq.gz
    ├── 028a8445292308b277c35724b440447e080f225f.nq.gz
    ├── 02f047d70fc811f8cc17f2c08ddc1f328576fb94.nq.gz
    ├── 044f82313e97a95a76fbc7e1ea4ca7ff8eeb3b48.nq.gz
    ├── 055db7d902fe0d8862fd575846ddc39a7f5d68e0.nq.gz
    ├── 05e4c6c5867330a5af95cd6816ade311a0cac82d.nq.gz
    ├── 06d44638e28bf5ff89f5713e3761921740e427ee.nq.gz
    ├── 0715d58bc1873c8bae589a08752cbbae562692c7.nq.gz
    ├── 07e4c5f4ac3852571b17cb33fe565a5ea2c49f0a.nq.gz
    ├── 08bdd8845b573cc51139e6c94fdaffbad9d4fa8e.nq.gz
    ├── 08f0128ee681d8f7e1df186d93514f3f4cff2830.nq.gz
    ├── 092e40d70122f764fd2630957be1d3e32858f6f5.nq.gz
    ├── 093f0a0cb7495b5d50751bc0cb5b22df4a67c763.nq.gz
    ├── 09e54e5c7c5bb2384e37626d4b985cfad29ed29b.nq.gz
    ├── 0a0878ce26f138bb8c5505f954863e191a82409b.nq.gz
    ├── 0a81cbddfa2813041472b716baa91c35a8451379.nq.gz
    ├── 0a948c2eaca30cde2963c330144215ba52d67c5e.nq.gz
    ├── 0aba9ffd89dcbb47f1bf003dad75227f08d99679.nq.gz
    ├── 0c0bdbda2a72022180bde561f6693268e27beb6b.nq.gz
    ├── 0c3ba4d03d6b794446d72f95c59f081242be70eb.nq.gz
    ├── 0d79662716b445f61e5577bdb09e7c91e4a40d28.nq.gz
    ├── 0d8c993bd1cf2fa2cbf002421ec9c0fb2b29645b.nq.gz
    ├── 0da1d1e211bc6b9b081959c1d510583cb9eb7102.nq.gz
    ├── 0ec475647055bd235131c6620aa46da7f43209ac.nq.gz
    ├── 0edc52b9b783827a8ac1090fe350bfe13977f745.nq.gz
    ├── 0edc72cfe46b1976bff562929501f202a205d0cc.nq.gz
    ├── 103ea5406e4fb073cbe0841894db368a7bff5739.nq.gz
    ├── 10556d5d856a0f33afd8da2b07a2005e7be80fb0.nq.gz
    ├── 1092f4b61a1b203f7feabb586b51085bb72602dc.nq.gz
    ├── 109fe41562e89a026f828125f960498f62fb5d95.nq.gz
    ├── 119d1d0f4043c51af5625508e6fcfc2b797b5b37.nq.gz
    ├── 11d988e10a3e318a7cba485d995872636d1acaf0.nq.gz
    ├── 131d77b54a2087ada0bb3a27d03bf752f84326a7.nq.gz
    ├── 137867c8bf5b2df2e55e8c0c84ecc7deafc3ba79.nq.gz
    ├── 13aef80cbbcf0c938b8d11d92b0755e146a501d2.nq.gz
    ├── 145bb6fb162e192da18e0991c00578d43475b384.nq.gz
    ├── 14b2ad09ead50a62d5e2b426396c51f9beb293be.nq.gz
    ├── 14e6de583bbfae0e94d713f137be928dd0063d1d.nq.gz
    ├── 157573b1d340e0f57a0dd4d9698bd3798cbf7136.nq.gz
    ├── 160a53e045c872be729de80a522bb8b6f6ddee91.nq.gz
    ├── 166e4341d6ce65728367641a467a925800044df6.nq.gz
    ├── 16bac8444656c393288dcc0209a96c7c3f487a19.nq.gz
    ├── 1755147fab44e07b7527ce1eaf3ae991473fb222.nq.gz
    ├── 1782fa1c2ff2bf0b4706ec59ce23f62eec805e6d.nq.gz
    ├── 17d2b1582df89d5794f20fb028956dd9da154922.nq.gz
    ├── 18112346129a885b5d5fa27109682b63784f72c0.nq.gz
    ├── 18d0d14afc1cdf37c8f3607181e3f72211da99e9.nq.gz
    ├── 1975a3a4bd0ed93db1d10a2c562eb5bc3baaa489.nq.gz
    ├── 1a4c8ea86361731f4d7e854ac66d96a5ce6b2dbf.nq.gz
    ├── 1aa066ce38fce7bd0a680f51d6f075718d153a77.nq.gz
    ├── 1bcae6a2c32664bb63dbf85bf3a7580b2b4e32cc.nq.gz
    ├── 1c21afaeea9b8f690cdaa1db869a98da42f971db.nq.gz
    ├── 1d64b3912461729615b137a6ad5fec87ddcd74dc.nq.gz
    ├── 1dcc8d85434c9d016f170cb2f16811ebef327b77.nq.gz
    ├── 1dd08b1cafd4b36ce963bdc42a075665fa723b54.nq.gz
    ├── 1e689c25f29d7833abff87a83bc6a1cac70e4d09.nq.gz
    ├── 1e6d48d1ca4e5416913c41e8814dc045c57d5b58.nq.gz
    ├── 1f1cecb848560c0ccff116090e23b0b811925496.nq.gz
    ├── 21e84571ee1694758dd244ed0702fbae962648e6.nq.gz
    ├── 22e705ca1ab1218e9f36b9f4f607258389853c8b.nq.gz
    ├── 231bf9c3b713e3676dbd8f3ced867973c601e104.nq.gz
    ├── 2359c44bd00ed44d2cdbf4f0aa0d9cea507814ed.nq.gz
    ├── 23e1fdbb07cf23ff1c5731ee27afe951bca12765.nq.gz
    ├── 23ead1c004ffd82c03b69b44e147daef4c07c961.nq.gz
    ├── 23f94063684b2331acd4447fd699632098337901.nq.gz
    ├── 23fca12205222be27c167e597df5086520f699cf.nq.gz
    ├── 240ebb2bfb22642570a6053445a6e71864e7f48a.nq.gz
    ├── 247caa631ab9964c1de8b35294fe4551a9167af4.nq.gz
    ├── 24f925a2dd33d487e41cb38b9c3b4c420af69c1d.nq.gz
    ├── 2558607951d760fd5f9a8aa18a6b660fb4134b65.nq.gz
    ├── 25a63ec8b9951c94fc00a8c6c9d18d2151b26dde.nq.gz
    ├── 25c0232d95492333e8c1aef7321a24a331e2e24a.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 2626b0550341a0605087f33cac6952d5fbb24e67.nq.gz
    ├── 26354e89460e7c9e585d62ab477cd69a5559b554.nq.gz
    ├── 2684d8f8b89f7807ed4a0fcba89822b24a0166bb.nq.gz
    ├── 26af4c90b3b75009916ac78884371bc2d8f5302d.nq.gz
    ├── 27539c2243ff2c6be1fe890995485be2df39bf77.nq.gz
    ├── 28136808b6d1029676448d8711265d8c55cb4bae.nq.gz
    ├── 285bed2c63a5debe034a661431d2a1c03dfb0dad.nq.gz
    ├── 28c61cdb35682fbb0e9f52e323dcbd2b8dfcefea.nq.gz
    ├── 28d2c56e1a991556b5aca45108e3415f3ebfe868.nq.gz
    ├── 298b8326ca7ab3e86b5f508fd06fc744b4a142f6.nq.gz
    ├── 29ad0334727ceb23c106b2d0b80181016c6f1549.nq.gz
    ├── 2a42c83efe16c3c8da4d750df0a82be4908c8896.nq.gz
    ├── 2a49c6c50f4c21765232712d18a6cbbeedafc441.nq.gz
    ├── 2a6dd250059b8f8024a2c6cc5f741d1e60ca878d.nq.gz
    ├── 2b272cbca57e63fbf4dc7e311f7ccf8564022cb6.nq.gz
    ├── 2b6a06088ef603f03fb482b628347ff72970fe3d.nq.gz
    ├── 2b6c2eea14df07392729ae9f5712a44ec4f02bae.nq.gz
    ├── 2cf03e51cc6983ae978a2dab030ddb5c9acb06a8.nq.gz
    ├── 2dbe8f00d1b83d28e22cffc3589133b232bf893d.nq.gz
    ├── 2dc5f20209e7b22a1fb7a28695d6f47de0ba4444.nq.gz
    ├── 2f676d3bf5c8599994bcabd402ca30efa4cde5dd.nq.gz
    ├── 2fc74e947389cf4371baece8ac66945df1b208fe.nq.gz
    ├── 30315cc07893d4da19ffd04a655084908c369d29.nq.gz
    ├── 305abcb8a2217834e8333a2c486ccd389199a334.nq.gz
    ├── 30d3a672bf64d0d787ac92bc75d9bc1cc62855c9.nq.gz
    ├── 310774ea4fdd1798782a41f905d16e3548cd191e.nq.gz
    ├── 3110cdfd6e6f4ccd889447657dff43560d5aaee0.nq.gz
    ├── 3181eae7a8ca4e226ba8186f4953b30727a4e2e0.nq.gz
    ├── 31973271d2f87f7e9df4e8b0a1481f09a9e5407d.nq.gz
    ├── 323cd3818ac6f77b4394982ea5a342b9ed262777.nq.gz
    ├── 32a2eec4e0d9f15540fb34544922336c9dd54ec7.nq.gz
    ├── 32b11f70437119d20e58e40bf657f1a0f57966e0.nq.gz
    ├── 32c1941634aec9e7721fcf8e9b323e7d99c7f337.nq.gz
    ├── 336f932e8d458b5096d4aa9483f3177f8d5888eb.nq.gz
    ├── 341a0235ef488ee623aba36a8b5928122774d2fb.nq.gz
    ├── 3475536c0c28b1af38cfc355ef1b392c141b953d.nq.gz
    ├── 35a52e53d123b5ef5d293b3af19046630f02bb66.nq.gz
    ├── 35d89d036d07c3f28dec64092ab1b533c21ae2bc.nq.gz
    ├── 35efc02322775b04c44c69902f52435d0352b47a.nq.gz
    ├── 36535bdf5cfbdedfc70b4d7899de7351b8eb5070.nq.gz
    ├── 36681ed78eaf0b46f8d142884cf7ae8903a18907.nq.gz
    ├── 378919ea113105881f9ade477d91692f6ac263b9.nq.gz
    ├── 38036a32831d149c6c737dfa49f0947f066288b1.nq.gz
    ├── 381ae6c463260d85ce92d6585b6420fed0c096dd.nq.gz
    ├── 38685d4219d244f56f665c8afb92eaa6737badb8.nq.gz
    ├── 388df2969f2dc56738183bd4f0d5755c4533a797.nq.gz
    ├── 390347f442a486e296689c189e3346695bba5105.nq.gz
    ├── 3a0d330ffd2f08396290960527fc8fc186356161.nq.gz
    ├── 3a40d1175a7d81d8a307d0e546a1fe9a40888b29.nq.gz
    ├── 3ae969114563a5d7a1df96237c38a10df92baf56.nq.gz
    ├── 3b0e3b7eaa12dd3fa29066779281762efddee424.nq.gz
    ├── 3b62585d0a13c9b35824ff7ecc91e29428c360e1.nq.gz
    ├── 3bfbbc563cf97dc2548ff8974ab23dcde28e8744.nq.gz
    ├── 3c3584e09ae47e9ab4e174fb375345679e06c95b.nq.gz
    ├── 3c4a951d4990e82c545c0cc3a66fcb51d9d0b6e8.nq.gz
    └── 3d64a1edb687664b43ebda3a373eec95608a96e7.nq.gz

48 directories, 200 files
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

[python/tzdata](https://github.com/python/tzdata)

---
*Parsed on 2026-09-19 by [repolex](https://repolex.ai)*
