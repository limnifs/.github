# LimniFS

**Layered, Immutable, Merkle-rooted, Network Image filesystem.**

LimniFS is a content-addressed, compressed, immutable filesystem image format
for reproducible releases and efficient distribution.

## Repositories

- [limnifs/limnifs](https://github.com/limnifs/limnifs) — Rust workspace + implementation plans
- [limnifs/spec](https://github.com/limnifs/spec) — format specification (FlatBuffers schema, registries)
- [limnifs/limnifs-py](https://github.com/limnifs/limnifs-py) — Python reference reader (spec-sufficiency oracle)
- [limnifs/limnifs-frozen2](https://github.com/limnifs/limnifs-frozen2) — DwarFS Frozen2 read-only adapter
- [limnifs/.github](https://github.com/limnifs/.github) — this repo (org workflows + profile)

## Status

Pre-alpha. Specification in flight.

---

This repo also holds org-level reusable GitHub Actions workflows under
`.github/workflows/`, consumed by the product repos above.
