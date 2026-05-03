# Codex Pets

Custom pet assets for Codex.

## Structure

```text
pets/
  <pet-id>/
    pet.json
    spritesheet.webp
    qa/
      contact-sheet.png
      validation.json
```

Each pet folder contains the installable Codex pet files plus lightweight QA artifacts. Keep large temporary generation runs outside the repository unless they are needed for review or reproduction.

## Pets

- [Xueying Doll](pets/xueying-doll/) - Snow-themed chibi doll pet based on Xueying Doll / 雪影娃娃.

## Notes

- `pet.json` and `spritesheet.webp` are the files Codex needs to load the pet.
- `qa/contact-sheet.png` is useful for quickly reviewing all animation rows.
- `qa/validation.json` records atlas validation results.
