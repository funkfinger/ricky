# Bird Oracle 🐦

A bird feeder with personality — identifies species and tells you something meaningful about each visitor.

## Concept

Instead of just logging bird sightings, this device *interprets* them. When a bird arrives, it identifies the species and shares folklore, facts, or poetic observations via text-to-speech or an e-ink display.

> "The junco has arrived. In some traditions, this means snow is coming."

## Components from Inventory

- **Google Coral** — ML inference for species ID
- **Pixy2 Camera** — Vision input (or use a Pi camera)
- **Speaker** — For TTS output
- **E-ink display** — For "fortune" style printouts
- **Weatherproof enclosure** — TBD

## Technical Approach

1. **Detection**: Camera watches feeder area
2. **Classification**: Coral runs bird species model (TensorFlow Lite, 900+ species available)
3. **Lookup**: Match species to content database
4. **Output**: TTS or e-ink display

## Content Ideas

- Folklore and mythology associated with each species
- Seasonal significance ("First robin of spring")
- Behavioral facts presented poetically
- Cumulative stats ("This is the 47th chickadee this month")

## Mood

Magical realism. Technology as a lens for wonder, not just data collection.

## Status

- [x] Concept defined
- [ ] Hardware gathered
- [ ] Bird model tested
- [ ] Content database created
- [ ] Enclosure designed
- [ ] Installed and running

## Links

- [[google-coral-ideas]]
- [[projects/index|← Back to Projects]]

## Tags

#ml #coral #nature #art #outdoor
