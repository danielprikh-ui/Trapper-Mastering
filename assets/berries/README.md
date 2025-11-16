# Berry Assets

This folder contains berry sprites and growth stage visualizations.

## Structure

Berry assets should include:
- **Ripe Berries**: Fully grown berry sprites
- **Growth Stages**: Visual progression from planted to ripe
- **Icons**: Small inventory icons for each berry type

## Berry Types (from config/berry_types.yaml)

### Common Berries
- oran_berry (sweet, calming)
- razz_berry (tart, attraction)
- nanab_berry (slows aggressive creatures)
- bluk_berry (water-type attraction)
- pomeg_berry (friendship)

### Uncommon Berries
- pinap_berry (reward doubler)
- sitrus_berry (healing, trust)
- figy_berry (fire-type attraction)
- wiki_berry (psychic/ghost attraction)
- mago_berry (flying attraction)
- aguav_berry (territorial calming)

### Rare Berries
- golden_razz_berry (catch rate boost)
- silver_pinap_berry (triple rewards)
- leppa_berry (shiny boost)
- lum_berry (legendary attraction)

### Legendary Berries
- enigma_berry (random powerful effects)

## Naming Convention

- Ripe berry: `berry_name.png` (e.g., `oran_berry.png`)
- Growth stages: `berry_name_stage#.png` (stage 1-4)
  - Stage 1: Planted seed
  - Stage 2: Sprouting
  - Stage 3: Growing plant
  - Stage 4: Ripe berry
- Inventory icon: `berry_name_icon.png` (smaller 32x32)
- Planted in ground: `berry_name_planted.png`

## Image Specifications

- **Format**: PNG with transparency
- **Berry sprite**: 48x48 pixels (standalone)
- **Growth stages**: 64x64 pixels (includes plant)
- **Inventory icon**: 32x32 pixels
- **Color depth**: 32-bit RGBA

## Color Coding

- **Common**: Natural colors (orange, blue, yellow)
- **Uncommon**: Vibrant colors (bright pink, purple, green)
- **Rare**: Metallic/glowing (gold, silver, shimmer)
- **Legendary**: Multi-colored/prismatic (rainbow, shifting hues)

## Visual Effects

- Rare berries should have subtle glow/sparkle effects
- Legendary berries should have animated shimmer (sprite sheet)
- Golden/Silver variants have metallic sheen
