# GUID plugin for Craft CMS

## Installation

To install GUID, follow these steps:

1. Download & unzip the file and place the `guid` directory into your `craft/plugins` directory
2.  -OR- do a `git clone https://github.com/romainpoirier/guid.git` directly into your `craft/plugins` folder.  You can then update it with `git pull`
3.  -OR- install with Composer via `composer require /guid`
4. Install plugin in the Craft Control Panel under Settings > Plugins
5. The plugin folder should be named `guid` for Craft to see it.  GitHub recently started appending `-master` (the branch name) to the name of the folder for zip file downloads.

GUID works on Craft 2.4.x and Craft 2.5.x.

## Using GUID

{{ getUUID() }}

## Changelog

### 1.0.0 -- 2017.09.28

* Initial release