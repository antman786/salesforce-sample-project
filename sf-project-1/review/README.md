# Sample Salesforce: review snapshot

Exported from vca-review on 2026-11-16. Each export is a pull request; git history holds earlier snapshots.

## Layout

- `entities/<type>/<KEY>-<slug>.md`: one file per entity. YAML frontmatter (`id`, `entity_type`, `name`, `sources`, `links`, `data`) plus a markdown body. Links point at other entities by `id` (`KEY: Name`); the key before the colon is the file's prefix.
- `entities/research/`: research requests and results. `trusted: false` results are unverified and must not feed recommendations.
- `assets/`: primary sources (SOWs, transcripts, notes) that entities cite in `sources[].asset`.
- `review/state.json`: review status per entity key. Only `confirmed` entities are reviewed; `candidate` means extracted but not yet checked by a person; `rejected` and `merged` are kept for history. Entries marked `illustrative: true` are sample data, not facts about the engagement.
- `review/decisions.json`: append-only log of every review decision (who, when, before, after, why), including progress changes.
- `review/comments.json`: reviewer discussion on entities (entityKey, author, text, mentions).
- `review/tracker.json`: workflow status mirrored from the delivery tracker (e.g. Jira) at export time. Story files never carry status.
- `review/approvals.json`: who was asked to approve each story, their answer, and the tracker issue each pushed story became. An approval covers the wording at the time (`hash`); a story edited since needs approving again.
- `review/project.json`: project settings (stage weights, export settings).

## Reading it as an agent

Start from `review/state.json` to know what is confirmed. Follow `links` between files by key. Treat candidates as unverified, illustrative entities as examples, and untrusted research as leads, not facts.

## This export

58 entities (58 new, 0 changed, 0 unchanged), 0 research, 2 new source documents, 73 decisions, 0 tracker items.
