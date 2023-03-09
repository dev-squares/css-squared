# Quick Start #

Before starting remember these rules:

* Never add, edit, or delete files, or directories, inside either of the core directories
* Never add, edit, or delete the css-squared.scss file
* Add all custom files and directories into the root of the css-squared directory. Examples:
    * /css-squared/_custom-file.scss
    * /css-squared/custom-directory/_custom-file.scss
* Import all custom files using the _app-all.scss file that will be created during this quick start process.

## Step 1. Installation ##

Pull this respository as a subtree (recommended), or download as a zip, and install to /path/to/app/css/resources/css-squared

## Step 2. Create Required Files ##
Create the following two required files in the root of the css-squared directory:

* _app-all.scss
* _app-variables.scss

These files will contain or import all custom variables and styles.

## Step 3. Variables ##
* Add custom variables (or override core variables), inside _app-variables.scss

## Step 4. Create and Import Custom Files ##
* Add all custom files and directories into the root of the css-squared directory. Examples:
    * /css-squared/_custom-file.scss
    * /css-squared/custom-directory/_custom-file.scss
* Import all custom files inside the _app-all.scss file.
* Additionally import any of the optional core files listed in Step 5 inside the _app-all.scss file.

## Step 5. Optional Core Files  ##
To use any of the below optional core files add the import snipper to the _app-all.scss file.
### Frameworks ###
* @import "./core-optional/wordpress/all";

### JS-Squared ###
* @import "./core-optional/js-squared/all";

### Mixins - SVG Icons ###
* @import "./core-optional/mixins/";
* @import "./core-optional/mixins/svg-icon-chevron";
* @import "./core-optional/mixins/svg-icon-article-stack";
* @import "./core-optional/mixins/svg-icon-cloud-fill";
* @import "./core-optional/mixins/svg-icon-cloud-outline";
* @import "./core-optional/mixins/svg-icon-copy";
