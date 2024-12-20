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

#### leftPanel

##### expandFullEnabled
**Type**: `boolean`  
**Default**: `false`  
Determines if expand full is enabled.

##### panelAnimationDuration
**Type**: `number`  
**Default**: `250`  
*Repeated -  edit in contentLeftPanel*.                                                       
Determines the duration of the panel expand/collapse animation.

##### panelCollapsedWidth
**Type**: `number`  
**Default**: `30` 
*Repeated -  edit in contentLeftPanel*.                                                 
Width of the collapsed panel.

##### panelExpandedWidth
**Type**: `number`  
**Default**: `255`  
*Repeated -  edit in contentLeftPanel*.                     
Width of the collapsed panel. 

##### panelOpen
**Type**: `boolean`  
**Default**: `false`  
*Repeated -  edit in contentLeftPanel*.                  
Determines if the panel is open.

##### autoExpandTreeEnabled
**Type**: `boolean`  
**Default**: `false`  
Determines if tree should expand automatically.

##### autoExpandTreeIfFewerThan
**Type**: `number`  
**Default**: `20`  
Number of items to auto expand tree.

##### branchNodesExpandOnClick
**Type**: `boolean`  
**Default**: `false`  
Determines if branch nodes expand on click.

##### branchNodesSelectable
**Type**: `boolean`  
**Default**: `false`  
Determines if branch nodes are selectable.

##### defaultToTreeEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if tree is the default view.

##### defaultToTreeIfGreaterThan
**Type**: `number`  
**Default**: `0`  
Number of items to default to tree view (when defaultToTreeEnabled = true; defaults to 0).

##### defaultToTreeIfCollection
**Type**: `boolean`  
**Default**: `true`  
Determines if collection should default to tree view (even if defaultToTreeEnabled = false).

##### elideCount
**Type**: `number`  
**Default**: `40`  
Number of characters to elide at.

##### expandFullEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if expand full is enabled.

##### galleryThumbChunkedResizingEnabled
**Type**: `boolean`  
**Default**: `true`                         
**Compatible file types**: Openseadragon only.                    
Determines if chunked resizing is enabled for gallery thumbnails.

##### galleryThumbChunkedResizingThreshold
**Type**: `number`  
**Default**: `400`                             
Threshold for chunked resizing of gallery thumbnails.

##### galleryThumbHeight
**Type**: `number`  
**Default**: `320`  
Height of the gallery thumbnail.

##### galleryThumbLoadPadding
**Type**: `number`  
**Default**: `3`  
Padding for loading gallery thumbnails.

##### galleryThumbWidth
**Type**: `number`  
**Default**: `200`  
Width of the gallery thumbnail.

##### oneColThumbHeight
**Type**: `number`  
**Default**: `320`  
Height of the one column thumbnail.

##### oneColThumbWidth
**Type**: `number`  
**Default**: `200`  
Width of the one column thumbnail.

##### pageModeEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if page mode is enabled.

##### panelAnimationDuration
**Type**: `number`  
**Default**: `250`              
Determines the duration of the panel expand/collapse animation.

##### panelCollapsedWidth
**Type**: `number`  
**Default**: `30`  
Width of the collapsed panel.

##### panelExpandedWidth
**Type**: `number`  
**Default**: `255`  
Width of the expanded panel.

##### panelOpen
**Type**: `boolean`  
**Default**: `true`  
Determines if the panel is open.

##### tabOrder
**Type**: `string`  
**Default**: ``  
Order of the tabs. 

##### thumbsCacheInvalidation
  ###### enabled
  **Type**: `boolean`  
  **Default**: `true`  
  ###### paramType
  "?"                             
Configuration for thumbs cache invalidation

##### thumbsEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if thumbnails are enabled. 

##### thumbsExtraHeight
**Type**: `number`  
**Default**: `8`  
Extra height for thumbnails. 

##### thumbsImageFadeInDuration
**Type**: `number`  
**Default**: `300`  
Duration for thumbnails image fade in. 

##### thumbsLoadRange
**Type**: `number`  
**Default**: `15`  
Load range for thumbnails. 

##### topCloseButtonEnabled
**Type**: `boolean`  
**Default**: `false`  
If the top button is enabled, add an additional close button for consistency.

##### treeEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if tree is enabled. 

##### twoColThumbHeight
**Type**: `number`  
**Default**: `150`  
Height of the two column thumbnail.

##### twoColThumbWidth
**Type**: `number`  
**Default**: `90`  
Width of the two column thumbnail.

#### Dialogue

##### topCloseButtonEnabled
**Type**: `boolean`  
**Default**: `false`  
If the top button is enabled, add an additional close button for consistency.

#### downloadDialogue

##### confinedImageSize
**Type**: `number`  
**Default**: `1000`  
Size of the confined image.

##### currentViewDisabledPercentage
**Type**: `number`  
**Default**: `90`  
Percentage of the current view that is disabled.

##### downloadCurrentViewEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if download of current view is enabled.

##### downloadWholeImageHighResEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if download of whole image in high resolution is enabled.

##### downloadWholeImageLowResEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if download of whole image in low resolution is enabled.

##### maxImageWidth
**Type**: `number`  
**Default**: `5000`  
Maximum width of the image.

##### optionsExplanatoryTextEnabled
**Type**: `boolean`  
**Default**: `false`  
Determines if explanatory text for options is enabled.

##### selectionEnabled
**Type**: `boolean`  
**Default**: `false`  
Determines if selection is enabled.

#### footerPanel

##### bookmarkEnabled
**Type**: `boolean`  
**Default**: `false`  
Determines if bookmarking is enabled.

##### downloadEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if downloading is enabled.

##### embedEnabled
**Type**: `boolean`  
**Default**: `false`  
Determines if embedding is enabled.

##### feedbackEnabled
**Type**: `boolean`  
**Default**: `false`  
Determines if feedback is enabled.

##### fullscreenEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if fullscreen mode is enabled.

##### minimiseButtons
**Type**: `boolean`  
**Default**: `true`  
Determines if buttons are minimised.

##### moreInfoEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if more information is enabled.

##### openEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if opening is enabled.

##### printEnabled
**Type**: `boolean`  
**Default**: `false`  
Determines if printing is enabled.

##### shareEnabled
**Type**: `boolean`  
**Default**: `true`  
Determines if sharing is enabled.
