ember-renderspeed
=================

A script for instrumenting rendering speed in an Ember.js Application.

## Installation

You can install ember-renderspeed using [Bower](http://bower.io/):

```
bower install ember-renderspeed --save-dev
```

(Or if you wish, simply download the script from github and put it in your project.)

## Usage

Include the script in your Ember.js project. Open your developer log and you'll
see a nice expandable graph of rendering speeds:

![ember-renderspeed screenshot](http://eviltrout.com/images/ember-renderspeed.png)

You can use it to figure out what bits of rendering are taking the longest.

### Ember-CLI

```javascript
// ember-cli-build.js
if (app.env === 'development') {
  app.import('bower_components/ember-renderspeed/ember-renderspeed.js');
}
```

## Authors

[Robin "Evil Trout" Ward](http://eviltrout.com)


## License

MIT





