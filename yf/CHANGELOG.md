# Changelog

All notable changes to Yellowfall are documented here.

## [0.0.3] - 2026-01-22

### Added
- **Now Cards**: New card category that executes immediately when played, before the schedule runs
- **Forget Card**: Common Now card that burns a target card from your hand (costs 0 in shop)
- **Library Card**: Rare card that grants +1 card draw size (1 use, burns after use)
- **Burn Mechanic**: Cards marked as "burns" are removed from the game instead of going to discard
- **Variable Hand Size**: Base draw of 3 cards, increased by bonuses from scheduled cards like Library
- **Boss Loot Choices**: Boss battles in unlimited mode now offer 2 loot cards to choose from
- **High Score Tracking**: Tracks best day reached separately for Tutorial and Advanced modes, persists across sessions

### Changed
- **Recruit Card**: Now gives +1 soldier with 2 uses (was +2 soldiers with 1 use)
- **Loot System**: Reworked to use rarity pools (Common/Uncommon/Rare)
- Updated compendium with all new cards
- Battle screen now uses matching unit icons from the header

### Fixed
- Morning preview tooltip now renders above the schedule
- Layout overflow in game over overlay
- 0-damage attacks (farmers) no longer appear in battle log

### Documentation
- Added CHANGELOG.md for tracking releases
- Added Changelog link to main menu
- Updated README with current game info and all cards

---

## [0.0.2] - Advanced Mode Update

### Added
- **Advanced Game Mode**: New mode with Redo card in starter deck
- **Redo Card**: Uncommon card that repeats the last card's effect (2 uses)
- **Card Compendium**: View all cards and their stats from the main menu
- **Exit Button**: Leave game with confirmation dialog
- **Game Simulation**: Headless game runner for automated testing and strategy analysis

### Changed
- Renamed "Start Game" to "Start Tutorial" for clarity
- Reduced boss battle imps from 5 to 3 per boss level
- Increased granary capacity to 20 food
- Starting army changed to 3 soldiers + 3 farmers
- Card display unified across shop and loot screens

### Fixed
- Card uses badge now shows remaining uses correctly
- Morning preview tooltip made fully opaque

---

## [0.0.1] - Initial Release

### Added
- Core city-building card game mechanics
- 7-card starter deck with Forage, Recruit, Pasture, and Caravan
- Schedule system for queuing and executing cards
- Morning phase with food production and consumption
- Battle system with initiative-based combat
- Battle days every 5th day with scaling imp encounters
- Boss battle on day 30
- Unlimited mode after defeating the boss
- Shop system via Caravan card
- Loot drops from battle victories
- Granary storage system
