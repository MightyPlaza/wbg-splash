# Changelog

* [Unreleased](#unreleased)
* [1.2.0](#1-2-)
* [1.1.0](#1-1-0)


## Unreleased
### Added

* Nanosvg updated to 93ce879dc4c04a3ef1758428ec80083c38610b1f
* JPEG XL support ([#14][14])


### Changed
### Deprecated
### Removed
### Fixed

* Alpha not being applied correctly to PNG images.
* Compilation error on musl libc ([#11][11]).

[11]: https://codeberg.org/dnkl/wbg/issues/11
[14]: https://codeberg.org/dnkl/wbg/pulls/14


### Security
### Contributors

* Leonardo Hernández Hernández


## 1.2.0

### Added

* We now hint to the compositor that the background is fully opaque.
* SVG support.


### Changed

* Image is now zoomed, rather than stretched ([#6][6]).

[6]: https://codeberg.org/dnkl/wbg/issues/6


### Fixed

* Respect the `layer_surface::closed()` event.


### Contributors

* Leonardo Hernández Hernández
* sewn


## 1.1.0

### Added

* webp support


### Fixed

* meson: can’t use `SOURCE_DIR` in `custom_targets()`.
* build: version script is now run in a C locale.
* Don’t re-render frame on same-size configure events


### Contributors

*  Leonardo Hernández
