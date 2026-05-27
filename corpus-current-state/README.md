# Corpus current substrate state — 2026-05-27

These renders are from the current substrate `public/models/spike/substrate-male.glb`
on the `autonomous-run-2026-05-20` branch at HEAD (commit `ca5b124` / `bafcd62`).

If the live `corpushealth.xyz` site doesn't match these, the published `dist/`
or the `corpus-public` nginx container has stale assets.

## What you should see

- `elbow-AFTER-Z.png` vs `elbow-BEFORE-Z.png`: the CT capsule torus now wraps the
  humerus-ulna joint correctly (was floating in mid-air).
- `shoulder-torus-current.png`: shoulder joint capsule positioned between scapula
  and humerus (no more "huge floating ring").
- `skeleton-front-current.png`: humerus articulates with scapula (gap closed to ~17mm
  from 50mm). NOTE: hand+foot phalange meshes are still absent from BodyParts3D
  manifest — that's the known 2-of-9 gap awaiting source-data ingestion approval.
- `all-layers-front-current.png` / `all-layers-side-current.png`: skin envelops
  body cleanly (every containment gate at literal 100% — 0 violations).
