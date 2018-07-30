# way-of-sunvox.github.io

## About

This repo hosts the site Way of SunVox, which is a resource for the music making application SunVox.

## Building

This site uses Gulp and Nunjucks to build and modularize repeated sections into partials so you'll need to install those to build it. Currently github pages reads from the root level only (unless its a project site which this isn't), so there's no `dist` folder. Instead, you work out of the `app` folder, and when you run gulp, the root level site will be automatically generated/updated.
