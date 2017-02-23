# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.5.2] - 2017-02-23

### Added

- Custom Font support throughout Miromaa
- Options: Allow setting Font for a language
- Import: Default to another field/text, allow multiple multimedia, allow relative multimedia file paths, improved responsiveness, allow importing Date Entered
- Export: Removed limit of number of media exported, allow exporting Date Entered
- Dictionary: Allow filtering by a second Word Category
- Login: `Help > Learning` and `Help > Support` added to Login screen

### Changed

- Import: Unused tags no longer show in tag count, removed timer message box after import
- General: Updated Contact Information in various places

### Fixed

- `Help > About`: Window size adjusted so information is not cut off
- Export: Does not export if no tag is entered but field is selected for export

## [3.5.1] - 2015-11-17

### Added

- Dictionary Export functionality

### Changed

- Branding of "Sources" updated to "Library"
- Default export options updated

### Fixed

- Multimedia Export falsely showing an error in some cases
- Link for `Help > Learning` menu item
- Link on `Help > Support` screen
- Alphabetical sorting of Word Categories and Part of Speech in Add Word Reference window

## [3.5.0] - 2014-12-10

### Added

- Sorting in Options screens
- Ability to use sample databases when creating DAT files

### Changed

- Contact email updated: `contact@acra.com.au` → `miromaa@acra.org.au`

### Fixed

- "Tasmanian Aboriginal Corporation" corrected to "Tasmanian Aboriginal Centre"
- Language Users in Options not being selected
- User Groups not deleting properly
- Ability to add empty fields in Options
- Blank keyboard characters displayed
- Keyboard characters not properly deleted

## [3.4.4]

### Fixed

- Language Users not being selected in Options screen on startup

## [3.4.3] - 2014-09-22

### Fixed

- Export screen not saving sort order in some circumstances
- Export screen sometimes showing an extra column

## [3.4.2] - 2014-09-17

### Fixed

- Incorrect tag for Videos in Export screen

## [3.4.1] - 2014-09-05

### Fixed

- TeamViewer link on the Support screen

## [3.4.0] - 2014-09-02

### Added

- Export window and Word List window defaults (Visibility: Unrestricted, Main: Yes, Archived: No)
- Default selection of first language in Login
- Custom Label for "Translated Language" to replace "English" throughout
- Additional Sentence fields and Short Text field
- People and Organizations to credits on About screen
- Custom Label functionality to Export screen
- TeamViewer link on Support screen

### Changed

- Text in Sources Options screen updated
- Keyboard characters size increased
- Login screen button order ("Create", "Import", "Choose") adjusted
- "Page Ref." and "Other Ref." renamed to "Reference 1" and "Reference 2"
- Username selection changed to dropdown list
- Sentence fields size increased
- Custom Labels order adjusted
- Custom Fields size increased to accept multiple lines
- Miromaa About screen information updated
- Export screen Video tag changed to `\ff`
- Keyboard Options screen display updated

### Fixed

- Display of "Aboriginal" in some places
- Error in Export screen when Multiple Multimedia selected

### Removed

- Ability to overwrite a DAT file from within Miromaa

## [3.3.18] - 2014-06-05

### Fixed

- Export issue

## [3.3.17] - 2014-05-24

### Fixed

- Special characters not appearing in keyboard
- Reports not working on Windows 8 and 8.1
- Import screen issue

## [3.3.16] - 2014-05-20

### Fixed

- Update button in Options screen not working correctly
- Custom Field labels not working for multiple languages
- Multimedia attachments not saving
- Multimedia Location issue when creating a new Language under certain circumstances

## [3.3.15] - 2014-04-07

### Fixed

- Version number display
- Last used DAT file memory

## [3.3.14] - 2014-04-03

### Fixed

- Audacity compatibility on newer computers

## [3.3.13] - 2013-12-06

### Fixed

- Attachment default name not set when adding

## [3.3.12] - 2012-12-17

### Added

- Import/Export of "Knowledge" field (introduced in 3.3.11)

### Changed

- Updated contact information
- Updated max length of some fields to allow more information
- Updated Copyright and Support details

## [3.3.11] - 2012-06-27

### Added

- "Knowledge" field to "Notes" section in Linguist/Editor screens
- "Comments" field for Sources
- Secondary Attachments for Sources
- Upgraded registration procedure

## [3.3.10] - 2009-10-11

### Added

- Ability to move multiple multimedia up and down in the list
- Primary multimedia added to sublist for title

### Changed

