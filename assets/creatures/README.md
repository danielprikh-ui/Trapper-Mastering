# Creatures Assets

This folder contains creature sprites and animations organized by environment.

## Structure

Each environment subfolder should contain:
- **Sprites**: PNG files with transparent backgrounds for each creature
- **Animations**: Sprite sheets or individual frames for creature animations
  - `idle` - Creature standing/waiting
  - `walk` - Movement animation
  - `attack` - Aggressive behavior animation
  - `caught` - Animation when captured
  - `flee` - Running away animation

## Naming Convention

- Normal creature: `creature_name.png` (e.g., `forest_sprite.png`)
- Shiny variant: `creature_name_shiny.png` (e.g., `forest_sprite_shiny.png`)
- Animation frames: `creature_name_action_frame##.png` (e.g., `timber_wolf_walk_01.png`)

## Image Specifications

- **Format**: PNG with transparency
- **Size**: 64x64 pixels (standard), 128x128 (large creatures), 32x32 (tiny creatures)
- **Color depth**: 32-bit RGBA
- **Shiny variants**: Use different color palette but same shape

## Environments

27 environment folders:
- forest, lake, mountain, desert, ocean, sky, plains, canyon
- volcano, swamp, glacier, tundra, obsidian_wastes
- floating_islands, crystal_caves, mineshafts, caves, ravines
- salt_flats, estuaries, dunes, plateaus, badlands
- gas_vents, storm_peaks, lava_tubes, cliffs

## Reference

See `config/creature_spawns.yaml` for the complete list of creatures per environment.
