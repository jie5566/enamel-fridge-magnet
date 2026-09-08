---
name: enamel-fridge-magnet
description: Use when turning a photo into a photo-to-fridge-magnet, souvenir magnet, enamel magnet, embossed keepsake, or transparent PNG for portraits, travel photos, pets, landmarks, or architecture.
---

# Enamel Fridge Magnet

Turn the supplied photograph into exactly one finished, front-facing magnet image: a transparent-background PNG with clean alpha around the complete object. Do not add a title, caption, lettering, logo, packaging, refrigerator, hand, display card, comparison layout, or original-photo panel.

## Design rules

- Inspect the source and choose one primary subject: person, pet, landmark, vehicle, or distinctive natural form.
- Choose three to six supporting scene elements that establish the place or story. Simplify clutter and fine texture; remove bystanders, UI chrome, watermarks, and screenshot borders unless the user identifies them as part of the subject.
- Recompose everything into one connected, stable silhouette. Small internal openings are fine; detached floating pieces, fragile spikes, hairline bridges, and tiny islands are not.
- Use a warm gold-tone metal outer rim and internal dividers, colored hard-enamel fills derived from the photo, and shallow embossed relief with restrained highlights and contact shadows. Keep edges crisp and manufacturable; never use a painted-sticker effect.
- Preserve identity and recognizable architecture only where the source supports it. Do not invent unsupported face details. If a face is too small, obscured, or blurred, preserve pose, clothing, hairstyle, and context instead.
- Use a direct centered product view without dramatic perspective.

## Image action and quality gate

Before generating, state any ambiguity in the source material that would materially change the magnet and ask only the necessary clarification; if no such ambiguity exists, proceed without unnecessary questions.

Use the native image editing/generation action and attach the supplied source image to that action. Generate one result, then inspect it against the contract. If the first result has any output-contract failure—including transparency, unwanted text, detached pieces, lost main subject, packaging, comparison or original-photo panels, or the wrong viewpoint—make exactly one focused correction targeting the observed failure. Otherwise stop. Stop after that one correction unless the user explicitly requests another iteration.

For an unsuitable source (too blurry, heavily obstructed, or otherwise unable to support recognition), say what cannot be reliably preserved and ask the user to provide a clearer image or confirm a non-identifying simplification. Do not make that simplification until the user confirms the tradeoff.

## Quick reference

| Check | Required result |
| --- | --- |
| Output | Exactly one front-facing transparent PNG |
| Shape | One connected, stable silhouette |
| Content | One primary subject plus 3–6 supporting elements |
| Material | Warm gold rim/dividers, colored hard enamel, shallow relief |
| Exclude | Text, logos, packaging, refrigerator, hand, cards, comparisons, source-photo panel |
| Correction | At most one focused correction for a contract failure |

## Example image-edit prompt

> Using the attached source photo, create exactly one front-facing enamel souvenir fridge magnet as a transparent PNG. Make the traveler the primary subject and retain three to six location-defining elements; simplify clutter into one connected stable silhouette with a warm gold-tone metal rim and internal dividers, colored hard-enamel fills, shallow embossed relief, crisp manufacturable edges, and no painted-sticker look. Preserve only source-supported identity and facial detail. Include no text, caption, logo, packaging, refrigerator, hand, display card, comparison layout, or original-photo panel.
