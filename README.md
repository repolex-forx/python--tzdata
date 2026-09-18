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
│   │   ├── 4997cab882668ef36ced53c797a7eecc229d6f66
│   │   │   └── chunk-001.nq.gz
│   │   ├── 53f247e8b897d76321f883e67639ae85c62fbf3b
│   │   │   └── chunk-001.nq.gz
│   │   └── d14cebc1f27c90ca244dac9f12327fffc14d5cf9
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 4997cab882668ef36ced53c797a7eecc229d6f66.nq.gz
│   │   ├── 53f247e8b897d76321f883e67639ae85c62fbf3b.nq.gz
│   │   └── d14cebc1f27c90ca244dac9f12327fffc14d5cf9.nq.gz
│   └── repolex
│       ├── 4997cab882668ef36ced53c797a7eecc229d6f66
│       │   └── chunk-001.nq.gz
│       ├── 53f247e8b897d76321f883e67639ae85c62fbf3b
│       │   └── chunk-001.nq.gz
│       └── d14cebc1f27c90ca244dac9f12327fffc14d5cf9
│           └── chunk-001.nq.gz
└── blob
    ├── 001289ceecff85fe0d0f376a6bc394329445f13f.nq.gz
    ├── 00841a62213e6cccf7f0b7353e5e8ae214185486.nq.gz
    ├── 00a27264c2cb3e28f2f46e5c267e12d575236a9d.nq.gz
    ├── 00bc80a65e9a7aa470d63fba1ce1b29ef173d922.nq.gz
    ├── 017bb2e34746c8a11c6955d49cc492c974412801.nq.gz
    ├── 01c47ccb86ccbde2bf9ad0803298e8df87178a34.nq.gz
    ├── 020e33d976179e8f61a6040caaef3c8eb7f348bc.nq.gz
    ├── 02f047d70fc811f8cc17f2c08ddc1f328576fb94.nq.gz
    ├── 044f82313e97a95a76fbc7e1ea4ca7ff8eeb3b48.nq.gz
    ├── 05e4c6c5867330a5af95cd6816ade311a0cac82d.nq.gz
    ├── 06d44638e28bf5ff89f5713e3761921740e427ee.nq.gz
    ├── 0715d58bc1873c8bae589a08752cbbae562692c7.nq.gz
    ├── 07e4c5f4ac3852571b17cb33fe565a5ea2c49f0a.nq.gz
    ├── 08bdd8845b573cc51139e6c94fdaffbad9d4fa8e.nq.gz
    ├── 08f0128ee681d8f7e1df186d93514f3f4cff2830.nq.gz
    ├── 092e40d70122f764fd2630957be1d3e32858f6f5.nq.gz
    ├── 09e54e5c7c5bb2384e37626d4b985cfad29ed29b.nq.gz
    ├── 0a0878ce26f138bb8c5505f954863e191a82409b.nq.gz
    ├── 0a81cbddfa2813041472b716baa91c35a8451379.nq.gz
    ├── 0aba9ffd89dcbb47f1bf003dad75227f08d99679.nq.gz
    ├── 0c0bdbda2a72022180bde561f6693268e27beb6b.nq.gz
    ├── 0d79662716b445f61e5577bdb09e7c91e4a40d28.nq.gz
    ├── 0d8c993bd1cf2fa2cbf002421ec9c0fb2b29645b.nq.gz
    ├── 0da1d1e211bc6b9b081959c1d510583cb9eb7102.nq.gz
    ├── 0ec475647055bd235131c6620aa46da7f43209ac.nq.gz
    ├── 0edc52b9b783827a8ac1090fe350bfe13977f745.nq.gz
    ├── 0edc72cfe46b1976bff562929501f202a205d0cc.nq.gz
    ├── 10556d5d856a0f33afd8da2b07a2005e7be80fb0.nq.gz
    ├── 1092f4b61a1b203f7feabb586b51085bb72602dc.nq.gz
    ├── 109fe41562e89a026f828125f960498f62fb5d95.nq.gz
    ├── 119d1d0f4043c51af5625508e6fcfc2b797b5b37.nq.gz
    ├── 11d988e10a3e318a7cba485d995872636d1acaf0.nq.gz
    ├── 131d77b54a2087ada0bb3a27d03bf752f84326a7.nq.gz
    ├── 13aef80cbbcf0c938b8d11d92b0755e146a501d2.nq.gz
    ├── 145bb6fb162e192da18e0991c00578d43475b384.nq.gz
    ├── 14b2ad09ead50a62d5e2b426396c51f9beb293be.nq.gz
    ├── 157573b1d340e0f57a0dd4d9698bd3798cbf7136.nq.gz
    ├── 166e4341d6ce65728367641a467a925800044df6.nq.gz
    ├── 16bac8444656c393288dcc0209a96c7c3f487a19.nq.gz
    ├── 1755147fab44e07b7527ce1eaf3ae991473fb222.nq.gz
    ├── 1782fa1c2ff2bf0b4706ec59ce23f62eec805e6d.nq.gz
    ├── 17d2b1582df89d5794f20fb028956dd9da154922.nq.gz
    ├── 18112346129a885b5d5fa27109682b63784f72c0.nq.gz
    ├── 1975a3a4bd0ed93db1d10a2c562eb5bc3baaa489.nq.gz
    ├── 1a4c8ea86361731f4d7e854ac66d96a5ce6b2dbf.nq.gz
    ├── 1aa066ce38fce7bd0a680f51d6f075718d153a77.nq.gz
    ├── 1c21afaeea9b8f690cdaa1db869a98da42f971db.nq.gz
    ├── 1d64b3912461729615b137a6ad5fec87ddcd74dc.nq.gz
    ├── 1dcc8d85434c9d016f170cb2f16811ebef327b77.nq.gz
    ├── 1dd08b1cafd4b36ce963bdc42a075665fa723b54.nq.gz
    ├── 1e6d48d1ca4e5416913c41e8814dc045c57d5b58.nq.gz
    ├── 21e84571ee1694758dd244ed0702fbae962648e6.nq.gz
    ├── 22e705ca1ab1218e9f36b9f4f607258389853c8b.nq.gz
    ├── 231bf9c3b713e3676dbd8f3ced867973c601e104.nq.gz
    ├── 2359c44bd00ed44d2cdbf4f0aa0d9cea507814ed.nq.gz
    ├── 23ead1c004ffd82c03b69b44e147daef4c07c961.nq.gz
    ├── 23fca12205222be27c167e597df5086520f699cf.nq.gz
    ├── 240ebb2bfb22642570a6053445a6e71864e7f48a.nq.gz
    ├── 247caa631ab9964c1de8b35294fe4551a9167af4.nq.gz
    ├── 24f925a2dd33d487e41cb38b9c3b4c420af69c1d.nq.gz
    ├── 25a63ec8b9951c94fc00a8c6c9d18d2151b26dde.nq.gz
    ├── 25c0232d95492333e8c1aef7321a24a331e2e24a.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 2626b0550341a0605087f33cac6952d5fbb24e67.nq.gz
    ├── 26354e89460e7c9e585d62ab477cd69a5559b554.nq.gz
    ├── 2684d8f8b89f7807ed4a0fcba89822b24a0166bb.nq.gz
    ├── 27539c2243ff2c6be1fe890995485be2df39bf77.nq.gz
    ├── 28136808b6d1029676448d8711265d8c55cb4bae.nq.gz
    ├── 285bed2c63a5debe034a661431d2a1c03dfb0dad.nq.gz
    ├── 28c61cdb35682fbb0e9f52e323dcbd2b8dfcefea.nq.gz
    ├── 28d2c56e1a991556b5aca45108e3415f3ebfe868.nq.gz
    ├── 298b8326ca7ab3e86b5f508fd06fc744b4a142f6.nq.gz
    ├── 29ad0334727ceb23c106b2d0b80181016c6f1549.nq.gz
    ├── 2a42c83efe16c3c8da4d750df0a82be4908c8896.nq.gz
    ├── 2a49c6c50f4c21765232712d18a6cbbeedafc441.nq.gz
    ├── 2b6a06088ef603f03fb482b628347ff72970fe3d.nq.gz
    ├── 2b6c2eea14df07392729ae9f5712a44ec4f02bae.nq.gz
    ├── 2dc5f20209e7b22a1fb7a28695d6f47de0ba4444.nq.gz
    ├── 2f676d3bf5c8599994bcabd402ca30efa4cde5dd.nq.gz
    ├── 305abcb8a2217834e8333a2c486ccd389199a334.nq.gz
    ├── 30d3a672bf64d0d787ac92bc75d9bc1cc62855c9.nq.gz
    ├── 310774ea4fdd1798782a41f905d16e3548cd191e.nq.gz
    ├── 3110cdfd6e6f4ccd889447657dff43560d5aaee0.nq.gz
    ├── 3181eae7a8ca4e226ba8186f4953b30727a4e2e0.nq.gz
    ├── 31973271d2f87f7e9df4e8b0a1481f09a9e5407d.nq.gz
    ├── 32a2eec4e0d9f15540fb34544922336c9dd54ec7.nq.gz
    ├── 32b11f70437119d20e58e40bf657f1a0f57966e0.nq.gz
    ├── 32c1941634aec9e7721fcf8e9b323e7d99c7f337.nq.gz
    ├── 336f932e8d458b5096d4aa9483f3177f8d5888eb.nq.gz
    ├── 341a0235ef488ee623aba36a8b5928122774d2fb.nq.gz
    ├── 3475536c0c28b1af38cfc355ef1b392c141b953d.nq.gz
    ├── 35a52e53d123b5ef5d293b3af19046630f02bb66.nq.gz
    ├── 35d89d036d07c3f28dec64092ab1b533c21ae2bc.nq.gz
    ├── 35efc02322775b04c44c69902f52435d0352b47a.nq.gz
    ├── 36681ed78eaf0b46f8d142884cf7ae8903a18907.nq.gz
    ├── 38036a32831d149c6c737dfa49f0947f066288b1.nq.gz
    ├── 381ae6c463260d85ce92d6585b6420fed0c096dd.nq.gz
    ├── 38685d4219d244f56f665c8afb92eaa6737badb8.nq.gz
    ├── 388df2969f2dc56738183bd4f0d5755c4533a797.nq.gz
    ├── 390347f442a486e296689c189e3346695bba5105.nq.gz
    ├── 3a0d330ffd2f08396290960527fc8fc186356161.nq.gz
    ├── 3a40d1175a7d81d8a307d0e546a1fe9a40888b29.nq.gz
    ├── 3b0e3b7eaa12dd3fa29066779281762efddee424.nq.gz
    ├── 3bfbbc563cf97dc2548ff8974ab23dcde28e8744.nq.gz
    ├── 3d7a71ba0e96de946446fc96add2f38a806a44a5.nq.gz
    ├── 3e0785086639e483597890d2b53b9bc4c4ccfe91.nq.gz
    ├── 3e75731baa7c47f2a60ad07733d6f8467ccfbebf.nq.gz
    ├── 3ec32224f2982db46a19d1a159f9017286fd1413.nq.gz
    ├── 3eeb1b72b68993e26a2452afe98a6420ac66bafb.nq.gz
    ├── 3f8e44b8a6e171a0fde96736ed9d4fcde1bcd4a8.nq.gz
    ├── 40baa9aba2a879f7a38a5a0f67e16e7a2d677a5e.nq.gz
    ├── 40e3d492e6c22c30041c31f159d4fe0ee9451c03.nq.gz
    ├── 425ad3fda7c517742fe01db74e38c0130be4a7ab.nq.gz
    ├── 43484117e2858004a0377195b5c83c3a9748062d.nq.gz
    ├── 43914b2b07cbcc23fb530a9f6126cc7d7adde6a0.nq.gz
    ├── 43c3d7f1089366e1c48297906c2693712ac6d99c.nq.gz
    ├── 465546bd396ae5eb75076f13ba9c29b0c926c835.nq.gz
    ├── 475583e1a70435fa72ac5b470f4cde5b5fd07332.nq.gz
    ├── 47b4dc34160dd3ff97ebc35ccdc99fcf49c7ffbb.nq.gz
    ├── 497592cb8eda8be1831c4639dff7e7c2b3cb7703.nq.gz
    ├── 4ae35234b9722a8b673823e67106479eae6d31a6.nq.gz
    ├── 4b2fb3e560f6ad26b30b2215d26b3d6176d076b2.nq.gz
    ├── 4c49bbf52440631eca750cacb7d79f259eeb8bd2.nq.gz
    ├── 4ce8f74784e970731f5f44b84f73780087890fa5.nq.gz
    ├── 4cfbb3a3d8436becc084938731ac9fc9c858aa64.nq.gz
    ├── 4d4ec8ceea9a96956864eddff4900fc4fb9ba8f1.nq.gz
    ├── 4e5cedeb466365de641f660c771c8bb3d12e944e.nq.gz
    ├── 4eb17ff0057b8843a0b840c6fef4b77accfe43b5.nq.gz
    ├── 4f771828c9b54d9bcaef82639425df4b3559b5e1.nq.gz
    ├── 5090cdc793c4cd8abb4c1d887caa616aecb4ae5c.nq.gz
    ├── 50a064fa0166a0dc22f89cdadf957a545d3f6544.nq.gz
    ├── 516f074c75591ec39eb404675ed9b9e5adab9d04.nq.gz
    ├── 51b65a6bfe40eb5a4e70d43a15f52de118c63b01.nq.gz
    ├── 52d876f72a96efe49efc6e4b4a4e9c049d7e2c3e.nq.gz
    ├── 53a3c14312bc770bf9bca1d2e7518763fec7a485.nq.gz
    ├── 53e2331df5f02936820284367e4821bff2aff5a7.nq.gz
    ├── 54dff005b876339f5c1ff3dc0aeae1519c29b368.nq.gz
    ├── 550e2a08773b328683ab10fb9feddee2038e9e58.nq.gz
    ├── 551884d322bcd2201b4b9898ec765141277e6eee.nq.gz
    ├── 55dce5722cc9d913164747da068f37d3529e799f.nq.gz
    ├── 56a4dd2a19fac5cc1bb1951dedf3ae93e0b9e321.nq.gz
    ├── 57240cf89fb33139a92451ec2eb99cb67b2f49c1.nq.gz
    ├── 581bb0e08b616a433d422ccb8f958cbebdae1770.nq.gz
    ├── 58863e0436d16ef8ff8ba3d96b452086e4ae8ff5.nq.gz
    ├── 589990ae8966d1af67f1e05c21e14149adec2089.nq.gz
    ├── 58a82e4eb701ecb0413f908c57080646be392bba.nq.gz
    ├── 58d75bc26eec90272e97696f40483eb56c2b8b45.nq.gz
    ├── 5990010b649745369501c7641c401bcad4345b85.nq.gz
    ├── 59bc6e40b7bb0b4eb199dd8c17f416ee00ca4158.nq.gz
    ├── 59c952ebc65169dce30078a3e1ee371e0da52ae4.nq.gz
    ├── 59d3dbc70d6cf3f8b5f7248ea107aff77d7efca9.nq.gz
    ├── 5aa6039ea4cb36077f048782b54c6275c25e86b3.nq.gz
    ├── 5ab3243a5f01f5056127f160cfe693c33edf0531.nq.gz
    ├── 5d8fc3a1b253d1df3a0184013469c6e46f6f6f75.nq.gz
    ├── 5e6b6de6451b4408fb71ef73950712a0827d49a6.nq.gz
    ├── 5e71e07e2b87201b1d2f93711b87c2b11a8a03d2.nq.gz
    ├── 5ef7be71fd96e4ef66fce3ab675303559dbb22a3.nq.gz
    ├── 5f4ebcb7f9789c4ecda13ac66c2e768851113004.nq.gz
    ├── 5f865ea808b57d97634d4331fc5fce84349ded36.nq.gz
    ├── 60bdf4d07e6ef544ff18013b272dfb851f1cc27c.nq.gz
    ├── 610b850b1dec4966d570eb36f9a8b35fd6aacd68.nq.gz
    ├── 62c5840a83e29b4fcedba95e438581cec96b3cf6.nq.gz
    ├── 639ca3be4062496b10a8dee26be3733cf457fbdd.nq.gz
    ├── 645ee9453073acf4cff9f9420b358a8ebbe40f93.nq.gz
    ├── 65a9fa2cd2e8548b13f1d0895bcba46fa11600a4.nq.gz
    ├── 65ee428ce1c5093a4b3dd29512d98a33b4c753a0.nq.gz
    ├── 660ce4cf695702ee8c6eef5c0e2419de37d6df74.nq.gz
    ├── 668e70d765dc3fb0eda16fb0f1932af607b53412.nq.gz
    ├── 679d321e3b691b5403d9c9493367651360ea6f15.nq.gz
    ├── 6855e4e9fe021cbbc392c76e1effef86dd53510c.nq.gz
    ├── 68ddaae768e665a8170ea1485aae51c686f5cfed.nq.gz
    ├── 691c56978a033586e3302db2ef600e4b0ffd6366.nq.gz
    ├── 69f0faad1e7247882721bb81a7242ddd4b1d269f.nq.gz
    ├── 69ff7f6fb4973efb1185cad9f553f8c770c75934.nq.gz
    ├── 6b08d15bdaba6cf94dcb2681887154f4d265d8ba.nq.gz
    ├── 6bc216823e007c8dbdd6a5e8402b2e0cc5eaf3fc.nq.gz
    ├── 6d1d90dede9888571eb09299dbd0b3e7dcfb1cc9.nq.gz
    ├── 6d5ce3db7323d63f73e9e92b6f4d3d6b77632a94.nq.gz
    ├── 6dd927cb94101609afa1d505129296370cd8aabe.nq.gz
    ├── 6e08a261274e48f93eb5e221ba294e54ca671b94.nq.gz
    ├── 6ea24b72cd9552c973510d1c17ace66fd35e1cc5.nq.gz
    ├── 6eb3ac46ec56985b52488ae6a8d80247c2adcd4a.nq.gz
    ├── 6f5d3a15abbe48b8a4dc72aadc88c416160a56a6.nq.gz
    ├── 6fd31e075a29223eeea3f9a1a747b4531775f8ef.nq.gz
    ├── 71b0eab085dbbb48050d7b6a271ebb1a29fb1926.nq.gz
    ├── 720c679017404f9b9ecec0687c09a879abf6d256.nq.gz
    ├── 720c9863f2a834f310280cc9113bedc59a25206d.nq.gz
    ├── 7220bda0adb9f04d704cb893a5d1ee8bd9173b82.nq.gz
    ├── 72a3d4e87a0d6f568eeb84b4a9dfae0b679d23ff.nq.gz
    ├── 72fec9e8c52ab8bb3dc6519b9d7f0c311900ac16.nq.gz
    └── 7409d74983c8d0cd8347a663c3bfbc1c041124da.nq.gz

12 directories, 200 files
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
*Parsed on 2026-09-18 by [repolex](https://repolex.ai)*
