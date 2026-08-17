---
name: real-scene-character-stylizer
description: Analyze a real photograph, propose scene-appropriate illustrated character choices, and create or direct a photo-plus-flat-hand-drawn-character stylization. Use for adding whimsical people, animals, or fantasy characters to real streets, buildings, landscapes, transit scenes, landmarks, or editorial photo compositions. Do not use for fully repainting the photo or for ordinary photorealistic compositing.
---

# Real-scene character stylizer

Create a deliberate collision between a recognizable real photograph and a clearly two-dimensional illustrated character. Preserve the photograph as the spatial world; make the illustration interact with it rather than merely sit on top.

## Start from the photograph

Inspect the supplied image before proposing a character. Identify:

- setting, season, weather, time of day, and visible activity;
- camera angle, horizon, perspective, dominant lines, and open negative space;
- surfaces a character can sit on, stand behind, hold, cross, ride, lean against, or emerge from;
- visual mood, existing colors, and any safety or cultural constraints.

If no photograph is attached, ask for one before designing scene-specific choices.

## Offer tailored choices before generation

Unless the user already specified enough details, present a compact menu based on the actual photograph. Offer 2–4 strong choices per unresolved category, not a universal catalog.

Ask for or infer with confirmation:

1. **Character type:** person, animal, fantasy creature, or small ensemble.
2. **Presentation:** boy/man, girl/woman, androgynous or non-specified when relevant; use age-appropriate labels and never infer identity from the photographed people.
3. **Role or personality:** for example commuter, explorer, skater, reader, cyclist, dreamer, tourist, gardener, or playful giant—only when plausible for the scene.
4. **Outfit:** propose clothing compatible with weather, activity, setting, and desired contrast. Include silhouette and palette, not just garment names.
5. **Action and placement:** derive actions from usable architecture and perspective.
6. **Scale and mood:** small companion, human-scale, oversized, or city-giant; gentle, lively, absurd, cinematic, or editorial.
7. **Finish:** clean flat color, pencil texture, crayon doodle, or poster/editorial treatment.

Show a recommended combination first and briefly explain why it fits the image. Let the user answer by option labels or describe a custom direction. Do not repeatedly ask about details that are already clear.

## Compose the result

- Keep the source environment recognizable and retain meaningful photographic texture.
- Establish believable contact, occlusion, scale cues, and perspective even when the character is fantastically large.
- Use a readable silhouette, simplified anatomy, flat color masses, restrained interior detail, and small hand-drawn irregularities.
- Let the character respond to a real visual anchor. Good interactions include sitting on a ledge, peeking from behind a building, stepping across a street, riding a line-drawn bicycle, fishing into water, or holding a landmark.
- Add decorative doodles only when they reinforce motion, mood, or narrative. Concentrate them around the focal action and preserve breathing room.
- Preserve faces, text, logos, and important architecture unless the user asks to transform them.
- When generating or editing the image, use the available image-editing tool and include the source photograph as the reference.

Read [references/style-system.md](references/style-system.md) for the shared visual grammar and character construction rules. Read [references/scene-options.md](references/scene-options.md) when building the user-facing choice menu or resolving composition.

## Quality check

Before delivering, verify:

- the photograph still reads as a real place;
- the character reads instantly at thumbnail size;
- feet, hands, props, and occlusions agree with the scene geometry;
- clothing fits the weather and action unless intentional contrast was chosen;
- the illustration is neither a floating sticker nor a near-photorealistic person;
- decorative elements do not cover essential photographic information;
- no extra limbs, malformed hands, accidental text, or unexplained objects were introduced.
