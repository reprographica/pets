# Pets

Codex-compatible custom pet packages and their retained validation artifacts.

## Repository layout

Each pet lives under `pets/<pet-id>/`:

- `package/<pet-id>/` contains the install-ready `pet.json` and `spritesheet.webp` pair.
- `final/` contains the validated v2 atlas and deterministic validation report.
- `qa/` contains contact sheets, motion previews, direction checks, and the run summary.
- `references/` and `pet_request.json` retain the source and generation provenance needed for later repair or review.

Generated pet runs belong in this repository, not in unrelated application or plugin repositories.

## Install a pet

Copy the contents of `pets/<pet-id>/package/<pet-id>/` to `~/.codex/pets/<pet-id>/`.
