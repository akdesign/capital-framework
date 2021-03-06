All notable changes to this project will be documented in this file.
We follow the [Semantic Versioning 2.0.0](http://semver.org/) format.

## Unreleased

### Added
-

### Changed
- **capital-framework:** [PATCH] Fixed various linting errors and warnings in tests and gulp tasks.

### Removed
-

## 3.6.1 - 2016-08-12

### Changed
- **cf-icons:** Standardized the usage doc.
- **cf-pagination:** Standardized the usage doc.
- **cf-forms:** Standardized the usage doc.

### Removed
- **capital-framework:** Remove post install script to allow shrinkwrapping.


## 3.6.0 - 2016-08-02

### Added
- **capital-framework:** Added CSS autoprefixer to build pipeline.

### Changed
- **cf-typography:** Many documentation fixes and standardization.
- **cf-core:** Standardized the usage doc.
- **cf-tables:** Fix documentation order and details.

### Removed
- **cf-typography:** Removed remaining Less from branded bullets
- **cf-buttons:** Removed vendor prefixes handled by autoprefixer.
- **cf-core:** Removed vendor prefixes handled by autoprefixer.
- **cf-grid:** Removed vendor prefixes handled by autoprefixer.
- **cf-icons:** Removed vendor prefixes handled by autoprefixer.


## 3.5.2 - 2016-07-06

### Changed
- **capital-framework:** Improve contributing docs in readme for outside contributors and documentation fixes.


## 3.5.1 - 2016-07-05

### Changed
- **cf-layout:** Add negative side margin to FCMs so they don't double
  up the border when against a sidebar.
- **cf-layout:** Update recommended FCM markup to use `category-slug`.
- **cf-forms:** Fix markup in documentation.
- **cf-typography:** Fix markup in documentation.


## 3.5.0 - 2016-05-26

### Added
- **cf-core:** Add respond-to-dpi mixin and respond-to-print mixin

### Changed
- **all components:** Improve components' usage documentation
- **capital-framework:** Add note about bumping versions in contribution documentation
- **cf-buttons:** Update default colors to 18F colors in Web Design Standards
- **cf-core:** Update default colors to 18F colors in Web Design Standards
- **cf-expandables:** Update default colors to 18F colors in Web Design Standards
- **cf-forms:** Update default colors to 18F colors in Web Design Standards
- **cf-icons:** Update default colors to 18F colors in Web Design Standards
- **cf-pagination:** Update default colors to 18F colors in Web Design Standards
- **cf-tables:** Update link to 18F Web Design Standards
- **cf-typography:** Update link to 18F Web Design Standards


## 3.4.1 - 2016-05-13

### Changed
- **capital-framework:** Update contributing documentation.


## 3.4.0 - 2016-05-09

### Changed
- **cf-layout:** Updated main content spacing


## 3.3.0 - 2016-04-06

### Added
- **cf-layout:** Add `overlay` and `white-text` modifiers to the hero

### Changed
- **capital-framework:** Move Travis CI from Node v4 to v5.
- **cf-core:** Fix padding in `<th>`s to be 10px.
- **cf-tables:** Match sortable `<th>` styles to non-sortable `<th>` styles.
- **cf-tables:** Harmonize variables with those found in cf-core.
- **cf-layout:** Updated the Hero styles to properly match the content layout and simplified the rules.

## 3.2.1 - 2016-03-10

### Changed
- **All components:** Normalize markdown formatting across usage.md files.


## 3.2.0 - 2016-02-26

### Added
- **cf-tables:** Add new component.
- **cf-core:** Add font-size vars.


## 3.1.4 - 2016-02-23

### Changed
- Include `usage.md` in built components.


## 3.1.3 - 2016-02-23

### Changed

- Update build process to include `usage.md` with built components.


## 3.1.2 - 2016-02-10

### Fixed
- **cf-core:** Fix improper usage of `:not` to target non-nav `li` elements.
- **cf-core:** Remove `margin-bottom` from last-child `li` elements.
- **cf-layout:** Fix a bug where columns nested 2 levels deep in a
  large-gutter modifier gain the extra wide gutters.
- **cf-layout:** Remove `block` borders when `__flush` modifiers are also applied.
- **capital-framework:** Added `CONTRIBUTING.md` with contribution docs.

### Changed
- **cf-layout:** Hero updates:
  - Use new breakpoint variables
  - Subheading should not be medium on smaller screens
  - CTA links should match size and weight of subheading
  - Margin between subheading and CTA is 30px


## 3.1.1 - 2016-01-04

### Changed
- **capital-framework:** Improve contributing docs in readme.


## 3.1.0 - 2016-01-04

### Changed
- **capital-framework:** Edit Gulp styles task to use Less' `paths` option instead of npm import plugin.
- **cf-core:** Update `normalize.css` `@import` paths to play nicer with Less `paths` option.
- **cf-grid:** Update `normalize.css` `@import` paths to play nicer with Less `paths` option.
- **cf-icons:** Replace icon fonts to fix "Failed to decode downloaded font" error.


## 3.0.8 - 2015-12-22

### Added
- Ability to publish CF from local machine (instead of only Travis).


## 3.0.7 - 2015-12-22

### Removed
- Topdoc comments from component source files.


## 3.0.6 - 2015-12-18

### Added
- Initial WCAG accessibility tests.


## 3.0.5 - 2015-12-18

### Changed
- Individual components' readme template.


## 3.0.3 - 2015-12-18

### Added
- Add automatic changelog updating to Travis CI release script.


## 3.0.0 - 2015-12-17

### Changed
- Voltrazord refactor. All components now live in this repo.
