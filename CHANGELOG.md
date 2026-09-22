# Changelog

## [Unreleased]

### Changed

- Package identity is now `studapart/adf-tools`, a Studapart-maintained fork of DamienHarper/adf-tools 1.2.1. The public `DH\Adf` API and production requirements (`php >= 7.4`, `ext-json`) are unchanged.
- Development toolchain targets PHPUnit 11 and allows `symfony/var-dumper` `^5 || ^6 || ^7 || ^8` as a **require-dev** dependency only. PHP-CS-Fixer `mb_str_functions` is off so PHP 8.4 CI cannot rewrite `trim()` to PHP 8.4-only `mb_trim()`.
- CI runs the 1.x test job on PHP 8.4.

### Added

- Composer `replace` for `damienharper/adf-tools` so consumers can switch packages without installing both.

The next tagged release is intended to be **1.2.2**.
