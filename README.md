# Changelog - Veneer Web Library 

## [3.3.0] - 06/12/2020

#### 🚀 Highlights
- Disabled states for fields and controls are now more obviously disabled
- Ground work done in Figma to migrate to decoupled iconography library

#### 🐛 Bug Fixes
- [Figma] Bug fix on separate label select filled (high density) and tab item auto layout (standard density)
- [Adobe XD] Fixed bug where button would expand beyond its bounds

### ✅ Added
- [Figma] Attached tab component
    - Created atoms for each tab state
    - Created attached tab component for high density mode, as well as tab atoms for high density

### 🔄 Changed
##### Figma / Adobe XD
- [Figma / Adobe XD] Field updates - filled state update, disabled fields added
- [Figma / Adobe XD] Tab updates - default state: label color to colorGray7, Hover state: label color to colorGray10
- [Figma / Adobe XD] Control updates - disabled state: border color to colorGray2 (checkbox, radio button, slider, and toggle)

##### Figma
- [Figma] Icon updates
    - Migrated all icons to leverage the icon components from the new Iconography library
    - Edited the names of following icons: arrow up, chevron down, building, slash circle, check circle, external link, eye off, x circle, ellipsis, globe off, globe, ellipsis circle, lock open
    - Updated the shape of the following icons: cloud, download, upload, eye, eye off, external link, rpos
- [Figma] Contained tab - Fixed space in between the tab items to be zero
- [Figma] Table corner radius updated to 12px for high density, and 16px for standard density
- [Figma] Radio button disabled selected/unselected name fix, fixed inner circle size for selected/disabled state (high density)

##### Adobe XD
- [Adobe XD] Table component row height updated to match Figma. Avatar component added to rows
- [Adobe XD] Breadcrumb fixes, tab fixes

### ⛔ Removed

- [Adobe XD] Removed prototyping states from components
