# nxjs

A JavaScript library that contains several packages to be used in all the various nx projects. (It has dependencies that should be included before it is itself)

## Setup

This library will be exposed as a var available in `<script/>` tags after it is imported in its own script tag. It is intended to be included in the `<head/>` of the html file; in this case, I include it there because it is an expected global in all the nx projects as it is used commonly and doesn't have to be manually imported in each module in the bundle.js file.

Webpack Library Building Link:
[https://webpack.js.org/guides/author-libraries/](https://webpack.js.org/guides/author-libraries/)

Webpack will be used to create this library.
