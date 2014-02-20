*This repository is a mirror of the [component](http://component.io) module [juliangruber/find-urls](http://github.com/juliangruber/find-urls). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/juliangruber-find-urls`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# find-urls

  Find all urls in a text

## Example

```js
var find = require('find-urls');

var urls = find('Some http://google.com/ and http://segment.io.');
// => ['http://google.com/', 'http://segment.io']
```

## Installation

  Install with [component(1)](http://component.io):

    $ component install juliangruber/find-urls

## API

### find(text)

  Return an array of urls inside `text`.
  
  Duplicates are removed and urls that end with punctuation are cleaned up.

## License

  MIT
