# Hyperlegible Sans

![Hyperlegible Sans cover image](https://matthewstephens.com/wp-content/uploads/2026/01/Hyperlegible-Sans-Cover-Image-copy-6@2x-scaled.png)


**Hyperlegible Sans** is an accessibility-focused, open-source sans serif inspired by the Inter typeface and informed by the principles of hyperlegible design.

It preserves the modern, geometric feel of Inter while making targeted changes to improve clarity, disambiguation, and readability, especially for low-vision users and accessibility-first interfaces.

This project is a fork of [Inter](https://github.com/rsms/inter) and is distributed under the same SIL Open Font License (OFL 1.1).

---

## Why Hyperlegible Sans?

Inter is one of the best and most widely used open-source UI fonts available. Its clean geometry, strong engineering, and broad adoption make it a default choice for modern design systems.

However, when working on accessibility-focused products, especially interfaces designed for users with low vision or motor and neurological conditions, certain limitations became more noticeable:

- Ambiguous glyphs at small sizes
- Tight apertures that close under blur or low contrast
- Characters like `I`, `l`, and `1` that are difficult to distinguish
- Kerning pairs that visually collapse in dense UI text

At the same time, accessibility-first fonts like Atkinson Hyperlegible offer excellent clarity and disambiguation, but often lack the contemporary visual tone many designers expect from modern UI typography.

Hyperlegible Sans exists to bridge that gap.

---

## Design goals

- Maintain the visual identity and modern feel of Inter
- Reduce ambiguity in commonly confused glyphs
- Improve readability at small sizes and under low-vision conditions
- Favor openness, clarity, and generous spacing over tight density
- Make accessibility improvements without making the font feel “special” or clinical

The goal is not to replace Inter or Atkinson Hyperlegible, but to offer another option that combines the strengths of both.

---

## What’s changed

Hyperlegible Sans makes a small number of deliberate, high-impact modifications to Inter:

### Glyph improvements
- **Capital I**: Added subtle top and bottom bars to clearly distinguish it from `l` and `1`
- **Lowercase l**: Added a small baseline spur for improved disambiguation
- **Zero (0)**: Uses a slashed zero to avoid confusion with capital O
- **Capital O**: Slightly widened to further differentiate it from zero
- **a and e**: Opened apertures to improve readability at small sizes and under blur

### Spacing and kerning
While Inter’s spacing and kerning are excellent for general-purpose design, Hyperlegible Sans introduces additional spacing for accessibility-critical pairs that commonly collapse:

- `rn`, `ri`, `rl`
- `fi`, `fl`, `ft`, `tt`
- `ii`, `ll`, `il`, `li`
- `la`

These changes are intentionally conservative and designed to improve clarity without disrupting overall rhythm.

---

## Current status

**Version 1** includes:
- Regular
- Medium
- Bold

Roman (upright) styles only.

---

## Roadmap

Planned future work includes:

- Additional weights
- Italics
- A full variable font
- Expanded punctuation
- Improved numerals and tabular figures
- Broader language support
- Refinements for dark mode and low-contrast environments

This project is evolving and feedback is welcome.

---

## License

Hyperlegible Sans is licensed under the **SIL Open Font License, Version 1.1**.

- You are free to use, study, modify, and redistribute the font
- The font may be bundled with software or products
- The font itself may not be sold on its own
- The name “Inter” is a Reserved Font Name and is not used as the primary font name

See `LICENSE.txt` for full details.

---

## Attribution

Hyperlegible Sans is derived from **Inter**, designed by Rasmus Andersson and contributors.

Inter is © The Inter Project Authors  
https://github.com/rsms/inter

This project is not affiliated with or endorsed by the original Inter project.

---

## Contributing

Contributions, issues, and discussion are welcome.

If you’d like to contribute:
- Open an issue to discuss changes or bugs
- Submit a pull request with clear explanations
- Keep accessibility and readability as the primary design criteria

---

## Contact

If you’re using Hyperlegible Sans in a project or have feedback, feel free to open an issue or share your work.

---

*Not less beautiful. Not more clinical. Just clearer, easier, more humane.*