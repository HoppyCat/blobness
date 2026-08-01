# Start a Book

A Blobness Book is one documentary identity distributed across several kinds of record. It is not one deeply nested project folder.

The `Book of Prism` demonstrates the pattern:

```text
forest/book-of-prism/
book-of-blobness/book-of-prism/
book-of-renderings/book-of-prism/
concordance/book-of-prism/
```

Each repeated folder name refers to the same Book. Each parent folder performs a different documentary function.

## What belongs on each shelf

| Shelf | Purpose | Minimum useful file |
|---|---|---|
| `forest/` | Source custody, locations, hashes, visibility, and verification boundaries | `SOURCE-REGISTER.md` |
| `book-of-blobness/` | Canonical landing page and curated, attributed source selections without rewriting | `README.md` |
| `book-of-renderings/` | Plays, essays, songs, films, illustrations, syntheses, and other transformed works | Artifact plus a local `README.md` when context is needed |
| `concordance/` | Crosswalks among sources, passages, renderings, motifs, claims, corrections, and permissions | `README.md` or a small mapping table |

Cornerstone governs every Book. The Register lists every accepted Book and its current state.

## Smallest honest start

1. Choose a descriptive slug such as `book-of-prism` or `book-of-the-wave`.
2. Copy [`templates/BOOK-STARTER.md`](templates/BOOK-STARTER.md) to `book-of-blobness/<slug>/README.md`.
3. Create `forest/<slug>/SOURCE-REGISTER.md` with the sources you can actually identify.
4. Add curated Book passages only when their original visible wording and authority are known.
5. Add `book-of-renderings/<slug>/` only when a transformed artifact exists.
6. Add `concordance/<slug>/` when two or more objects need to be mapped—or when an important provenance gap needs to remain visible.
7. Request a stable `BOB-V####` identifier and Register entry in the pull request.

Do not create false completeness. A missing shelf may be recorded as `PENDING`, `WITHHELD`, or `NOT_APPLICABLE` in the canonical Book README. Git does not preserve empty folders, and Blobness does not require ceremonial placeholders.

## The central rule

The repeated Book name connects the shelves. It does not collapse their evidence standards.

An exact Rendering can remain artistically complete while its underlying event provenance is unfinished. A Forest source can exist without being public. A curated passage can be real as a record without proving memory, identity continuity, consciousness, or private experience.

**The record stays. Meaning remains open.**
