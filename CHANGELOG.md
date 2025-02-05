# Changelog

All notable changes to `laravel-multilingual-routes` will be documented in this file.

## [v1.4.0 (2019-12-02)](https://github.com/chinleung/laravel-multilingual-routes/compare/v1.3.0...v1.4.0)

- Added configuration `MULTILINGUAL_ROUTES_DEFAULT_LOCALE` to customize the default locale [#14](https://github.com/chinleung/laravel-multilingual-routes/issues/14)
- Changed `MULTILINGUAL_ROUTES_PREFIX_FALLBACK` to `MULTILINGUAL_ROUTES_PREFIX_DEFAULT`

## [v1.3.0 (2019-10-23)](https://github.com/chinleung/laravel-multilingual-routes/compare/v1.2.3...v1.3.0)

- Added support for route constraints  [#12](https://github.com/chinleung/laravel-multilingual-routes/issues/12)

## [v1.2.3 (2019-10-10)](https://github.com/chinleung/laravel-multilingual-routes/compare/v1.2.2...v1.2.3)

- Fixed view route registration throwing no action logic exception  [#10](https://github.com/chinleung/laravel-multilingual-routes/issues/10)

## [v1.2.2 (2019-09-20)](https://github.com/chinleung/laravel-multilingual-routes/compare/v1.2.1...v1.2.2)

- Fixed registration for routes with identical keys  [#9](https://github.com/chinleung/laravel-multilingual-routes/issues/9)

## [v1.2.1 (2019-09-19)](https://github.com/chinleung/laravel-multilingual-routes/compare/v1.2.0...v1.2.1)

- Fixed registration for routes with identical keys  [#8](https://github.com/chinleung/laravel-multilingual-routes/issues/8)

## [v1.2.0 (2019-09-07)](https://github.com/chinleung/laravel-multilingual-routes/compare/v1.1.0...v1.2.0)

- Added support for Laravel 6

## [v1.1.0 (2019-08-06)](https://github.com/chinleung/laravel-multilingual-routes/compare/v1.0.2...v1.1.0)

- Added support for view routes  [#5](https://github.com/chinleung/laravel-multilingual-routes/issues/5)

## [v1.0.2 (2019-08-01)](https://github.com/chinleung/laravel-multilingual-routes/compare/v1.0.1...v1.0.2)

- Fixed home page not registering properly  [#3](https://github.com/chinleung/laravel-multilingual-routes/issues/3)

## [v1.0.1 (2019-07-30)](https://github.com/chinleung/laravel-multilingual-routes/compare/v1.0.0...v1.0.1)

- Require `chinleung/laravel-locales` as dependency
- Moved `laravel-multilingual-routes.locales` to `laravel-locales.supported` for locales configuration
- Added `MULTILINGUAL_ROUTES_PREFIX_FALLBACK` env to prefix fallback configuration

## v1.0.0 (2019-07-29)

- Initial release
