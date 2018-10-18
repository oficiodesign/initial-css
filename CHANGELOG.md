# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

[QA]: Quality assurance

## [Unreleased]

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


[Unreleased]: undefined/compare/v0.2.1...HEAD
[0.2.1]: undefined/compare/v0.2.0...v0.2.1
[0.2.0]: undefined/tree/v0.2.0
