# Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## [Unreleased]
### Added
- The underlying rubyipmi gem supports setting the driver used for the connection so we expose that via the `---driver` argument (@peterhoeg)
- Updated the README with possible fixes when talking to older (< v2) IPMI hosts (@peterhoeg)

## [1.0.1] - 2017-08-07
### Changed
- Change `sensu-plugin` dependency to `~> 1.2` (@eheydrick)

### Fixed
- Fix deprecated timeout method (@peterhoeg)

## [1.0.0] - 2017-07-12
### Added
- Testing on 2.3.0 & 2.4.1

### Breaking Changes
- Dropped Ruby 1.9.3 support

## [0.0.2] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## 0.0.1 - 2015-06-28
### Added
- initial release

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-ipmi/compare/1.0.1...HEAD
[1.0.1]: https://github.com/sensu-plugins/sensu-plugins-ipmi/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/sensu-plugins/sensu-plugins-ipmi/compare/0.0.2...1.0.0
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-ipmi/compare/0.0.1...0.0.2
