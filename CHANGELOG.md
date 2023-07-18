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
