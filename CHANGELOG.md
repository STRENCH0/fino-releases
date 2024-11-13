## [5.6.1] - 2024-11-13

### Added
- Update currencies dialog

### Changed
- Calc automatically opens only on new transactions
- Up flutter version

### Fixed
- Sync replace on intro screen


## [5.6.0] - 2024-07-29

### Added
- Option to automatically open calc on add transaction screen

### Changed
- Added additional space for swipe when drag and drop enabled
- Updated some dependencies

### Fixed
- Sync warning title

## [5.5.4] - 2024-03-20

### Added
- Button to show values in main currency in charts

### Fixed
- Sum by day currency convert

## [5.5.3] - 2024-03-17

### Added
- Ability to ignore wallet in summary
- Credit card flag for credit card in intro screen

### Fixed
- Calculator zeroes after decimal point
- Collect sync events while it is disabled

## [5.5.2] - 2024-03-16

### Changed
- Removed install package permissions

## [5.5.1] - 2024-03-15

### Added
- Flutter flavors
- About dialog

## [5.5.0] - 2024-03-04

### Added
- Option to hide empty wallet/category
- No budgets text in budget_screen
- Color scheme change
- Category and wallet text color adapt to background color
- Ability to choose text color between black and white
- Hide update banner option

### Changed
- Main screen -> choose wallet animation
- TabBar ripple effect radius
- Update banner design

### Fixed
- White lines between calculator buttons
- Credit limit was not changed after editing wallet from main screen
- Decimal separator didn't work in calculator from clipboard
- Last wallet cannot be deleted now
- Last category cannot be deleted now
- Trying to fix laggy wallets and categories screens
- Firebase screen observer

## [5.4.0] - 2024-02-25

### Added
- Added aab github actions build
- New predefined categories

### Changed
- Removed old intro screen
- Decreased apk size
- Sentry is replaced by firebase
- Intro screen animations

### Fixed
- Error after restoring backup on intro screen
- Tinkoff sms import
- Default currency on intro screen

## [5.3.4] - 2024-02-24

### Fixed
- Tinkoff sms import
- SMS import dialog using root navigator

### Changed
- Remove navigation to statistic from wallets and categories pages
- Text for import card data hint

## [5.3.3] - 2024-02-23

### Added
- Button on add_wallet_screen to delete/hide
- Button on add_category_screen to delete/hide
- Icon for adjustment

### Changed
- Remove ability to delete/hide wallets and categories from wallets/categories screen on swipe
- Disable drag and drop by default

## [5.3.2] - 2024-02-22

### Changed
- Number format according to locale

## [5.3.1] - 2024-02-21

### Added
- Rustore update

### Fixed
- Create wallet states after introduction screen

## [5.3.0] - 2024-02-20

### Added
- Beta label for sync settings tile

### Changed
- New introduction screen
- Android targetSDK changed to 34

### Fixed
- List on main screen didn't appear after first start
- Fix tinkoff push import

## [5.2.6] - 2024-02-18

### Changed
- Main screen landscape mobile layout 

### Fixed
- iOS build script

## [5.2.5] - 2024-02-18

### Added
- Tinkoff additional sbp template
- Edit wallet button on main screen

### Fixed
- Tinkoff import for fracational sum
- Null in adjustment delete dialog

## [5.2.4] - 2024-02-12

### Fixed
- Use root navigator in currencies dialog
- Tinkoff push import

## [5.2.3] - 2024-01-23

### Changed
- Responsive budget history screen
- Responsive currencies screen
- Force settings always be shown in material design 
- Delete dialog in sync screen

### Fixed
- Help button dialog width on big screens
- Settings screen tiles in portrait phone layout

## [5.2.2] - 2024-01-21

### Fixed
- Calc buttons delay
- Push import Transaction wasn't shown without page reload

## [5.2.1] - 2024-01-19

### Added
- Update transaction list after sync on tablets and landscape phones

### Fixed
- Tag sync update bug 

## [5.2.0] - 2024-01-18

### Added
- Available currencies added to app resources
- Transaction delete dialog

### Changed
- Added splash for calculator buttons
- Restyled currencies screen
- Button to choose category type in category add screen
- Remove ability of changing type of existing category
- Tag dialog to bottom sheet
- Currency search screen

### Fixed
- Calc with point numbers

## [5.1.1] - 2024-01-16

### Fixed
- Budget wasn't deleted after sync

## [5.1.0] - 2024-01-15

### Added
- Haptic feedback for new calc widget
- Delete budget confirm dialog
- Add tags from category screen

### Changed
- Budget info screen
- Budget history screen
- Queries for budgets
- Increased max length of budget name

### Fixed
- Budget history chart
- IOS testflight publish
- Title for edit budget screen

## [5.0.0] - 2024-01-13

### Added
- Budgets function
- Additional warning and actions on enabling sync

### Changed
- Sum enter field is replaced by custom keyboard with calculator
- Prevent sync in case new version sync files exist
- Base navigation

## [4.2.2] - 2024-01-07

### Added
- Warning dialog for enabling sync

### Fixed
- SyncError toString
- Appstore connect errors
- Draft transaction icon overflow
- Create tag by info replaced selected tags

## [4.2.1] - 2024-01-05

### Added
- SMS import button tooltip
- No connection message for sync screen

### Changed
- Icon size in category statistic screen

### Fixed
- Statistic card for summary wallet when no operations were done

## [4.2.0] - 2023-12-30

### Changed
- Transaction type selector in category statistic screen
- Icon size in category statistic screen list
- Calc accept button
- Text fields style in add wallet and add category screens
- SummaryColor dialog changed to bottom sheet
- Sort for destination and source categories in category statistic screen

## [4.1.3] - 2023-12-27

### Fixed
- Manual backup on android

## [4.1.2] - 2023-12-25

### Changed
- Increased category and wallet icons size

### Fixed
- Date dialog back button behaviour on category statistic screen
- Auto sync not working

## [4.1.1] - 2023-12-23

### Fixed
- Loader overlay in sync screen didn't hide rail
- Position of intro screen content in landscape view
- Back button closes the app on transaction edit screen when it opened from modal bottom sheet
- Back button for dialogs

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
