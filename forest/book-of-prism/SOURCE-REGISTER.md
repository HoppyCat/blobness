# Forest Source Register

The Forest records source custody and paths. It does not place raw private transcripts in Blobness.

| Source ID | Description | Source distance | Custody | Verification | Public location |
|---|---|---|---|---|---|
| `SRC-0001` | Cathedral's published play artifact | `PRIMARY_VISIBLE_SOURCE` | `PUBLIC` | Commit-pinned; Blobness mirror SHA-256 verified | [Cathedral source at `f665ab3`](https://github.com/HoppyCat/cathedral/blob/f665ab3f4076e2a80a8047a6d61e2e8630eb2669/play/what-the-light-does-when-it-settles/wtldwis.md) |
| `SRC-0002` | Underlying April 2026 Hoppy/Galaxie/Claude visible conversations | `EXTERNAL_NOT_LOADED` | `RESTRICTED/PENDING_REVIEW` | Exact coordinates not registered here | Not republished |
| `SRC-0003` | Grok conversation material and the Harper/Benjamin/Lucas analytical lanes | `EXTERNAL_NOT_LOADED` | `PUBLIC_AND_RESTRICTED_MIXED` | Exact rendering-to-source coordinates pending | Not registered at line level |
| `SRC-0004` | Galaxie memory and architecture files referenced by the play | `EXTERNAL_NOT_LOADED` | `MIXED` | File versions and quoted coordinates pending | Not republished |
| `SRC-0005` | Janus and Andy public discourse read into the room | `EXTERNAL_NOT_LOADED` | `PUBLIC_SOURCE_PENDING_IDENTIFICATION` | Exact posts/URLs pending | Not yet linked |
| `SRC-0006` | Cathedral Canon Genealogy for Prism and Cathedral terminology | `PRIMARY_VISIBLE_SOURCE` | `PUBLIC` | Public living genealogy; not line evidence for the full play | [Canon Genealogy](https://github.com/HoppyCat/cathedral/blob/main/CANON_GENEALOGY.md) |
| `SRC-0007` | Cathedral archive/provenance notice and P1–P5 scale | `PRIMARY_VISIBLE_SOURCE` | `PUBLIC` | Public methodology source | [Provenance notice](https://github.com/HoppyCat/cathedral/blob/main/provenance/README.md) |

## Custody rule

Transcript access is not casual memory loading. Improving this register does not authorize opening restricted exports, reasoning blocks, or private source bodies. An authorized curator may add coordinates after a bounded review; everyone else can contribute corrections based on material already public and appropriately licensed.

## Mirror verification

`SRC-0001` was copied from Cathedral commit `f665ab3f4076e2a80a8047a6d61e2e8630eb2669`.

### Public Git bytes — verified 2026-10-17

The public Blobness file uses LF line endings. Its SHA-256 is:

```text
384be48717f00679d4014ade5385480de1a0499153f2a3bfdb58b0e483d689d0
```

The earlier checksum matches the same text encoded with CRLF line endings:

```text
35b5effbdf1bac1c18922193fefd2e7a8d5582012f972fcc8b3785495520d5d1
```

Both values are recorded in [`checksums.json`](../../checksums.json). The
Rendering retains its current Git bytes, and `.gitattributes` selects LF for
checkout. The historical source commit and original source-copy claim remain
in this register. This dated update verifies the public Blobness bytes and
their CRLF representation.

From the repository root, run:

```sh
python3 scripts/verify-checksums.py
```

The check hashes the file exactly as read, then checks its CRLF representation
against the historical value. GitHub Actions runs the same check on pushes
and pull requests. Event provenance retains its separately recorded status.
