## Drop

[![npm
version](https://badge.fury.io/js/tether-drop.svg)](http://badge.fury.io/js/tether-drop)
[![Bower
version](https://badge.fury.io/bo/tether-drop.svg)](http://badge.fury.io/bo/tether-drop)

Drop.js is a powerful Javascript and CSS library for creating dropdowns and other floating displays.

[![Drop Docs](http://i.imgur.com/sgmx9aJ.png)](http://github.hubspot.com/drop/)


## Install

__Dependencies__

* __[Tether](https://github.com/HubSpot/tether)__

Installing via `npm` and `bower` will bring in the above dependencies as well.


__npm__
```sh
$ npm install tether-drop
```

__bower__
```sh
$ bower install tether-drop
```

## Usage

```javascript
let dropInstance = new Drop({
  target: document.querySelector('.drop-target'),
  content: 'Welcome to the future',
  classes: 'drop-theme-arrows',
  position: 'bottom left',
  openOn: 'click'
})
```

[API documentation](http://github.hubspot.com/drop)

[Demo](http://github.hubspot.com/drop/docs/welcome)


## Contributing

We encourage contributions of all kinds. If you would like to contribute in some way, please review our [guidelines for contributing](CONTRIBUTING.md).


## License
Copyright &copy; 2015 HubSpot - [MIT License](LICENSE)
