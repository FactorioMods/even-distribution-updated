# Factorio 2.1 notes

Version **1.0.3** updates fuel categories, recipe lookup, product probabilities and rendering targets for Factorio 2.1.

## Factorio 2.1.24 headless checks

- Distributing 120 items across three chests produced 40 in each.
- Adding 30 items to those three 40-item inventories produced 50 in each after balancing.
- Fuel replacement split 100 coal evenly and returned all 40 displaced wood.
- Half-stack distribution placed 15 items in each of three chests and retained 45 from a stack of 90.

These checks exercised the delayed distribution pipeline and native inventories.

## Earlier Factorio 2.1.23 host/client checks

Distribution, balancing, half stacks and fuel replacement passed with a connected client. Disconnecting during a pending drag preserved its 120 items. Inventories survived save, restart and rejoin. The tests invoked the production event pipeline directly.
