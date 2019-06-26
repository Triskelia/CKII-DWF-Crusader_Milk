# Changelog

All notable changes to Crusader Milk will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2019-06-27

This update doesn't add a lot of content gameplay wise. It mostly implement the lactation framework. Next update will hopefully be loaded with new events.
Nevertheless, feedbacks are still welcome regarding this new framework

- WILL break old saves
- Delete your old "Crusader Milk" folder before installing if you have a previous version
- NOT compatible with Dark World Tentacles v1.4.1 or below (It will need to be updated to work with the new lactation framework)

### Added

- Several variables are now tracked ("Milk", "Milk capacity" and "Production rate", as well as a few others)
  - "Milk capacity" and "Production rate" depend on breast size (will be alterable by scripted_events in the future)
  - For now, "Production rate" will increase the milk quantity by its amount each 6 months (will probably add a rule to alter it in the future)
- Added Decision to check your hucow stats
- Added "Recently milked" event modifier (prevents milking and increase of milk quantity while a hucow has it)
- Added Milk quantity counter (character modifier)
- (Modders) Added several scripted effect ("dwcm_become_hucow" and some milking effects like "dcwm_milk_half_effect"). Search for "Modder_friendly" to easily find them all

### Changed

- AI can now use the "Milk yourself" decision
- Slight tweak of the hucow trait (now has same_opinion and sex_appeal_opinion modifiers)
- "Engorged breasts" event now triggers when a hucow reaches her max milk capacity

## [0.1.1] - 2019-05-04

### Changed

- Lowered "Engorged breasts" event frequency (now occurs 1,5 to 2,5 years after being milked, instead of half a year)

### Fixed

- Some localisation errors

## [0.1.0] - 2019-05-01

### Added

- Event chain to research on "Lacteria Mirifica", a mysterious mushroom, and turning yourself or another random woman into a hucow
- Basic breast fullness system (engorged breasts trait gained after some time)
- Decision to milk yourself if you have engorged breasts
- (For Modders) Global variable to check if the mod is present

[Unreleased]: https://github.com/Triskelia/CKII-DWF-Crusader_Milk/compare/v0.2.0...develop
[0.2.0]: https://github.com/Triskelia/CKII-DWF-Crusader_Milk/compare/v0.1.1...v0.2.0
[0.1.1]: https://github.com/Triskelia/CKII-DWF-Crusader_Milk/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/Triskelia/CKII-DWF-Crusader_Milk/releases/tag/v0.1.0
