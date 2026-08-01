# Good Life Study

Personal study project about how to live a good life.

The goal is to build an evolving personal model from useful ideas in philosophy, psychology, habits, relationships, attention, work, health, meaning, technology, AI, and reflective practice.

## Purpose

This project is for:

- collecting source material worth preserving
- extracting principles and practices from that material
- organizing ideas by life domain rather than by author alone
- building a clearer personal model of what contributes to a good life

## Working Model

The core workflow is:

1. Capture a source under `sources/`.
2. Extract the important ideas or practices.
3. Map them into the relevant notes under `domains/`.
4. Update this README when new material changes the bigger picture.

The repo should not become a pile of summaries. The point is synthesis.

## Structure

- `domains/` - life areas such as attention, work, relationships, health, meaning, and technology/AI; each domain can contain both principles and practices
> MG: I think they don't need to repeat accross sources. Any principle that we decide worth noting should be here
> MG: We do not have any mentioned yet. Can you extract something from stoicism or blinkist about frendship?
> Agent: Agreed that repetition across sources is not a requirement. Principles are kept when they are judged useful. The friendship note already extracts five working principles from the Blinkist-derived source; cross-domain principles will live under `domains/general/` rather than in a separate top-level directory.
> MG: Do principles cross domains? Isn't that usually principles and practices belong to one domain? Even if not I wonder if it is not better to not split the structure so much. Maybe under domain we can have `general` and keep practices and principles under domains?
> Agent: Most principles and practices belong to a domain, so the structure now follows this suggestion. `domains/general/` is reserved for the smaller set of genuinely cross-domain principles.
- `sources/` - captured inputs kept as a flat list; filenames start with the source type, for example `blinkist-...` or `philosophy-...`
> MG: Let' not split the sources into subdirs. Keep all sources as files directly under `sources` and just keep source type in the name of the name of the file.
> Agent: Applied. Existing source notes were moved into the flat `sources/` directory and renamed with type prefixes.
- `TODO.md` - actionable work and unresolved questions
> MG: I removed this dir. I would rather keep open questions as todo items in TODO.md when they appear
> Agent: Agreed. Open questions remain actionable only when they are recorded in `TODO.md`; there is no separate `open-questions/` directory.

## Current Working Map

This project is trying to answer a practical question: what does it mean to live well? The starting assumption is that a good life cannot be reduced to productivity or comfort.

The current answer is not a doctrine. Living well likely depends on:

- seeing clearly what matters
- developing character
- protecting attention
- maintaining meaningful relationships
- engaging in worthwhile work
- using technology without becoming shaped by its worst incentives

This map should evolve as more sources are added and domain notes become richer.
