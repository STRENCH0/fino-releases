## [2.7.0] - 2023-08-12

### Added
- Support for custom currencies
- Update banner on main screen
- Support for credit cards (available balance is shown on main screen)

### Changed
- Alert dialogs unified style

### Fixed
- A bug when choose wallet function doesn't actually change wallet on screen

## [2.6.3] - 2023-08-03

### Added
- Indication on reorder start
- Statistic screen from budget chart

### Fixed
- Reorderable container size

## [2.6.2] - 2023-08-03

Hotfix

### Fixed
- Back gesture bug

## [2.6.1] - 2023-08-02

Small fixes

### Added
- Drag target hovering indication

### Changed
- Increased droppable zone for changing page
- Slightly decreased pager animation duration while dragging category

### Fixed
- Changed color of draggable list item indicator

## [2.6.0] - 2023-08-02

Drag and drop operations creation and UX improvements

### Added
- Ability to create operations by dragging category icons onto another one
- Setting to turn off draggable categories
- New choose wallet dialog by tapping on wallet
- Drag indicator for draggable list items

### Changed
- Moved settings button from bottom bar to app bar
- Massive UX improvements in statistic screen

### Fixed
- Error while using back gesture on import screen
- State loss on changing theme

## [2.5.1] - 2023-07-24

### Changed
- Category statistic sum range filter respects current main currency and not just value

### Fixed
- Active update button right after update to the latest version
- Category statistic sum range filter upper bound
- No save button after calc use

## [2.5.0] - 2023-07-22

### Added
- Calculator for sum field in add transaction screen and add wallet screen
- Hide FAB on scroll in category add screen

### Changed
- OTA dialog animation

## [2.4.1] - 2023-07-18

### Fixed
- Small fixes

## [2.4.0] - 2023-07-18

### Added
- OTA updates


## [2.3.2] - 2023-07-18

### Added
- Automatic release pipeline


## [2.3.1] - 2023-07-16

GazpromBank push import fix

### Changed
- Refactored push import model

### Fixed
- GPB import pattern


## [2.3.0] - 2023-07-15

GazpromBank push import

### Added
- Push import for Gazprombank
- Push statistic manual sharing

### Changed
- Refactored push import
- Foreground notification text and description

### Fixed
- Text translation in push setup dialog


## [2.2.2] - 2023-07-07

Minor bug fix

### Added
- SMS import for Gazprombank
- Auto hide floating action button on scroll events
- Sum range filter text fields
- Unable to change name of wallet


## [2.2.1] - 2023-07-07

Minor bug fix

### Fixed
- Laggy scroll on main screen


## [2.2.0] - 2023-07-06

This release brings on a lot of refactoring and some new features.

### Added
- SMS import for Gazprombank
- Auto hide floating action button on scroll events
- Sum range filter text fields
- Added CHANGELOG.md

### Changed
- Refactored sms import (all current imports will be deleted due to lack of backward compatibility)
- Refactored translations resources
- Increased wallet name max length
- README.md

### Fixed
- Removed deprecated field "name" from wallet model
