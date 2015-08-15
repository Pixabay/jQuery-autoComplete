jQuery-autoComplete
===================

An extremely lightweight completion suggester plugin for jQuery.

Compatible with jQuery 1.7.0+ in Firefox, Safari, Chrome, Opera, Internet Explorer 7+. No dependencies except the jQuery library.
Released under the MIT License: http://www.opensource.org/licenses/mit-license.php

This plugin was developed by and for [Pixabay.com](https://pixabay.com/) - an international repository for sharing free public domain images.
We have implemented this plugin in production and we share this piece of software - in the spirit of Pixabay - freely with others.

## Demo and Documentation

https://goodies.pixabay.com/jquery/auto-complete/demo.html

## Features

* Lightweight: 3.4 kB of JavaScript - less than 1.4 kB gzipped
* Fully flexible data source
* Smart caching, delay and minimum character settings
* Callbacks

## Changelog

### Version 1.0.7 - 2015/08/15

* Fixed #29: Select item with tab.
* Fixed #33: Suggestions not hidden on fast input.
* Fixed incorrect selection by mouse when suggestions are scrolled down.

### Version 1.0.6 - 2015/04/22

* Fixed #7: Firing onSelect callback on enter and passing event and selected suggestion item as additional arguments.

### Version 1.0.5 - 2014/11/26

* Fixed #4: renderItem bugfix

### Version 1.0.4 - 2014/11/26

* Added renderItem function options allowing custom data passing and autoComplete rendering (https://github.com/Pixabay/jQuery-autoComplete/pull/3).
* Improved auto positioning.

### Version 1.0.3 - 2014/11/17

* Added menuClass option for custom styling multiple autoComplete dropdowns on one page.
* Fixed destroy method.

### Version 1.0.2 - 2014/09/13

* Another fix of the auto-positioning method on init.

### Version 1.0.1 - 2014/08/10

* Fixed auto positioning of suggestions container on init.

### Version 1.0.0-beta - 2014/07/15

* First release
