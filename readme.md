# Intro #

CSS-Squared is intended to be a super lightweight CSS modifier framework that is both simple and quick to customise. There is no relearning how everything is meant to work (assuming you have knowledge of CSS and SCSS), or additional package manager requirements such as node/npm.

The 'core' by itself comes in at approximately 6kb in size when minified, truly lightweight, and includes basic variables so you can get started straight away.

I will attempt to get around to writing documentation soon. But given it's simple nature it kind of explains itself!

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
* Add custom variables (or override core variables), in _app-variables.scss

## Step 4. Create and Import Custom Files ##
* Add all custom files and directories into the root of the css-squared directory. Examples:
    * /css-squared/_custom-file.scss
    * /css-squared/custom-directory/_custom-file.scss
* Import all custom files in the _app-all.scss file.
* Additionally import any of the optional core files listed in Step 5 in the _app-all.scss file.

## Step 5. Optional Core Files  ##

Add the import snippet for any of the following optional core files that you wish to use in _app-all.scss.

### Frameworks ###

* @import "./core-optional/wordpress/all";

### JS-Squared ###

* @import "./core-optional/js-squared/all";