# forgetful · brand guide

A spaced-repetition memory aid. The 1 / 2 / 7 / 30 rhythm helps you re-encounter what you want to remember before you forget it.

## Voice
Quiet, lowercase, slightly editorial. Never shouty. Never marketing.

## Palette (CSS variables in `index.html`)
- `--bg` `#F4EEDF` — warm cream paper
- `--paper` `#FAF6EC` — surface (lighter cream, for cards)
- `--ink` `#1F1B17` — primary text
- `--ink-soft` `#5C544B` — muted text
- `--line` `#E2D9C5` — hairline borders
- `--accent` `#B85A2E` — burnt orange (single accent, used sparingly)
- `--accent-soft` `#E5C9B2` — accent tint for hover/active

## Type
- **Display:** Fraunces (variable, optical-size aware) — used for the brand mark, weekday names, day numbers
- **Body / labels:** Inter — used for tags, captions, and small UI copy
- Roles: `display` (28–32px), `headline` (18px italic), `body` (12–14px), `caption` (10–11px, uppercase tracking)

## Visual style
Soft rounded (16–20px radii). Hairline borders + subtle paper-tone shadows. No gradients on surfaces; ambient gradients only as background atmosphere.

## Motion
Spring-light. Entrance: gentle rise + fade, staggered. Interaction: scale-down on tap (0.98–0.99). Update: short color/scale pulse to confirm a change.

## Components
- **Anchor card** — full-width, larger surface, tap target opens native date picker
- **Interval card** — small, three-up grid, displays editable day number + computed date
- **Divider** — hairline + uppercase tracked label, used to separate anchor from reminders

## Spacing
4 / 8 / 12 / 16 / 20 / 24 / 32 / 48
