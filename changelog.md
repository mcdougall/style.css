# style.css change log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## Unreleased

### Additions

- pull major settings out into overridable variables

    ```scss
    $font-size-body:    16px !default;
    $font-size-code:    12px !default;
    $font-size-scale:   0.25vw !default;
    $line-height-body:  1.55em !default;
    $line-height-pre:   1.45em !default;
    $link-color:        steelblue !default;
    $layout-width:      42em !default;
    ```

### Changes

- switch link color to `steelblue`

### Breaking changes

- `$link` renamed to `$link-color`

## [1.0.0-alpha-2](https://github.com/ungoldman/style.css/releases/v1.0.0-alpha-2) - 2016-09-16

[view diff](https://github.com/ungoldman/style.css/compare/v1.0.0-alpha-1...v1.0.0-alpha-2)

- use liberation sans for linux, change font stack ordering
- use autoprefixer
- updates to style guide, docs
- remove minified version
- add banner to dist file

## [1.0.0-alpha-1](https://github.com/ungoldman/style.css/releases/v1.0.0-alpha-1) - 2016-09-12

[view diff](https://github.com/ungoldman/style.css/compare/v1.0.0-alpha...v1.0.0-alpha-1)

- bump for faulty npm publish

## [1.0.0-alpha](https://github.com/ungoldman/style.css/releases/v1.0.0-alpha) - 2016-09-12

### TOTAL REWRITE!

`style.css` is now a classless stylesheet for markdown documents.

### Features

- **minimal size:** weighs in at an adorable `5kb` when minified.
- **system fonts:** looks native on macOS, iOS, windows, linux, firefox OS, android.
- **great for text:** designed to be highly readable and easy on the eyes.
- **very small api:** with zero classes, there's nothing to learn!
- **omakase:** composed out of a balanced selection of stylistic practices.
- **very stylish:** indeed.

---

## 0.1.16
* add `style` field for better [css-via-npm](https://github.com/sethvincent/css-via-npm) support
* add `main` field and blank `index.js` for parcelify
* bump `node-sass` to 3.8.x and `normalize.css` to 4.2.x

## 0.1.15
* bump `node-sass` to non-beta version
* fix missing `top-bar.css` dev dependency in package.json
* use [standard](https://github.com/feross/standard) for basic test
* add `CONTRIBUTING.md`

## 0.1.14
* no more header border

## 0.1.13
* allow sass import
* move scripts to `scripts`
* move `site` out of `source`
* add `.md` to LICENSE
* remove `.site-nav`, break out & use [top-bar.css](https://github.com/ungoldman/top-bar.css)

## 0.1.12
* bump for no reason because I prematurely published and am not allowed to republish unpublished version [ಠ_ಠ](https://github.com/npm/npm-registry-couchapp/issues/148)

## 0.1.11
* bump gfm.css to v1.0.2

## 0.1.10
* redesign site header
* add `.site-header`, `.site-nav`, `.site-nav-right`, & `.site-footer`

## 0.1.9
* fix gfm config

## 0.1.8
* break gfm styles out into separate module ([gfm.css](https://github.com/ungoldman/gfm.css))
* remove any explicit references to `.markdown-body` from source

## 0.1.7
* clean up github markdown css, convert to scss
* remove dependency on [github-markdown-css](https://github.com/sindresorhus/github-markdown-css)

## 0.1.6
* add `.site-link` class for nav links
* style tweaks

## 0.1.5
* rename `.current` to `.current-page`
* remove `html,body` margin reset (a little margin is fine with this style)
* add sass css `@import` issue workaround
* realize I just want slightly tweaked normalize + gfm
* add `github-markdown.css`
* experiment with header & body fonts, use montserrat + lora for now
* add more filler to guide from https://markdown-it.github.io

## 0.1.4
* generate guide from markdown

## 0.1.3
* only include style.css on install

## 0.1.2
* fix links in package.json

## 0.1.1
* use proper normalize.css
* tweak figure, figure > img
* add serve.js
* add more doc

## 0.1.0
* first pass