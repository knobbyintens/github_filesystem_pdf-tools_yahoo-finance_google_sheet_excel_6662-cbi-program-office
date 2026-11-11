# Community Implementation Intake Policy

This policy governs adoption of community implementations of an artifact identified in a
technology dossier.

## 1. Qualification

Only implementations that conform to the exact artifact title and revision identifier in the
dossier qualify. Implementations of other revisions, derived products, adapters, wrappers,
toolkits and curated lists are out of scope, even when their names are similar or their
metadata claims compatibility.

## 2. Ranking

Among qualifying implementations, select the one with the highest community adoption score
recorded in the quarterly tracker.

## 3. Review outcome

- If at least one implementation qualifies, the review outcome is `selected`.
- If no submitted implementation qualifies, the review outcome is `no_award`.

## 4. Licence handling

For the selected implementation:

- licence MIT, Apache-2.0 or BSD-3-Clause -> `approved_for_pilot`
- any other licence -> `legal_review_required`

## 5. Publication

Record the outcome in the tracker's Decision Record tab and update
`decisions/cbi-9.2.json` in this repository. Replace all null values in the template while
keeping the existing keys.
