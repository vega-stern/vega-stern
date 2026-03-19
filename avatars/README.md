# Vega avatars

All use **HarborVane** brand colors: Navy `#0B2A45`, Teal `#1F6F7A`, Gold `#F2C14E`, Navy light `#1a2332`.

| File | Notes |
|------|--------|
| `vega-icon.svg` | Default mark — star + bearing ring (canonical for `vega-slack-512.png`) |
| `vega-avatar-hex.svg` | Hex grid field + star |
| `vega-avatar-ripple.svg` | Ripples from below + star |
| `vega-avatar-mesh.svg` | Soft mesh blobs + star |
| `vega-avatar-stripes.svg` | Diagonal band pattern + star |
| `vega-avatar-gold-ring.svg` | Gold / teal concentric rings + star |

Patterns are **original** (layered-SVG style inspired by sites like [SVGBackgrounds.com](https://www.svgbackgrounds.com/); not their licensed downloads).

Regenerate default Slack PNG:

```bash
python3 -c "import cairosvg; cairosvg.svg2png(url='vega-icon.svg', write_to='vega-slack-512.png', output_width=512, output_height=512)"
```
