
<!-- TITLE/ -->

# pipe action for [ChainyJS](http://chainyjs.org)

<!-- /TITLE -->


<!-- BADGES/ -->

[![Build Status](http://img.shields.io/travis-ci/chainy-plugins/chainy-plugin-pipe.png?branch=master)](http://travis-ci.org/chainy-plugins/chainy-plugin-pipe "Check this project's build status on TravisCI")
[![NPM version](http://badge.fury.io/js/chainy-plugin-pipe.png)](https://npmjs.org/package/chainy-plugin-pipe "View this project on NPM")
[![Dependency Status](https://david-dm.org/chainy-plugins/pipe.png?theme=shields.io)](https://david-dm.org/chainy-plugins/pipe)
[![Development Dependency Status](https://david-dm.org/chainy-plugins/pipe/dev-status.png?theme=shields.io)](https://david-dm.org/chainy-plugins/pipe#info=devDependencies)<br/>
[![Gittip donate button](http://img.shields.io/gittip/bevry.png)](https://www.gittip.com/bevry/ "Donate weekly to this project using Gittip")
[![Flattr donate button](http://img.shields.io/flattr/donate.png?color=yellow)](http://flattr.com/thing/344188/balupton-on-Flattr "Donate monthly to this project using Flattr")
[![PayPayl donate button](http://img.shields.io/paypal/donate.png?color=yellow)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=QB8GQPZAH84N6 "Donate once-off to this project using Paypal")
[![BitCoin donate button](http://img.shields.io/bitcoin/donate.png?color=yellow)](https://coinbase.com/checkouts/9ef59f5479eec1d97d63382c9ebcb93a "Donate once-off to this project using BitCoin")
[![Wishlist browse button](http://img.shields.io/wishlist/browse.png?color=yellow)](http://amzn.com/w/2F8TXKSNAFG4V "Buy an item on our wishlist for us")

<!-- /BADGES -->


<!-- CHAINY_DOCUMENTATION/ -->

<!-- DESCRIPTION/ -->

Chainy action that pipes the chain's data to a writable stream

<!-- /DESCRIPTION -->


Note: Despite pipe calls usually returning the piped stream, this plugin, like all the other chainy actions, returns the chain.

``` javascript
require('chainy').create().require('set pipe')
	.set('some data')
	.pipe(
		require('fs').createWriteStream(process.cwd()+'/out.txt')
	)  // will write "some data" to the file "out.txt"
```

<!-- /CHAINY_DOCUMENTATION -->


<!-- INSTALL/ -->

## Install

### [NPM](http://npmjs.org/)
- Use: `require('chainy-plugin-pipe')`
- Install: `npm install --save chainy-plugin-pipe`

### [Browserify](http://browserify.org/)
- Use: `require('chainy-plugin-pipe')`
- Install: `npm install --save chainy-plugin-pipe`
- CDN URL: `//wzrd.in/bundle/chainy-plugin-pipe@1.0.1`

### [Ender](http://ender.jit.su/)
- Use: `require('chainy-plugin-pipe')`
- Install: `ender add chainy-plugin-pipe`

<!-- /INSTALL -->


<!-- HISTORY/ -->

## History
[Discover the change history by heading on over to the `HISTORY.md` file.](https://github.com/chainy-plugins/chainy-plugin-pipe/blob/master/HISTORY.md#files)

<!-- /HISTORY -->


<!-- CONTRIBUTE/ -->

## Contribute

[Discover how you can contribute by heading on over to the `CONTRIBUTING.md` file.](https://github.com/chainy-plugins/chainy-plugin-pipe/blob/master/CONTRIBUTING.md#files)

<!-- /CONTRIBUTE -->


<!-- BACKERS/ -->

## Backers

### Maintainers

These amazing people are maintaining this project:

- Benjamin Lupton <b@lupton.cc> (https://github.com/balupton)

### Sponsors

No sponsors yet! Will you be the first?

[![Gittip donate button](http://img.shields.io/gittip/bevry.png)](https://www.gittip.com/bevry/ "Donate weekly to this project using Gittip")
[![Flattr donate button](http://img.shields.io/flattr/donate.png?color=yellow)](http://flattr.com/thing/344188/balupton-on-Flattr "Donate monthly to this project using Flattr")
[![PayPayl donate button](http://img.shields.io/paypal/donate.png?color=yellow)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=QB8GQPZAH84N6 "Donate once-off to this project using Paypal")
[![BitCoin donate button](http://img.shields.io/bitcoin/donate.png?color=yellow)](https://coinbase.com/checkouts/9ef59f5479eec1d97d63382c9ebcb93a "Donate once-off to this project using BitCoin")
[![Wishlist browse button](http://img.shields.io/wishlist/browse.png?color=yellow)](http://amzn.com/w/2F8TXKSNAFG4V "Buy an item on our wishlist for us")

### Contributors

These amazing people have contributed code to this project:

- [Benjamin Lupton](https://github.com/balupton) <b@lupton.cc> — [view contributions](https://github.com/chainy-plugins/pipe/commits?author=balupton)

[Become a contributor!](https://github.com/chainy-plugins/chainy-plugin-pipe/blob/master/CONTRIBUTING.md#files)

<!-- /BACKERS -->


<!-- LICENSE/ -->

## License

Licensed under the incredibly [permissive](http://en.wikipedia.org/wiki/Permissive_free_software_licence) [MIT license](http://creativecommons.org/licenses/MIT/)

Copyright &copy; 2014+ Bevry Pty Ltd <us@bevry.me> (http://bevry.me)

<!-- /LICENSE -->


