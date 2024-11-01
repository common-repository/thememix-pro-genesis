# Genesis Pro by ThemeMix

* Contributors: thememix, defries
* Tags: genesis, page templates, genesis compatibility, genesis, thememix
* Requires at least: 4.3
* Tested up to: 4.9
* Version: 1.0.6
* Stable tag: 1.0.6
* License: GPLv2 or later
* License URI: http://www.gnu.org/licenses/gpl-2.0.html

A plugin that enhances, adds, modifies or removes certain elements of the Genesis Framework.

## Description

This plugin currently has the following features:

### Page Templates

Genesis Pro by ThemeMix adds the following page templates:

* Login Page
* Private Page
* Beaver Builder Full Width

### Genesis Compatibility

There are numerous plugins out there that help Genesis play nice with plugins that featured rich custom post types. Most, if not all, of these plugins area quite old or still depend on old configuration. We've gone ahead and rewritten current solution to a more modern approach of what we think Genesis Compatibility should looks like. No bloat, only loading what is necessary to make Genesis play nice.

By activating Genesis Pro by ThemeMix you'll have Genesis play nice with the following plugins:

* BuddyPress
* bbPress
* WooCommerce
* Easy Digital Downloads

### Genesis Featured Content

We've added an up to date Genesis Featured Content widget that is based on the various solutions out there, but made more modern. We've also, as a bonus, made it compatible with displaying featured BuddyPress Groups.

#### Features:

* Featured Content (Posts, Pages, Custom Post Types)
* FontAwesome Icon selector integration
* BuddyPress Group as Featured Page selector

This feature currently is still in beta, but we believe it to be stable enough to use on your live site.

## Installation

1. Upload the plugin files to the `/wp-content/plugins/plugin-name` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Use the Settings->Plugin Name screen to configure the plugin
4. (Make your instructions match the desired user flow for activating and installing your plugin. Include any steps that might be needed for explanatory purposes)

## Frequently Asked Questions

#### What are some of your features you have on your roadmap

Glad you asked. Our internal roadmap is not public (yet), but we sure are curious what you think this plugin should offer. Find us on [twitter](https://twitter.com/thememix/) and let us know!

#### How can I update the list of Font Awesome icons in the widget

Upgrading to the latest version of the plugin should fix this, although there is also an advanced setting which allows you to manually update it by going to /wp-admin/?generate-font-awesome=yes whilst logged in as an administrator. Note that any changes you make will be wiped out during the next plugin update, but those changes will likely be included in the new version anyway.

### Where can I follow development and report bugs?

Head over to our [Github repo](https://github.com/thememix/thememix-pro-genesis) if you'd like to contribute or create an issue.

## Changelog

### 1.0.6
* Temporarily fixing checkboxes being uncheckable. This change will break the checkboxes being autosaved for the Featured Content Widget. Props @mbootsman

= 1.0.5 = 
* Adding page templates for Full Width Beaver Builder pages and posts

### 1.0.4 
* Fixing FontAwesome Size selection
* Fixing bug which prevented posts from being linked to hard coded URL
* Adding correct number of %s's to allow for closing links 

### 1.0.3
* Fixing BuddyPress related PHP notices in the Customizer

### 1.0.2

* Fixing bug/fatal error when the plugin was activated but the theme switched away from Genesis.
* Fixing bug where the color set for the selected font icon wasn't reflected in the output.
* Fixing bug where the icon font selector didn't display previous and next button to access the full set.
* Fixing bug where the Featured Content Widget was not displayed properly within the context of the Customizer. Todo: make the font icon selector work as intended in the Customizer as well.
* Updating to FontAwesome  4.6.3.
* Adding FontAwesome updater seperate from plugin update.
* Fixing prefixes and namespaces to be more congruent.

### 1.0.1

* Fixing activation function clashing with Genesis Translations plugin.

### 1.0.0

* Adding Genesis Compatibility layer
* Adding extra page template
* Bug fixes


### 0.9

* Bug fixing and code cleanup.

### 0.3

* Adding of Font Awesome functionality to the featured content widget.
* Adding of BuddyPress Groups functionality to the featured content widget.

### 0.2

* Adding featured content widget.

### 0.1.0

* Into the light I command thee!
* Adding page template functionality.