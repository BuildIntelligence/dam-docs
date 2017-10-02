#v1.8.1
Minor changes to UI. 
##Fixes:
- Fixed Release Notes section on Home Page not appearing.
- Fixed "What's New" section not displaying correctly in certain cases

# Changes 1.8.0:

Version 1.8.0 brings in some major behind the scenes overhauls to greatly improve stability, performance, and user experience. Saving, editing, and updating entities no longer has occasional errors saving locally.

### Improvements:
- Marketing Asset Tags are now out of alpha and are into release candidate builds! This RC has improved UI, improved adding. The text box for adding tags will also now show suggestions for existing tags based on the text typed into the field.
- Indicators added to details pages to make it more apparent to the user that saving is in progress

### Fixes:
- Fixed issues where items would sometimes save successfully to the cloud but not to local storage.
- Fixed issues where items would intermittently fail to save to the cloud.
- Fixed issues where UI would sometimes not update after successfully saving updates to an existing item
- Fixed issue where  going directly from typing in a textbox to clicking the save button would not save changes made in that text box.
- Fixed bug where some pages had fields overlapping in the detail view
- A few fields were changed from editable to readonly. There were a few database generated fields that were erroneously editable in the grid view in some pages.
- Fixed issue where the search box in the grid/details views would not display correctly autosuggestions
- Fixed an issue where the search box would not populate any results.


# Changes 1.7.8:
### New features:
Uploading assets now set assets in the “Domo Data Templates” page. Domo Data Templates missing assets will have them automatically assigned. Uploading a new asset when one is already selected causes a dialog window to appear asking the user whether they want to update the Domo Data Template with the newly uploaded asset
### Improvements:
- Improved Image loading and rendering
- Improved notifications on saves and deletes
- All fields shown for a record in details view
- Only relevant fields shown on grid view
- Marketing Tags section looks improved
- Other Minor UI improvements
### Fixes:
- fixed not selecting a file in the file picker crashing the app

# Changes 1.7.6:
- Minor UI improvements

# Changes 1.7.4:
Small update, reported that 1.7.3 didn’t have all the fixes included so we’re releasing another build sooner than expected.
### Improvements:
- Made editing an entity from a details page more streamlined

# Changes 1.7.3:
### What’s New:
- Delete asset/item functionality reintroduced
- Preview Release of basic Marketing Ad Asset Tagging functionality in Ad Details page. Visual improvements are in the works
### Fixes:
- Fixed Issue where going into editing on a grid list view with an image column would cause the window to scroll to the top
- Fixed Issue where navigation UI would sometimes disappear after saving a new item

# Changes 1.7.0:
No one expects a Spanish Inquisition,
but everyone expects great User Interfaces so we’ve made some improvements.
### Improvements:
- New Navigation menu.
- New Home Page
- Page Search navigation
### Fixes:
- Minor UI text fixes
- Dropdown Sorting now sorts dropdowns alphabetically
- Better Data Loading, especially on Template pages

# Changes 1.6.6.0:
### Fixes:
- Home Model Details Page Dropdown for Garage Loading now has “Front”, “Rear”, and “Side”

# Changes 1.6.5.0:
- Asset Viewer Column in Grid views
### Fixes:
- Fixed dropdowns not displaying properly when editing an existing item
- Fixed UI having the word “Legacy” inserted into random locations

# Changes 1.6.4.0:
following the big changes released over the previous changes we’ve completed a few more improvements
- More pages re-enabled
- Behind the scenes authentication improvements
- Minor Bug Fixes and UI adjustments
### Coming Soon:
- Streamlined navigation experience to better group related/similar pages
- Tagging feature for Marketing Ad Assets
- Improved in-app asset viewer

# Changes 1.6.3.0:
Big changes!
New Grid/Detail view which has many features including:
- Grouping
- Filtering
- Sorting
- Searching
and more!
Transfered to a new database, syncing, saving, and updating is much more reliable.
More syncing improvements on the way.
Several Builds will be released over the next few days to re-enable some missing views, clean up the UI navigation, and minor bug fixes
Marketing Ad Assets are introduced in this version with basic tagging functionality coming soon

# 1.1.10.0:
- Fixed Code Regression resulting in the app displaying an old page version
- Fixed issue causing app to crash after successfully uploading a digital asset

# 1.1.9.0
- Fixed issue where Front Elevation Photo would not save to database on Model Elevation Garage Template Page
- Additional app declarations to mitigate app crashes on pre-creators update versions of Windows 10

# 1.1.8.0
- Telemetry Improvements (Better Error Tracking!)
- Image viewer on asset pages

# 1.1.7.0
- Loading indicator when the app is syncing with the Azure Database
- Fix issues scrolling on small screen sizes
- Improved sync method to minimize sync related app crashes
- Update app to utilize new cloud server backend