# TODO

## [FOR HUMAN]

# [DONE 2026-08-01.2] Feedback
* remove domains that are empty now?
  > Agent: Yes. Empty placeholder domains did not carry knowledge and made the current map look more complete than it is. Removed `health`, `meaning`, and `work`; a domain file can be created when there is material to preserve.
* Why attention is a life domain? Worth to explain in README.md what life domain is?
  > Agent: Added a definition of a life domain to `README.md`. A domain can be a familiar area of life or a cross-cutting condition in which related principles and practices accumulate. Attention belongs because it affects what is noticed, sustained, interpreted, and acted on across the other areas.
* "Attention is one of the core conditions of a good life." - if we state that we should give some explanation
  > Agent: Replaced the unsupported standalone claim with a concrete explanation in both `README.md` and the attention note: attention shapes perception, judgment, action, learning, and presence, while fragmentation can weaken work, relationships, and rest.
* Do we need separate README.md and digital-exhaustion.md under `domains/attention`. Maybe simplify it to 'domains/attention.md` (same for other domains)?
  > Agent: No at the current size. Flattened every active domain to one file: `attention.md`, `general.md`, `relationships.md`, and `technology-and-ai.md`. Merged the former index and content files and updated current cross-references.

> Changes: Simplified `domains/` to one file per active domain, removed empty placeholders, documented what a life domain means and why attention qualifies, and repaired links in domain and source notes.
> Validation: `git diff --check`; confirmed exactly four files directly under `domains/`; searched current README, domain, and source notes for references to the removed nested paths.
> Learning: Create a domain when useful content exists. Keep it as one file until its size or internal structure makes a directory meaningfully easier to navigate.

# [DONE 2026-08-01.3] Remove `technology-and-ai.md`
The file does not contribute anything to the current synthesis.

> Changes: Removed the domain file. Technology and AI remain themes in the working map, but they will get a dedicated domain again only when there are principles or practices that do not belong naturally in an existing domain.
> Validation: Confirmed that no README, domain, or source note references `domains/technology-and-ai.md` and that the remaining domain files contain substantive synthesis.
> Learning: A list of questions and a link to another domain are not enough to justify a separate domain file.
