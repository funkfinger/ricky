# Mist Portal 🌫️

An illuminated mist vessel that responds to presence — reach toward it and the colors shift.

## Concept

A bowl or vessel filled with water, creating ethereal illuminated fog via ultrasonic mist. A time-of-flight sensor detects when someone reaches toward it, causing the light patterns to respond. The Pixelblaze makes programming gorgeous reactive patterns trivial.

People can't resist reaching into glowing fog.

## Components from Inventory

- **Ultrasonic mist maker** (BUZ-MIST-20)
- **NeoPixel strips/rings** — Illumination
- **Pixelblaze V3** — LED control and patterns
- **VL53L0X time-of-flight sensor** — Hand detection
- **Vessel** — Glass bowl, ceramic planter, etc.

## Technical Approach

1. Mist maker in water creates fog
2. NeoPixels around/under vessel illuminate the mist
3. ToF sensor measures distance to approaching hand
4. Pixelblaze maps distance → color/pattern shift
5. Pixelblaze's sensor expansion board can read the ToF

## Pattern Ideas

- Slow aurora when idle
- Brightening/warming as hand approaches
- Ripple effect on "touch"
- Sound-reactive mode for parties

## Considerations

- Water level monitoring (mist makers need water)
- Splash protection for electronics
- Power delivery (mist maker + LEDs)

## Status

- [x] Concept defined
- [ ] Vessel selected
- [ ] Electronics tested
- [ ] Patterns programmed
- [ ] Assembled

## Links

- [[projects/index|← Back to Projects]]

## Tags

#art #interactive #led #pixelblaze #easy-win
