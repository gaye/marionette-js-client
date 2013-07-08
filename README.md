# Marionette JS Client

JavaScript client for
[Marionette](https://developer.mozilla.org/en-US/docs/Marionette).

Designed to run on nodejs & xpcshell.

- [Api Docs](http://lightsofapollo.github.com/marionette_js_client/api-docs/)

## Hacking

### Install

Fork repo

``` sh
npm install .
```

### Tests

Tests are written in [Mocha](https://github.com/visionmedia/mocha) / [Chai](http://chaijs.com/)


Node:

``` sh
make test-node
```

Browser:

``` sh
make package
make test-server
# GOTO: http://localhost:8789/test-agent/index.html in your browser

make test-browser
# you can also use
# "make test" to run both node and browser tests.
```

### Documentation

The landing page is autogenerated from this README.md file.
API documentation is made using yuidocjs. 

The `make doc-server` / `make doc-publish` are used to preview and publish content.

### Reviwers

Find us on irc.mozilla.org in the #gaia channel.

irc: gaye - Gareth Aye
irc: mhenretty - Michael Henretty - mikehenrty (github)
irc: lightsofapollo - James Lal
