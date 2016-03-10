# ProcessPageCloneAdaptUrls
ProcessWire module that adapts links and img sources in CKEditor fields when cloning a page.

## Usage

Make sure that ProcessPageClone is installed. Simply extract the zip package into site/modules, select "Modules" => "Refresh" in the menu and install this module.

### How it works

When you clone a page, you'll notice a few additional messages at the top:

![Messages Image](https://bitpoet.github.io/img/ppcau-messages.png)

If you clone whole page trees at once, only the configured number of pages is adapted at once. This is to prevent running into memory or time limits. You can change this value (default 50) in the module's settings, but be careful with it!

The message at the top shows you how many pages were updated and how many pages were cloned in total. You can see the pending updates in their own admin page and trigger the next update task from there:

![Menu Image](https://bitpoet.github.io/img/ppcau-adminmenu.png)

![Admin Page](http://bitpoet.github.io/img/ppcau-adminpage.png)

## Status

Alpha

This is a major change to the original module (version < 0.0.5) and needs thorough testing.

### Issues / Todos

Currently, permissions are not really checked. This is a major bummer for the admin page and on top of the todo list.

## License

Released under Mozilla Public License (MPL v2). See the LICENSE file for details.

## Caveats

This module is still beta, but you can help out testing it and leaving feedback.

## Author

Written 2016 by BitPoet
