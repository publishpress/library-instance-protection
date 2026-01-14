# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.1.0] - 2024-XX-XX

### Added
- Internationalization (i18n) support with translation files for multiple languages
- Translation loading mechanism in `include.php` to automatically load language files based on WordPress locale

### Changed
- Updated `getVersion()` method in `InstanceChecker` to return version `2.1.0`

### Deprecated
- `InstanceChecker::getVersion()` method is now deprecated and will be removed in the next major version
