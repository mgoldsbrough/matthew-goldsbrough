# Matthew Goldsbrough Brand Colour Palette

Purpose: a restrained palette for `matthewgoldsbrough.com` and related NED campaign material. It should feel experienced, clear-eyed and commercially useful, with enough warmth to avoid looking like a generic financial services site.

## Core Palette

| Role | Name | Hex | Use |
|---|---:|---:|---|
| Primary dark | Board Green | `#244B3D` | Primary buttons, favicon background, footer bands, high-confidence blocks |
| Primary depth | Deep Board Green | `#19362C` | Button hover, dark section depth, active states |
| Main background | Warm Paper | `#F7F2E8` | Page background, calm editorial surface |
| Raised surface | Ivory Panel | `#FFFAF0` | Cards, quotes, selected writing panels, logo foreground |
| Main text | Charcoal Ink | `#171819` | Headings and body copy |
| Secondary text | Graphite | `#5F625D` | Metadata, navigation, supporting copy |
| Border | Stone Line | `#D8D3C8` | Hairlines, dividers, quiet structure |
| Human accent | Clay | `#A35D3B` | Eyebrows, small highlights, favicon rule, active markers |
| Evidence accent | Old Gold | `#B8944F` | Proof points, quote rules, limited chart emphasis |
| Digital accent | Blue Slate | `#3D6173` | Links, data visualisation, technology cues, sparingly |

## Suggested CSS Variables

```css
:root {
  --ink: #171819;
  --muted: #5f625d;
  --line: #d8d3c8;
  --paper: #f7f2e8;
  --panel: #fffaf0;
  --green: #244b3d;
  --green-dark: #19362c;
  --clay: #a35d3b;
  --gold: #b8944f;
  --blue-slate: #3d6173;
  --white: #ffffff;
}
```

## Usage Rules

- Let Warm Paper and Charcoal Ink do most of the work. The site should feel edited, not decorated.
- Use Board Green for the main action and the strongest brand moments. It carries the NED and board signal.
- Use Clay for judgement, challenge and attention. It should stay small: labels, rules, tiny icons and selected emphasis.
- Use Old Gold only when pointing to evidence, proof or experience. Avoid making it the main CTA colour.
- Use Blue Slate only where a cooler technology or data signal is needed, such as links, charts or selected writing tags.
- Keep large areas away from bright white unless they are functional. Ivory Panel is warmer and more consistent with the current site.
- Avoid dominant blue, purple, black-and-gold, or bright startup palettes. They would pull the brand away from sober technology board advisory work.

## Accessibility Pairings

- `#171819` on `#F7F2E8` for body copy.
- `#171819` on `#FFFAF0` for panels.
- `#FFFFFF` or `#FFFAF0` on `#244B3D` for buttons and dark bands.
- `#FFFFFF` or `#FFFAF0` on `#19362C` for hover and footer states.
- Avoid Clay or Old Gold as body text on Warm Paper. They work better as accents.

## Brand Read

The palette says: senior, direct, commercially grounded, technology-literate, warm enough to be human. It avoids the two traps for this positioning: over-polished corporate blue and lifestyle-consultant beige.
