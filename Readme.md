*This repository is a mirror of the [component](http://component.io) module [code42day/ua](http://github.com/code42day/ua). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/code42day-ua`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# ua

  [Google Universal Analytics][gua] tracking snippet

## Installation

    $ component install code42day/ua

## API

  Activate Google Analytics on the page and track page

    require('ua')("UA-XXXX-X");

  Alternatively you can define ua property ID as a data attribute of document body

  	<body data-ua-property-id="UA-XXXX-X">

  Check [test/index.html](https://github.com/code42day/ua/blob/master/test/index.html) for example.

## License

  MIT

[gua]: https://support.google.com/analytics/answer/2790010?hl=en
