# PR comparison assets — design-gemini-provider

These three PNGs are visual evidence for the PR that adds Gemini (Nano Banana 2) as a design provider to gstack.

All three render the same design brief (a browser-based drone Ground Control Station main view — dark theme, amber accent, CesiumJS terrain map, floating telemetry/weather/attitude panels, flight mode pill, ARM/TAKEOFF/RTL bottom bar), generated from the same prompt family on three consecutive days using three different providers:

| File | Provider | Model | Native res | Generated |
|---|---|---|---|---|
| `01-dalle-3.png` | OpenAI | `dall-e-3` | 1792×1024 | 2026-04-11 10:04 |
| `02-gpt-4o-image-generation.png` | OpenAI | `gpt-4o` Responses API + `image_generation` tool | 2752×1536 | 2026-04-11 12:14 |
| `03-gemini-3-pro-image-preview.png` | Google | `gemini-3-pro-image-preview` (Nano Banana 2) | 1264×848 | 2026-04-12 11:14 |

All three resized to 1600px wide for consistent rendering in the PR body.

This branch is intentionally orphaned — no code history, just the three images + this README. Referenced from the PR description via raw.githubusercontent.com URLs.
