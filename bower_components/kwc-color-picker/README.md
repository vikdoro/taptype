# \<kwc-color-picker\>

Tile based color picker with customizable palette

 - What is it called?
     - kwc-color-picker
 - What is it made out of?
     - A set of colored tiles that when clicked, provides a selected value
 - What variants are needed?
     - Idle: hover styling is still here, but no selection is possible
     - Tiles: Different sizes and margin between them
 - How does it scale?
     - Tiles size are defined in pixels, and the rowSize defines the total width
 - What style variables are in use?
     - Colors: The list of colors available for selection
     - Outline: Can customize the style of the outline when over a light or dark color
- Anything to keep in mind?
     - If the display state of the element changes (i.e. it gets hidden/unhidden), you need to call notifyResize, otherwise the element will not properly render.

## Installation
Clone this repository.
Run `bower i`

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test --skip-plugin junit-reporter
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