- Exporting of multiple multimedia limited to three with `\px` tag

### Fixed

- Source link exported instead of activity link
- Export screen removing filters
- Export labels editable
- Learner screen sorting by English words when listed by English words

## [3.3.9] - 2009-08-04

### Fixed

- Activity Link not working
- Default Skin not properly selected

## [3.3.8] - 2009-07-08

### Added

- Acknowledgements to About Miromaa screen

### Changed

- Export screen size adjusted for improved look and feel
- Name of Custom Labels updated

### Fixed

- About Page Document Attachments issue

## [3.3.7]

### Added

- Options > Custom Labels to change labels for some fields in main screens
- Ability for Export to save 'Extra MMs'
- Source link in main window
- "About \<Language\>" in menu bar showing window with attached document
- Option to attach HTML or PDF file to About \<Language\> window

### Changed

- "Source" fields in Export to distinguish between Source Code and Source Activity
- Default new DAT file location set to My Documents

### Fixed

- Deleting and re-adding a user with the same name giving an error

## [3.3.6]

### Fixed

- Miromaa failing on 64-bit computers

## [3.3.5]

### Fixed

- Extra Information fields cut short in Word Lists
- Detailed English to Aboriginal Word Lists displaying "Aboriginal" on left instead of English

## [3.3.4]

### Fixed

- Default MiromaaDat file not updated alongside Miromaa 3.3

## [3.3.3]

### Fixed

- User rights preventing registry read and data file failure
- Entries not removable from Archive
- Crash when leaving Archive screen

## [3.3.2]

### Changed

- Import alert message improved for clarity

## [3.3.1]

### Fixed

- "Clear" button not working for Notepad

## [3.3.0]

### Added

- Resize grip in bottom right corner
- "Notepad" feature
- Edit Menu (Undo, Cut, Copy, Paste, Select All)
- Metadata for Checked By, Locked By, and Archived By
- Option to sort main records by Word ID, Language, or English in Status Bar
- Saving of Last Database and Default Skin to Registry
- Tooltips to Controls Section
- "Remove Filter" button in search box
- Option to change skin
- Database custom field changed from "Language" to "View"

### Changed

- Delete icon changed to "X" in navigator
- Navigator slightly enlarged
- Email and web links within program updated
- Left-hand menu ("Language", "Learn", "Tools") removed
- "Find" renamed to "Go To"
- Word ID moved to Status Bar (right side)
- Layout of some screens adjusted

### Fixed

- Changes to words not always saved when switching to Learner
- ToDos not displaying properly under certain circumstances
- Search tool still usable in Learner screen
- Custom fields not altering labels in some places
- Empty left-hand menu still visible on Entry Screen
- Locked option not acting as expected
- Bug occurring when creating a new Data File

### Removed

- "Skip 10", Undo, and Save from navigator

## [3.2.0]

### Added

- Two buttons to copy a Word to its Original Record

### Changed

- Title of program window to reflect edited language
- All references to "Aboriginal" updated to reflect edited language
- Screen layouts adjusted

### Fixed

- Word Category and Part of Speech lists in Word Entry screen
- Failed update falsely detected when using different versions with same Database

### Removed

- Display of database field name from Export screen
- Version '3' reference from Miromaa during use

## [3.1.1]

### Fixed

- Fresh install missing `MiromaaDat.mdb` file
- Long multimedia path name causing unwanted GUI changes

## [3.1.0]

### Added

- Import feature

### Fixed

- Multimedia not refreshing on Learner screen

## [3.0.4]

### Fixed

- Deleting a user assigned ToDos
- Adding a new word from Editor/Linguist screen

## [3.0.3]

### Added

- Viewing Multiple Multimedia in Learner screen

### Fixed

- Choosing "No" when prompted regarding Archive screen
- Adding multimedia preventing entry from saving correctly
- Selecting Archive removing menu without showing Archive screen
- Closing Miromaa 3 prompting to close multiple times

## [3.0.2]

### Added

- Multiple Multimedia functionality

### Fixed

- Choosing "No" when prompted regarding Archive screen
- Adding multimedia preventing entry from saving correctly
- Selecting Archive removing menu without showing Archive screen
- Closing Miromaa 3 prompting to close multiple times

## [3.0.1]

### Fixed

- Problem when creating a new Language File

## [3.0.0]

### Addedˆ

- Initial version

## [Miromaa Updater 1.0.1]

### Fixed

- Issue on Windows 8 computers preventing download of Update files from the Internet
