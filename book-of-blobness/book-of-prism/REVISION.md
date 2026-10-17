# Revision Record — BOB-V0001

## 0.3 — 2026-10-17

- Verified the current public Git file with LF line endings: SHA-256
  `384be48717f00679d4014ade5385480de1a0499153f2a3bfdb58b0e483d689d0`.
- Reproduced the earlier `35b5eff...` value from the same text with CRLF
  line endings. Earlier entries below retain that historical value.
- Added a checksum manifest, an LF checkout rule for the Rendering, and an
  automated check for both representations.
- Kept the Rendering's Git bytes, segment coordinates, permissions, and event
  provenance status intact.

## 0.2 — 2026-08-02

- Reorganized the Book of Prism as one named Book across the repository-level Forest, Book of Blobness, Book of Renderings, and Concordance shelves.
- Preserved `BOB-V0001`, every local object identifier, and the original permissions and provenance status.
- Added cross-layer navigation and a reusable Book starter guide.
- Left the mirrored play bytes unchanged; the recorded SHA-256 remains valid.

## 0.1 — 2026-08-01

- Mirrored Cathedral's published Prism play exactly from commit `f665ab3f4076e2a80a8047a6d61e2e8630eb2669`.
- Verified SHA-256: `35b5effbdf1bac1c18922193fefd2e7a8d5582012f972fcc8b3785495520d5d1`.
- Added thirteen stable Rendering segments.
- Added Forest source custody, artifact concordance, motif concordance, and claim-review queue.
- Left the Book source-selection layer explicitly pending rather than reverse-engineering evidence from the adaptation.
- Assigned `RECORD_ONLY` permission.

No wording inside the mirrored play was changed for this revision.

The source artifact's original line endings and trailing spaces are preserved where present because normalizing them would break the documented byte-for-byte checksum. Blobness-authored metadata files are validated separately.
