# \<vip-aersia-player\>

A Polymer player for vip.aersia.net

##Why?

Basically I'm building a relatively simple application to try and learn Polymer.

In this specific application, Polymer allows me to spend less time messing with CSS or Javascript due to the available components: the graphical elements were basically already done, the styling is mostly done with mixins, using ajax to get the playlist data was easy due to a component and data binding made syncing the music list and the player reasonably easy.

##Issues

Due to poor Javascript and Polymer skills, the following issues exist:

* Scrolling is poorly done (doesn't works for first song, forces the selected element to top)
* Controls are always to the right on all devices

##TODO

* Redo scrolling, preferably with a WebComponent
* Implement seek bar
* Implement volume control

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
