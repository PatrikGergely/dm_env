# Changelog

All significant changes to this project will be documented here.

## [Unreleased]

## [1.3]

Release date: 2020-10-30

*   Added a `StringArray` spec subclass for representing arrays of variable-
    length strings.
*   Added a check to enforce that `minimum <= maximum` for `BoundedArray`.

## [1.2]

Release date: 2019-11-12

### Changed

*   `test_utils.EnvironmentTestMixin` can now be used to validate
    implementations of `dm_env.Environment` where actions, observations, rewards
    and/or discounts are arbitrary nested structures containing numpy arrays or
    scalars.

## [1.1]

Release date: 2019-08-12

### Added

*   Specs now have a `replace` method that can be used to create a new instance
    with some of the attributes replaced (similar to `namedtuple._replace`).

### Changed

*   The `BoundedArray` constructor now casts `minimum` and `maximum` so that
    their dtypes match that of the spec instance.

## [1.0]

Release date: 2019-07-18

*   Initial release.

[Unreleased]: https://github.com/deepmind/dm_env/compare/v1.3...HEAD
[1.3]: https://github.com/deepmind/dm_env/compare/v1.2...v1.3
[1.2]: https://github.com/deepmind/dm_env/compare/v1.1...v1.2
[1.1]: https://github.com/deepmind/dm_env/compare/v1.0...v1.1
[1.0]: https://github.com/deepmind/dm_env/releases/tag/v1.0
