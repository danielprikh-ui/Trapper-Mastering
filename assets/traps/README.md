# Trap Assets

This folder contains trap sprites, animations, and upgrade visualizations.

## Structure

Trap assets should include:
- **Base Traps**: Static sprites for each trap type
- **Animations**: Triggered animations when trap activates
  - `set` - Trap being placed/set
  - `idle` - Trap waiting/armed
  - `trigger` - Trap activating
  - `capture` - Successful capture animation
  - `break` - Trap failing/breaking

## Trap Types (from config/trap_types.yaml)

### Tier 1
- basic_net
- pitfall_trap

### Tier 2
- reinforced_net
- spiked_pitfall
- cage_trap
- freeze_trap
- flame_trap

### Tier 3
- master_net
- void_pitfall
- electro_cage
- absolute_zero_trap
- inferno_trap
- psychic_barrier

### Tier 4
- master_ball_trap

## Naming Convention

- Base trap: `trap_name.png` (e.g., `basic_net.png`)
- Upgraded version: `trap_name_tier#.png` (e.g., `reinforced_net_tier2.png`)
- Animation frames: `trap_name_action_frame##.png` (e.g., `cage_trap_trigger_01.png`)
- Damaged state: `trap_name_damaged.png`

## Image Specifications

- **Format**: PNG with transparency
- **Size**: 64x64 pixels (standard), 96x96 (large traps like pitfalls)
- **Color depth**: 32-bit RGBA
- **Effects**: Use particle effects for elemental traps (fire, ice, electric)

## Special Effects

- **Electro_cage**: Blue electric sparks
- **Freeze_trap**: Icy mist/crystals
- **Flame_trap**: Fire particles
- **Psychic_barrier**: Purple/pink psychic waves
- **Void_pitfall**: Dark portal/dimensional effects
