[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/arsnebula/nebula-radio)

[![Build Status](https://saucelabs.com/browser-matrix/arsnebula.svg)](https://saucelabs.com/beta/builds/c75ef10b869e46dab8a80bd4efecb2d7)

# \<nebula-radio\>

A web component to display a group of radio buttons.

* Elegant ghost-style radio buttons
* Customizable button icons
* Easily customized using CSS variables, mixins or style attributes
* Looks great on a light or dark background
* Consistent visual presentation across all browsers
* Supports [WAI-ARIA](https://www.w3.org/TR/wai-aria-practices-1.1/#radiobutton) authoring practices for **a11y**

## Installation

```
$ bower install -S arsnebula/nebula-radio
```

## Usage

Import the element:

```html
<link rel="import" href="/bower_components/nebula-radio/nebula-radio.html"> 
```

Add and configure the element.

```html
<nebula-radio-group direction="vertical" value="{{radioGroupValue}}">
  <nebula-radio-button value="orange" checked>Orange</nebula-radio-button>
  <nebula-radio-button value="banana">Banana</nebula-radio-button>
  <nebula-radio-button value="apple">Apple</nebula-radio-button>
</nebula-radio-group>
```

*For more information on element properties and methods see the element API documentation.*

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Change Log

See [CHANGELOG](/CHANGELOG.md)

## License

See [LICENSE](/LICENSE.md)