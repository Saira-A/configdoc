# Configuration Options

> This document provides a detailed explanation of the configuration options available within the Universal Viewer. Each option is described with its purpose, data type, default value, and applicable file formats, helping users customise and optimise the viewer's behaviour and appearance for specific needs.

## uv-iiif-config.json

The uv-iiif-config.json file contains global options and modules settings that override the same settings in individual configuration files for all formats.

### options:

##### dropEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if [drag and drop](https://iiif.io/guides/using_iiif_resources/) is enabled - the IIIF logo is located in the share/embed dialogue box.

##### footerPanelEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if the footer panel is enabled.

##### headerPanelEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if the header panel is enabled.

##### leftPanelEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if the left panel is enabled.

##### limitLocales
**Type**: `boolean`  
**Default**: `false`  
Determines if locales are limited.

##### overrideFullScreen
**Type**: `boolean`  
**Default**: `false`  
Determines if full-screen behavior is overridden.

##### pagingEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if paging is enabled.

##### rightPanelEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if the right panel is enabled.

##### clickToZoomEnabled
**Type**: `boolean`  
**Default**: `false`  
Determines if click to zoom is enabled.

##### saveUserSettings
**Type**: `boolean`  
**Default**: `true`  
Determines if user settings are saved.

### modules:

#### avCenterPanel

##### mostSpecificRequiredStatement
**Type**: `boolean`  
**Default**: `true`  
Determines if user settings are saved.
  
#### downloadDialogue

##### selectionEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if selection is enabled. 

#### headerPanel

##### localeToggleEnabled
**Type**: `boolean`  
**Default**: `false`  
Determines if locale toggle is enabled.

#### pagingHeaderPanel

##### pagingToggleEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if paging toggle is enabled.

#### openSeadragonCenterPanel

##### autoHideControls
**Type**: `boolean`  
**Default**: `false`  
Determines if controls are hidden automatically.

##### showHomeControl
**Type**: `boolean`  
**Default**: `true`  
Determines if home control is shown.

##### showAdjustImageControl
**Type**: `boolean`  
**Default**: `true`  
Determines if adjust image control is shown. 

#### footerPanel

##### downloadEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if downloading is enabled.

## Options

These options exist in the individual configuration json files for each of the file formats that UV supports, and can be modified in those files independently.

##### allowStealFocus
**Type**: `boolean`  
**Default**: `false`  
Determines if the focus can be stolen. 

##### authAPIVersion
**Type**: `number`  
**Default**: `1`  
Version of the authentication API.

##### bookmarkThumbHeight
**Type**: `number`  
**Default**: `150`  
Height of the bookmark thumbnail.

##### bookmarkThumbWidth
**Type**: `number`  
**Default**: `90`  
Width of the bookmark thumbnail.

##### dropEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if [drag and drop](https://iiif.io/guides/using_iiif_resources/) is enabled - the IIIF logo is located in the share/embed dialogue box. Overriden in uv-iiif-config.json file.  

##### footerPanelEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if footer panel is enabled.

##### headerPanelEnabled
**Type**: `boolean`  
**Default**: `false`  
Determines if header panel is enabled.

##### leftPanelEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if left panel is enabled.

##### limitLocales
**Type**: `boolean`  
**Default**: `true`  
Determines if locales are limited.

##### doubleClickAnnotationEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if double click annotation is enabled. 

##### metrics
**Type**: `number`  
**Default**: `sm: 0, md: 768, lg: 1024, xl: 1280`             
Metrics array. 

##### multiSelectionMimeType
**Type**: `string`  
**Default**: `application/zip`  
MIME type for multi selection.

##### navigatorEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if the navigator is enabled.

##### openTemplate
**Type**: `string`  
**Default**: `http://universalviewer.io?manifest={0}`                
Template for opening.

##### overrideFullScreen
**Type**: `boolean`  
**Default**: `false`  
Determines if full screen is overridden.

##### pagingEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if paging is enabled.

##### pagingOptionEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if paging option is enabled.

##### pessimisticAccessControl
**Type**: `boolean`  
**Default**: `false`  
Determines if access control is pessimistic.

##### preserveViewport
**Type**: `boolean`  
**Default**: `false`  
Determines if viewport is preserved.

##### rightPanelEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if the right panel is enabled.

##### saveUserSettings
**Type**: `boolean`  
**Default**: `true`  
Determines if user settings are saved.

##### clickToZoomEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if click to zoom is enabled.

##### truncateThumbnailLabels
**Type**: `boolean`  
**Default**: `true`  
Determines if setting to truncate thumbnail labels is enabled.

##### searchWithinEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if search within is enabled.

##### seeAlsoEnabled
**Type**: `boolean`  
**Default**: `false`  
Determines if seealso content is enabled.

##### termsOfUseEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if terms of use are enabled.

##### theme
**Type**: `string`  
**Default**: `uv-en-GB-theme`          
Theme string.

##### tokenStorage
**Type**: `string`  
**Default**: `session`                     
Storage for tokens.

##### useArrowKeysToNavigate
**Type**: `boolean`  
**Default**: `false`  
Determines if arrow keys can be used to navigate.

##### zoomToSearchResultEnabled
**Type**: `boolean`  
**Default**: `true`  
 Determines if zoom to search result is enabled.

##### zoomToBoundsEnabled
**Type**: `boolean`  
**Default**: `true`  
 Determines if zoom to bounds is enabled.


## Modules
