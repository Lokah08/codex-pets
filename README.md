# Codex Pets

Custom Codex pet assets and production notes.

## Pets

### Cherry

Cherry is a tiny deep-pink cat companion based on `source/cherry/cherry.png`.

Installable files live in `pets/cherry/`:

- `pet.json`
- `spritesheet.webp`

### Lumo

Lumo is a tiny hot-pink companion with lime-green eyes based on `source/lumo/lumo.png`.

Installable files live in `pets/lumo/`:

- `pet.json`
- `spritesheet.webp`

Lumo uses the standard Codex pet atlas layout, with the Jumping row previewed as Typing and the Running row previewed as FastTyping.

Copy a pet package into your Codex pets folder:

```text
%USERPROFILE%\.codex\pets\<pet-id>
```

## Repository Layout

```text
pets/       Installable Codex pet packages.
source/     Original source images used as references.
runs/       Production prompts, final spritesheets, and QA files.
docs/       Human-friendly preview images for README or GitHub viewing.
```

## Preview

Open `preview.html` in a browser to switch between pets and animation states.

## Making Another Pet

Use `runs/cherry/pet_request.json` and `runs/cherry/prompts/` as a reference for the next pet. Add the new original image under `source/<pet-id>/`, then create matching output folders under `pets/<pet-id>/` and `runs/<pet-id>/`.

## Cherry QA

- Atlas: 8 columns x 9 rows
- Cell size: 192 x 208
- Final size: 1536 x 1872
- Validation: `runs/cherry/final/validation.json`
- Contact sheet: `docs/cherry-contact-sheet.png`

## Lumo QA

- Atlas: 8 columns x 9 rows
- Cell size: 192 x 208
- Final size: 1536 x 1872
- Validation: `runs/lumo/final/validation.json`
- Contact sheet: `docs/lumo-contact-sheet.png`
