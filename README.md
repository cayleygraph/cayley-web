# Cayley Web interface

<img src="img/screens/s01.png?raw=true" alt="UI" />

# Hacking

## Install the Polymer-CLI

First, install bower dependencies `bower install` and make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing

```
$ polymer serve
```

## Building

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```
