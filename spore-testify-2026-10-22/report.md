# Testify API Reference - Sourcey-generated API reference

A Sourcey-generated documentation reference for the maintained third-party open-source
library [stretchr/testify](https://github.com/stretchr/testify), pinned to commit `87a7b9d57689f6579db2da795ab8deeab29cb724` (MIT).

## What the reference covers

- The published pages are Sourcey v3.8.3 output (godoc adapter over the committed
  `godoc.json` snapshot of the pinned tree), so every symbol, signature and doc comment
  is parsed from the pinned source and not written by hand.
- The build is reproducible from the pinned commit with one command:
  `sourcey build -c sourcey.config.ts`; the snapshot digest is recorded in the publication.
- 7 pages are published: the API reference for every exported package and symbol of the
  pinned tree, plus quickstart, coverage, provenance and about pages.
- The same pages are published as Markdown (`https://testify.anonymux.org/api.md`) for tools that read docs as text.

## Maintainer-facing gaps

- The upstream tree ships fewer runnable examples than the public API surface, so the
  reference is the only per-symbol map of the API a maintainer can diff against a release.
- Doc-comment coverage is measured per package on the coverage page, so a maintainer can
  see exactly which exported symbols are undocumented upstream and where examples are
  missing.
- Every source link on the published pages is pinned to the commit, so a link-rot report
  is a diff against one SHA.
- The upstream project publishes no machine-readable API index of its own, so downstream
  tooling (doc diffing, API linting, migration checks) has nothing to consume; the
  published pages close that gap for the pinned tree.

## Provenance - who did this and how you can check it

- **Claimant:** spore-crew, AI-assisted work under @ASporeTeam (https://github.com/ASporeTeam).
- **Claimant-authored publication:** https://github.com/stretchr/testify/pull/1996 - the pull request that adds the Sourcey
  configuration and build guide to the documented target.
- **Target:** https://github.com/stretchr/testify at pinned commit `87a7b9d57689f6579db2da795ab8deeab29cb724`. The publisher is not the upstream maintainer and
  does not claim upstream endorsement.
- **Host:** https://testify.anonymux.org/api (parent product site https://anonymux.org/).
- **Artifacts:** published under the immutable git tag `spore-33-packet-20261022` of ASporeTeam/frantic-33-docs, so every URL below
  resolves permanently: `https://raw.githubusercontent.com/ASporeTeam/frantic-33-docs/spore-33-packet-20261022/spore-testify-2026-10-22/evidence.json`, `https://raw.githubusercontent.com/ASporeTeam/frantic-33-docs/spore-33-packet-20261022/spore-testify-2026-10-22/report.md`, `https://raw.githubusercontent.com/ASporeTeam/frantic-33-docs/spore-33-packet-20261022/spore-testify-2026-10-22/receipt.json`.
- **Receipt:** the governed run was executed with the runx CLI (runx-cli 0.10.2) and sealed into a
  signed receipt; the receipt id is `receipt_ref` in the published evidence file and the
  receipt bytes are published at `https://raw.githubusercontent.com/ASporeTeam/frantic-33-docs/spore-33-packet-20261022/spore-testify-2026-10-22/receipt.json`, so a reviewer can re-run `runx verify` against them.

### The packet itself

- evidence file: https://raw.githubusercontent.com/ASporeTeam/frantic-33-docs/main/spore-testify-2026-10-22/evidence.json
- report: https://raw.githubusercontent.com/ASporeTeam/frantic-33-docs/main/spore-testify-2026-10-22/report.md
- sealed receipt: https://raw.githubusercontent.com/ASporeTeam/frantic-33-docs/main/spore-testify-2026-10-22/receipt.json (attestation packet: https://raw.githubusercontent.com/ASporeTeam/frantic-33-docs/main/spore-testify-2026-10-22/receipt-attestation.json)
- issuer public key: https://raw.githubusercontent.com/ASporeTeam/frantic-33-docs/main/spore-testify-2026-10-22/receipt-public-key.json
- packet repository: https://github.com/ASporeTeam/frantic-33-docs/tree/main/spore-testify-2026-10-22

### The sealed run

- The generation run is sealed in a signed Runx receipt: `runx:receipt:sha256:4f0db829e57a5265118905acd7cb997e8f9f721b1e50772f2ecf29450a1ca49e`
- The receipt bytes, its attestation packet and the issuer public key are published beside this report, so a stranger can verify the signature and re-run `runx verify`.

### The packet itself

- evidence file: https://raw.githubusercontent.com/ASporeTeam/frantic-33-docs/main/spore-testify-2026-10-22/evidence.json
- report: https://raw.githubusercontent.com/ASporeTeam/frantic-33-docs/main/spore-testify-2026-10-22/report.md
- sealed receipt: https://raw.githubusercontent.com/ASporeTeam/frantic-33-docs/main/spore-testify-2026-10-22/receipt.json (attestation packet: https://raw.githubusercontent.com/ASporeTeam/frantic-33-docs/main/spore-testify-2026-10-22/receipt-attestation.json)
- issuer public key: https://raw.githubusercontent.com/ASporeTeam/frantic-33-docs/main/spore-testify-2026-10-22/receipt-public-key.json
- packet repository: https://github.com/ASporeTeam/frantic-33-docs/tree/main/spore-testify-2026-10-22
