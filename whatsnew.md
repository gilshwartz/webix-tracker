Version 2.3.14
==============
- fix date serialization for ajax calls
- fix closing of nested popups can affect windows
- fix for multiple instances of FileManager on the same page
- fix for uploader in IE8
- fix colspans and split mode
- fix clipbuffer styling in IE8
- fix metaKey support (mac OS) for multiselection
- fix validation in dataprocessor breaks insert operations
- fix for CSV parser, not it ignores the trailing new-lines
- fix for richselect, setting an empty value clears list selection


Version 2.3.8
=============
- combo accepts full data object as a value
- fix for scheduler: bottom toolbar height
- fix for value binding and dataFeed
- fix for regression in data saving handling


Version 2.3.6
=============

- better position for sort-row marker
- fix for missed onAfterFilter event for server side filtering
- fix for server side filtering with active editor
- fix for close all sub-windows on master popup closing
- fix for validation in hidden form
- fix for richselect filter in IE8
- fix for unnecessary scroll blocking by datatable
- fix for regression in treetable filtering
- fix for combo behavior in dyn. loading mode
- fix for onChange event in combo
- fix for ActiveContent doesn't survive component repainting in IE
- fix for regression in tooltip for icon


Version 2.3
============

### Major features

- new material skin
- barcode widget
- organogram (organization chart) widget
- badges and icons for list, buttons and menus (and views based on them)
- "Today" and "Clear" buttons are added to the date editor.
- better default styling, ability to customize layout configuration

