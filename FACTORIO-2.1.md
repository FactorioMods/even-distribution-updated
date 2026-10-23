# Factorio 2.1 notes

Tested with **Factorio 2.1.23**. Current fork version: **1.0.3**.

## Changes

- Updated fuel-category handling, recipe lookup, product probabilities and rendering target offsets.
- Fixed in-game changelog parsing; original entries are preserved in docs/UPSTREAM-CHANGELOG.txt.

## Tests

- Distribution, balancing, half stacks and fuel replacement with a connected client.
- Disconnect cancelled a pending drag without losing its 120 items.
- Saved inventories survived restart/rejoin and a clean-archive continuation.

Fixtures entered the production event queue directly. Actual keyboard and mouse gestures were not automated.

Tests used private copies of saves and local host/client sessions. Raw player data and test hooks are not shipped.

The 1.0.3 patch changes changelog text and version metadata only; the feature tests above apply to the unchanged gameplay code.
