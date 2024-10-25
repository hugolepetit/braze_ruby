# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog][] and this project adheres to
[Semantic Versioning][].

[Keep a Changelog]: https://keepachangelog.com
[Semantic Versioning]: https://semver.org

## [Unreleased][]

### Added

* Add a CHANGELOG ([#61][])

### Changed

### Deprecated

### Removed

### Fixed

### Security

## [0.8.0][] - 2022-01-24

### Added

* Add a Configuration class ([#42][])
* Add an endpoint for messages that are scheduled ([#43][])
* Document #scheduled_messages ([#45][])
* Add support for deleting scheduled triggers ([#47][])

### Changed

* Standardize rest test code structure ([#44][])

### Fixed

* Fix typo in README code example ([#46][])

## [0.7.0][] - 2021-09-29

### Added

* Add campaign scheduling endpoint ([#41][])

### Fixed

* Fix syntax error in "send campaigns" example ([#38][])

## [0.6.0][] - 2021-07-23

### Added

* Add retry configuration pass through ([#31][])
* Endpoint for 'remove email address from spam' ([#32][])
* Ability to set Faraday connection options ([#34][])

### Changed

* Publish via GitHub actions ([#36][])
* Allow options when exporting users by ids ([#37][])

## [0.5.0][] - 2021-05-06

### Added

* Add .circleci/config.yml ([#25][])
* Setup and comply with standardrb ([#28][])
* Add release workflow to publish gem from CI ([#29][])
* Add script to help automate releases ([#30][])

### Changed

* Modernize a few files and tinker with CI setup ([#26][])
* Update authors and license ([#27][])

[Unreleased]: https://github.com/jonallured/braze_ruby/compare/v0.8.0...HEAD

[0.5.0]: https://github.com/jonallured/braze_ruby/releases/tag/v0.5.0
[0.6.0]: https://github.com/jonallured/braze_ruby/releases/tag/v0.6.0
[0.7.0]: https://github.com/jonallured/braze_ruby/releases/tag/v0.7.0
[0.8.0]: https://github.com/jonallured/braze_ruby/releases/tag/v0.8.0

[#25]: https://github.com/jonallured/braze_ruby/pull/25
[#26]: https://github.com/jonallured/braze_ruby/pull/26
[#27]: https://github.com/jonallured/braze_ruby/pull/27
[#28]: https://github.com/jonallured/braze_ruby/pull/28
[#29]: https://github.com/jonallured/braze_ruby/pull/29
[#30]: https://github.com/jonallured/braze_ruby/pull/30
[#31]: https://github.com/jonallured/braze_ruby/pull/31
[#32]: https://github.com/jonallured/braze_ruby/pull/32
[#34]: https://github.com/jonallured/braze_ruby/pull/34
[#36]: https://github.com/jonallured/braze_ruby/pull/36
[#37]: https://github.com/jonallured/braze_ruby/pull/37
[#38]: https://github.com/jonallured/braze_ruby/pull/38
[#41]: https://github.com/jonallured/braze_ruby/pull/41
[#42]: https://github.com/jonallured/braze_ruby/pull/42
[#43]: https://github.com/jonallured/braze_ruby/pull/43
[#44]: https://github.com/jonallured/braze_ruby/pull/44
[#45]: https://github.com/jonallured/braze_ruby/pull/45
[#46]: https://github.com/jonallured/braze_ruby/pull/46
[#47]: https://github.com/jonallured/braze_ruby/pull/47
[#61]: https://github.com/jonallured/braze_ruby/pull/61