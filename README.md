# Mitutoyo OEM figures

Interactive Hairline line figures for Mitutoyo OEM products. Hosted for iframe embeds.

## Gallery

https://redelefant-mr-e.github.io/mitutoyo-oem-figures/

## Embed

```html
<iframe
  src="https://redelefant-mr-e.github.io/mitutoyo-oem-figures/embed.html?f=laser-scan&plate=white&intensity=0.5&play=1"
  title="OEM figure"
  style="width:100%;aspect-ratio:5/4;border:0"
></iframe>
```

Query parameters on `embed.html`:

| Param | Values | Default |
| --- | --- | --- |
| `f` | `laser-scan`, `line-laser`, `linear-scale`, `wide-vmu`, `linear-gauge`, `taglens`, `micrometer-head` | first in list |
| `plate` | `white`, `grey`, `orange`, `dark` | `white` |
| `intensity` | `0`…`1` | `0.5` |
| `play` | `1` to autoplay the tour | off |
| `theme` | `light`, `dark` | unset |

## Source

Built from the Mitutoyo OEM Production project (`library/oem-figures/`). Rebuild there with `scripts/oem_figures/build_library.mjs`, then copy `index.html`, `embed.html`, and `dist/` into this repo.

## Product film

Orange studio product film (7 s, 1920×1080):

- File: https://redelefant-mr-e.github.io/mitutoyo-oem-figures/media/mitutoyo-objective-orange-product-film.mp4
- Player page: https://redelefant-mr-e.github.io/mitutoyo-oem-figures/media/objective-orange-product-film.html

```html
<iframe
  src="https://redelefant-mr-e.github.io/mitutoyo-oem-figures/media/objective-orange-product-film.html"
  title="Mitutoyo objective · orange product film"
  style="width:100%;aspect-ratio:16/9;border:0;background:#000"
  allow="autoplay"
></iframe>
```

Or with a native video element:

```html
<video
  src="https://redelefant-mr-e.github.io/mitutoyo-oem-figures/media/mitutoyo-objective-orange-product-film.mp4"
  autoplay muted loop playsinline controls
  style="width:100%;aspect-ratio:16/9;background:#000"
></video>
```
