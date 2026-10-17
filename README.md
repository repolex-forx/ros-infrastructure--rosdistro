# Repolex Knowledge Graph of ros-infrastructure/rosdistro

RDF knowledge graph data for [ros-infrastructure/rosdistro](https://github.com/ros-infrastructure/rosdistro), parsed by [repolex](https://repolex.ai).

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
rlex download ros-infrastructure/rosdistro
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 960790d1e03c172a68f639190e71ba1fd04e81b9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 960790d1e03c172a68f639190e71ba1fd04e81b9
│           └── chunk-001.nq.gz
├── blob
│   ├── 0983c7fce045e4779bfc82052e8d72957bb21e40.nq.gz
│   ├── 0b3b537229fa53aa4e62798276f28e12eb692d57.nq.gz
│   ├── 0bd7cf48ba17ef970383c3743a5a1558ea3a8bb7.nq.gz
│   ├── 1025450631e34c5491bacc51d6eb1bbddeeb4bdc.nq.gz
│   ├── 110486a187f19adba7dc4990c3d1f146e074765c.nq.gz
│   ├── 14656d7f7a2b7bedf3ad4cef97831fc0390375ea.nq.gz
│   ├── 1b24935c2901b551046603f68a901a44323dd5bd.nq.gz
│   ├── 247dad5d0802b26a35a043b943b73e353e43815e.nq.gz
│   ├── 2507f72d557315a83d8743eb197fe16e79f9514f.nq.gz
│   ├── 25e594b1480c8030404571a30f6194cbcbfbe969.nq.gz
│   ├── 2741e21b3b5ed500aaf7de4549388c16b18465cd.nq.gz
│   ├── 2b461b6c77f2e894babb752f74b0b8da8f0a53d8.nq.gz
│   ├── 2bec693bba82b9522a0641398829adb674c4893a.nq.gz
│   ├── 2c0ead0373ed0c622cb66d2817941136d880c9e9.nq.gz
│   ├── 2d033353a10bd5f986c9fdeae0f0bc0739b3606a.nq.gz
│   ├── 304f8653fe6c622ba381844c375d5b3f85afdf69.nq.gz
│   ├── 30fe473dfc3a4476d8036e572e24ab9a64b08626.nq.gz
│   ├── 31e303c3ddc6e4d8627fe4ea10e85e1dfc5cd7ed.nq.gz
│   ├── 3651da9f466b5591d708856d42ccd88a751dc98a.nq.gz
│   ├── 375316318ad536c471413f0c12995a27cabc0595.nq.gz
│   ├── 38199c63c11b557d99ef12188dbb1c9376c39f92.nq.gz
│   ├── 386d832ede9b944b64c84f5c43abeccd1db01a31.nq.gz
│   ├── 3fecc19771d6476f5ae48f425e0a4f3af8ff59af.nq.gz
│   ├── 4074e61c92f2426604bef8f42a1d704527d6135a.nq.gz
│   ├── 41b7be0a19b526a6f3858f5e100ac908c51d9800.nq.gz
│   ├── 42dc948501b580b73b35702b9170506239ace2d2.nq.gz
│   ├── 442b871639f4f3db68c55ea5f83b8650bd5c91de.nq.gz
│   ├── 44ba8c158009132d673f1f532b6dc4999c8da100.nq.gz
│   ├── 46235ed9048e4ce8258807974963a025b72c706e.nq.gz
│   ├── 473dc03f0cfc98de54affa4c41850919a0bcd7c5.nq.gz
│   ├── 4a94a7cc1b9c837952fdd803f5fc1f390a5ce41a.nq.gz
│   ├── 4b05825cd6bc7403c144f6f1d8f1bca7d85b59c7.nq.gz
│   ├── 52f8d310960f74c8edd24a2faa524c8f0db1cc9f.nq.gz
│   ├── 54a7b6278f51b1ab21efe46e12dfe5f80eefc321.nq.gz
│   ├── 570842389f34fb0e6971b7f6184e51cccb156e22.nq.gz
│   ├── 5771ae59002607484568cc37947d5dfa46c0ad0a.nq.gz
│   ├── 596276501f427edf995c89beeee2f1d473b63c6c.nq.gz
│   ├── 5ba807ec05cbd06f1e7d300a440496cd3eccbfb6.nq.gz
│   ├── 602a8a0b0aa26fc9d5c3ac773a7c3aeda187686f.nq.gz
│   ├── 659426e06f0e770e5678f363dfb117f813efc9a9.nq.gz
│   ├── 666779f0c3c1c4a8f88bfce4bbcfbab3ede985a5.nq.gz
│   ├── 687b069190a91bca2e5dd44098246d52e2f7f0bb.nq.gz
│   ├── 6a922ffb807f14a458e84e1e769f013baa7e3506.nq.gz
│   ├── 6be4ecbec6c301f36860582c73d4d7b93beb5a1a.nq.gz
│   ├── 6e9e5e60abe004f7774a713017b73019a57741b9.nq.gz
│   ├── 6f8faca141df52b3923bafe9006c3b5df3cd84ea.nq.gz
│   ├── 8181b871333dc22dbc84fb9d39b9cdf49938f2c3.nq.gz
│   ├── 83ee72adb547848999fd37b7cc8df907364c4060.nq.gz
│   ├── 85de71a8cf5d28a782a11a4a374846830b0fb81c.nq.gz
│   ├── 8646fe55615b36ff12de04bb60d9c4c02a273348.nq.gz
│   ├── 86d4a8b52a79c9e9b80601118e0ed8ab67c880a8.nq.gz
│   ├── 890e3c3713c134530b82fa9f4c21d79ad366b9b8.nq.gz
│   ├── 8cd038c7e19ad0f8d54cdba4109b1e6c25114c7c.nq.gz
│   ├── 8d0ba4571f27523cc4be847a588f565604eac8d3.nq.gz
│   ├── 8d412eeb75eb80f75532404c5d00776f0cbff9fd.nq.gz
│   ├── 91aa2efc48734100692f73dc2d744b7941030e39.nq.gz
│   ├── 9260d962091ea2a7eaa0c7cb4a0f9f894550339e.nq.gz
│   ├── 938bd6ad6affa5f492cae77490bd29537a922087.nq.gz
│   ├── 9505ad0e2a21199a19fc6bc561afefe72344dbba.nq.gz
│   ├── 95862269d878e43977798228268e3e60cedc4b75.nq.gz
│   ├── 9c91e84253675b021b092349b35b9c3dbe1d48ad.nq.gz
│   ├── 9d5a32ea88dfd77629501825320fe2c803a0979f.nq.gz
│   ├── 9da09bfbfff80d7c15396ed1125b969c0e2de4ac.nq.gz
│   ├── 9ebd9fca7bd452b75d3d6e9d470d1eafdf611f00.nq.gz
│   ├── 9ec738cef56742954ba2c02a1e2332713fbef1ae.nq.gz
│   ├── a042df64bb74f0d7e1b21ee89ff138d29848dc9c.nq.gz
│   ├── a274bea8c0dcef2fdb99398ea636e0cf9950eb9c.nq.gz
│   ├── a97e4626ab4e0879d4d9092f831c1a8f72b1483e.nq.gz
│   ├── a9c89a416e1d5276ae66bd8c714ea1b6a649d675.nq.gz
│   ├── aac913b8ce6a56f67452eb20c13600ce133744ac.nq.gz
│   ├── ac76942462b4254a3a97a91fbce0fed543f61184.nq.gz
│   ├── ad13f3f4b65af6c76408a759d468a76b8b7d6570.nq.gz
│   ├── ad59de6cc31ffd511a39c28a6a3e37018af79b72.nq.gz
│   ├── af25849ec180d71527d6b9b33a81423fcaf6386b.nq.gz
│   ├── b34a165d839dcdbeafc0d3c065e13fd45f0cebce.nq.gz
│   ├── b514965dd3799616c499a93f063c851e605617fe.nq.gz
│   ├── b84208b1c88ad3c55642972c1eb93e65607002f0.nq.gz
│   ├── c285cbf5ea0181d3886ce532f0f09ece37ccd7ec.nq.gz
│   ├── c525ceda83c23918e0a3cd54bb756d1d8a7cb681.nq.gz
│   ├── c742c06d4319c056947d9559a5dbbce059a85f37.nq.gz
│   ├── cfa98a5183a21af77b591001a7d52b8e8d3afa5a.nq.gz
│   ├── d0d96482edd98a82b4bf2d7ec5a45b89863c3afa.nq.gz
│   ├── d162e6dcf0e4b9076b5dd10325a1ed2b8eb3a524.nq.gz
│   ├── d33ffe6dafaf8f2471d5fc4bf60018e90c1aec1d.nq.gz
│   ├── d4db2a847535179eb8d7e64c5872b71e7a826130.nq.gz
│   ├── d5169fbae602c364faa2b801a3964d9e9b96dff3.nq.gz
│   ├── d6be9da53c7ff6dbfa8a3370c0305f5a220aa7e8.nq.gz
│   ├── dac073c782a6bfde51241bbbbdf610ed69f291e3.nq.gz
│   ├── ddc5cddcd334c5181548867b39280e10e62f4c8f.nq.gz
│   ├── e164f6919d35a4161640e2bb5d851ab9d8b71a52.nq.gz
│   ├── e3562af8d87e7f1cc4085c645c5851e04473c4dd.nq.gz
│   ├── e5620741b96fdcf531dd54f373fcb52524eb7d98.nq.gz
│   ├── e832028c54a9602e774e06d9cd61212c01c7998d.nq.gz
│   ├── e94b9cc5af84cfc3d3c7e2abe0654fc9567fca7d.nq.gz
│   ├── ebb385867364584910bd3acafc775f2664e699a2.nq.gz
│   ├── ef2b76d067f6739e281776fb8546d33df41ec8a6.nq.gz
│   ├── f68850497f764fc1caa4d70fe0ed52dae00b10cb.nq.gz
│   └── fcd74a2e6eb7837cc37005d05adcdb76a38b57c2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 960790d1e03c172a68f639190e71ba1fd04e81b9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 106 files
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

[ros-infrastructure/rosdistro](https://github.com/ros-infrastructure/rosdistro)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