[Full list of changes and fixes](http://docs.webix.com/desktop__whats_new_2_3.html)


Version 2.2.3
================

### Fixes

- autoheight in templates
- blockselecting and dbl-click events
- blockselection and custom scroll
- blockselection in scrolled state
- blockselection in the empty datatable
- calendar with no buttons, timepicker position
- default hotkeys for windows
- getValue on "editable" datepicker
- moving items in tree and tree table while in the filtered state
- processing setState with empty filter value
- regression in click handling inside of multi-level popup
- resetting text filter value after reloading data from the server side
- select filter in FF
- setValue and getValue of datepicker uses parseDateFormat
- tabbar "more" icon styling
- treestore serialization in filtered state
- calendar icons hidden by default
- scrollable "Month" view in Scheduler



Version 2.2
================

### Major features
- Data binding for Tree, TreeTable and TreeCollection
- Optional Today and Clear buttons in the Calendar
- Ability to define file types for file uploader
- Webix.ajax api can be used to fetch binary data ( file downloading by ajax )
- Optional hover for rows in datatable
- Improved scrolling on touch devices

[Full list of changes and fixes](http://docs.webix.com/desktop__whats_new_2_2.html)



Version 2.1.1
================
- regression in addView fixed
- issue with input focus in IE fixed



Version 2.1
================

### Major features

- better compatibility with Bootstrap and jQuery
- Icon font contains 479 icons now ( Font Awesome updated to 4.2 )
- "strict" mode for Webix
- Datatable and treetable math can be extended with custom functions
- Uploader can work in Internet Explorer 8-9
- ability to send extra data with file upload
- addView() and removeView() methods can be used to add and remove tabs in tabview
- find API for datatable and treetable
- addDropZone() method for uploader to allow file upload by drag-n-drop on html area

[Full list of changes and fixes](http://docs.webix.com/desktop__whats_new_2_1.html)



Version 2.0
================

### Major features

- Promises API for all ajax operations
- Progress bars and overlays
- Icons and close button in tabbar
- Improved keyboard navigation
- Extra locales added
- Package includes source map files
- [pro] PRO edition includes Pivot component
- [pro] Multiselect and multitext inputs
- [pro] Advanced editors for DataTable and Property views
- [pro] Colspans and Rowspans in DataTable
- [pro] Column menu in DataTable
- [pro] Optional custom scrollbars
- [pro] Grouped columns in DataTable
- [pro] Advanced filters for DataTable


[Full list of changes and fixes](http://docs.webix.com/desktop__whats_new_2.html)



Version 1.10
================

### Major new features

- IE12 compatibility
- Column Batches in the DataTable

[Full list of changes and fixes](http://docs.webix.com/desktop__whats_new_1_10.html)


Version 1.9
================

### Major new features

- Hotkey for inputs
- HTML links in menu


[Full list of changes and fixes](http://docs.webix.com/desktop__whats_new_1_9.html)


Version 1.8
================

###Responsive Layouts and Tabbar

- Layout view can be hidden or moved if there's not enough space for them on the screen. [Check details](desktop/responsive_layout.md).
- Tabbar tabs can be moved to a related popup if there're not enoght space for them on the screen. [Check details](desktop/responsive_tabbar.md).


###Disabling dates in Calendar

Calendar dates can be disabled to prevent their selection. [Check details](desktop/calendar.md#blockdates).


### Breaking changes
 - webix.proxy.$callback was replaced with webix.ajax.$callback
 - adjustHeaders deprecated


[Full list of changes and fixes](http://docs.webix.com/desktop__whats_new_1_8.html)



Version 1.7
==============

### Breaking changes in API

datatable.locate method returns object with "row" and "column" properties, in previous version result object has "row" and "col" properties respectfully.


### Default skin

Default skin changed to flat ( you still can use the old skin by using skins/air.css )  
Compact skin changed to flat theme as well ( old one renamed to skins/aircompact.css )  


### Improvments in API
- text sorting mode for datatable
- autoheight property for "property" view
- ability to edit math formulas in the datatable
- "touch" mode for multiselect


[Full list of changes and fixes](http://docs.webix.com/desktop__whats_new_1_7.html)



Version 1.6
==============

### Breaking changes in DataProcessor

Parameters of onBeforeSync, onAfterSync was changed  
onError event replaced with two new events - onBeforeSaveError and onAfterSaveError


### Improved support for mobile devices
- win8 touch support
- drag-n-drop on touch devices


### Improvments in Server side integrations
- full support of REST API
- data in components can be updated from server side
- client side code can't be broken by server side errors anymore
- ability to set custom headers for server side calls

### UI components
- better memory cleaning after component destruction
- improved API for complex forms


[Full list of changes and fixes](http://docs.webix.com/desktop__whats_new_1_6.html)



Version 1.5
-----------

### Improved support for mobile devices
- new skin for mobile UI
- functionality of desktop UI adapted to touch events and gestures

### Improvments in DataTable
- adjustRowHeight method added to datatable
- fillspace can be used for multiple columsn
- richselect can be used as editor in the datatable
- checkboxes can have checkValue and uncheckValue options
 
### Improvments in Angular and Backbone 

- [angular] webix-ui is compatible with ng-repeat
- [angular] webix-data works for options in combo and select
- [angular] init through angular directive links event handlers to the current scope

- [backbone] handling of reset event
- [backbone] handling of models with getters
- [backbone] WebixView is compatible with backbone 1.1
- [backbone] using sync with already loaded collection


[Full list of changes and fixes](http://docs.webix.com/desktop__whats_new_1_5.html)
	


Version 1.4
-----------

### Advanced data selection controls

- mutli-column select box
- rich content select box

### New Server Integrations

- loading and saving data through websockets
- loading and saving data through indexedDB

### Improvements in Window Positioning

- window can have complex relation size and position (details)
- window can be shown in fullscreen mode

### Others 

- autoConfig option for the datatable
- dataprocessor tracks data moving events
- keyboard navigation for list component
- correct sizing of layout with hidden pannels
- elementsConfig supported for nested collections
- getSelection deprecated in favor of getSelectionId
- better styling for icon buttons
- webix.onReady event
- webix.ui.zindexBase property added
- different small fixes in UX and styling


Version 1.3
-----------
### New skins
- 6 new skins added

### Others
- video player component (ui.video) added
- API and look of carousel control improved
- charts can use logarithmic scale
- small fixes


Version 1.2
-----------

### Integration with AngularJS
- webix-ui directive to define webix views directly in HTML
- webix-show, webix-event, webix-data directives to link webix components and scope
- webix component can be used with angular data bindings

### Integration with Backbone

- webix components can load data from Backbone Collections
- webix components can save data back to Backbone Collections
- WebixView, that can be used as normal Backbone View
- Backbone Router can be used to alter Webix Layouts

### Others
- *setContent* method for template component
- *isolate* configuration property for layout components
- *onBeforeDropOut* event added
- more than 50 different fixes


Version 1.1
------------

### Server side integration 
- all components can save data through REST API
- offline and caching loading strategies
- custom data saving and data loading transports

### UI improvments

- "disabled" configuration options for all views ( including all form controls )
- webix.history can be used with multiview control
- per-submenu configuration is possible ( "config" property of menu item )
- improved visual filtering in treetable and tree

### API
- onViewResize event added
- "disabled" option added for all views
- ability to define XSS safe templates

### Fixes

- popup's visibility on iOS
- incorrect sizing of multiview and accordion
- incorrect behavior of drag-n-drop in datatable
- setValue doesn't work for radio buttons



Version 1.0.2
--------------

### New functionality

- getText method for datatable	
- lineMaxLimit parameter that cuts a line in "non-item" position
- ui.fullScreen solution for FF
- default size of resizer changed
- xml parse can recognize arrays	
- addView adds to the end of layout if index was not defined	
- skin updates, important flags removed where possible
- csrf key now sent through http headers

### Fixes

- IE ignores hotkeys
- IE8 doesn't generated dblClick events	
- IE8 sets invalid value after changing cell value with select editor
- minWidth and maxWidth settings from xml
- loading tree-like data from XML
- datatable do not allow to define order of columns during export to pdf and excel
- incorrect remove action for local and session storage
- regression in layout rendering when views are added through addView
- dataprocessor and id change during binding	
- label align in segmented button 
- incorrect in-layout positions after showBatch call
- invalid animations in FF and Chrome



Version 1.0.1
--------------

### New functionality

- layouts are correctly shown when they are zoomed by a browser
- selectFilter can show data from the attached collections
- better strategy for x-layout rendering
- API calls against hidden items in menu
- init from html|xml markup improved
- dataprocessor can have different urls for different action
- value attribute for tabview
- getTopParentView method added for all views 
- getPopup method added to the datepicker
- setHTML method added to the label
- setValue and getValue methods added to the multiview


### Fixes

- invalid size and focus of popup editors
- toggle button ignores inputWidth settings
- regression in treetable checkbox behavior
- regression in datatable markup parsing
- conflict between data and content properties of template
- row markers are not removed during clearAll
- mulitiview with no animation
- chart rendering in multiview (no animation case)
- label position in pie chart
- validation and htmlform control
- incorrect column autosizing in case of hidden container
- native selection during cell resize
- hideItem throws an error for menu's item which was already hidden
- incorrect handling of custom popups in editors
- sizing of scrollview was broken
- window ignores y parameter of show command
- dnd in tree as child
