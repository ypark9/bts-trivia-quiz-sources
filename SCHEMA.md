# Sourcebook schema

Each generated JSON entry has these public fields:

- `id`: stable private-pack question ID.
- `mode`, `member`, `category`: the game scope.
- `question`, `answer`, `explanation`: the full verifiable quiz item.
- `claimType`: `fan-context` or `official-record`.
- `sources`: title, HTTPS URL, and source type (`official`, `independent`, or `community`).
- `sourceVerifiedAt`: date the private reviewer checked its references.
- `sampleReview`: whether the question belongs to the 70-item owner sample.

`official-record` claims must cite at least one official or independent reference. Community references, including NamuWiki, are permitted as supplementary public references and for fan-context questions; their prose is not copied into the sourcebook.
