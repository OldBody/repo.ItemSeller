# REPO ItemEquippable Seller

A mod for REPO game that allows converting equippable items into money.

## ⚠️ IMPORTANT WARNING ⚠️

**WARNING**: When converting an item into money, it is completely removed from the current save. After reloading the level or saving, this item will be permanently lost. Make sure you really want to sell the item before using this feature.

## How to Use

1. Approach the item you want to sell
2. Pick up the item (using the standard item pickup mechanism)
3. Press the `H` key (default) to convert the item into money
4. The item will disappear and the corresponding amount of money will appear in its place

## Features

- Supports all types of equippable items:
  - Drones
  - Item upgrades
  - Player upgrades
  - Power crystals
  - Grenades
  - Melee weapons
  - Health packs
  - Guns
  - Trackers
  - Mines
  - Pocket carts
  - Duck buckets

- Item value is calculated based on:
  - Base item value
  - Battery condition (if applicable)
  - Quality multiplier

## Configuration

The key for selling items can be changed in the mod configuration:
- Default: `H`
- Configuration file: `BepInEx/config/OldBody.ItemSeller.cfg`


## Requirements

- BepInEx 5.x

## Author

OldBody

## License

MIT License
