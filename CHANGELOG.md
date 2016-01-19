# Changelog

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

## [0.6.1-beta](https://github.com/contentful/contentful.php/tree/0.6.1-beta) (2015-01-19)

### Added
* Send a User-Agent header with API requests.

### Changed
* When GitHub is generating archieves, are few files with metadata are excluded.

### Fixed
* Calling the get*Id Method on a field that is not a link or an array of links did not cause an error. (#2, originally reported by @andrewevansmith)
* Accessing a non-localized field would fail with and throw a PHP notice.

## [0.6.0-beta](https://github.com/contentful/contentful.php/tree/0.6.0-beta) (2015-12-11)

Initial release

[Unreleased]: https://github.com/contentful/contentful.php/compare/0.6.0-beta...HEAD
[0.6.0-beta]: https://github.com/contentful/contentful.php/tree/0.6.0-beta