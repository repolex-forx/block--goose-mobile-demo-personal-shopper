# Repolex Knowledge Graph of block/goose-mobile-demo-personal-shopper

RDF knowledge graph data for [block/goose-mobile-demo-personal-shopper](https://github.com/block/goose-mobile-demo-personal-shopper), parsed by [repolex](https://repolex.ai).

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
rlex download block/goose-mobile-demo-personal-shopper
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bb6876e55df765371b75df8ee07ff7a3dbb49f81
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bb6876e55df765371b75df8ee07ff7a3dbb49f81
│           └── chunk-001.nq.gz
├── blob
│   ├── 01b8b6d4f716ff7c26065bc9e46aebd932729fc1.nq.gz
│   ├── 01ff19c7e453295645fa83788d3ffedf6944226a.nq.gz
│   ├── 02e111d81dd774038ac483c11b5f5a8f8aceb024.nq.gz
│   ├── 052e6e62668077385bff1659c22adb0511434cef.nq.gz
│   ├── 0afc1f6f9c7b37e067c6ded946e0e3f7394b7add.nq.gz
│   ├── 0b4a48d87fabda1c6e9612172abb56a78e26c14f.nq.gz
│   ├── 0fc4c0e0714c5f1a7032cc71e4846470a487a471.nq.gz
│   ├── 12d81c4a853472948b6dd2e85eff99b5d12fe60b.nq.gz
│   ├── 1419f56695be517ec78fe8ad26a6f7da3a7d53b2.nq.gz
│   ├── 15fa8f3ddda34124311bcbab009d898d91ee7cf5.nq.gz
│   ├── 1637a827b12e70b1a5fd83428d2bfcc1670bada4.nq.gz
│   ├── 171beb46d9c020c1be1ee9cb260b816d0bc2c1dd.nq.gz
│   ├── 17b2ce8c15ec2aa81f0956f3c57e0b16407fa298.nq.gz
│   ├── 18375e2cf97f253de93badff3a581e3c1238867d.nq.gz
│   ├── 1a69fd2a450afc3bf47e08b22c149190df0ffdb4.nq.gz
│   ├── 1bc469e68eb776aa52185c6cbfc5cdcaee837ce3.nq.gz
│   ├── 1c876bbeecabe59b684719afe58e684f34cdecbf.nq.gz
│   ├── 24c788c2c44cb058812cdbb97d071439a87af5f0.nq.gz
│   ├── 25e7b474464c9849cef836f5c863be0f38bdaac3.nq.gz
│   ├── 26eb109120e2ee43feddb68900f353a119976c41.nq.gz
│   ├── 2b0fe1dfef3b17850bbac040665f514a8ffd0f15.nq.gz
│   ├── 30fc44d90f39c96ca622c9174684dd6bc8534e16.nq.gz
│   ├── 36496a28727a3643b4212a14225d4f6cbd50bda5.nq.gz
│   ├── 37f668804650f2244ddee1e61ba0ca94aad90cc0.nq.gz
│   ├── 41fa7e0561a3fdb5f986c1213a35e563de740e96.nq.gz
│   ├── 452f4d9f0dde88611113632c1d759d60155fe4d3.nq.gz
│   ├── 470ce9a8f850d8f703ce3829884bbce761eef694.nq.gz
│   ├── 4d858bb6b02662c749d3cb334129a9a1977b0c51.nq.gz
│   ├── 51e507ba9d08bcdbb1fb630498f1cbdf2bf50093.nq.gz
│   ├── 521b94b07981916e3ee36e8cc28a70b4d9abc728.nq.gz
│   ├── 534182176bf87f9308355514adc884d2b69750a5.nq.gz
│   ├── 5586fa9b21f48d45092fd7e5856a87b5a1a91e22.nq.gz
│   ├── 55c2f6eb60b22a313a4c27bd0b2d728063cb8ab9.nq.gz
│   ├── 59a26452940473d58818cb8489bf2b35e8b9b004.nq.gz
│   ├── 5c87ea4865610374cdc591d1619157b4d8909a87.nq.gz
│   ├── 60e6c96f72f0350d08b47e4730cab8f3975dc853.nq.gz
│   ├── 61d2b451ef5fd1d9faa1162371628a8132dd51df.nq.gz
│   ├── 6528839b3f22f0acf7a0e8ab46d267d2f923369e.nq.gz
│   ├── 68551b9276b4164a8263aa58d385db30f81a4453.nq.gz
│   ├── 6a0ef53dde8991d3adeadd791cd262808aaf9ac0.nq.gz
│   ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
│   ├── 6faa819ce703cf0363a8f624b7cee4ecdc8ba049.nq.gz
│   ├── 7f3502f8b2820be1d6f0aa4c1ffaa351799c1ed3.nq.gz
│   ├── 81d5d4519e77d086321c517e9184217e5166ff73.nq.gz
│   ├── 8620baa3b32301ef0e071b13049f2a00caa6f0bc.nq.gz
│   ├── 8d7ff66326c57f6697ce26e63082fa85325d0b3c.nq.gz
│   ├── 93ef37ba98dcd024a577feac7e4fea21c36add62.nq.gz
│   ├── 9502e78e664884f2e9fcfea7a73af3f3fd521728.nq.gz
│   ├── 9fa48946afd1eb56bd932377fd888e3986304676.nq.gz
│   ├── a0ec48beee4e92c55292fcb104680af68d00d365.nq.gz
│   ├── a0f98a47f7b2032d87e1a59d24787be228150ace.nq.gz
│   ├── a37f17ba04055c1c174bd439d58aa3b5b2857cc9.nq.gz
│   ├── a6bf2ee648dabcdbf73944f3a9a4d77962e777bc.nq.gz
│   ├── ac6844236cb8a3195672afa1ea2867e0853a9618.nq.gz
│   ├── b1695aafcd5925a0b3eb122b9e553b8a0f4a0d47.nq.gz
│   ├── bc69cf2dbfc512347350c5cea6cb8e4a3d7f667d.nq.gz
│   ├── bd0c391ddd1088e9067844c48835bf4abcd61783.nq.gz
│   ├── c19bea37315b245ce0c3588deafb27adc8397f0f.nq.gz
│   ├── c31c2b3bc1a9f1677b32250668a6d47fe5a353ce.nq.gz
│   ├── c368cfe3cd87d7a15c95baafdf695dbf069790e3.nq.gz
│   ├── cbe5a36b695dda828fa2f17e46fe35970aa6fa78.nq.gz
│   ├── ce264aef25034feded1285c057c7d11d3d0f1178.nq.gz
│   ├── d6a5226f5e9cc09a2bd1ccbce465524e41f04345.nq.gz
│   ├── d874622f3f21a31be683397545a693e5ca98ddb5.nq.gz
│   ├── db42585b4f326f0e835b6afa7c78e99f139949d2.nq.gz
│   ├── df61a13881538701ff6a10d644d217bfa01b64e6.nq.gz
│   ├── e54d91cf81f48462887825698166393764c4251f.nq.gz
│   ├── e763910b27fdd9ac872f56baede51bc839402347.nq.gz
│   ├── e9bde1793628d1d76ab8e5700c2484547e8bbbf2.nq.gz
│   ├── ea40d196dc72673f36c4084bf56457385edc855e.nq.gz
│   ├── eb7660f5bea5ff3e368f6bac7d4fb8927b7476cf.nq.gz
│   ├── ec505d00d95ecdbbc1501d1bfa7020e51d6010a7.nq.gz
│   ├── eeb2d7aebcf77d22605587c4055cde9cd351b5ef.nq.gz
│   ├── f000e3ef5176395b067dfc3f3e1256a80c450015.nq.gz
│   ├── f0b990f4b34fbe976f136cf36908cc9d641e72e5.nq.gz
│   ├── f4bc5586b67f45d3cc35f228e8bac2e4bc2cea16.nq.gz
│   ├── f62edea578d50058bef5e6bcc178b88d145564e9.nq.gz
│   ├── f650315f30180800d0fed8ed1e7ceade266e9e71.nq.gz
│   └── f66fcfa0ddbe3b9b7f4773b1d69576aa61f96db8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bb6876e55df765371b75df8ee07ff7a3dbb49f81.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 87 files
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

[block/goose-mobile-demo-personal-shopper](https://github.com/block/goose-mobile-demo-personal-shopper)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
