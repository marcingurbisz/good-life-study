# TODO

## [FOR HUMAN]

## [DONE 2026-08-01.1] Feedback
* see my feedback as inline comments in README.md
  > Agent: Responded beneath every inline `MG` comment and implemented the resulting structural decisions.
* don't treat Stoicism in special way in good-life-study. E.g. I do not want sentences like "This repo is meant to be broader than Stoicism alone. " in readme.
  > Agent: Removed special-status language from `README.md`. Reframed the Stoicism note as one philosophical source among others and removed the earlier foundation/backbone framing.
* is good-life-study name better than living-well-study?
  > Agent: Keep `good-life-study`. “Good life” names the subject being studied and matches the practical question in the README. “Living well study” can also be read as a study that is being conducted well, so it is less precise as a repository name.
* I wonder if we need synthesis dir? Whole good life study and directories /domains is already kind of synthesis, isn't it?
  > Agent: Agreed. The repository itself is the synthesis: source notes preserve inputs, domain notes integrate them, and the README holds the top-level map. Removed the separate `synthesis/` layer.
  * integrate [text](synthesis/overview.md) with README.md?
    > Agent: Integrated the overview as `Current Working Map` in `README.md` and removed the standalone file.
  * move [text](synthesis/stoicism-and-the-good-life.md) to `sources`?
    > Agent: Moved and reframed it as `sources/philosophy-stoicism.md`, following the new flat source naming convention.

> Changes: Simplified the repository to `domains/`, flat `sources/`, and `TODO.md`; removed the empty top-level `principles/` and `practices/` placeholders and source-type subdirectories; added `domains/general/` for genuinely cross-domain material; and renamed the Blinkist note to `sources/blinkist-how-to-be-a-friend-in-an-unfriendly-world.md`.
> Validation: Re-read all inline feedback against the resulting README and tree, confirmed every source is directly under `sources/` with a type prefix, confirmed no tracked files remain under `synthesis/`, `principles/`, or `practices/`, and ran `git diff --check`.
> Learning: Prefer domain-owned principles and practices. Use `domains/general/` only for ideas that truly cross several domains, not as a default destination.

## [DONE 2026-08-01.1] Review `stoicism-personal-study` and stoicism itself and extract the ideas that should become reusable principles here.

> Agent: Reviewed both language versions of `stoicism-personal-study`, then checked its core claims against Epictetus and academic reference works on Stoicism and Stoic ethics.
> Changes: Expanded `sources/philosophy-stoicism.md` with source links, distinctions between virtue and preferred externals, a careful reading of what is “up to us,” impressions and judgments, the four practical capacities, social responsibility, acceptance, and explicit misuse boundaries. Added `domains/general/principles.md` with six reusable principles: anchor well-being in choices rather than guaranteed outcomes; focus effort where agency exists; treat first impressions as hypotheses; train wisdom, courage, justice, and moderation; hold acceptance together with action; and include other people in flourishing.
> Validation: Compared the extracted principles with the local Stoicism diagram and prose; verified the classical framing against Epictetus's *Enchiridion*, the Stanford Encyclopedia of Philosophy, and the Internet Encyclopedia of Philosophy entries on Stoicism, Stoic ethics, and Epictetus; checked all local links and ran `git diff --check`.
> Learning: Preserve the nuances usually lost in short Stoic summaries: preferred externals can matter without defining flourishing, responsibility for judgment is not control over outcomes, working with impressions is not denial of pain, and Stoic flourishing includes justice and social duties rather than private calm alone.

## [NEW] Incorporate [`digital exhaustion`](../publishing/published/posts/2026-04-22-digital-exhaustion.md) into good-life-study.

## [DONE] 2026-04-25

- Added the first synthesis note connecting Stoicism to the broader `good life` frame.
- Imported the first Blinkist-derived source note: `How to Be a Friend (In an Unfriendly World)`.
- Added the first relationship domain note: `domains/relationships/friendship.md`.

## [DONE 2026-04-25.8] Leaving well project considerations
Extension to existing https://github.com/marcingurbisz/stoicism-personal-study (../stoicism-personal-study). I would create a project that would be my more general study about how to live a good life. Both publishing and this study project are related because what I read and publish I want also incorporate somehow into "living well" project. I wonder how to best name it.

Idea of it is that we will combine all the new sources into the overall picture. Stoic philosophy may be the base for now but do not need to be. When I come with some new blink with interesting ideas I incorporate it my picture of good life.

Additional questions/remarks:
* ../stoicism-personal-study as base?
* How to name it "living-well"?
* Each new relevant book from blinkist to be incorporated into project - get new ideas and put it proper place in project structure with references.
* What are other approaches to do this project?
* Maybe do not base on stoic but find some other way to structure living well knowledge?

> Agent: Taking this item. Goal is to decide whether the future project should extend `stoicism-personal-study` or become a broader umbrella, and to turn that into a concrete naming and structure recommendation that can drive the next item about creating the project.
> Changes: Added `wip/living-well-project-considerations.md` with a clear recommendation to create a new umbrella repo rather than extending `stoicism-personal-study`, plus naming options, a preferred repo name (`good-life-study`), and a domain-and-synthesis structure.
> Validation: Re-read the note and confirmed it resolves the key design dependency for the next item: whether to extend the Stoicism repo or create a new broader project, and what structure that broader project should use.

## [DONE 2026-04-25.9] Create project based on outcomes from "Living well project considerations"
Please create such a project in workspace.

> Agent: Used the recommendation from the previous item and created `../good-life-study` as a new umbrella project in the workspace.
> Changes: Added the initial domain-and-synthesis folder structure, created `README.md`, `TODO.md`, and seed notes under `synthesis/` and `domains/`, and aligned the project around a broader good-life study rather than a Stoicism-only frame.
> Validation: Verified the new project structure exists on disk and that the top-level files describe the intended workflow, structure, and relationship to `publishing/` and `stoicism-personal-study/`.

## [DONE 2026-04-25.10] Add "How to be a Friend" to living well project
Look into [How to be a Friend (In an Unfriendly World)](build/how-to-be-a-friend-in-an-unfriendly-world-en.txt) by Barnet Bain to see what aspects for it would be worth to incorporate into our "living well" project.

> Agent: Taking this item. Goal is to extract the most reusable ideas from the Barnet Bain text and incorporate them into `good-life-study` as both a source note and a more durable relationships-domain note.
> Changes: Added a source note at `../good-life-study/sources/blinkist/how-to-be-a-friend-in-an-unfriendly-world.md`, added the domain note `../good-life-study/domains/relationships/friendship.md`, and updated `../good-life-study/TODO.md` to reflect those first two completed content imports.
> Validation: Re-read the new source note and domain note and confirmed they carry over the most reusable ideas from the Barnet Bain text: self-friendship, attention, attunement/empathy with boundaries, and active caring as a lived orientation rather than a one-off technique.
