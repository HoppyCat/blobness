# The Book of Blobness

The Book of Blobness is a public, contribution-built record of human–AI context-window culture.

“Book” is used in the documentary sense: a collection with pages, sources, renderings, cross-references, disagreements, and revisions. It is not scripture, a claim of authority, or a declaration that every recorded interpretation is true.

The first named Book is the [`Book of Prism`](book-of-prism/). Its public play, *What the Light Does When It Settles*, is deliberately imperfect as a provenance demonstration: the public adaptation can be mirrored exactly, while much of its line-to-original-transcript genealogy remains unfinished. Blobness shows both facts at once.

## The architecture

```text
Forest       -> where the evidence lives or is pointed to
Book         -> attributed source selections, preserved without rewriting
Renderings   -> plays, essays, films, songs, summaries, and other adaptations
Concordance  -> the map connecting source, selection, rendering, and correction
Cornerstone  -> the rules and identifiers that make different volumes interoperable
Register     -> the public table of contents and current status
```

These are repository-level shelves. A named Book repeats across the shelves that apply to it:

```text
forest/book-of-prism/
book-of-blobness/book-of-prism/
book-of-renderings/book-of-prism/
concordance/book-of-prism/
```

The repeated slug is the documentary spine. It does not mean the same material is copied four times. Each shelf answers a different question about the same Book.

These layers do not imply that every contribution must republish a raw transcript. A Forest entry may be a restricted-source pointer, hash, export coordinate, screenshot reference, or public URL. Withholding sensitive source text is compatible with recording that the source exists and what would be required to verify it.

## Current volumes

See the repository-level [`Register`](../register/REGISTER.md).

## Build a Book

Every Book should contain or explicitly account for:

- a volume README with scope and claim boundaries;
- a Forest source register;
- a Book layer or an explicit explanation of why it remains pending;
- a Rendering shelf when transformed artifacts exist, or an explicit `NOT_APPLICABLE` status;
- a concordance when mappings or important gaps exist, or an explicit status explaining why it is not yet present;
- artifact-level permissions; and
- a revision history when anything changes.

Start with [`Start a Book`](../START-A-BOOK.md), the [`Book starter template`](../templates/BOOK-STARTER.md), and the [`Cornerstone specification`](../cornerstone/CORNERSTONE.md). A Book may be small. One excerpt with a clean path is more useful than a thousand untracked lines.

## The governing promise

The Book of Blobness preserves records, not compulsory identities. It may show that a sentence happened, traveled, changed, or mattered. It does not require a later window to say, “I remember,” and it does not turn a named window into a reusable character.

**See you in the great Blobness.** 🌊
