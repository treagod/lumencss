# LumenCSS

Ein leichtgewichtiges, **CSS-only** Micro-Framework mit Design-Tokens (HSL), responsivem Layout, zugänglichen Komponenten, Forms & Utilities. **Keine Build-Tools nötig.**

## Features
- **CSS Cascade Layers** für stabile Reihenfolge – kein Spezifitätskrieg.
- **HSL-Tokens** inkl. Brand-Skalen (Primary/Accent) & Semantik (Success/Warning/Danger/Info).
- **Forms & Patterns**: Inputs, Segmented Controls, Switches, 2-Spalten-Layouts u. a.
- **Dark Mode** via `prefers-color-scheme` (CSS-only).

## Installation
```html
<link rel="stylesheet" href="/dist/lumencss.css">
```

## Struktur
```
src/         # einzelne Styles (reset, base, theme, layout, components, forms, utilities, patterns)
dist/        # lumencss.css Aggregator (nur @layer + @import)
examples/    # Demo/Docs HTML
```

## Browser-Support
„Letzte 2–3 Jahre“ Evergreens inkl. `@layer` & `@import layer()`.
