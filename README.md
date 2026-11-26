# Semester 3 Jury

A jury presentation on one continuous dot-grid canvas. Slides change with a gentle zoom and fade (strength: `ZOOM` in `index.html`). Clicking an image still enlarges it.

Talk order:

1. **The Fear Between Us** — data storytelling
2. **Time Wanderers** — multimodal interaction
3. **Saath** — Design Project 2, mixed reality

The screen-by-screen plan is in [storyboard.md](storyboard.md).

## View it

Live: https://rushabhm-blip.github.io/Semester-3-jury/

Locally, open `index.html` from a web server (images load by relative path), for example `npx serve .`

## Controls

- `→` / `Space` / click: next step (some screens step through their images first)
- `←` previous · `Esc` back to the three projects · `F` full screen · `Home` / `End`
- `D`: backup project, Neurovascular Journey (outside the talk; `Esc` returns to where you were)
- `B`: backup project, Branching Beyond (same rules as `D`)
- Add `#screen-id` to the URL to jump to a screen (for example `#a10` for the Saath journey)
- Scroll to zoom, drag to pan

## Images

All images the deck uses live in `img/v/`: crops from the Saath Figma file, the Time Wanderers slides, and The Fear Between Us illustrations.
To show the real sightings map, save a screenshot as `img/v/fear-map.png`; it replaces the drawn stand-in automatically.
