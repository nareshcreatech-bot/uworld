# UWorld Design System

A comprehensive design system for the UWorld platform — providing consistent UI tokens, components, and guidelines.

## Structure

```
design-system/
├── README.md              # This file
├── tokens/
│   ├── colors.css         # Color palette & semantic tokens
│   ├── typography.css     # Font families, sizes, weights
│   └── spacing.css        # Spacing scale & layout tokens
├── components/
│   ├── buttons.css        # Button variants
│   ├── cards.css          # Card components
│   ├── forms.css          # Input, select, checkbox, radio
│   └── badges.css         # Status & label badges
└── foundations/
    └── reset.css          # CSS reset & base styles
```

## Getting Started

Import the design tokens and component styles into your project:

```css
@import 'design-system/tokens/colors.css';
@import 'design-system/tokens/typography.css';
@import 'design-system/tokens/spacing.css';
@import 'design-system/foundations/reset.css';
```

## Design Tokens

### Colors
- **Primary:** --color-primary — Main brand blue used for CTAs and interactive elements
- **Success:** --color-success — Correct answers, confirmations
- **Danger:** --color-danger — Incorrect answers, errors
- **Warning:** --color-warning — Alerts, partial credit
- **Neutral:** --color-neutral-* — Text, backgrounds, borders

### Typography
- **Font Family:** Inter (primary), system-ui (fallback)
- **Scale:** 12px to 48px

### Spacing
- **Base unit:** 4px
- **Scale:** 4, 8, 12, 16, 24, 32, 48, 64, 96px

## Components
- **Buttons** — Primary, Secondary, Ghost, Danger variants
- **Cards** — Question card, Explanation card, Stats card
- **Forms** — Input fields, Dropdowns, Checkboxes, Radio buttons
- **Badges** — Correct, Incorrect, Omitted, Difficulty level

## Contributing
Follow the naming conventions and token usage guidelines when adding new components.
