# Codex Pets

Custom Codex pet assets and production notes.

## Pets

### Cherry

Cherry is a tiny deep-pink cat companion based on `source/cherry/cherry.png`.

Installable files live in `pets/cherry/`:

- `pet.json`
- `spritesheet.webp`

Copy `pets/cherry/` into your Codex pets folder:

```text
%USERPROFILE%\.codex\pets\cherry
```

## Repository Layout

```text
pets/       Installable Codex pet packages.
source/     Original source images used as references.
runs/       Production prompts, final spritesheets, and QA files.
docs/       Human-friendly preview images for README or GitHub viewing.
```

## Making Another Pet

Use `runs/cherry/pet_request.json` and `runs/cherry/prompts/` as a reference for the next pet. Add the new original image under `source/<pet-id>/`, then create matching output folders under `pets/<pet-id>/` and `runs/<pet-id>/`.

## Cherry QA

- Atlas: 8 columns x 9 rows
- Cell size: 192 x 208
- Final size: 1536 x 1872
- Validation: `runs/cherry/final/validation.json`
- Contact sheet: `docs/cherry-contact-sheet.png`
