# Changelog

All notable changes to Yellowfall are documented here.

## [0.0.4] - 2026-01-22

### Added
- **Named Units**: Player units now have persistent names (e.g., "Soldier Bob", "Farmer Ada")
  - 270+ unique names, randomly assigned
  - When a unit dies, that specific named unit is removed
- **Now Card Visual Style**: Now cards display with distinct cyan border and "NOW" label

### Changed
- Battle logs now show unit names instead of generic "#1", "#2"

---

## [0.0.3] - 2026-01-22

### Added
- **Now Cards**: New card category that executes immediately when played
- **Forget Card**: Burns a target card from your hand (common, costs 0 in shop)
- **Library Card**: Permanently increases hand size by 1 (rare, burns after use)
- **Burn Mechanic**: Some cards are removed from the game instead of going to discard
- **Boss Loot Choices**: Boss battles in unlimited mode now offer 2 loot cards to choose from
- **High Score Tracking**: Best day reached persists across sessions

### Changed
- **Recruit Card**: Now gives +1 soldier with 2 uses (was +2 soldiers with 1 use)
- **Loot System**: Now uses rarity pools (Common/Uncommon/Rare)
- Updated compendium with all new cards

### Fixed
- Morning preview tooltip now renders above the schedule
- Layout overflow in game over overlay
- Farmers no longer clutter battle log with 0-damage attacks

---

## [0.0.2] - Advanced Mode Update

### Added
- **Advanced Game Mode**: New mode with Redo card in starter deck
- **Redo Card**: Repeats the last card's effect (uncommon, 2 uses)
- **Card Compendium**: View all cards and their stats from the main menu
- **Exit Button**: Leave game with confirmation dialog

### Changed
- Renamed "Start Game" to "Start Tutorial" for clarity
- Reduced boss battle imps from 5 to 3 per boss level
- Increased granary capacity to 20 food
- Starting army changed to 3 soldiers + 3 farmers

### Fixed
- Card uses badge now shows remaining uses correctly

---

## [0.0.1] - Initial Release

### Added
- Core city-building card game
- 7-card starter deck with Forage, Recruit, Pasture, and Caravan
- Schedule system for queuing and executing cards
- Morning phase with food production and consumption
- Battle system with initiative-based combat
- Battle days every 5th day with scaling encounters
- Boss battle on day 30
- Unlimited mode after defeating the boss
- Shop and loot systems
