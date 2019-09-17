# ignite-karaoke
Tool for running Ignite Karaokes

## About

This repo provides tools to allow someone to run a series of Ignite Karaokes.

Ignite Karaokes follow the [Ignite (Enlighten us, but make it quick)](http://www.ignitetalks.io/) format -- 20 slides, each slide is up for 15 seconds. But with a twist... you don't know what slides will appear!

## Thanks and Credits

> "If I have seen further it is by standing on the shoulders of Giants." -- Isaac Newton

It is built on the shoulders of:

* [hakimel/reveal.js: The HTML Presentation Framework](https://github.com/hakimel/reveal.js#slide-backgrounds)
* [slara/generator-reveal: Yeoman generator for Reveal.js](https://github.com/slara/generator-reveal)
* [Unsplash - The internet's source of freely usable images.](https://unsplash.com)

## Configuration

1. In order to run this, you need `npm`, `grunt`, and `bower` installed.
2. The script which randomizes things requires `bash` and `shuf`
3. Execute the following: `npm install && bower install`
4. Copy image files into `resources/images/ignite`; you need at least 20. The more the better! There are some sample files in the directory.

## Usage

1. Start the server with `grunt serve`
2. In the lower left, click on the "play" button to start. The first slide will be up for 5 seconds, afterwards there are 20 slides which are up for 15 seconds each.
3. To refresh and rewind, execute the `refill.sh` script.
