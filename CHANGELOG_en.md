# Changelog

## 1.1.1 - 11/27/2015
### Corrections
- [Reports] Fixed categories listing display

## 1.1.0
### Additions
- Extra fields in users
- Filter "By forwarding perimeter.." in reports search
- Added field "Perimeter" on report view
- Added search by name on the perimeter listing
- Added selection box of standard solver group for the perimeter

### Fixed
- Added infinite scroll to group listing by perimeters when editing a category
- Removed infinite scroll in group listing by perimeters and applied new rendering format
- Adjusted resolution of report images
- Fixed browser's back when editing the category of inventory items
- Improvement of the feedback to the user when changing report reference
- Modified the label "Commentary to the Citizen" to "Response to the applicant" (modal for changing the report status)
- Updated panzoom component and adjusted its configuration to allow for the displacement of the image in the visualization modal
- Visual adjustments on the notification's listing table (header and term text)
- Visual adjustments on the drag-n-drop box for uploading report images
- Adjustments on the perimeters listing (shapefiles) and query behavior
- Fixed z-index positioning of the auto-complete suggestion box of the component for choosing the address
- Fixed z-index positioning of the filter "By fields..." for inventory items
- Fixed display of the list of categories in report creation

## 1.0.4
### Fixed
- Fixed updating of information of responsible group and report history when there is an address update
- Fixed date formatting on the list of registered shapefiles
- Adjusted the transformation filter of the response of Goolgle Maps API for addresses (district)
- Adjusted ordering of log records for inventory items

## 1.0.3
### Additions
- Added shapefiles registration to categories configuration
- Selection directive in line of permissions of user groups
### Corrections
- Fixed incorrect behavior of popovers positioning
- Environment variables that were missing in the build
- Notifications permissions
- Fixed categories colors
- Does not display notifications area if the report category has no notifications
- Reversed the merge that omitted reports permissions in groups edition
- Fixed z-index attribute of pickcolor in inventory category edition
- Fixed z-index bug in autocomplete component
- Changed all the labels from "citizen" to "applicant"

## 1.0.2
### Additions
- New notifications feature 
- Fixed dependencies
- Field to add subtitles to report images

## 1.0.1
### Corrections
- Corrections in the section of report changes history
- Correction in the dynamic listing of users of the group

### Additions
- Changing the panel theme through environment variables

## 1.0.0

Initial stable release
