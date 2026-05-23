# Shuffle and Go — Brand Assets

Public CDN for the **Shuffle and Go** brand kit. Logos and color reference image, served via `raw.githubusercontent.com` and `cdn.jsdelivr.net` so any tool, API, or AI agent can fetch them by URL.

The full brand guide (voice, typography spec, post templates, strategy) is maintained privately. **This repo is asset delivery only.**

## What's here

```
Logos/
├── PNG/                                      Raster — web, social, video overlays
│   ├── ShuffleeGo_logo.png                   Default horizontal lockup (light bg)
│   ├── ShuffleeGo_logo vert.png              Vertical lockup (light bg)
│   ├── ShuffleeGo_logo para fundo verde.png  Horizontal on brand green
│   ├── ShuffleeGo_logo para fundo verde vertical.png  Vertical on brand green
│   ├── ShuffleeGo_negativo.png               White reverse for dark backgrounds
│   ├── ShuffleeGo_positivo.png               Full color on white
│   ├── ShuffleeGo_logo vert negativo.png     Vertical white reverse
│   ├── ShuffleeGo_logo vert positivo.png     Vertical full color
│   ├── ShuffleeGo_variante 2.png             Alternate variant
│   ├── ShuffleeGo_variante 3.png             Compressed horizontal — tight spaces
│   ├── ShuffleeGo_variante 4.png             Large vertical — print, posters
│   └── ShuffleeGo_logo b.png                 Black & white lockup
├── Vetor/                                    Vector (SVG) — design tools, print
│   └── (same variants as PNG, where vectors exist)
└── Icon_Insta.png                            Square Instagram profile icon
Colors/
└── Cores.jpeg                                Color palette reference image
```

## Brand colors (canonical)

| Token | Name | Hex |
|---|---|---|
| `--brand-forest` | Deep Forest Green | `#223728` |
| `--brand-gold` | Aged Gold | `#be9a50` |
| `--brand-charcoal` | Charcoal | `#575756` |
| `--brand-cream` | Cream | `#f4e4a9` |

## CDN URL patterns

Pick whichever serves your tool best. Both are free, persistent, and CORS-safe.

**GitHub raw** (immediate, no CDN cache):
```
https://raw.githubusercontent.com/alemeneghessosilva/shuffleandgo-brand-assets/main/<path>
```

**jsDelivr** (proper CDN, faster, cached globally):
```
https://cdn.jsdelivr.net/gh/alemeneghessosilva/shuffleandgo-brand-assets@main/<path>
```

Example — horizontal logo on green background via jsDelivr:
```
https://cdn.jsdelivr.net/gh/alemeneghessosilva/shuffleandgo-brand-assets@main/Logos/PNG/ShuffleeGo_logo%20para%20fundo%20verde.png
```

## Naming convention (Portuguese terms are intentional)

- `Vetor` = Vector (SVG files)
- `Cores` = Colors
- `negativo` = white/inverted version
- `positivo` = full-color version
- `fundo verde` = green background
- `variante` = variant

## For partners

If you're partnering with Shuffle and Go on co-branded content (sponsored video, event graphic, joint post, kit drop), grab the **partner kit** — one bundle with brand summary, color/font spec, logo usage rules, and all PNG + SVG logos.

**Download (zip):**
```
https://cdn.jsdelivr.net/gh/alemeneghessosilva/shuffleandgo-brand-assets@main/partners/Shuffle-and-Go-Brand-Partner-Kit.zip
```

**Or browse the docs on GitHub:**
- [`partners/README.md`](partners/README.md) — start here
- [`partners/BRAND-SUMMARY.md`](partners/BRAND-SUMMARY.md) — identity, voice, pillars, hard nos (1-pager)
- [`partners/colors-and-fonts.md`](partners/colors-and-fonts.md) — hex / CMYK / Pantone / type stack
- [`partners/LOGO-USAGE.md`](partners/LOGO-USAGE.md) — clearspace, minimum sizes, co-branding rules

## Usage

These assets represent the Shuffle and Go brand. Anyone may **fetch and embed** them for legitimate uses (covering Shuffle and Go content, partner integrations, fan creations crediting the channel). Do not use the marks to imply endorsement, claim affiliation, or build derivative brands. Contact via the channel for partnership inquiries.

## Maintainer

Alexandre (Alê) — Shuffle and Go. [youtube.com/@shuffleandgo](https://youtube.com/@shuffleandgo)
