# NRG1 Energizers — hero artwork framing study v0.7

Open **index.html** in your browser. Two independent controls let you compare three artwork framing treatments against three previously tested hero backgrounds.

- **A · Old white frame** — the original framed artwork treatment; retained only as a baseline.
- **B · Green edge, flush** — your 7px `var(--forest)` left border, 12px radius, **no padding**, no surrounding white border.
- **C · Green edge + padding** — same border and radius, **18px padding on desktop** and 14px on small screens; no surrounding white border.

The art is the white-background abstract image generated during the conversation (`ascending-orange-flow.png`). The horizontal NRG1 logo and square icon are unchanged.

## Where the CSS lives

`assets/css/nrg1.css` is the unchanged v0.5 baseline. `assets/css/hero-variations.css` retains the v0.6 background experiments. **All new framing rules are in `assets/css/hero-frame-v0.7.css`**. No need to edit Bootstrap's CSS or run a build tool.

The 7px left border and 12px radius use the existing forest color, `--forest: #19483e`, from the current NRG1 prototype. It is not yet Kevin's historical green palette.

## Notes

- This is **not a live-site deployment**.
- The frame is a decorative accent around artwork, not a semantic border.
- The original 2021 striped mural photograph is still included in assets for reference, but is **not used in v0.7**.
- The generated artwork has an almost-white background, not transparency. With gold hero backgrounds, its white rectangular canvas will remain visible.
- All other homepage sections are unchanged from v0.5.
