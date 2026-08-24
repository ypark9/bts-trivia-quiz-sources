# BTS Trivia Quiz Sourcebook

This public repository will publish the answers, sources, and review metadata for the BTS Trivia Quiz question pack. It deliberately prioritizes verification over avoiding game spoilers.

The game code and this sourcebook are separate. This repository must never contain Alexa exports, Lambda ZIP files, credentials, user data, or runtime configuration.

No question pack is published yet. The first generated sourcebook will be proposed only after the private 420-question content pull request has passed its reference and owner sample-review gates.

## Publication process

1. Validate the private pack: counts, IDs, choices, HTTPS sources, source-review dates, and 70 sampled review IDs.
2. Generate JSON and Markdown with the private repository's deterministic exporter.
3. Run the private verifier against the generated JSON; IDs, answers, references, and review metadata must match exactly.
4. Open a separate PR here. Do not automatically push from the private repository.

See [SCHEMA.md](SCHEMA.md) for the intended public fields.
