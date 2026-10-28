# Matthew Goldsbrough Brand Colour Palette

Purpose: a bold but readable palette for `matthewgoldsbrough.com`, drawn from Matthew's current headshot. The dark shirt and background provide authority and contrast; the skin tones supply warmth and energy. The result should feel purposeful and attention-grabbing without weakening the site's professional message.

## Core Palette

| Role | Name | Hex | Use |
|---|---:|---:|---|
| Primary dark | Midnight Navy | `#0F111A` | Strong colour bands, portrait frame and high-confidence sections |
| Primary depth | Deep Navy | `#07080D` | Footer and deepest contrast |
| Main background | Warm Paper | `#F4ECE9` | Hero and alternating section backgrounds |
| Raised surface | Ivory | `#FCF8F6` | Cards, content panels and header |
| Main text | Ink | `#171315` | Headings and body copy |
| Secondary text | Muted Umber | `#6D5E5B` | Metadata, navigation and supporting copy |
| Border | Rose Stone | `#D8C8C4` | Hairlines, dividers and quiet structure |
| Human accent | Terracotta | `#A87069` | Primary actions, hero rule and emphatic card bands |
| Action colour | Deep Terracotta | `#9B625C` | Primary button background with Ivory text |
| Warm accent | Warm Rose | `#C58E86` | Gradients and restrained secondary emphasis |
| Cool accent | Slate | `#454A5A` | Experience, writing and technology cues |

## CSS Variables

```css
:root {
  --ink: #171315;
  --muted: #6d5e5b;
  --line: #d8c8c4;
  --paper: #f4ece9;
  --panel: #fcf8f6;
  --terracotta: #a87069;
  --terracotta-action: #9b625c;
  --terracotta-dark: #754a45;
  --clay: #a87069;
  --gold: #c58e86;
  --blue-slate: #454a5a;
  --midnight: #0f111a;
  --deep-navy: #07080d;
  --white: #fcf8f6;
}
```

## Usage Rules

- Keep the established editorial layout and generous spacing. The energy should come from colour, bands and the portrait rather than denser content.
- Use Midnight Navy for the strongest brand moments and Terracotta for actions and directional emphasis.
- Use Warm Paper and Ivory for long-form reading surfaces. Body copy should remain Ink or Muted Umber.
- Cycle Midnight Navy, Terracotta and Slate across small card rules rather than filling every card with colour.
- Keep Warm Rose inside gradients and secondary details. It should support Terracotta rather than compete with it.
- Use Ivory text on Deep Terracotta buttons. Avoid light text on the lighter Terracotta or Warm Rose unless the specific pairing has passed a contrast check.
- Keep the source headshot in `../Media Content/`; the site stores only the optimised web derivative required for deployment.

## Accessibility Pairings

- `#171315` on `#F4ECE9` for body copy.
- `#171315` on `#FCF8F6` for cards and panels.
- `#FCF8F6` on `#0F111A` for the principal dark bands.
- `#FCF8F6` on `#9B625C` for primary buttons.
- `#FCF8F6` on `#754A45` for button hover states.
- Use Terracotta, Warm Rose and Slate as accent rules when a colour and background pairing has not been contrast-tested for text.

## Brand Read

The palette says: experienced, clear-eyed, human and decisive. It retains the site's calm structure but replaces the previous muted neutrality with stronger visual purpose.
