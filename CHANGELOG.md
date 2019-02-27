# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

[QA]: Quality assurance

## [Unreleased]

## [0.3.0][] - 2019-02-27

### Added

- default background to text fields
- focus ring removoal on elements focusable only by script
- `:focus-within` to `<label>`
- `!important` to `<template>` and `[hidden]`
- QA tests:
  - flag incomplete responsive images
  - flag use of `[usemap]` inside `<a>` or `<button>`
  - elements with `aria-busy` should have `aria-hidden`

### Changed

- rename `variables.scss` to `config.scss`
- inherit default text fields reset on `<select>`
- some QA errors changed to warnings

### Fixed

- missing anchor colors on anchor rules
- missing constants on QA styles
- moving links on focus
- white-space inside textarea not being respected
- wrong path of loading background

### Removed

- obsolete indentation of text fields
- outdated image rendering properties

## [0.2.2][] - 2018-10-18

### Changed

- Normalize `else if` conditionals
- Normalize `str-slice` and `adjust-hue` functions
- Rename `develop` branch as `dev`

### Fixed

- `pre` typographic and basic styles mixed on `typography.scss`

## [0.2.1][] - 2018-10-17

### Changed

- sass lint variable name config to allow BEM

## [0.2.0][] - 2018-10-16

### Added

- Max line length on article paragraphs
- Missing rule to hide `tfoot` on narrow screens
- Narrow variation of maximum section width
- Reset links inside navigation lists
- Rounded corners to tables
- Sass Lint auto fix

### Changed

- `border-spacing` property order lint
- Improve version tagging and release
- Maximum section width unit
- Prevent table accessibility issues on mobile

### Fixed

- `$placeholder-bg` color variables
- `input[type=image]` QA style selector
- skip links visibility on focus

### Removed

- Conflicting settings between CSSComb and SassLint
- Table head cells alignment
- Unnecessary fallback margin on lists


[Unreleased]: undefined/compare/v0.3.0...HEAD
[0.3.0]: undefined/compare/v0.2.2...v0.3.0
[0.2.2]: undefined/compare/v0.2.1...v0.2.2
[0.2.1]: undefined/compare/v0.2.0...v0.2.1
[0.2.0]: undefined/tree/v0.2.0
