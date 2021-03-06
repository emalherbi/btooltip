# [BTooltip](http://emalherbi.github.io/btooltip/)

[![Bower](https://img.shields.io/bower/v/bootstrap.svg)](https://github.com/emalherbi/btooltip/)
[![Build Status](https://travis-ci.org/emalherbi/btooltip.svg?branch=master)](https://travis-ci.org/emalherbi/btooltip)
[![status](https://sourcegraph.com/api/repos/github.com/emalherbi/btooltip/.badges/status.svg)](https://sourcegraph.com/github.com/emalherbi/btooltip)
[![views](https://sourcegraph.com/api/repos/github.com/emalherbi/btooltip/.counters/views.svg)](https://sourcegraph.com/github.com/emalherbi/btooltip)
[![views 24h](https://sourcegraph.com/api/repos/github.com/emalherbi/btooltip/.counters/views-24h.svg)](https://sourcegraph.com/github.com/emalherbi/btooltip)

The BTooltip plugin JS, created for destroy [tooltip bootstrap](http://getbootstrap.com/javascript/#tooltips) automatically!
<img align="right" height="150" src="http://bower.io/img/bower-logo.png">

## Bower.io

This package is available on Bower.

#### Installing

```sh
# install a package and add it to bower.json
$ bower install btooltip --save
```

#### Install Bower.io

```sh
$ npm install -g bower
```

Bower depends on [Node.js](http://nodejs.org/) and [npm](http://npmjs.org/). Also make sure that [git](http://git-scm.com/) is installed as some bower
packages require it to be fetched and installed.

## Usage

```javascript
$('#input').btooltip({title : 'msg', placement: 'right'});
```

## Options

```
@param placement | type : string  | default : top  | how to position the popover - top | bottom | left | right
@param title     | type : string  |                | default title value if `title` tag isn't present
@param destroy   | type : boolean | default : true | destroy tooltip or not
@param time      | type : number  | default : 2000 | time to tooltip destroy (miliseconds)
```

## Required

[jQuery](http://jquery.com/). [Bootstrap](http://getbootstrap.com/).

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Test your changes to the best of your ability.
4. Update the documentation to reflect your changes if they add or changes current functionality.
5. Commit your changes (`git commit -am 'Added some feature'`)
6. Push to the branch (`git push origin my-new-feature`)
7. Create new Pull Request

## Creator

Created and maintained by [Eduardo Malherbi](https://github.com/emalherbi).

## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
