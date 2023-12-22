## [4.1.0] - 2023-12-22

### Added
- Optimization for large screens
- Optimization for phone landscape orientation
- Automatic sync for operations

### Changed
- Completely changed routing library to introduce more stable experience
- Dialogs in statistic screen replaced by modal bottom sheets

### Fixed
- Sync categories bug
- Different navigation bugs

## [4.0.0] - 2023-12-16

### Added
- Sync between multiple devices
- Transaction data modal on statistic screen
- Save selected month in pie charts
- Ability to choose multiple categories on statistic screen
- Income and expanse widgets on main screen
- Quick action to add transaction

### Changed
- Old gdrive backup option is replaced by sync
- Updated introduction screen

### Fixed
- Converted sum suggestion fix
- Pie charts data wasn't updated when there aren't new data in month
- Fixed db backup restore panic

## [3.3.3] - 2023-12-07
### Fixed
- Crashes

## [3.3.2] - 2023-12-07

### Added
- Ability to set new currencies as crypto

### Changed
- New icons for settings

### Fixed
- Incorrect number formatter on add transaction screen
- Month dialog on charts screen was not dismissible

## [3.3.1] - 2023-11-29

### Changed
- Hide dev settings
- Moved main currency selector to currencies screen
- Dropdowns width decreased
- Icon picker dialog

### Fixed
- Removed tags section from source category page
- Modal bottom sheet now opens over bottom navigation bar
- Close currency action pane on button tap

## [3.3.0] - 2023-11-28

### Added
- Operation import to CSV

### Changed
- Upgraded flutter version

### Fixed
- English locale bug

## [3.2.0] - 2023-11-03

### Added
- Manual backup restore from Google Drive
- Button to manually fix wallet states

### Changed
- Tags name are not unique now
- Tag labels are used to identify category by info

### Fixed
- Bug with wallet states update

## [3.1.3] - 2023-10-07

### Fixed
- Tinkoff push import 2

## [3.1.2] - 2023-10-06

### Fixed
- Tinkoff push import

## [3.1.1] - 2023-10-05

### Changed
- Order of fields in bottom sheet
- Removed info from push import transaction when tags found
- Show tags on list item prior to info

## [3.1.0] - 2023-10-03

### Added
- Autofocus for tag name field
- Reorder of tags
- Tags filter in statistic screen

### Fixed
- No tags in category screen when import is disabled

## [3.0.0] - 2023-10-02

### Added
- Tags for transactions

### Changed
- Drag is activated by tapping on drag icon
- Transaction modal sheet font sizes

### Fixed
- Change theme wiped app state
- Scroll in add transaction screen

## [2.9.9] - 2023-09-30

### Changed
- Rework of charts page
- Increased duration of animation in choose wallet screen

### Fixed
- Not working back gesture after going to choose message screen

## [2.9.8] - 2023-09-30

### Changed
- Animation in choose wallet screen

### Fixed
- Bug when wallet and category were not updated after saving

## [2.9.7] - 2023-09-29

### Changed
- Some hero animations duration

### Fixed
- Not working hero animations inside wallets and category pages

## [2.9.6] - 2023-09-29

### Added
- New animations for choose wallet screen

### Fixed
- Reordering bug

## [2.9.5] - 2023-09-16

### Added
- Fab hide animation

## [2.9.4] - 2023-09-09

### Added
- Haptic feedback on long press for choose wallet screen

### Changed
- Faster scroll animation for cards page view

### Fixed
- Laggy scrolling for cards page view

## [2.9.3] - 2023-09-08

### Added
- Ability to fast travel to summary wallet
- Reordering summary wallet from choose wallet screen
- Auto remove push statistic older than 7 days

### Fixed
- Optimized main screen

## [2.9.2] - 2023-09-02

### Fixed
- Absence of nav bar in settings 

## [2.9.1] - 2023-09-02

### Fixed
- Operation type label
- Snapping grid division by zero error

## [2.9.0] - 2023-09-01

### Added
- PageView height respects number of categories in add transaction screen
- App bar button to open card choose screen
- Fade animation for sync button on scrolling
- Selected date in add transaction header

### Changed
- New charts data style
- New transaction list style
- New card chooser style
- No indicator for PageView with single page
- Move settings button to navigation bar
- Summary settings labels
- Save button moved to center in add transaction screen
- Optimization of day summary loading in main screen
- New UI for selecting transaction type

### Fixed
- Label overflow in pie chart
- Day summary not updating after transaction delete
- Removed zero elements from pie chart

## [2.8.0] - 2023-08-30

### Added
- Google drive sync

### Changed
- Cupertino style alert dialogs
- Cupertino style date dialogs

### Fixed
- FAB pushing up by keyboard inside add transaction screen
- Fixed date summary spendings while setting up date using calendar widget
- Dialogs not popping on back button
 
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
