# BTS Trivia Quiz Sourcebook

This public repository will publish the answers, sources, and review metadata for the BTS Trivia Quiz question pack. It deliberately prioritizes verification over avoiding game spoilers.

The game code and this sourcebook are separate. This repository must never contain Alexa exports, Lambda ZIP files, credentials, user data, or runtime configuration.

The first generated sourcebook is now available in `SOURCEBOOK.json` and
`SOURCEBOOK.md`. It was generated only after private PR #1 passed its reference
and owner sample-review gates and was merged.

## Current publication

- Pack: `bts-approved-en-us-v1`
- Locale: `en-US`
- Questions: 420 (280 member questions and 140 category questions)
- Owner sample review: 70 IDs, five from each of 14 buckets
- Source verification date: `2026-08-24`
- Private source commit: `bde0ea8604da5bb3a9cf9f1c3b93a554cb77b538`

The public files intentionally include answers and references. See
`VERIFICATION.md` for the parity and privacy checks performed before this PR.

## Publication process

1. Validate the private pack: counts, IDs, choices, HTTPS sources, source-review dates, and 70 sampled review IDs.
2. Generate JSON and Markdown with the private repository's deterministic exporter.
3. Run the private verifier against the generated JSON; IDs, answers, references, and review metadata must match exactly.
4. Open a separate PR here. Do not automatically push from the private repository.

See [SCHEMA.md](SCHEMA.md) for the intended public fields.
