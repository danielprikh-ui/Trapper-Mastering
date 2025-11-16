# Environment Assets

This folder contains background images and environmental effects for each location.

## Structure

Environment assets should include:
- **Backgrounds**: Layered parallax backgrounds for each environment
- **Weather Effects**: Rain, snow, fog, storm sprites
- **Day/Night Variants**: Different lighting for time of day
- **Environmental Hazards**: Quicksand, poison plants, lava flows, etc.

## Environment Types (from BusinessRequirements)

Total of 27+ unique environments:

### Natural Environments
- forest
- lake
- mountain
- desert
- ocean
- plains
- canyon
- swamp
- glacier
- tundra

### Extreme Environments
- volcano
- lava_tubes
- obsidian_wastes
- storm_peaks
- gas_vents
- salt_flats

### Underground
- caves
- crystal_caves
- mineshafts
- ravines

### Sky/Floating
- sky
- floating_islands
- cliffs

### Coastal/Water
- estuaries
- ocean_depths

### Arid
- dunes
- plateaus
- badlands

## Naming Convention

- Base background: `environment_name_bg.png`
- Parallax layers:
  - `environment_name_bg_layer1.png` (far background)
  - `environment_name_bg_layer2.png` (middle)
  - `environment_name_bg_layer3.png` (foreground)
- Time variants: `environment_name_dawn.png`, `_day.png`, `_dusk.png`, `_night.png`
- Weather: `environment_name_weather_type.png`
- Hazards: `environment_name_hazard.png`

## Image Specifications

- **Format**: PNG with transparency (for layers)
- **Size**: 1920x1080 pixels (HD), scalable
- **Parallax layers**: Use transparency for depth effect
- **Color depth**: 32-bit RGBA

## Lighting for Time of Day

### Dawn
- Warm orange/pink hues
- Long shadows
- Soft lighting

### Day
- Bright, natural colors
- Clear visibility
- Sharp shadows

### Dusk
- Purple/orange sunset colors
- Lengthening shadows
- Atmospheric lighting

### Night
- Dark blues/purples
- Moonlight/starlight
- Reduced visibility

## Weather Effects

Overlay sprites for:
- **Rain**: Animated rainfall
- **Snow**: Falling snowflakes
- **Fog**: Misty overlay reducing visibility
- **Storm**: Dark clouds, lightning flashes
- **Sandstorm**: Swirling sand particles
- **Ash Fall**: Volcanic ash (for volcano areas)
- **Aurora**: Northern lights (for glacier/tundra)
- **Clear**: No overlay, base visibility

## Environmental Hazards

Visual indicators for:
- Quicksand patches (swamp, desert)
- Poisonous plants (forest, swamp)
- Lava flows (volcano, lava_tubes)
- Ice patches (glacier, tundra)
- Toxic gas vents (gas_vents)
- Unstable ground (ravines, cliffs)
- Extreme heat waves (desert, volcano)
- Blizzard conditions (glacier, storm_peaks)

## Parallax Effect

Layer structure (back to front):
1. **Sky/Background**: Static or slow-moving
2. **Distant terrain**: Medium speed
3. **Mid-ground**: Faster movement
4. **Foreground**: Fastest parallax, includes obstacles
5. **Effects**: Weather, particles, hazards on top
