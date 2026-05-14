# forgetful · brand guide

A spaced-repetition memory aid. The 1 / 2 / 7 / 30 rhythm helps you re-encounter what you want to remember before you forget it.

## Voice
Quiet, lowercase, slightly editorial. Never shouty. Never marketing.

## Palette (CSS variables in `index.html`)
- `--bg` `#F4EEDF` — background with subtle ambient gradient
- `--paper` `#FAF6EC` — card surface (lighter cream)
- `--ink` `#1F1B17` — primary text
- `--ink-soft` `#5C544B` — secondary text (labels, captions)
- `--ink-faint` `#8A8175` — tertiary text (disabled, hints)
- `--line` `#E2D9C5` — hairline borders, dividers
- `--line-strong` `#D6CAB0` — stronger borders, input focus
- `--accent` `#B85A2E` — burnt orange (used sparingly: labels, focus states)
- `--accent-soft` `#E5C9B2` — accent tint (hover/active states)

## Type
- **All text:** Inter (system-ui fallback) — used throughout the interface
- Roles: `brand` (38px, bold), `label` (12px, uppercase tracking), `body` (14px), `caption` (12px, muted)

## Visual style
Soft rounded (16–20px radii). Hairline borders + subtle paper-tone shadows. No gradients on surfaces; ambient gradients only as background atmosphere.

## Motion
Spring-light, subtle. Entrance: gentle rise + fade, staggered. Interaction: scale-down on tap (0.98–0.99). Updates: brief color/brightness pulse to confirm state change.
- **Sidebar:** slide in from right (250ms ease), backdrop fades in, input focus draws hairline border

## Components
- **Anchor card** — full-width, larger surface (22px radius), shows Day 1 date + weekday. Tap opens native date picker.
- **Curve card** — displays review checkpoints (Day 2, 7, 30 by default). Shows computed date + weekday. Three-up grid layout.
- **Increment card** — displays days after the anchor date (+ N days from anchor). Three-up grid, mirrors curve dates and weekdays.
- **Divider** — hairline border + uppercase tracked label. Separates sections.
- **Settings sidebar** — right-side panel (overlay on mobile). Contains three rows of editable Day N inputs. Slide-out animation with semi-transparent backdrop. Reset button returns to defaults.

## Footer
Subtle attribution right-aligned in italic with accent heart: "♥ by chuawt"

## Spacing
4 / 8 / 12 / 16 / 20 / 24 / 32 / 48
