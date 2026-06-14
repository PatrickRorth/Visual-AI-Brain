# Visual AI Brain

Interactive holographic AI energy core rendered on HTML5 canvas — a noise-deformed particle ring with a glowing nucleus, energy bands, and a living network of connections. Single self-contained file with a live control panel to tweak everything, plus localStorage save and JSON export/import. Zero dependencies.

## Preview

A minimalist, futuristic energy field on a near-black background: thousands of glowing particles and lines flow in organic, water/plasma-like waves around a luminous core — like looking into the mind of a super-AI.

## Features

- **Organic energy ring** — driven by 3D simplex noise, constantly reshaping (no rotation), ~12s breathing cycle
- **Living particle network** — up to 40,000 particles that flow, connect, fade, and regenerate
- **Glowing core** — pulsing nucleus with holographic halo
- **Energy bands** — flowing wireframe ribbons
- **Atmosphere** — drifting volumetric fog, radial glow, and vignette
- **Live control panel** — tune ring, particles, network, bands, core, glow, atmosphere, and all colors in real time
- **Persistence** — settings auto-save to `localStorage`; export/import as JSON to share or back up
- **Zero dependencies** — everything inlined in one HTML file

## Usage

Just open the file in any modern browser:

```
ai-energy-ring.html
```

Double-click it, or serve it from any static host.

### Control panel

Click the gear icon (⚙) in the top-right corner to open the panel.

| Button | Action |
| --- | --- |
| **Save** | Save current settings to the browser |
| **Export JSON** | Download settings as `energy-ring-settings.json` |
| **Import JSON** | Load settings from a JSON file |
| **Reset** | Reset to defaults |
| **Hide panel** | Hide the panel for a clean view |

> Settings are stored per-browser in `localStorage`. To share your tuned look, export the JSON and have the recipient import it.

## Embedding

Drop it into your own page via an `<iframe>`:

```html
<iframe src="ai-energy-ring.html" style="border:0;width:100%;height:100vh"></iframe>
```

## License

MIT
