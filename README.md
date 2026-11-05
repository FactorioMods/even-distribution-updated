# Even Distribution: Updated

Use Ctrl+click-drag to distribute items evenly between machines, or Shift+C to distribute unwanted inventory items to nearby machines.

**Factorio 2.1 · Version 1.0.3**

## Fork changes

- Fixes fuel handling for the current fuel-category system, including fuels accepted by more than one category.
- Keeps fuel replacement working: better fuel can replace weaker fuel, and displaced items return to your inventory.
- Corrects recipe lookup and expected product amounts for the current Factorio API, so recipe-based eligibility checks keep working.
- Updates item and count markers to current rendering targets, including their positioning on spidertrons.

The original distribution controls remain: balance existing contents, distribute a new stack, or use half-stack distribution. The fork preserves the original machine and inventory workflow.

## Installation

Requires Factorio 2.1.23+. Disable `even-distribution` before enabling this fork; the two identities are incompatible. Space Age is optional.

Distribution, balancing, half stacks and fuel replacement are covered in the [validation guide](FACTORIO-2.1.md), which separates current headless checks from earlier connected-client checks.

Original mod by [321freddy](https://github.com/321freddy/even-distribution). Maintained by johnmart19 / FactorioMods under [LGPLv3](ATTRIBUTION.md).

[Mod Portal](https://mods.factorio.com/mod/even-distribution-updated) · [Source](https://github.com/FactorioMods/even-distribution-updated) · [Downloads](https://github.com/FactorioMods/even-distribution-updated/releases)
