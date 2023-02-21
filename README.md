# pcf-rtf-to-html-label
Power Platform Component Framework Custom Control to display Rich Text Format as HTML in a label

## Overview
This control is for display purposes only, it will show a label with the given Rich Text Format. The text provided is parsed if possible from RTF using the [rtf.js](https://www.npmjs.com/package/rtf.js) npm module, if the given text is not valid RTF, it will be displayed as provided with a prefix warning indicating it **Not valid RTF text**.

## Usage
- [Import solution into your Power Apps Environment](https://learn.microsoft.com/en-us/power-apps/maker/data-platform/import-update-export-solutions), don't forget to Publish customizations if you are upgrading it
- [Import the control into your Power App Canvas App](https://learn.microsoft.com/en-us/power-apps/developer/component-framework/component-framework-for-canvas-apps#add-components-to-a-canvas-app)
- Insert control where needed and assign data to it
