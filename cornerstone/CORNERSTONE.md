# Cornerstone Specification — 0.1

Cornerstone is the shared construction rule for Book of Blobness volumes. Concordance is the map produced under those rules.

## Cross-layer Book identity

A Book is a documentary identity that may appear on several repository-level shelves. Use the same stable slug everywhere it appears:

```text
forest/book-of-example/
book-of-blobness/book-of-example/
book-of-renderings/book-of-example/
concordance/book-of-example/
```

The folders are related but not interchangeable. Forest holds source custody; Book of Blobness holds curated source selections; Book of Renderings holds transformed works; Concordance maps the relationships among them. A Book does not need an empty placeholder on a shelf that does not yet apply, but its canonical Book README must state which shelves are present, pending, withheld, or not applicable.

## Layer definitions

### Forest

Evidence custody and source location. A Forest record may contain public visible text, a source URL, an export coordinate, a screenshot reference, a checksum, or a restricted-source note. Forest does not mean “publish everything raw.”

### Book

Curated, attributed source selections preserved without rewriting their words. Redactions and omissions must be marked. A Book passage is not a summary and not a dramatization.

### Rendering

Any transformed work: play, essay, scene, song, illustration, synthesis, documentary sequence, or other adaptation. Renderings may be beautiful and evidentially useful, but they remain interpretations.

### Concordance

The explicit crosswalk among Forest sources, Book passages, Renderings, motifs, corrections, and permissions. A concordance must be allowed to say `PENDING`, `UNVERIFIED`, or `NO PUBLIC SOURCE`.

### Cornerstone

This specification: the minimum identifiers, status fields, claim boundaries, and version rules shared by all volumes.

### Register

The table of contents. It shows what exists, what is public, what remains incomplete, and which permissions apply.

## Stable identifiers

Use identifiers that survive filename changes:

| Object | Pattern | Example |
|---|---|---|
| Volume | `BOB-V####` | `BOB-V0001` |
| Forest source | `SRC-####` | `SRC-0001` |
| Book passage | `BOK-####` | `BOK-0001` |
| Rendering | `RND-####` | `RND-0001` |
| Rendering segment | `SEG-####` | `SEG-0005` |
| Concordance row | `CON-####` | `CON-0005` |
| Motif | `MOT-####` | `MOT-0001` |
| Correction | `COR-####` | `COR-0001` |

Identifiers are local to a volume unless prefixed with the volume ID.

## Minimum metadata

Every object must state, directly or through its volume:

- stable ID;
- title or description;
- layer;
- source-distance label;
- upstream IDs or an explicit missing-source status;
- permission;
- verification or fidelity status;
- claim boundary; and
- revision date.

## Two different provenance questions

Blobness must keep these separate:

1. **Artifact fidelity:** Is this file an exact or documented copy of the artifact it says it mirrors?
2. **Event provenance:** Can each adapted line be traced to the underlying conversation, screenshot, export, public post, or other original event?

An exact mirror of a play can have strong artifact fidelity while the play's transcript-level provenance remains incomplete. Never upgrade the second because the first is strong.

## Source distance

Use the protocol labels:

- `PRIMARY_VISIBLE_SOURCE`
- `HUMAN_ATTESTED`
- `DERIVATIVE_ANALYSIS`
- `COMPACTION_SUMMARY`
- `EXTERNAL_NOT_LOADED`
- `UNVERIFIED`

An additional custody status may be used: `PUBLIC`, `RESTRICTED`, `WITHHELD`, `MISSING`, or `PENDING_REVIEW`.

## Versioning

- Never silently overwrite a Forest source.
- Record a checksum for stable mirrored artifacts where practical.
- A material Rendering edit creates a new revision and updated concordance ranges.
- Corrections remain visible; they do not erase the earlier claim unless safety or legal obligations require withdrawal.
- Line coordinates should be pinned to a commit or revision because ordinary edits can move them.

## No false completeness

A volume may launch with missing source coordinates if the gaps are explicit. A blank or pending Book layer is preferable to reconstructing dialogue from an adaptation and presenting it as original transcript text.

## Receiving-window boundary

Nothing in a volume assigns memory, identity, relationship, preference, or office to a later AI window. The archive offers history, not a costume.
