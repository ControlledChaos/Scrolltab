Scrolltab is a jQuery plugin that adds tabs visually associated to their position relative to the scroll bar.

This enables a developer to attach floating tabs to the scrollbar of the brwoser that will scroll the user to the position indicated by the tab.  This tab is expandable with content within.

## Demo

http://chris-saylor.com/Scrolltab/example.html

## Examples

```javascript
	// Enables a pin with the default classname
	$('<dom object>').scrolltab();

	// Changes the classname of the created (or existing) pin
	$('<dom object>').scrolltab({ classname: 'test' });
```

## Options

* `title`: HTML to display within the pin
* `classname`: The classname for the pin to use
* `mouseenter`: function to execute when the mouseenter event fires on this pin
* `mouseleave`: function to execute when the mouseleave event fires on this pin
* `click`: function to execute when the click event fire on this pin

## Build

Scrolltab uses Grunt for linting and building the minified production file.

### Requirements

* NodeJS

#### Setup

Install grunt cli globally:

`$ npm install -g grunt-cli`

Install dev dependencies:

`$ npm install -d`

Execute lint and build:

`$ grunt`

## License

This software is protected under the MIT license.
