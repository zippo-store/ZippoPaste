# ZippoPaste

ZippoPaste is inspired by Haste, Haste is an open-source pastebin software written in node.js, which is easily
installable in any network.  It can be backed by either redis or filesystem,
and has a very easy adapter interface for other stores.  A publicly available
version can be found at [hastebin.com](http://hastebin.com)

Major design objectives:

* Be really pretty
* Be really simple
* Be easy to set up and use

Haste works really well with a little utility called
[haste-client](https://github.com/seejohnrun/haste-client), allowing you
to do things like:

`cat something | haste`

which will output a URL to share containing the contents of `cat something`'s
STDOUT.  Check the README there for more details and usages.

## Tested Browsers

* Firefox 8
* Chrome 17
* Safari 5.3

## Installation

1.  Download the package, and expand it
2.  Explore the settings inside of config.js, but the defaults should be good
3.  `npm install`
4.  `npm start` (you may specify an optional `<config-path>` as well)
