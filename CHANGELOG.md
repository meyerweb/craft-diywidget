# Changelog

## 2.0.1 - 2018-05-29

### Changed
- The plugin now removes all DIY widgets that were installed under Craft 2 from the dashboards when it gets installed.

## 2.0.0 - 2018-05-29

### Added
- Added Craft 3 compatibility.

### Changed
- Each widget is now it’s own widget type and can be added to the Dashboard by selecting it from the “New widget” dropdown.
- Each widget can now provide its own icon.

## 1.2.1 - 2016-07-24

### Added
- Added plugin and widget icons.

## 1.2.0 - 2016-07-24

### Added
- Added a very basic “Welcome” example widget.

### Changed
- Made some UI improvements to the “Search” example widget, a spinner is now shown while results are loading.

### Fixed
- The “Recent Assets” example widget now really shows the latest assets.
- The widget’s ID passed in to the templates doesn’t contain the word `widget` any longer.
- The `Craft.DiyWidget` object is now only created in the example Javascripts if it doesn’t already exist.

## 1.1.0 - 2016-07-23

### Added
- Added a new “Entry Search” example widget.
- Added a `getHtml` controller action to request the templates using Ajax.

### Changed
- Templates starting with an underscore are no longer listed in the widget settings.

## 1.0.0 - 2016-07-22

### __other__
- First release
