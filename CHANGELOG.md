# Changelog

All notable changes to this project will be documented in this file.

## [0.1.0] - 2025-04-03
### Added
- Initial release of **nvidia-smi-remote**.
- Added support for querying GPU status locally using `nvidia-smi`.
- Implemented remote GPU querying via SSH using a JSON configuration file.
- Integrated colorized output using the `blessed` library.
- Added command-line options:
  - `--remote-config` to specify remote server configurations.
  - `--interval` for watch mode.
  - `--no-header` to disable header output.
  - `--no-color` to disable colored output.
  - `--used-only` to display only GPUs in use.
  - `--unused-only` to display only GPUs not in use.
- Provided error handling for mutually exclusive options (`--used-only` and `--unused-only`).

## [Unreleased]
- Future enhancements and bug fixes will be documented here.