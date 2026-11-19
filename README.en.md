# Courtyard Glow · Desktop Strip

A tiny garden that lives at the bottom of your screen. It grows while you work;
you look up once in a while.

This is a **3-day prototype** used to test one question:
*if a garden quietly grows on your desktop, will you come back to check on it after 30 minutes?*

## Play

Open `index.html` in a browser (no server, no network needed), or visit the
GitHub Pages link.

For the intended experience, resize the browser window into a wide, short strip
and place it at the bottom of your screen.

## What's in it

- 6 planting plots; plants grow through 3 visible stages; tap a ripe plant to harvest
- 4 structures (flower bed, lantern, water wheel, stone tower), each upgradeable
- Day/night cycle; lanterns glow at night
- Four seasons with different palettes
- Occasional visitors; tap them for a temporary boost
- One handwritten letter after 5 minutes of play
- Offline progress (capped at 8 hours, 50% efficiency)
- All UI drawn on a single canvas; one HTML file, zero external requests

## Status

Prototype. No story, no achievements, no multiple save slots, not final quality.

## Tech

Plain JavaScript + Canvas 2D. No framework, no build step for the demo file.
A desktop shell (Electron) lives in `games/courtyard-desktop/electron` in the
private production repository.

## License

Demo only, all rights reserved. See `LICENSE`.
