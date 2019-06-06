# Chairtime

A small HTML only application to display remaining time to speakers at
conferences, workshops etc.

Based on [reveal.js](http://revealjs.com/) to be fully customizable.

## Usage

Doubleclick on slide to enter fullscreen mode (usefull on tablets and
smartphones).

Hit "s" to open notes view with timers.

This might be extended with auto-sliding and multiplexing for remote control,
see [upstream project](https://github.com/hakimel/reveal.js).

You might either use it directly from https://poikilotherm.github.io/chairtime
if the default timeframe of 20 minutes suits your needs.

When you want custom time, simply edit the `data-timing` attribute of the
first slide. You need to copy the folders mentioned below plus `index.html`
to some kind of webserver (or open locally in your browser).

## Folder Structure

- **css/** Core styles without which the project does not function
- **js/** Like above but for JavaScript
- **plugin/** Components that have been developed as extensions to reveal.js
- **lib/** All other third party assets (JavaScript, CSS, fonts)

## License

Apache 2.0

Copyright (C) 2019 Oliver Bertuch
